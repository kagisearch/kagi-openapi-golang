# SearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** | Search query to run. | 
**Workflow** | Pointer to **string** | Type of results to return. | [optional] [default to "search"]
**Format** | Pointer to **string** | **(EXPERIMENTAL)** Format to serialize the API response as. The exact contents and structure of markdown output is still being worked on - please send your feedback! | [optional] [default to "json"]
**LensId** | Pointer to **string** | Lens to apply to the search. Can be a built-in lens&#39;s identifier or a lens ID as shown on https://kagi.com/settings/lenses when a lens is set to be shareable. Can be just the ID portion of the URL (&#x60;https://kagi.com/lenses/ID&#x60;) or the full URL. | [optional] 
**Lens** | Pointer to [**SearchRequestLens**](SearchRequestLens.md) |  | [optional] 
**Timeout** | Pointer to **float32** | Number of seconds to allow for collecting search results. Lower values will return results more quickly, but may be lower quality or inconsistent between calls. If omitted, will use the latest recommended value by Kagi. | [optional] 
**Page** | Pointer to **int32** | Page number for paginated results. Must be between 1 and 10. | [optional] 
**Limit** | Pointer to **int32** | Maximum number of results to return. Must be between 1 and 1024. | [optional] 
**Filters** | Pointer to [**SearchRequestFilters**](SearchRequestFilters.md) |  | [optional] 
**Extract** | Pointer to [**SearchRequestExtract**](SearchRequestExtract.md) |  | [optional] 
**SafeSearch** | Pointer to **bool** | Whether safe search is enabled, omitting potentially NSFW content. | [optional] [default to true]
**Personalizations** | Pointer to [**SearchRequestPersonalizations**](SearchRequestPersonalizations.md) |  | [optional] 

## Methods

### NewSearchRequest

`func NewSearchRequest(query string, ) *SearchRequest`

NewSearchRequest instantiates a new SearchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestWithDefaults

`func NewSearchRequestWithDefaults() *SearchRequest`

NewSearchRequestWithDefaults instantiates a new SearchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchRequest) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetWorkflow

`func (o *SearchRequest) GetWorkflow() string`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *SearchRequest) GetWorkflowOk() (*string, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *SearchRequest) SetWorkflow(v string)`

SetWorkflow sets Workflow field to given value.

### HasWorkflow

`func (o *SearchRequest) HasWorkflow() bool`

HasWorkflow returns a boolean if a field has been set.

### GetFormat

`func (o *SearchRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *SearchRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *SearchRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *SearchRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetLensId

`func (o *SearchRequest) GetLensId() string`

GetLensId returns the LensId field if non-nil, zero value otherwise.

### GetLensIdOk

`func (o *SearchRequest) GetLensIdOk() (*string, bool)`

GetLensIdOk returns a tuple with the LensId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensId

`func (o *SearchRequest) SetLensId(v string)`

SetLensId sets LensId field to given value.

### HasLensId

`func (o *SearchRequest) HasLensId() bool`

HasLensId returns a boolean if a field has been set.

### GetLens

`func (o *SearchRequest) GetLens() SearchRequestLens`

GetLens returns the Lens field if non-nil, zero value otherwise.

### GetLensOk

`func (o *SearchRequest) GetLensOk() (*SearchRequestLens, bool)`

GetLensOk returns a tuple with the Lens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLens

`func (o *SearchRequest) SetLens(v SearchRequestLens)`

SetLens sets Lens field to given value.

### HasLens

`func (o *SearchRequest) HasLens() bool`

HasLens returns a boolean if a field has been set.

### GetTimeout

`func (o *SearchRequest) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *SearchRequest) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *SearchRequest) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *SearchRequest) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.

### GetPage

`func (o *SearchRequest) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SearchRequest) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SearchRequest) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SearchRequest) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetLimit

`func (o *SearchRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SearchRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SearchRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SearchRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetFilters

`func (o *SearchRequest) GetFilters() SearchRequestFilters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *SearchRequest) GetFiltersOk() (*SearchRequestFilters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *SearchRequest) SetFilters(v SearchRequestFilters)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *SearchRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetExtract

`func (o *SearchRequest) GetExtract() SearchRequestExtract`

GetExtract returns the Extract field if non-nil, zero value otherwise.

### GetExtractOk

`func (o *SearchRequest) GetExtractOk() (*SearchRequestExtract, bool)`

GetExtractOk returns a tuple with the Extract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtract

`func (o *SearchRequest) SetExtract(v SearchRequestExtract)`

SetExtract sets Extract field to given value.

### HasExtract

`func (o *SearchRequest) HasExtract() bool`

HasExtract returns a boolean if a field has been set.

### GetSafeSearch

`func (o *SearchRequest) GetSafeSearch() bool`

GetSafeSearch returns the SafeSearch field if non-nil, zero value otherwise.

### GetSafeSearchOk

`func (o *SearchRequest) GetSafeSearchOk() (*bool, bool)`

GetSafeSearchOk returns a tuple with the SafeSearch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafeSearch

`func (o *SearchRequest) SetSafeSearch(v bool)`

SetSafeSearch sets SafeSearch field to given value.

### HasSafeSearch

`func (o *SearchRequest) HasSafeSearch() bool`

HasSafeSearch returns a boolean if a field has been set.

### GetPersonalizations

`func (o *SearchRequest) GetPersonalizations() SearchRequestPersonalizations`

GetPersonalizations returns the Personalizations field if non-nil, zero value otherwise.

### GetPersonalizationsOk

`func (o *SearchRequest) GetPersonalizationsOk() (*SearchRequestPersonalizations, bool)`

GetPersonalizationsOk returns a tuple with the Personalizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonalizations

`func (o *SearchRequest) SetPersonalizations(v SearchRequestPersonalizations)`

SetPersonalizations sets Personalizations field to given value.

### HasPersonalizations

`func (o *SearchRequest) HasPersonalizations() bool`

HasPersonalizations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


