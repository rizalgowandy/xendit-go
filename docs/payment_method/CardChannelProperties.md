# CardChannelProperties
Card Channel Properties

## Properties
| Name | Type | Required | Description | Examples |
|------------|:-------------:|:-------------:|-------------|:-------------:|
| **SkipThreeDSecure** | Pointer to **NullableBool** |  | This field value is only being used for reusability &#x3D; MULTIPLE_USE. To indicate whether to perform 3DS during the linking phase. Defaults to false. |  |
| **SuccessReturnUrl** | Pointer to **NullableString** |  | URL where the end-customer is redirected if the authorization is successful |  |
| **FailureReturnUrl** | Pointer to **NullableString** |  | URL where the end-customer is redirected if the authorization failed |  |
| **CardonfileType** | Pointer to **NullableString** |  | Type of “credential-on-file” / “card-on-file” payment being made. Indicate that this payment uses a previously linked Payment Method for charging. |  |
| **ExpiresAt** | Pointer to **time.Time** |  |  |  |
| **InstallmentConfiguration** | Pointer to [**NullableCardInstallmentConfiguration**](CardInstallmentConfiguration.md) |  |  |  |
| **MerchantIdTag** | Pointer to **string** |  | Tag for a Merchant ID that you want to associate this payment with. For merchants using their own MIDs to specify which MID they want to use |  |

## Methods

### NewCardChannelProperties

`func NewCardChannelProperties() *CardChannelProperties`

NewCardChannelProperties instantiates a new CardChannelProperties object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCardChannelPropertiesWithDefaults

`func NewCardChannelPropertiesWithDefaults() *CardChannelProperties`

NewCardChannelPropertiesWithDefaults instantiates a new CardChannelProperties object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSkipThreeDSecure

`func (o *CardChannelProperties) GetSkipThreeDSecure() bool`

GetSkipThreeDSecure returns the SkipThreeDSecure field if non-nil, zero value otherwise.

### GetSkipThreeDSecureOk

`func (o *CardChannelProperties) GetSkipThreeDSecureOk() (*bool, bool)`

GetSkipThreeDSecureOk returns a tuple with the SkipThreeDSecure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipThreeDSecure

`func (o *CardChannelProperties) SetSkipThreeDSecure(v bool)`

SetSkipThreeDSecure sets SkipThreeDSecure field to given value.

### HasSkipThreeDSecure

`func (o *CardChannelProperties) HasSkipThreeDSecure() bool`

HasSkipThreeDSecure returns a boolean if a field has been set.

### SetSkipThreeDSecureNil

`func (o *CardChannelProperties) SetSkipThreeDSecureNil(b bool)`

 SetSkipThreeDSecureNil sets the value for SkipThreeDSecure to be an explicit nil

### UnsetSkipThreeDSecure
`func (o *CardChannelProperties) UnsetSkipThreeDSecure()`

UnsetSkipThreeDSecure ensures that no value is present for SkipThreeDSecure, not even an explicit nil
### GetSuccessReturnUrl

`func (o *CardChannelProperties) GetSuccessReturnUrl() string`

GetSuccessReturnUrl returns the SuccessReturnUrl field if non-nil, zero value otherwise.

### GetSuccessReturnUrlOk

`func (o *CardChannelProperties) GetSuccessReturnUrlOk() (*string, bool)`

GetSuccessReturnUrlOk returns a tuple with the SuccessReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessReturnUrl

`func (o *CardChannelProperties) SetSuccessReturnUrl(v string)`

SetSuccessReturnUrl sets SuccessReturnUrl field to given value.

### HasSuccessReturnUrl

`func (o *CardChannelProperties) HasSuccessReturnUrl() bool`

HasSuccessReturnUrl returns a boolean if a field has been set.

### SetSuccessReturnUrlNil

`func (o *CardChannelProperties) SetSuccessReturnUrlNil(b bool)`

 SetSuccessReturnUrlNil sets the value for SuccessReturnUrl to be an explicit nil

### UnsetSuccessReturnUrl
`func (o *CardChannelProperties) UnsetSuccessReturnUrl()`

UnsetSuccessReturnUrl ensures that no value is present for SuccessReturnUrl, not even an explicit nil
### GetFailureReturnUrl

`func (o *CardChannelProperties) GetFailureReturnUrl() string`

GetFailureReturnUrl returns the FailureReturnUrl field if non-nil, zero value otherwise.

### GetFailureReturnUrlOk

`func (o *CardChannelProperties) GetFailureReturnUrlOk() (*string, bool)`

GetFailureReturnUrlOk returns a tuple with the FailureReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReturnUrl

`func (o *CardChannelProperties) SetFailureReturnUrl(v string)`

SetFailureReturnUrl sets FailureReturnUrl field to given value.

### HasFailureReturnUrl

`func (o *CardChannelProperties) HasFailureReturnUrl() bool`

HasFailureReturnUrl returns a boolean if a field has been set.

### SetFailureReturnUrlNil

`func (o *CardChannelProperties) SetFailureReturnUrlNil(b bool)`

 SetFailureReturnUrlNil sets the value for FailureReturnUrl to be an explicit nil

### UnsetFailureReturnUrl
`func (o *CardChannelProperties) UnsetFailureReturnUrl()`

UnsetFailureReturnUrl ensures that no value is present for FailureReturnUrl, not even an explicit nil
### GetCardonfileType

`func (o *CardChannelProperties) GetCardonfileType() string`

GetCardonfileType returns the CardonfileType field if non-nil, zero value otherwise.

### GetCardonfileTypeOk

`func (o *CardChannelProperties) GetCardonfileTypeOk() (*string, bool)`

GetCardonfileTypeOk returns a tuple with the CardonfileType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardonfileType

`func (o *CardChannelProperties) SetCardonfileType(v string)`

SetCardonfileType sets CardonfileType field to given value.

### HasCardonfileType

`func (o *CardChannelProperties) HasCardonfileType() bool`

HasCardonfileType returns a boolean if a field has been set.

### SetCardonfileTypeNil

`func (o *CardChannelProperties) SetCardonfileTypeNil(b bool)`

 SetCardonfileTypeNil sets the value for CardonfileType to be an explicit nil

### UnsetCardonfileType
`func (o *CardChannelProperties) UnsetCardonfileType()`

UnsetCardonfileType ensures that no value is present for CardonfileType, not even an explicit nil
### GetExpiresAt

`func (o *CardChannelProperties) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CardChannelProperties) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CardChannelProperties) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CardChannelProperties) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetInstallmentConfiguration

`func (o *CardChannelProperties) GetInstallmentConfiguration() CardInstallmentConfiguration`

GetInstallmentConfiguration returns the InstallmentConfiguration field if non-nil, zero value otherwise.

### GetInstallmentConfigurationOk

`func (o *CardChannelProperties) GetInstallmentConfigurationOk() (*CardInstallmentConfiguration, bool)`

GetInstallmentConfigurationOk returns a tuple with the InstallmentConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallmentConfiguration

`func (o *CardChannelProperties) SetInstallmentConfiguration(v CardInstallmentConfiguration)`

SetInstallmentConfiguration sets InstallmentConfiguration field to given value.

### HasInstallmentConfiguration

`func (o *CardChannelProperties) HasInstallmentConfiguration() bool`

HasInstallmentConfiguration returns a boolean if a field has been set.

### SetInstallmentConfigurationNil

`func (o *CardChannelProperties) SetInstallmentConfigurationNil(b bool)`

 SetInstallmentConfigurationNil sets the value for InstallmentConfiguration to be an explicit nil

### UnsetInstallmentConfiguration
`func (o *CardChannelProperties) UnsetInstallmentConfiguration()`

UnsetInstallmentConfiguration ensures that no value is present for InstallmentConfiguration, not even an explicit nil
### GetMerchantIdTag

`func (o *CardChannelProperties) GetMerchantIdTag() string`

GetMerchantIdTag returns the MerchantIdTag field if non-nil, zero value otherwise.

### GetMerchantIdTagOk

`func (o *CardChannelProperties) GetMerchantIdTagOk() (*string, bool)`

GetMerchantIdTagOk returns a tuple with the MerchantIdTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerchantIdTag

`func (o *CardChannelProperties) SetMerchantIdTag(v string)`

SetMerchantIdTag sets MerchantIdTag field to given value.

### HasMerchantIdTag

`func (o *CardChannelProperties) HasMerchantIdTag() bool`

HasMerchantIdTag returns a boolean if a field has been set.


[[Back to README]](../../README.md)


