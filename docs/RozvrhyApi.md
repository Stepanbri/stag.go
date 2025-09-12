# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetGetpozadavkynacasvyuky**](RozvrhyApi.md#GetGetpozadavkynacasvyuky) | **Get** /rozvrhy/getPozadavkyNaCasVyuky | rozvrhy operation
[**GetGetrozvrhbykatedra**](RozvrhyApi.md#GetGetrozvrhbykatedra) | **Get** /rozvrhy/getRozvrhByKatedra | rozvrhy operation
[**GetGetrozvrhbykatedraical**](RozvrhyApi.md#GetGetrozvrhbykatedraical) | **Get** /rozvrhy/getRozvrhByKatedraICAL | rozvrhy operation
[**GetGetrozvrhbykatedrapdf**](RozvrhyApi.md#GetGetrozvrhbykatedrapdf) | **Get** /rozvrhy/getRozvrhByKatedraPDF | rozvrhy operation
[**GetGetrozvrhbykrouzek**](RozvrhyApi.md#GetGetrozvrhbykrouzek) | **Get** /rozvrhy/getRozvrhByKrouzek | rozvrhy operation
[**GetGetrozvrhbykrouzekical**](RozvrhyApi.md#GetGetrozvrhbykrouzekical) | **Get** /rozvrhy/getRozvrhByKrouzekICAL | rozvrhy operation
[**GetGetrozvrhbykrouzekpdf**](RozvrhyApi.md#GetGetrozvrhbykrouzekpdf) | **Get** /rozvrhy/getRozvrhByKrouzekPDF | rozvrhy operation
[**GetGetrozvrhbymistnost**](RozvrhyApi.md#GetGetrozvrhbymistnost) | **Get** /rozvrhy/getRozvrhByMistnost | rozvrhy operation
[**GetGetrozvrhbymistnostacas**](RozvrhyApi.md#GetGetrozvrhbymistnostacas) | **Get** /rozvrhy/getRozvrhByMistnostACas | rozvrhy operation
[**GetGetrozvrhbymistnostical**](RozvrhyApi.md#GetGetrozvrhbymistnostical) | **Get** /rozvrhy/getRozvrhByMistnostICAL | rozvrhy operation
[**GetGetrozvrhbymistnostpdf**](RozvrhyApi.md#GetGetrozvrhbymistnostpdf) | **Get** /rozvrhy/getRozvrhByMistnostPDF | rozvrhy operation
[**GetGetrozvrhbyplan**](RozvrhyApi.md#GetGetrozvrhbyplan) | **Get** /rozvrhy/getRozvrhByPlan | rozvrhy operation
[**GetGetrozvrhbyplanical**](RozvrhyApi.md#GetGetrozvrhbyplanical) | **Get** /rozvrhy/getRozvrhByPlanICAL | rozvrhy operation
[**GetGetrozvrhbyplanpdf**](RozvrhyApi.md#GetGetrozvrhbyplanpdf) | **Get** /rozvrhy/getRozvrhByPlanPDF | rozvrhy operation
[**GetGetrozvrhbypredmet**](RozvrhyApi.md#GetGetrozvrhbypredmet) | **Get** /rozvrhy/getRozvrhByPredmet | rozvrhy operation
[**GetGetrozvrhbypredmetical**](RozvrhyApi.md#GetGetrozvrhbypredmetical) | **Get** /rozvrhy/getRozvrhByPredmetICAL | rozvrhy operation
[**GetGetrozvrhbypredmetpdf**](RozvrhyApi.md#GetGetrozvrhbypredmetpdf) | **Get** /rozvrhy/getRozvrhByPredmetPDF | rozvrhy operation
[**GetGetrozvrhbystudent**](RozvrhyApi.md#GetGetrozvrhbystudent) | **Get** /rozvrhy/getRozvrhByStudent | rozvrhy operation
[**GetGetrozvrhbystudentical**](RozvrhyApi.md#GetGetrozvrhbystudentical) | **Get** /rozvrhy/getRozvrhByStudentICAL | rozvrhy operation
[**GetGetrozvrhbystudentpdf**](RozvrhyApi.md#GetGetrozvrhbystudentpdf) | **Get** /rozvrhy/getRozvrhByStudentPDF | rozvrhy operation
[**GetGetrozvrhbyucitel**](RozvrhyApi.md#GetGetrozvrhbyucitel) | **Get** /rozvrhy/getRozvrhByUcitel | rozvrhy operation
[**GetGetrozvrhbyucitelical**](RozvrhyApi.md#GetGetrozvrhbyucitelical) | **Get** /rozvrhy/getRozvrhByUcitelICAL | rozvrhy operation
[**GetGetrozvrhbyucitelpdf**](RozvrhyApi.md#GetGetrozvrhbyucitelpdf) | **Get** /rozvrhy/getRozvrhByUcitelPDF | rozvrhy operation
[**GetGetrozvrhovaakceinfo**](RozvrhyApi.md#GetGetrozvrhovaakceinfo) | **Get** /rozvrhy/getRozvrhovaAkceInfo | rozvrhy operation
[**GetGetrozvrhoveakce**](RozvrhyApi.md#GetGetrozvrhoveakce) | **Get** /rozvrhy/getRozvrhoveAkce | rozvrhy operation

# **GetGetpozadavkynacasvyuky**
> RozvrhType GetGetpozadavkynacasvyuky(ctx, optional)
rozvrhy operation

Operace 'GetGetpozadavkynacasvyuky' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetpozadavkynacasvyukyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetpozadavkynacasvyukyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **ucitIdno** | **optional.Int64**|  | 
 **katedra** | **optional.String**|  | 
 **fakulta** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykatedra**
> RozvrhType GetGetrozvrhbykatedra(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykatedra' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykatedraOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykatedraOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykatedraical**
> GetGetrozvrhbykatedraical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykatedraical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykatedraicalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykatedraicalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykatedrapdf**
> GetGetrozvrhbykatedrapdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykatedrapdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykatedrapdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykatedrapdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykrouzek**
> RozvrhType GetGetrozvrhbykrouzek(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykrouzek' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykrouzekOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykrouzekOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **kod** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykrouzekical**
> GetGetrozvrhbykrouzekical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykrouzekical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykrouzekicalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykrouzekicalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **kod** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbykrouzekpdf**
> GetGetrozvrhbykrouzekpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbykrouzekpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbykrouzekpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbykrouzekpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **kod** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbymistnost**
> RozvrhType GetGetrozvrhbymistnost(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbymistnost' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbymistnostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbymistnostOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **budova** | **optional.String**|  | 
 **mistnost** | **optional.String**|  | 
 **identifikatorMistnosti** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbymistnostacas**
> RozvrhType GetGetrozvrhbymistnostacas(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbymistnostacas' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbymistnostacasOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbymistnostacasOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **budova** | **optional.String**|  | 
 **mistnost** | **optional.String**|  | 
 **timestamp** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbymistnostical**
> GetGetrozvrhbymistnostical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbymistnostical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbymistnosticalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbymistnosticalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **budova** | **optional.String**|  | 
 **mistnost** | **optional.String**|  | 
 **identifikatorMistnosti** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbymistnostpdf**
> GetGetrozvrhbymistnostpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbymistnostpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbymistnostpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbymistnostpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **budova** | **optional.String**|  | 
 **mistnost** | **optional.String**|  | 
 **identifikatorMistnosti** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyplan**
> RozvrhType GetGetrozvrhbyplan(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyplan' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyplanOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyplanOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stplIdno** | **optional.Int64**|  | 
 **rocnik** | **optional.Int32**|  | 
 **statuty** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **zkrBudovy** | **optional.String**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyplanical**
> GetGetrozvrhbyplanical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyplanical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyplanicalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyplanicalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stplIdno** | **optional.Int64**|  | 
 **rocnik** | **optional.Int32**|  | 
 **statuty** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **zkrBudovy** | **optional.String**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyplanpdf**
> GetGetrozvrhbyplanpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyplanpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyplanpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyplanpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stplIdno** | **optional.Int64**|  | 
 **rocnik** | **optional.Int32**|  | 
 **statuty** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **zkrBudovy** | **optional.String**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbypredmet**
> RozvrhType GetGetrozvrhbypredmet(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbypredmet' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbypredmetOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbypredmetOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbypredmetical**
> GetGetrozvrhbypredmetical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbypredmetical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbypredmeticalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbypredmeticalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbypredmetpdf**
> GetGetrozvrhbypredmetpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbypredmetpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbypredmetpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbypredmetpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **zkratka** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbystudent**
> RozvrhType GetGetrozvrhbystudent(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbystudent' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbystudentOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbystudentOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osCislo** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbystudentical**
> GetGetrozvrhbystudentical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbystudentical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbystudenticalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbystudenticalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osCislo** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbystudentpdf**
> GetGetrozvrhbystudentpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbystudentpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbystudentpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbystudentpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osCislo** | **optional.String**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyucitel**
> RozvrhType GetGetrozvrhbyucitel(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyucitel' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyucitelOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyucitelOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **ucitIdno** | **optional.Int64**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyucitelical**
> GetGetrozvrhbyucitelical(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyucitelical' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyucitelicalOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyucitelicalOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **ucitIdno** | **optional.Int64**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhbyucitelpdf**
> GetGetrozvrhbyucitelpdf(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhbyucitelpdf' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhbyucitelpdfOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhbyucitelpdfOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **ucitIdno** | **optional.Int64**|  | 
 **rok** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **datumOd** | **optional.Time**|  | 
 **datumDo** | **optional.Time**|  | 
 **vsechnyAkce** | **optional.Bool**|  | 
 **vsechnyCasyKonani** | **optional.Bool**|  | 
 **jenRozvrhoveAkce** | **optional.Bool**|  | 
 **jenBudouciAkce** | **optional.Bool**|  | 
 **grafickyRozvrh** | **optional.Bool**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/pdf

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhovaakceinfo**
> AkceType GetGetrozvrhovaakceinfo(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhovaakceinfo' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhovaakceinfoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhovaakceinfoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **roakIdno** | **optional.Int64**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**AkceType**](akceType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetrozvrhoveakce**
> RozvrhType GetGetrozvrhoveakce(ctx, optional)
rozvrhy operation

Operace 'GetGetrozvrhoveakce' z kategorie 'rozvrhy'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***RozvrhyApiGetGetrozvrhoveakceOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a RozvrhyApiGetGetrozvrhoveakceOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **pracoviste** | **optional.String**|  | 
 **zkrPredm** | **optional.String**|  | 
 **zkrBudovy** | **optional.String**|  | 
 **cisloMistnosti** | **optional.String**|  | 
 **ucitIdno** | **optional.Int64**|  | 
 **den** | **optional.String**|  | 
 **rokVarianty** | **optional.String**|  | 
 **semestr** | **optional.String**|  | 
 **typ** | **optional.String**|  | 
 **owner** | **optional.String**|  | 
 **platnost** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

[**RozvrhType**](rozvrhType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

