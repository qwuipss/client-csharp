# Moira.ApiClient.Model.DtoTriggerModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AloneMetrics** | **Dictionary&lt;string, bool&gt;** | A list of targets that have only alone metrics | [optional] 
**ClusterId** | **string** | Shows the exact cluster from where the metrics are fetched | [optional] 
**CreatedAt** | **string** | Datetime when the trigger was created | [optional] 
**CreatedBy** | **string** | Username who created trigger | [optional] 
**Desc** | **string** | Description string | [optional] 
**ErrorValue** | **decimal** | ERROR threshold | [optional] 
**Expression** | **string** | Used if you need more complex logic than provided by WARN/ERROR values | [optional] 
**Id** | **string** | Trigger unique ID | [optional] 
**IsRemote** | **bool** | Shows if trigger is remote (graphite-backend) based or stored inside Moira-Redis DB  Deprecated: Use TriggerSource field instead | [optional] 
**MuteNewMetrics** | **bool** | If true, first event NODATA → OK will be omitted | [optional] 
**Name** | **string** | Trigger name | [optional] 
**Patterns** | **List&lt;string&gt;** | Graphite patterns for trigger | [optional] 
**Sched** | [**MoiraScheduleData**](MoiraScheduleData.md) |  | [optional] 
**Tags** | **List&lt;string&gt;** | Set of tags to manipulate subscriptions | [optional] 
**Targets** | **List&lt;string&gt;** | Graphite-like targets: t1, t2, ... | [optional] 
**TriggerSource** | **string** | Shows the type of source from where the metrics are fetched | [optional] 
**TriggerType** | **string** | Could be: rising, falling, expression | [optional] 
**Ttl** | **long** | When there are no metrics for trigger, Moira will switch metric to TTLState state after TTL seconds | [optional] 
**TtlState** | **string** | When there are no metrics for trigger, Moira will switch metric to TTLState state after TTL seconds | [optional] 
**UpdatedAt** | **string** | Datetime  when the trigger was updated | [optional] 
**UpdatedBy** | **string** | Username who updated trigger | [optional] 
**WarnValue** | **decimal** | WARN threshold | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

