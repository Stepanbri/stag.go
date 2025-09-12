# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetGetstaguserforactualuser**](HelpApi.md#GetGetstaguserforactualuser) | **Get** /help/getStagUserForActualUser | help operation
[**GetGetstaguserlistforactualuser**](HelpApi.md#GetGetstaguserlistforactualuser) | **Get** /help/getStagUserListForActualUser | help operation
[**GetGetstaguserlistforactualuserv2**](HelpApi.md#GetGetstaguserlistforactualuserv2) | **Get** /help/getStagUserListForActualUserV2 | help operation
[**GetGetstaguserlistforloginticket**](HelpApi.md#GetGetstaguserlistforloginticket) | **Get** /help/getStagUserListForLoginTicket | help operation
[**GetGetstaguserlistforloginticketv2**](HelpApi.md#GetGetstaguserlistforloginticketv2) | **Get** /help/getStagUserListForLoginTicketV2 | help operation
[**GetInvalidateticket**](HelpApi.md#GetInvalidateticket) | **Get** /help/invalidateTicket | help operation
[**GetOrganizaceinfo**](HelpApi.md#GetOrganizaceinfo) | **Get** /help/organizaceInfo | help operation
[**GetTestservice**](HelpApi.md#GetTestservice) | **Get** /help/testService | help operation

# **GetGetstaguserforactualuser**
> StagUserType GetGetstaguserforactualuser(ctx, optional)
help operation

Operace 'GetGetstaguserforactualuser' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetGetstaguserforactualuserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetGetstaguserforactualuserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**StagUserType**](stagUserType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforactualuser**
> StagUserListType GetGetstaguserlistforactualuser(ctx, optional)
help operation

Operace 'GetGetstaguserlistforactualuser' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetGetstaguserlistforactualuserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetGetstaguserlistforactualuserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**StagUserListType**](stagUserListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforactualuserv2**
> StagUserListV2Type GetGetstaguserlistforactualuserv2(ctx, optional)
help operation

Operace 'GetGetstaguserlistforactualuserv2' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetGetstaguserlistforactualuserv2Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetGetstaguserlistforactualuserv2Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**StagUserListV2Type**](stagUserListV2Type.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforloginticket**
> StagUserListType GetGetstaguserlistforloginticket(ctx, optional)
help operation

Operace 'GetGetstaguserlistforloginticket' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetGetstaguserlistforloginticketOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetGetstaguserlistforloginticketOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticket** | **optional.String**|  | 

### Return type

[**StagUserListType**](stagUserListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforloginticketv2**
> StagUserListV2Type GetGetstaguserlistforloginticketv2(ctx, optional)
help operation

Operace 'GetGetstaguserlistforloginticketv2' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetGetstaguserlistforloginticketv2Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetGetstaguserlistforloginticketv2Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticket** | **optional.String**|  | 

### Return type

[**StagUserListV2Type**](stagUserListV2Type.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetInvalidateticket**
> GetInvalidateticket(ctx, optional)
help operation

Operace 'GetInvalidateticket' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetInvalidateticketOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetInvalidateticketOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticket** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetOrganizaceinfo**
> OrganizaceInfoType GetOrganizaceinfo(ctx, )
help operation

Operace 'GetOrganizaceinfo' z kategorie 'help'.

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**OrganizaceInfoType**](organizaceInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetTestservice**
> StringListType GetTestservice(ctx, optional)
help operation

Operace 'GetTestservice' z kategorie 'help'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***HelpApiGetTestserviceOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a HelpApiGetTestserviceOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **parametr** | **optional.String**|  | 

### Return type

[**StringListType**](stringListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

