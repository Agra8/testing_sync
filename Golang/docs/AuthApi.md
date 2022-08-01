# \AuthApi

All URIs are relative to *https://virtserver.swaggerhub.com/Agra8/Test/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Login**](AuthApi.md#Login) | **Post** /loginv2.php | Login


# **Login**
> Login(ctx, optional)
Login

Login to Ttsm

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***AuthApiLoginOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a AuthApiLoginOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **optional.String**| username | 
 **password** | **optional.String**| password | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

