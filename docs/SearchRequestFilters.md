# SearchRequestFilters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Region** | Pointer to **string** | Filter results to a specific region using an ISO 3166-1 Alpha-2 country code. See https://help.kagi.com/api/regions for supported codes. | [optional] 
**After** | Pointer to **string** | Filter for results published or updated after this date. | [optional] 
**Before** | Pointer to **string** | Filter for results published or updated before this date. | [optional] 

## Methods

### NewSearchRequestFilters

`func NewSearchRequestFilters() *SearchRequestFilters`

NewSearchRequestFilters instantiates a new SearchRequestFilters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestFiltersWithDefaults

`func NewSearchRequestFiltersWithDefaults() *SearchRequestFilters`

NewSearchRequestFiltersWithDefaults instantiates a new SearchRequestFilters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegion

`func (o *SearchRequestFilters) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *SearchRequestFilters) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *SearchRequestFilters) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *SearchRequestFilters) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetAfter

`func (o *SearchRequestFilters) GetAfter() string`

GetAfter returns the After field if non-nil, zero value otherwise.

### GetAfterOk

`func (o *SearchRequestFilters) GetAfterOk() (*string, bool)`

GetAfterOk returns a tuple with the After field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAfter

`func (o *SearchRequestFilters) SetAfter(v string)`

SetAfter sets After field to given value.

### HasAfter

`func (o *SearchRequestFilters) HasAfter() bool`

HasAfter returns a boolean if a field has been set.

### GetBefore

`func (o *SearchRequestFilters) GetBefore() string`

GetBefore returns the Before field if non-nil, zero value otherwise.

### GetBeforeOk

`func (o *SearchRequestFilters) GetBeforeOk() (*string, bool)`

GetBeforeOk returns a tuple with the Before field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBefore

`func (o *SearchRequestFilters) SetBefore(v string)`

SetBefore sets Before field to given value.

### HasBefore

`func (o *SearchRequestFilters) HasBefore() bool`

HasBefore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


