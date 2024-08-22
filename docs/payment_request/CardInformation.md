# CardInformation
Card Information

## Properties
| Name | Type | Required | Description | Examples |
|------------|:-------------:|:-------------:|-------------|:-------------:|
| **TokenId** | Pointer to **string** |  |  |  |
| **MaskedCardNumber** | Pointer to **string** |  | 1st 6 and last 4 digits of the card |  |
| **ExpiryMonth** | Pointer to **string** |  | Card expiry month in MM format |  |
| **ExpiryYear** | Pointer to **string** |  | Card expiry month in YY format |  |
| **CardholderName** | Pointer to **NullableString** |  | Cardholder name |  |
| **Fingerprint** | Pointer to **string** |  |  |  |
| **Type** | Pointer to **string** |  |  |  |
| **Network** | Pointer to **string** |  |  |  |
| **Country** | Pointer to **string** |  |  |  |
| **Issuer** | Pointer to **string** |  |  |  |
| **CardNumber** | Pointer to **string** |  |  |  |
| **OneTimeToken** | Pointer to **string** |  |  |  |

## Methods

### NewCardInformation

`func NewCardInformation() *CardInformation`

NewCardInformation instantiates a new CardInformation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCardInformationWithDefaults

`func NewCardInformationWithDefaults() *CardInformation`

NewCardInformationWithDefaults instantiates a new CardInformation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTokenId

`func (o *CardInformation) GetTokenId() string`

GetTokenId returns the TokenId field if non-nil, zero value otherwise.

### GetTokenIdOk

`func (o *CardInformation) GetTokenIdOk() (*string, bool)`

GetTokenIdOk returns a tuple with the TokenId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenId

`func (o *CardInformation) SetTokenId(v string)`

SetTokenId sets TokenId field to given value.

### HasTokenId

`func (o *CardInformation) HasTokenId() bool`

HasTokenId returns a boolean if a field has been set.

### GetMaskedCardNumber

`func (o *CardInformation) GetMaskedCardNumber() string`

GetMaskedCardNumber returns the MaskedCardNumber field if non-nil, zero value otherwise.

### GetMaskedCardNumberOk

`func (o *CardInformation) GetMaskedCardNumberOk() (*string, bool)`

GetMaskedCardNumberOk returns a tuple with the MaskedCardNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaskedCardNumber

`func (o *CardInformation) SetMaskedCardNumber(v string)`

SetMaskedCardNumber sets MaskedCardNumber field to given value.

### HasMaskedCardNumber

`func (o *CardInformation) HasMaskedCardNumber() bool`

HasMaskedCardNumber returns a boolean if a field has been set.

### GetExpiryMonth

`func (o *CardInformation) GetExpiryMonth() string`

GetExpiryMonth returns the ExpiryMonth field if non-nil, zero value otherwise.

### GetExpiryMonthOk

`func (o *CardInformation) GetExpiryMonthOk() (*string, bool)`

GetExpiryMonthOk returns a tuple with the ExpiryMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryMonth

`func (o *CardInformation) SetExpiryMonth(v string)`

SetExpiryMonth sets ExpiryMonth field to given value.

### HasExpiryMonth

`func (o *CardInformation) HasExpiryMonth() bool`

HasExpiryMonth returns a boolean if a field has been set.

### GetExpiryYear

`func (o *CardInformation) GetExpiryYear() string`

GetExpiryYear returns the ExpiryYear field if non-nil, zero value otherwise.

### GetExpiryYearOk

`func (o *CardInformation) GetExpiryYearOk() (*string, bool)`

GetExpiryYearOk returns a tuple with the ExpiryYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryYear

`func (o *CardInformation) SetExpiryYear(v string)`

SetExpiryYear sets ExpiryYear field to given value.

### HasExpiryYear

`func (o *CardInformation) HasExpiryYear() bool`

HasExpiryYear returns a boolean if a field has been set.

### GetCardholderName

`func (o *CardInformation) GetCardholderName() string`

GetCardholderName returns the CardholderName field if non-nil, zero value otherwise.

### GetCardholderNameOk

`func (o *CardInformation) GetCardholderNameOk() (*string, bool)`

GetCardholderNameOk returns a tuple with the CardholderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardholderName

`func (o *CardInformation) SetCardholderName(v string)`

SetCardholderName sets CardholderName field to given value.

### HasCardholderName

`func (o *CardInformation) HasCardholderName() bool`

HasCardholderName returns a boolean if a field has been set.

### SetCardholderNameNil

`func (o *CardInformation) SetCardholderNameNil(b bool)`

 SetCardholderNameNil sets the value for CardholderName to be an explicit nil

### UnsetCardholderName
`func (o *CardInformation) UnsetCardholderName()`

UnsetCardholderName ensures that no value is present for CardholderName, not even an explicit nil
### GetFingerprint

`func (o *CardInformation) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *CardInformation) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *CardInformation) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.

### HasFingerprint

`func (o *CardInformation) HasFingerprint() bool`

HasFingerprint returns a boolean if a field has been set.

### GetType

`func (o *CardInformation) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CardInformation) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CardInformation) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CardInformation) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNetwork

`func (o *CardInformation) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *CardInformation) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *CardInformation) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *CardInformation) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetCountry

`func (o *CardInformation) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CardInformation) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CardInformation) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CardInformation) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetIssuer

`func (o *CardInformation) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *CardInformation) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *CardInformation) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.

### HasIssuer

`func (o *CardInformation) HasIssuer() bool`

HasIssuer returns a boolean if a field has been set.

### GetCardNumber

`func (o *CardInformation) GetCardNumber() string`

GetCardNumber returns the CardNumber field if non-nil, zero value otherwise.

### GetCardNumberOk

`func (o *CardInformation) GetCardNumberOk() (*string, bool)`

GetCardNumberOk returns a tuple with the CardNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCardNumber

`func (o *CardInformation) SetCardNumber(v string)`

SetCardNumber sets CardNumber field to given value.

### HasCardNumber

`func (o *CardInformation) HasCardNumber() bool`

HasCardNumber returns a boolean if a field has been set.

### GetOneTimeToken

`func (o *CardInformation) GetOneTimeToken() string`

GetOneTimeToken returns the OneTimeToken field if non-nil, zero value otherwise.

### GetOneTimeTokenOk

`func (o *CardInformation) GetOneTimeTokenOk() (*string, bool)`

GetOneTimeTokenOk returns a tuple with the OneTimeToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOneTimeToken

`func (o *CardInformation) SetOneTimeToken(v string)`

SetOneTimeToken sets OneTimeToken field to given value.

### HasOneTimeToken

`func (o *CardInformation) HasOneTimeToken() bool`

HasOneTimeToken returns a boolean if a field has been set.


[[Back to README]](../../README.md)


