---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

query_params = UnifiedRoleManagementAlertItemRequestBuilder.UnifiedRoleManagementAlertItemRequestBuilderGetQueryParameters(
		expand = ["*"],
)

request_configuration = UnifiedRoleManagementAlertItemRequestBuilder.UnifiedRoleManagementAlertItemRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.role_management_alerts.alerts.by_unified_role_management_alert_id('unifiedRoleManagementAlert-id').get(request_configuration = request_configuration)


```