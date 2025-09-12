# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetGetinfoooborupredmetu**](PredmetyApi.md#GetGetinfoooborupredmetu) | **Get** /predmety/getInfoOOboruPredmetu | predmety operation
[**GetGetliteraturapredmetu**](PredmetyApi.md#GetGetliteraturapredmetu) | **Get** /predmety/getLiteraturaPredmetu | predmety operation
[**GetGetneakreditovanepredmety**](PredmetyApi.md#GetGetneakreditovanepredmety) | **Get** /predmety/getNeakreditovanePredmety | predmety operation
[**GetGetneakreditovanepredmetyects**](PredmetyApi.md#GetGetneakreditovanepredmetyects) | **Get** /predmety/getNeakreditovanePredmetyEcts | predmety operation
[**GetGetneakreditovanepredmetyseznamzmen**](PredmetyApi.md#GetGetneakreditovanepredmetyseznamzmen) | **Get** /predmety/getNeakreditovanePredmetySeznamZmen | predmety operation
[**GetGetoborypredmetu**](PredmetyApi.md#GetGetoborypredmetu) | **Get** /predmety/getOboryPredmetu | predmety operation
[**GetGetpredmetectsinfo**](PredmetyApi.md#GetGetpredmetectsinfo) | **Get** /predmety/getPredmetECTSInfo | predmety operation
[**GetGetpredmetinfo**](PredmetyApi.md#GetGetpredmetinfo) | **Get** /predmety/getPredmetInfo | predmety operation
[**GetGetpredmetinfopdf**](PredmetyApi.md#GetGetpredmetinfopdf) | **Get** /predmety/getPredmetInfoPDF | predmety operation
[**GetGetpredmetybyblok**](PredmetyApi.md#GetGetpredmetybyblok) | **Get** /predmety/getPredmetyByBlok | predmety operation
[**GetGetpredmetybyblokfullinfo**](PredmetyApi.md#GetGetpredmetybyblokfullinfo) | **Get** /predmety/getPredmetyByBlokFullInfo | predmety operation
[**GetGetpredmetybyfakulta**](PredmetyApi.md#GetGetpredmetybyfakulta) | **Get** /predmety/getPredmetyByFakulta | predmety operation
[**GetGetpredmetybyfakultafullinfo**](PredmetyApi.md#GetGetpredmetybyfakultafullinfo) | **Get** /predmety/getPredmetyByFakultaFullInfo | predmety operation
[**GetGetpredmetybykatedra**](PredmetyApi.md#GetGetpredmetybykatedra) | **Get** /predmety/getPredmetyByKatedra | predmety operation
[**GetGetpredmetybykatedrafullinfo**](PredmetyApi.md#GetGetpredmetybykatedrafullinfo) | **Get** /predmety/getPredmetyByKatedraFullInfo | predmety operation
[**GetGetpredmetybyobor**](PredmetyApi.md#GetGetpredmetybyobor) | **Get** /predmety/getPredmetyByObor | predmety operation
[**GetGetpredmetybyoborfullinfo**](PredmetyApi.md#GetGetpredmetybyoborfullinfo) | **Get** /predmety/getPredmetyByOborFullInfo | predmety operation
[**GetGetpredmetybystudent**](PredmetyApi.md#GetGetpredmetybystudent) | **Get** /predmety/getPredmetyByStudent | predmety operation
[**GetGetpredmetybyucitel**](PredmetyApi.md#GetGetpredmetybyucitel) | **Get** /predmety/getPredmetyByUcitel | predmety operation
[**GetGetpredmetypodlimit**](PredmetyApi.md#GetGetpredmetypodlimit) | **Get** /predmety/getPredmetyPodLimit | predmety operation
[**GetNajdipredmety**](PredmetyApi.md#GetNajdipredmety) | **Get** /predmety/najdiPredmety | predmety operation

# **GetGetinfoooborupredmetu**
> OborPredmetuType GetGetinfoooborupredmetu(ctx, optional)
predmety operation

Operace 'GetGetinfoooborupredmetu' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetinfoooborupredmetuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetinfoooborupredmetuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **oborIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**OborPredmetuType**](oborPredmetuType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetliteraturapredmetu**
> LiteraturaListType GetGetliteraturapredmetu(ctx, optional)
predmety operation

Operace 'GetGetliteraturapredmetu' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetliteraturapredmetuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetliteraturapredmetuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**LiteraturaListType**](literaturaListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetneakreditovanepredmety**
> PredmetyAkreditaceType GetGetneakreditovanepredmety(ctx, optional)
predmety operation

Operace 'GetGetneakreditovanepredmety' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetneakreditovanepredmetyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetneakreditovanepredmetyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stavAkreditace** | **optional.String**|  | 
 **fakulta** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 

### Return type

[**PredmetyAkreditaceType**](predmetyAkreditaceType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetneakreditovanepredmetyects**
> PredmetyAkreditaceEctsType GetGetneakreditovanepredmetyects(ctx, optional)
predmety operation

Operace 'GetGetneakreditovanepredmetyects' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetneakreditovanepredmetyectsOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetneakreditovanepredmetyectsOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stavAkreditace** | **optional.String**|  | 
 **fakulta** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 

### Return type

[**PredmetyAkreditaceEctsType**](predmetyAkreditaceEctsType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetneakreditovanepredmetyseznamzmen**
> PredmetyAkreditaceSeznamZmenType GetGetneakreditovanepredmetyseznamzmen(ctx, optional)
predmety operation

Operace 'GetGetneakreditovanepredmetyseznamzmen' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetneakreditovanepredmetyseznamzmenOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetneakreditovanepredmetyseznamzmenOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stavAkreditace** | **optional.String**|  | 
 **fakulta** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 

### Return type

[**PredmetyAkreditaceSeznamZmenType**](predmetyAkreditaceSeznamZmenType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetoborypredmetu**
> OborPredmetuListType GetGetoborypredmetu(ctx, optional)
predmety operation

Operace 'GetGetoborypredmetu' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetoborypredmetuOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetoborypredmetuOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**OborPredmetuListType**](oborPredmetuListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetectsinfo**
> PredmetEctsInfoListType GetGetpredmetectsinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetectsinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetectsinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetectsinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fakulta** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **garantUcitIdno** | **optional.Int64**|  | 
 **oborIdno** | **optional.Int64**|  | 
 **zobrazovatVECTS** | **optional.String**|  | 
 **akreditace** | **optional.String**|  | 
 **ectsAkreditace** | **optional.String**|  | 

### Return type

[**PredmetEctsInfoListType**](predmetECTSInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetinfo**
> PredmetInfoType GetGetpredmetinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetInfoType**](predmetInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetinfopdf**
> GetGetpredmetinfopdf(ctx, optional)
predmety operation

Operace 'GetGetpredmetinfopdf' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetinfopdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetinfopdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyblok**
> PredmetyBlokuType GetGetpredmetybyblok(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyblok' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyblokOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyblokOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **blokIdno** | **optional.Int64**|  | 
 **vyznamPredmetu** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyBlokuType**](predmetyBlokuType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyblokfullinfo**
> PredmetyBlokuFullInfoType GetGetpredmetybyblokfullinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyblokfullinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyblokfullinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyblokfullinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **blokIdno** | **optional.Int64**|  | 
 **vyznamPredmetu** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyBlokuFullInfoType**](predmetyBlokuFullInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyfakulta**
> PredmetyKatedryType GetGetpredmetybyfakulta(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyfakulta' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyfakultaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyfakultaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fakulta** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **vyucovaciJazyk** | **optional.String**|  | 
 **jenNabizeneECTSPrijezdy** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyKatedryType**](predmetyKatedryType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyfakultafullinfo**
> PredmetInfoListType GetGetpredmetybyfakultafullinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyfakultafullinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyfakultafullinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyfakultafullinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fakulta** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **vyucovaciJazyk** | **optional.String**|  | 
 **jenNabizeneECTSPrijezdy** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetInfoListType**](predmetInfoListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybykatedra**
> PredmetyKatedryType GetGetpredmetybykatedra(ctx, optional)
predmety operation

Operace 'GetGetpredmetybykatedra' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybykatedraOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybykatedraOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **jenNabizeneECTSPrijezdy** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyKatedryType**](predmetyKatedryType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybykatedrafullinfo**
> PredmetyKatedryFullInfoType GetGetpredmetybykatedrafullinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetybykatedrafullinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybykatedrafullinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybykatedrafullinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **jenNabizeneECTSPrijezdy** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyKatedryFullInfoType**](predmetyKatedryFullInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyobor**
> PredmetyOboruType GetGetpredmetybyobor(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyobor' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyoborOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyoborOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oborIdno** | **optional.Int64**|  | 
 **cisloOboru** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **vyznamPredmetu** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyOboruType**](predmetyOboruType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyoborfullinfo**
> PredmetyOboruFullInfoType GetGetpredmetybyoborfullinfo(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyoborfullinfo' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyoborfullinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyoborfullinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **oborIdno** | **optional.Int64**|  | 
 **cisloOboru** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **vyznamPredmetu** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyOboruFullInfoType**](predmetyOboruFullInfoType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybystudent**
> PredmetyStudentaType GetGetpredmetybystudent(ctx, optional)
predmety operation

Operace 'GetGetpredmetybystudent' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybystudentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybystudentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osCislo** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **nevracetUznane** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyStudentaType**](predmetyStudentaType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetybyucitel**
> PredmetyUciteleType GetGetpredmetybyucitel(ctx, optional)
predmety operation

Operace 'GetGetpredmetybyucitel' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetybyucitelOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetybyucitelOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ucitIdno** | **optional.Int64**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **jenCoMajiVyuku** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyUciteleType**](predmetyUciteleType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetpredmetypodlimit**
> PredmetPodLimitListType GetGetpredmetypodlimit(ctx, optional)
predmety operation

Operace 'GetGetpredmetypodlimit' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetGetpredmetypodlimitOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetGetpredmetypodlimitOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pracoviste** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetPodLimitListType**](predmetPodLimitListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetNajdipredmety**
> PredmetyKatedryType GetNajdipredmety(ctx, optional)
predmety operation

Operace 'GetNajdipredmety' z kategorie 'predmety'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***PredmetyApiGetNajdipredmetyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a PredmetyApiGetNajdipredmetyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **nazev** | **optional.String**|  | 
 **pracoviste** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**PredmetyKatedryType**](predmetyKatedryType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

