---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = BranchSite(
	name = "My updated branch",
)

result = await graph_client.network_access.connectivity.branches.by_branch_site_id('branchSite-id').patch(request_body)


```