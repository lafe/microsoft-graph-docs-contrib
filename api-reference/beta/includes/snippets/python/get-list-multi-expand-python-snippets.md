---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = ListItemRequestBuilder.ListItemRequestBuilderGetQueryParameters(
		select = ["name","lastModifiedDateTime"],
		expand = ["columns(select=name,description)","items(expand=fields(select=Name,Color,Quantity)",")"],
)

request_configuration = ListItemRequestBuilder.ListItemRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.sites.by_site_id('site-id').lists.by_list_id('list-id').get(request_configuration = request_configuration)


```