# {{classname}}

All URIs are relative to *https://stag-demo.zcu.cz/ws/services/rest2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetActivatestaguser**](UsersApi.md#GetActivatestaguser) | **Get** /users/activateStagUser | users operation
[**GetDeletestaguser**](UsersApi.md#GetDeletestaguser) | **Get** /users/deleteStagUser | users operation
[**GetGetexternalloginbyosobnicislo**](UsersApi.md#GetGetexternalloginbyosobnicislo) | **Get** /users/getExternalLoginByOsobniCislo | users operation
[**GetGetexternalloginbyucitidno**](UsersApi.md#GetGetexternalloginbyucitidno) | **Get** /users/getExternalLoginByUcitIdno | users operation
[**GetGetfotoosoby**](UsersApi.md#GetGetfotoosoby) | **Get** /users/getFotoOsoby | users operation
[**GetGetkalendarosoby**](UsersApi.md#GetGetkalendarosoby) | **Get** /users/getKalendarOsoby | users operation
[**GetGetosoba**](UsersApi.md#GetGetosoba) | **Get** /users/getOsoba | users operation
[**GetGetosobnicislabyexternallogin**](UsersApi.md#GetGetosobnicislabyexternallogin) | **Get** /users/getOsobniCislaByExternalLogin | users operation
[**GetGetstaguserforstaglogin**](UsersApi.md#GetGetstaguserforstaglogin) | **Get** /users/getStagUserForStagLogin | users operation
[**GetGetstaguserlistforexternallogin**](UsersApi.md#GetGetstaguserlistforexternallogin) | **Get** /users/getStagUserListForExternalLogin | users operation
[**GetGetstaguserlistforexternalloginv2**](UsersApi.md#GetGetstaguserlistforexternalloginv2) | **Get** /users/getStagUserListForExternalLoginV2 | users operation
[**GetGetstagusersroles**](UsersApi.md#GetGetstagusersroles) | **Get** /users/getStagUsersRoles | users operation
[**GetGetucitidnobyexternallogin**](UsersApi.md#GetGetucitidnobyexternallogin) | **Get** /users/getUcitIdnoByExternalLogin | users operation
[**GetKalendarLink**](UsersApi.md#GetKalendarLink) | **Get** /users/kalendar/{link} | users operation
[**GetKalendarLinkAnything**](UsersApi.md#GetKalendarLinkAnything) | **Get** /users/kalendar/{link}/{anything} | users operation
[**HeadKalendarLink**](UsersApi.md#HeadKalendarLink) | **Head** /users/kalendar/{link} | users operation
[**HeadKalendarLinkAnything**](UsersApi.md#HeadKalendarLinkAnything) | **Head** /users/kalendar/{link}/{anything} | users operation
[**PostInsertosoba**](UsersApi.md#PostInsertosoba) | **Post** /users/insertOsoba | users operation
[**PostInsertstaguser**](UsersApi.md#PostInsertstaguser) | **Post** /users/insertStagUser | users operation
[**PostUpdateosoba**](UsersApi.md#PostUpdateosoba) | **Post** /users/updateOsoba | users operation

# **GetActivatestaguser**
> GetActivatestaguser(ctx, optional)
users operation

Operace 'GetActivatestaguser' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetActivatestaguserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetActivatestaguserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stagUserNameForUpdate** | **optional.String**|  | 
 **stavAktivace** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetDeletestaguser**
> GetDeletestaguser(ctx, optional)
users operation

Operace 'GetDeletestaguser' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetDeletestaguserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetDeletestaguserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **stagUserNameForDelete** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetexternalloginbyosobnicislo**
> GetGetexternalloginbyosobnicislo(ctx, optional)
users operation

Operace 'GetGetexternalloginbyosobnicislo' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetexternalloginbyosobnicisloOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetexternalloginbyosobnicisloOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **osCislo** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetexternalloginbyucitidno**
> GetGetexternalloginbyucitidno(ctx, optional)
users operation

Operace 'GetGetexternalloginbyucitidno' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetexternalloginbyucitidnoOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetexternalloginbyucitidnoOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ucitIdno** | **optional.Int64**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetfotoosoby**
> GetGetfotoosoby(ctx, optional)
users operation

Operace 'GetGetfotoosoby' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetfotoosobyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetfotoosobyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osobIdno** | **optional.Int64**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetkalendarosoby**
> GetGetkalendarosoby(ctx, optional)
users operation

Operace 'GetGetkalendarosoby' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetkalendarosobyOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetkalendarosobyOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **login** | **optional.String**|  | 
 **rokOd** | **optional.Int64**|  | 
 **rokDo** | **optional.Int64**|  | 
 **semestr** | **optional.String**|  | 
 **lang** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/calendar

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetosoba**
> OsobaType GetGetosoba(ctx, optional)
users operation

Operace 'GetGetosoba' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetosobaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetosobaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **osobIdno** | **optional.Int64**|  | 
 **osCislo** | **optional.String**|  | 
 **rodCislo** | **optional.String**|  | 

### Return type

[**OsobaType**](osobaType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetosobnicislabyexternallogin**
> OsobniCislaType GetGetosobnicislabyexternallogin(ctx, optional)
users operation

Operace 'GetGetosobnicislabyexternallogin' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetosobnicislabyexternalloginOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetosobnicislabyexternalloginOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **login** | **optional.String**|  | 
 **pouzeStudujici** | **optional.Bool**|  | 

### Return type

[**OsobniCislaType**](osobniCislaType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserforstaglogin**
> StagUserType GetGetstaguserforstaglogin(ctx, optional)
users operation

Operace 'GetGetstaguserforstaglogin' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetstaguserforstagloginOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetstaguserforstagloginOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **login** | **optional.String**|  | 

### Return type

[**StagUserType**](stagUserType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforexternallogin**
> StagUserListType GetGetstaguserlistforexternallogin(ctx, optional)
users operation

Operace 'GetGetstaguserlistforexternallogin' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetstaguserlistforexternalloginOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetstaguserlistforexternalloginOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **externalLogin** | **optional.String**|  | 

### Return type

[**StagUserListType**](stagUserListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstaguserlistforexternalloginv2**
> StagUserListV2Type GetGetstaguserlistforexternalloginv2(ctx, optional)
users operation

Operace 'GetGetstaguserlistforexternalloginv2' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetstaguserlistforexternalloginv2Opts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetstaguserlistforexternalloginv2Opts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **externalLogin** | **optional.String**|  | 

### Return type

[**StagUserListV2Type**](stagUserListV2Type.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetstagusersroles**
> StagUserRoleListType GetGetstagusersroles(ctx, optional)
users operation

Operace 'GetGetstagusersroles' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetstagusersrolesOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetstagusersrolesOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 
 **fakulta** | **optional.String**|  | 
 **katedra** | **optional.String**|  | 
 **idRole** | **optional.String**|  | 

### Return type

[**StagUserRoleListType**](stagUserRoleListType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetGetucitidnobyexternallogin**
> GetGetucitidnobyexternallogin(ctx, optional)
users operation

Operace 'GetGetucitidnobyexternallogin' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiGetGetucitidnobyexternalloginOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGetGetucitidnobyexternalloginOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **externalLogin** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, text/xml, application/json, text/yaml, text/csv, application/vnd.ms-excel, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetKalendarLink**
> GetKalendarLink(ctx, link)
users operation

Operace 'GetKalendarLink' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **link** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetKalendarLinkAnything**
> GetKalendarLinkAnything(ctx, link, anything)
users operation

Operace 'GetKalendarLinkAnything' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **link** | **string**|  | 
  **anything** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HeadKalendarLink**
> HeadKalendarLink(ctx, link)
users operation

Operace 'HeadKalendarLink' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **link** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HeadKalendarLinkAnything**
> HeadKalendarLinkAnything(ctx, link, anything)
users operation

Operace 'HeadKalendarLinkAnything' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **link** | **string**|  | 
  **anything** | **string**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostInsertosoba**
> OsobaType PostInsertosoba(ctx, optional)
users operation

Operace 'PostInsertosoba' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiPostInsertosobaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiPostInsertosobaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**OsobaType**](osobaType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostInsertstaguser**
> StagUserForEditType PostInsertstaguser(ctx, optional)
users operation

Operace 'PostInsertstaguser' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiPostInsertstaguserOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiPostInsertstaguserOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

[**StagUserForEditType**](stagUserForEditType.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PostUpdateosoba**
> PostUpdateosoba(ctx, optional)
users operation

Operace 'PostUpdateosoba' z kategorie 'users'.

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***UsersApiPostUpdateosobaOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiPostUpdateosobaOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stagUser** | **optional.String**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

