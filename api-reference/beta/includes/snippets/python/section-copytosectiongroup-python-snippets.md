---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = CopyToSectionGroupPostRequestBody(
	id = "id-value",
	group_id = "groupId-value",
	rename_as = "renameAs-value",
)

result = await graph_client.me.onenote.sections.by_onenote_section_id('onenoteSection-id').copy_to_section_group.post(request_body)


```