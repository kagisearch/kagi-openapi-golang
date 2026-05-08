# \ExtractAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ExtractContent**](ExtractAPI.md#ExtractContent) | **Post** /extract | Extract page content as markdown from URLs



## ExtractContent

> ExtractResponse ExtractContent(ctx).ExtractRequest(extractRequest).Execute()

Extract page content as markdown from URLs



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kagisearch/kagi-openapi-golang"
)

func main() {
	extractRequest := *openapiclient.NewExtractRequest([]openapiclient.PageInput{*openapiclient.NewPageInput("https://example.com/article")}) // ExtractRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExtractAPI.ExtractContent(context.Background()).ExtractRequest(extractRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExtractAPI.ExtractContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExtractContent`: ExtractResponse
	fmt.Fprintf(os.Stdout, "Response from `ExtractAPI.ExtractContent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExtractContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **extractRequest** | [**ExtractRequest**](ExtractRequest.md) |  | 

### Return type

[**ExtractResponse**](ExtractResponse.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/markdown

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

