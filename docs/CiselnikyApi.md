# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDeletepracoviste**](CiselnikyApi.md#GetDeletepracoviste) | **Get** /ciselniky/deletePracoviste | ciselniky operation
[**GetGetcasovarada**](CiselnikyApi.md#GetGetcasovarada) | **Get** /ciselniky/getCasovaRada | ciselniky operation
[**GetGetciselnik**](CiselnikyApi.md#GetGetciselnik) | **Get** /ciselniky/getCiselnik | ciselniky operation
[**GetGetciselniknewdomains**](CiselnikyApi.md#GetGetciselniknewdomains) | **Get** /ciselniky/getCiselnikNewDomains | ciselniky operation
[**GetGetciselniknewitems**](CiselnikyApi.md#GetGetciselniknewitems) | **Get** /ciselniky/getCiselnikNewItems | ciselniky operation
[**GetGethierarchiepracovist**](CiselnikyApi.md#GetGethierarchiepracovist) | **Get** /ciselniky/getHierarchiePracovist | ciselniky operation
[**GetGetseznamdomen**](CiselnikyApi.md#GetGetseznamdomen) | **Get** /ciselniky/getSeznamDomen | ciselniky operation
[**GetGetseznampracovist**](CiselnikyApi.md#GetGetseznampracovist) | **Get** /ciselniky/getSeznamPracovist | ciselniky operation
[**PostInsertpracoviste**](CiselnikyApi.md#PostInsertpracoviste) | **Post** /ciselniky/insertPracoviste | ciselniky operation
[**PostInserttitul**](CiselnikyApi.md#PostInserttitul) | **Post** /ciselniky/insertTitul | ciselniky operation
[**PostUpdatepracoviste**](CiselnikyApi.md#PostUpdatepracoviste) | **Post** /ciselniky/updatePracoviste | ciselniky operation
[**PostUpdatetitul**](CiselnikyApi.md#PostUpdatetitul) | **Post** /ciselniky/updateTitul | ciselniky operation

# **GetDeletepracoviste**
> GetDeletepracoviste(ctx, optional)
ciselniky operation

Operace 'GetDeletepracoviste' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiGetDeletepracovisteOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiGetDeletepracovisteOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **pracovisteForDelete** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetcasovarada**
> CasovaRadaType GetGetcasovarada(ctx, optional)
ciselniky operation

Operace 'GetGetcasovarada' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiGetGetcasovaradaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiGetGetcasovaradaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kod** | **optional.String**|  | 

### Return type

[**CasovaRadaType**](casovaRadaType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetciselnik**
> CiselnikType GetGetciselnik(ctx, optional)
ciselniky operation

Operace 'GetGetciselnik' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiGetGetciselnikOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiGetGetciselnikOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domena** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**CiselnikType**](ciselnikType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetciselniknewdomains**
> StringListType GetGetciselniknewdomains(ctx, )
ciselniky operation

Operace 'GetGetciselniknewdomains' z kategorie 'ciselniky'.

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**StringListType**](stringListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetciselniknewitems**
> CiselnikNewType GetGetciselniknewitems(ctx, optional)
ciselniky operation

Operace 'GetGetciselniknewitems' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiGetGetciselniknewitemsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiGetGetciselniknewitemsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domena** | **optional.String**|  | 
 **key** | **optional.String**|  | 
 **resultsStartAt** | **optional.Int32**|  | 
 **resultsEndAt** | **optional.Int32**|  | 
 **onlyValidItems** | **optional.Bool**|  | 
 **sortItems** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**CiselnikNewType**](ciselnikNewType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGethierarchiepracovist**
> PracovisteListType GetGethierarchiepracovist(ctx, )
ciselniky operation

Operace 'GetGethierarchiepracovist' z kategorie 'ciselniky'.

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**PracovisteListType**](pracovisteListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetseznamdomen**
> StringListType GetGetseznamdomen(ctx, )
ciselniky operation

Operace 'GetGetseznamdomen' z kategorie 'ciselniky'.

### Required Parameters
This endpoint does not need any parameter.

### Return type

[**StringListType**](stringListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetseznampracovist**
> PracovisteListType GetGetseznampracovist(ctx, optional)
ciselniky operation

Operace 'GetGetseznampracovist' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiGetGetseznampracovistOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiGetGetseznampracovistOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **zkratka** | **optional.String**|  | 
 **nadrazenePracoviste** | **optional.String**|  | 
 **typPracoviste** | **optional.String**|  | 

### Return type

[**PracovisteListType**](pracovisteListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostInsertpracoviste**
> PracovisteForEditType PostInsertpracoviste(ctx, optional)
ciselniky operation

Operace 'PostInsertpracoviste' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiPostInsertpracovisteOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiPostInsertpracovisteOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**PracovisteForEditType**](pracovisteForEditType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostInserttitul**
> WsCiselnikItemForEditType PostInserttitul(ctx, optional)
ciselniky operation

Operace 'PostInserttitul' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiPostInserttitulOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiPostInserttitulOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**WsCiselnikItemForEditType**](wsCiselnikItemForEditType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostUpdatepracoviste**
> PracovisteForEditType PostUpdatepracoviste(ctx, optional)
ciselniky operation

Operace 'PostUpdatepracoviste' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiPostUpdatepracovisteOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiPostUpdatepracovisteOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**PracovisteForEditType**](pracovisteForEditType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostUpdatetitul**
> WsCiselnikItemForEditType PostUpdatetitul(ctx, optional)
ciselniky operation

Operace 'PostUpdatetitul' z kategorie 'ciselniky'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***CiselnikyApiPostUpdatetitulOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a CiselnikyApiPostUpdatetitulOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**WsCiselnikItemForEditType**](wsCiselnikItemForEditType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

