# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetGetstudent**](VspApi.md#GetGetstudent) | **Get** /vsp/getStudent | vsp operation
[**GetGetstudijniplan**](VspApi.md#GetGetstudijniplan) | **Get** /vsp/getStudijniPlan | vsp operation

# **GetGetstudent**
> VspStudentType GetGetstudent(ctx, optional)
vsp operation

Operace 'GetGetstudent' z kategorie 'vsp'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***VspApiGetGetstudentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a VspApiGetGetstudentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osCislo** | **optional.String**|  | 

### Return type

[**VspStudentType**](vspStudentType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstudijniplan**
> VspStudijniPlanType GetGetstudijniplan(ctx, optional)
vsp operation

Operace 'GetGetstudijniplan' z kategorie 'vsp'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***VspApiGetGetstudijniplanOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a VspApiGetGetstudijniplanOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stplIdno** | **optional.Int64**|  | 

### Return type

[**VspStudijniPlanType**](vspStudijniPlanType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

