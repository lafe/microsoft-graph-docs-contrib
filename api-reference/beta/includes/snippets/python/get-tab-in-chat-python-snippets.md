---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = TeamsTabItemRequestBuilder.TeamsTabItemRequestBuilderGetQueryParameters(
		expand = ["teamsApp"],
)

request_configuration = TeamsTabItemRequestBuilder.TeamsTabItemRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.chats.by_chat_id('chat-id').tabs.by_teams_tab_id('teamsTab-id').get(request_configuration = request_configuration)


```