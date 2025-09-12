# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetGetblokinfo**](ProgramyApi.md#GetGetblokinfo) | **Get** /programy/getBlokInfo | programy operation
[**GetGetblokyplanu**](ProgramyApi.md#GetGetblokyplanu) | **Get** /programy/getBlokyPlanu | programy operation
[**GetGetblokysegmentu**](ProgramyApi.md#GetGetblokysegmentu) | **Get** /programy/getBlokySegmentu | programy operation
[**GetGetoblastivzdelavaniprogramu**](ProgramyApi.md#GetGetoblastivzdelavaniprogramu) | **Get** /programy/getOblastiVzdelavaniProgramu | programy operation
[**GetGetoborinfo**](ProgramyApi.md#GetGetoborinfo) | **Get** /programy/getOborInfo | programy operation
[**GetGetoboryqraminfo**](ProgramyApi.md#GetGetoboryqraminfo) | **Get** /programy/getOboryQRAMInfo | programy operation
[**GetGetoborystudijnihoprogramu**](ProgramyApi.md#GetGetoborystudijnihoprogramu) | **Get** /programy/getOboryStudijnihoProgramu | programy operation
[**GetGetplaninfo**](ProgramyApi.md#GetGetplaninfo) | **Get** /programy/getPlanInfo | programy operation
[**GetGetplanyoboru**](ProgramyApi.md#GetGetplanyoboru) | **Get** /programy/getPlanyOboru | programy operation
[**GetGetplanystudenta**](ProgramyApi.md#GetGetplanystudenta) | **Get** /programy/getPlanyStudenta | programy operation
[**GetGetsegmentinfo**](ProgramyApi.md#GetGetsegmentinfo) | **Get** /programy/getSegmentInfo | programy operation
[**GetGetsegmentyplanu**](ProgramyApi.md#GetGetsegmentyplanu) | **Get** /programy/getSegmentyPlanu | programy operation
[**GetGetstudijniprograminfo**](ProgramyApi.md#GetGetstudijniprograminfo) | **Get** /programy/getStudijniProgramInfo | programy operation
[**GetGetstudijniprogramy**](ProgramyApi.md#GetGetstudijniprogramy) | **Get** /programy/getStudijniProgramy | programy operation

# **GetGetblokinfo**
> BlokInfoType GetGetblokinfo(ctx, optional)
programy operation

Operace 'GetGetblokinfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetblokinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetblokinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **blokIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**BlokInfoType**](blokInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetblokyplanu**
> BlokInfoListType GetGetblokyplanu(ctx, optional)
programy operation

Operace 'GetGetblokyplanu' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetblokyplanuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetblokyplanuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stplIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**BlokInfoListType**](blokInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetblokysegmentu**
> BlokInfoListType GetGetblokysegmentu(ctx, optional)
programy operation

Operace 'GetGetblokysegmentu' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetblokysegmentuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetblokysegmentuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sespIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**BlokInfoListType**](blokInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetoblastivzdelavaniprogramu**
> ProgramOblVzdelListType GetGetoblastivzdelavaniprogramu(ctx, optional)
programy operation

Operace 'GetGetoblastivzdelavaniprogramu' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetoblastivzdelavaniprogramuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetoblastivzdelavaniprogramuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stprIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**ProgramOblVzdelListType**](programOblVzdelListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetoborinfo**
> OborInfoType GetGetoborinfo(ctx, optional)
programy operation

Operace 'GetGetoborinfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetoborinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetoborinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oborIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**OborInfoType**](oborInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetoboryqraminfo**
> OborQramInfoListType GetGetoboryqraminfo(ctx, optional)
programy operation

Operace 'GetGetoboryqraminfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetoboryqraminfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetoboryqraminfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oborIdno** | **optional.Int64**|  | 
 **fakulta** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **forma** | **optional.String**|  | 
 **typ** | **optional.String**|  | 
 **jazyk** | **optional.String**|  | 
 **pouzePlatne** | **optional.Bool**|  | 

### Return type

[**OborQramInfoListType**](oborQRAMInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetoborystudijnihoprogramu**
> OborInfoListType GetGetoborystudijnihoprogramu(ctx, optional)
programy operation

Operace 'GetGetoborystudijnihoprogramu' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetoborystudijnihoprogramuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetoborystudijnihoprogramuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stprIdno** | **optional.Int64**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**OborInfoListType**](oborInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetplaninfo**
> PlanInfoType GetGetplaninfo(ctx, optional)
programy operation

Operace 'GetGetplaninfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetplaninfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetplaninfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stplIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PlanInfoType**](planInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetplanyoboru**
> PlanInfoListType GetGetplanyoboru(ctx, optional)
programy operation

Operace 'GetGetplanyoboru' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetplanyoboruOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetplanyoboruOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oborIdno** | **optional.Int64**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PlanInfoListType**](planInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetplanystudenta**
> PlanInfoListType GetGetplanystudenta(ctx, optional)
programy operation

Operace 'GetGetplanystudenta' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetplanystudentaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetplanystudentaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **osCislo** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PlanInfoListType**](planInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetsegmentinfo**
> SegmentInfoType GetGetsegmentinfo(ctx, optional)
programy operation

Operace 'GetGetsegmentinfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetsegmentinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetsegmentinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sespIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**SegmentInfoType**](segmentInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetsegmentyplanu**
> SegmentInfoListType GetGetsegmentyplanu(ctx, optional)
programy operation

Operace 'GetGetsegmentyplanu' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetsegmentyplanuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetsegmentyplanuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stplIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**SegmentInfoListType**](segmentInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstudijniprograminfo**
> ProgramInfoType GetGetstudijniprograminfo(ctx, optional)
programy operation

Operace 'GetGetstudijniprograminfo' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetstudijniprograminfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetstudijniprograminfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stprIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**ProgramInfoType**](programInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstudijniprogramy**
> ProgramInfoListType GetGetstudijniprogramy(ctx, optional)
programy operation

Operace 'GetGetstudijniprogramy' z kategorie 'programy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***ProgramyApiGetGetstudijniprogramyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ProgramyApiGetGetstudijniprogramyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fakulta** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **kod** | **optional.String**|  | 
 **forma** | **optional.String**|  | 
 **typ** | **optional.String**|  | 
 **jazyk** | **optional.String**|  | 
 **profil** | **optional.String**|  | 
 **pouzePlatne** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**ProgramInfoListType**](programInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

