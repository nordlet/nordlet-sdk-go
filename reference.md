# Reference
## Reference
<details><summary><code>client.Reference.PostV1ReferenceExchangeRatesSync(request) -> *nordlet.PostV1ReferenceExchangeRatesSyncResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceExchangeRatesSyncRequest{}
client.Reference.PostV1ReferenceExchangeRatesSync(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceExchangeRatesList(request) -> *nordlet.PostV1ReferenceExchangeRatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceExchangeRatesListRequest{}
client.Reference.PostV1ReferenceExchangeRatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceExchangeRatesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceExchangeRatesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceExchangeRatesSet(request) -> *nordlet.PostV1ReferenceExchangeRatesSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceExchangeRatesSetRequest{
        Currency: "currency",
        Date: "date",
        Rate: "rate",
    }
client.Reference.PostV1ReferenceExchangeRatesSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**currency:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**rate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceExchangeRatesOverridesList(request) -> *nordlet.PostV1ReferenceExchangeRatesOverridesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceExchangeRatesOverridesListRequest{}
client.Reference.PostV1ReferenceExchangeRatesOverridesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceExchangeRatesOverridesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceExchangeRatesOverridesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceExchangeRatesOverridesDelete(request) -> *nordlet.PostV1ReferenceExchangeRatesOverridesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceExchangeRatesOverridesDeleteRequest{
        Currency: "currency",
        Date: "date",
    }
client.Reference.PostV1ReferenceExchangeRatesOverridesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**currency:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceCountriesList(request) -> *nordlet.PostV1ReferenceCountriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceCountriesListRequest{}
client.Reference.PostV1ReferenceCountriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceLtCountiesList(request) -> *nordlet.PostV1ReferenceLtCountiesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceLtCountiesListRequest{}
client.Reference.PostV1ReferenceLtCountiesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceLtMunicipalitiesList(request) -> *nordlet.PostV1ReferenceLtMunicipalitiesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceLtMunicipalitiesListRequest{}
client.Reference.PostV1ReferenceLtMunicipalitiesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countyCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceLtCitiesList(request) -> *nordlet.PostV1ReferenceLtCitiesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceLtCitiesListRequest{}
client.Reference.PostV1ReferenceLtCitiesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**municipalityCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**q:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceBanksList(request) -> *nordlet.PostV1ReferenceBanksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceBanksListRequest{}
client.Reference.PostV1ReferenceBanksList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceBanksListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceBanksListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceBanksUpsert(request) -> *nordlet.PostV1ReferenceBanksUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceBanksUpsertRequest{
        CountryCode: "countryCode",
        Name: "name",
        Bic: "bic",
    }
client.Reference.PostV1ReferenceBanksUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bankCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceLtRegionsList(request) -> *nordlet.PostV1ReferenceLtRegionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceLtRegionsListRequest{}
client.Reference.PostV1ReferenceLtRegionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceCurrenciesList(request) -> *nordlet.PostV1ReferenceCurrenciesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceCurrenciesListRequest{}
client.Reference.PostV1ReferenceCurrenciesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceCurrenciesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceCurrenciesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceVatClassifiersList(request) -> *nordlet.PostV1ReferenceVatClassifiersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceVatClassifiersListRequest{}
client.Reference.PostV1ReferenceVatClassifiersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceVatClassifiersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceVatClassifiersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceVatClassifiersUpsert(request) -> *nordlet.PostV1ReferenceVatClassifiersUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceVatClassifiersUpsertRequest{
        Rows: []*nordlet.PostV1ReferenceVatClassifiersUpsertRequestRowsItem{
            &nordlet.PostV1ReferenceVatClassifiersUpsertRequestRowsItem{
                Code: "code",
                Name: "name",
            },
        },
    }
client.Reference.PostV1ReferenceVatClassifiersUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `[]*nordlet.PostV1ReferenceVatClassifiersUpsertRequestRowsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceEuVatRatesList(request) -> *nordlet.PostV1ReferenceEuVatRatesListResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Effective EU VAT rate mapping for this company: EC TEDB defaults, replaced per country by any company overrides. Verify the mapping fits the goods and services you sell before relying on it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceEuVatRatesListRequest{}
client.Reference.PostV1ReferenceEuVatRatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceEuVatRatesSetOverrides(request) -> *nordlet.PostV1ReferenceEuVatRatesSetOverridesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the VAT rate mapping this company uses for one EU country. Pass an empty rates array to drop the overrides and return to the TEDB defaults. Overrides feed rate suggestions (vat/resolve) and OSS/IOSS return rate classification.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceEuVatRatesSetOverridesRequest{
        CountryCode: "countryCode",
        Rates: []*nordlet.PostV1ReferenceEuVatRatesSetOverridesRequestRatesItem{
            &nordlet.PostV1ReferenceEuVatRatesSetOverridesRequestRatesItem{
                Category: nordlet.PostV1ReferenceEuVatRatesSetOverridesRequestRatesItemCategoryStandard,
                RatePercent: "ratePercent",
            },
        },
    }
client.Reference.PostV1ReferenceEuVatRatesSetOverrides(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**rates:** `[]*nordlet.PostV1ReferenceEuVatRatesSetOverridesRequestRatesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceVatResolve(request) -> *nordlet.PostV1ReferenceVatResolveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceVatResolveRequest{}
client.Reference.PostV1ReferenceVatResolve(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**customerCountryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**customerIsBusiness:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**supplyType:** `*nordlet.PostV1ReferenceVatResolveRequestSupplyType` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**belowDistanceSalesThreshold:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**facilitatedByMarketplace:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**actingAsMarketplace:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**sellerEstablishedInEu:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**importedConsignmentValueEur:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceCnCodesList(request) -> *nordlet.PostV1ReferenceCnCodesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceCnCodesListRequest{}
client.Reference.PostV1ReferenceCnCodesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceCnCodesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceCnCodesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceCnCodesUpsert(request) -> *nordlet.PostV1ReferenceCnCodesUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceCnCodesUpsertRequest{
        Rows: []*nordlet.PostV1ReferenceCnCodesUpsertRequestRowsItem{
            &nordlet.PostV1ReferenceCnCodesUpsertRequestRowsItem{
                Code: "code",
                Name: "name",
            },
        },
    }
client.Reference.PostV1ReferenceCnCodesUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `[]*nordlet.PostV1ReferenceCnCodesUpsertRequestRowsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceComplianceVersionsList(request) -> *nordlet.PostV1ReferenceComplianceVersionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceComplianceVersionsListRequest{}
client.Reference.PostV1ReferenceComplianceVersionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**country:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceIntrastatThresholdsList(request) -> *nordlet.PostV1ReferenceIntrastatThresholdsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceIntrastatThresholdsListRequest{}
client.Reference.PostV1ReferenceIntrastatThresholdsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceUnitsList(request) -> *nordlet.PostV1ReferenceUnitsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceUnitsListRequest{}
client.Reference.PostV1ReferenceUnitsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceUnitsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceUnitsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceSeriesCreate(request) -> *nordlet.PostV1ReferenceSeriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceSeriesCreateRequest{
        DocumentType: "documentType",
        Year: int64(1000000),
    }
client.Reference.PostV1ReferenceSeriesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**documentType:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**startAt:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.PostV1ReferenceSeriesList(request) -> *nordlet.PostV1ReferenceSeriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReferenceSeriesListRequest{}
client.Reference.PostV1ReferenceSeriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReferenceSeriesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReferenceSeriesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Partners
<details><summary><code>client.Partners.PostV1PartnersAddressesCreate(request) -> *nordlet.PostV1PartnersAddressesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersAddressesCreateRequest{
        PartnerID: "partnerId",
    }
client.Partners.PostV1PartnersAddressesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1PartnersAddressesCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**street:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**city:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**postalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersAddressesUpdate(request) -> *nordlet.PostV1PartnersAddressesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersAddressesUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersAddressesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1PartnersAddressesUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**street:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**city:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**postalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersAddressesDelete(request) -> *nordlet.PostV1PartnersAddressesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersAddressesDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersAddressesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersAddressesList(request) -> *nordlet.PostV1PartnersAddressesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersAddressesListRequest{}
client.Partners.PostV1PartnersAddressesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersAddressesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersAddressesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersContactsCreate(request) -> *nordlet.PostV1PartnersContactsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersContactsCreateRequest{
        Name: "name",
        PartnerID: "partnerId",
    }
client.Partners.PostV1PartnersContactsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersContactsUpdate(request) -> *nordlet.PostV1PartnersContactsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersContactsUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersContactsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersContactsDelete(request) -> *nordlet.PostV1PartnersContactsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersContactsDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersContactsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersContactsList(request) -> *nordlet.PostV1PartnersContactsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersContactsListRequest{}
client.Partners.PostV1PartnersContactsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersContactsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersContactsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersBankAccountsCreate(request) -> *nordlet.PostV1PartnersBankAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersBankAccountsCreateRequest{
        Iban: "iban",
        PartnerID: "partnerId",
    }
client.Partners.PostV1PartnersBankAccountsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**iban:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersBankAccountsUpdate(request) -> *nordlet.PostV1PartnersBankAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersBankAccountsUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersBankAccountsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersBankAccountsDelete(request) -> *nordlet.PostV1PartnersBankAccountsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersBankAccountsDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersBankAccountsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersBankAccountsList(request) -> *nordlet.PostV1PartnersBankAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersBankAccountsListRequest{}
client.Partners.PostV1PartnersBankAccountsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersBankAccountsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersBankAccountsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersFilesList(request) -> *nordlet.PostV1PartnersFilesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersFilesListRequest{
        PartnerID: "partnerId",
    }
client.Partners.PostV1PartnersFilesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.RemindersTheOvernightDebtReminderJobWouldSendTodayForThisCompany(request) -> *nordlet.PostV1PartnersDebtRemindersPreviewResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersDebtRemindersPreviewRequest{}
client.Partners.RemindersTheOvernightDebtReminderJobWouldSendTodayForThisCompany(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersDebtRemindersList(request) -> *nordlet.PostV1PartnersDebtRemindersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersDebtRemindersListRequest{}
client.Partners.PostV1PartnersDebtRemindersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersDebtRemindersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersDebtRemindersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersValidateVat(request) -> *nordlet.PostV1PartnersValidateVatResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersValidateVatRequest{}
client.Partners.PostV1PartnersValidateVat(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersVatReviewsList(request) -> *nordlet.PostV1PartnersVatReviewsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersVatReviewsListRequest{}
client.Partners.PostV1PartnersVatReviewsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersVatReviewsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersVatReviewsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersVatReviewsResolve(request) -> *nordlet.PostV1PartnersVatReviewsResolveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersVatReviewsResolveRequest{
        ID: "id",
        Resolution: nordlet.PostV1PartnersVatReviewsResolveRequestResolutionConfirmedValid,
    }
client.Partners.PostV1PartnersVatReviewsResolve(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**resolution:** `*nordlet.PostV1PartnersVatReviewsResolveRequestResolution` 
    
</dd>
</dl>

<dl>
<dd>

**note:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersCreate(request) -> *nordlet.PostV1PartnersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersCreateRequest{
        Name: "name",
    }
client.Partners.PostV1PartnersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1PartnersCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**peppolID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceListID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**statusID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1PartnersCreateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.PostV1PartnersCreateRequestCorrespondenceAddress` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `*nordlet.PostV1PartnersCreateRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersFindOrCreate(request) -> *nordlet.PostV1PartnersFindOrCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersFindOrCreateRequest{
        Name: "name",
    }
client.Partners.PostV1PartnersFindOrCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1PartnersFindOrCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**peppolID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceListID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**statusID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1PartnersFindOrCreateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.PostV1PartnersFindOrCreateRequestCorrespondenceAddress` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `*nordlet.PostV1PartnersFindOrCreateRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersGet(request) -> *nordlet.PostV1PartnersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersGetRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersUpdate(request) -> *nordlet.PostV1PartnersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1PartnersUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**peppolID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceListID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**statusID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1PartnersUpdateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.PostV1PartnersUpdateRequestCorrespondenceAddress` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `*nordlet.PostV1PartnersUpdateRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersDelete(request) -> *nordlet.PostV1PartnersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.BlankAPartnersPersonalDataAndHideTheRecord(request) -> *nordlet.PostV1PartnersAnonymizeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes birth date, self-employment certificate number, email, phone, address, notes, contacts, addresses and bank accounts, then hides the partner. The name, code and VAT number stay because issued invoices must keep identifying the counterparty for the statutory retention period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersAnonymizeRequest{
        ID: "id",
    }
client.Partners.BlankAPartnersPersonalDataAndHideTheRecord(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersList(request) -> *nordlet.PostV1PartnersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersListRequest{}
client.Partners.PostV1PartnersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersGroupsCreate(request) -> *nordlet.PostV1PartnersGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersGroupsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Partners.PostV1PartnersGroupsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersGroupsUpdate(request) -> *nordlet.PostV1PartnersGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersGroupsUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersGroupsDelete(request) -> *nordlet.PostV1PartnersGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersGroupsDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersGroupsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersGroupsList(request) -> *nordlet.PostV1PartnersGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersGroupsListRequest{}
client.Partners.PostV1PartnersGroupsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersStatusesCreate(request) -> *nordlet.PostV1PartnersStatusesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersStatusesCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Partners.PostV1PartnersStatusesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersStatusesUpdate(request) -> *nordlet.PostV1PartnersStatusesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersStatusesUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersStatusesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersStatusesDelete(request) -> *nordlet.PostV1PartnersStatusesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersStatusesDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersStatusesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersStatusesList(request) -> *nordlet.PostV1PartnersStatusesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersStatusesListRequest{}
client.Partners.PostV1PartnersStatusesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersInquiriesCreate(request) -> *nordlet.PostV1PartnersInquiriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersInquiriesCreateRequest{
        Subject: "subject",
    }
client.Partners.PostV1PartnersInquiriesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**contactName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**contactEmail:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**contactPhone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**channel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersInquiriesUpdate(request) -> *nordlet.PostV1PartnersInquiriesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersInquiriesUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersInquiriesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**channel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1PartnersInquiriesUpdateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersInquiriesGet(request) -> *nordlet.PostV1PartnersInquiriesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersInquiriesGetRequest{
        ID: "id",
    }
client.Partners.PostV1PartnersInquiriesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersInquiriesList(request) -> *nordlet.PostV1PartnersInquiriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersInquiriesListRequest{}
client.Partners.PostV1PartnersInquiriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PartnersInquiriesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PartnersInquiriesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1PartnersCreditCheck(request) -> *nordlet.PostV1PartnersCreditCheckResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PartnersCreditCheckRequest{
        PartnerID: "partnerId",
    }
client.Partners.PostV1PartnersCreditCheck(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**additionalAmount:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsCreate(request) -> *nordlet.PostV1LeadsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsCreateRequest{
        Name: "name",
    }
client.Partners.PostV1LeadsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**contactName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sourceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1LeadsCreateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.PostV1LeadsCreateRequestDocumentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `[]string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsGet(request) -> *nordlet.PostV1LeadsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsGetRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsUpdate(request) -> *nordlet.PostV1LeadsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**contactName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sourceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1LeadsUpdateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.PostV1LeadsUpdateRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsDelete(request) -> *nordlet.PostV1LeadsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsList(request) -> *nordlet.PostV1LeadsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsListRequest{}
client.Partners.PostV1LeadsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LeadsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LeadsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsNotesCreate(request) -> *nordlet.PostV1LeadsNotesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsNotesCreateRequest{
        LeadID: "leadId",
        Body: "body",
    }
client.Partners.PostV1LeadsNotesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsNotesDelete(request) -> *nordlet.PostV1LeadsNotesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsNotesDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsNotesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsNotesList(request) -> *nordlet.PostV1LeadsNotesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsNotesListRequest{
        LeadID: "leadId",
    }
client.Partners.PostV1LeadsNotesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsFilesList(request) -> *nordlet.PostV1LeadsFilesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsFilesListRequest{
        LeadID: "leadId",
    }
client.Partners.PostV1LeadsFilesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsSourcesCreate(request) -> *nordlet.PostV1LeadsSourcesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsSourcesCreateRequest{
        Name: "name",
    }
client.Partners.PostV1LeadsSourcesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsSourcesUpdate(request) -> *nordlet.PostV1LeadsSourcesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsSourcesUpdateRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsSourcesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsSourcesDelete(request) -> *nordlet.PostV1LeadsSourcesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsSourcesDeleteRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsSourcesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsSourcesList(request) -> *nordlet.PostV1LeadsSourcesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsSourcesListRequest{}
client.Partners.PostV1LeadsSourcesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsSourcesOptions(request) -> *nordlet.PostV1LeadsSourcesOptionsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsSourcesOptionsRequest{}
client.Partners.PostV1LeadsSourcesOptions(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.PostV1LeadsConvert(request) -> *nordlet.PostV1LeadsConvertResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a customer partner from the lead, move the lead files to the partner, copy the lead notes into the partner notes and mark the lead as converted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LeadsConvertRequest{
        ID: "id",
    }
client.Partners.PostV1LeadsConvert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerType:** `*nordlet.PostV1LeadsConvertRequestPartnerType` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Catalog
<details><summary><code>client.Catalog.PostV1CatalogItemsCreate(request) -> *nordlet.PostV1CatalogItemsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsCreateRequest{
        Name: "name",
    }
client.Catalog.PostV1CatalogItemsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1CatalogItemsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `*nordlet.PostV1CatalogItemsCreateRequestTracking` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**barcode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**unit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**salePriceExclVat:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cnCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**originCountry:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**netMassKg:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryUnit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryQtyPerUnit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `map[string]string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1CatalogItemsCreateRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `[]*nordlet.PostV1CatalogItemsCreateRequestComponentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**kindID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**manufacturer:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**grossMassKg:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**minQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**costPrice:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isFreePrice:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**externalID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isReturnable:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**commentRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**priceFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**minPrice:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**maxDiscountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loyaltyPoints:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**department:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**ageRestriction:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**packageQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**taraCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**certificateNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**certificateDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**posFlags:** `map[string]bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsGet(request) -> *nordlet.PostV1CatalogItemsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsGetRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsUpdate(request) -> *nordlet.PostV1CatalogItemsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsUpdateRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1CatalogItemsUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `*nordlet.PostV1CatalogItemsUpdateRequestTracking` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**barcode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**unit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**salePriceExclVat:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cnCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**originCountry:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**netMassKg:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryUnit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryQtyPerUnit:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `map[string]*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1CatalogItemsUpdateRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `[]*nordlet.PostV1CatalogItemsUpdateRequestComponentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**kindID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**manufacturer:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**grossMassKg:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**minQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**costPrice:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isFreePrice:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**externalID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isReturnable:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**commentRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**priceFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**minPrice:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**maxDiscountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loyaltyPoints:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**department:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**ageRestriction:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**packageQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**taraCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**certificateNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**certificateDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**posFlags:** `map[string]*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsDelete(request) -> *nordlet.PostV1CatalogItemsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsDeleteRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsList(request) -> *nordlet.PostV1CatalogItemsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsListRequest{}
client.Catalog.PostV1CatalogItemsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1CatalogItemsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1CatalogItemsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsFilesList(request) -> *nordlet.PostV1CatalogItemsFilesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsFilesListRequest{
        ItemID: "itemId",
    }
client.Catalog.PostV1CatalogItemsFilesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsKindsCreate(request) -> *nordlet.PostV1CatalogItemsKindsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsKindsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.PostV1CatalogItemsKindsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**saftType:** `*nordlet.PostV1CatalogItemsKindsCreateRequestSaftType` 
    
</dd>
</dl>

<dl>
<dd>

**quantityAccounting:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsKindsUpdate(request) -> *nordlet.PostV1CatalogItemsKindsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsKindsUpdateRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsKindsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saftType:** `*nordlet.PostV1CatalogItemsKindsUpdateRequestSaftType` 
    
</dd>
</dl>

<dl>
<dd>

**quantityAccounting:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsKindsDelete(request) -> *nordlet.PostV1CatalogItemsKindsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsKindsDeleteRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsKindsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsKindsList(request) -> *nordlet.PostV1CatalogItemsKindsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsKindsListRequest{}
client.Catalog.PostV1CatalogItemsKindsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogUnitsCreate(request) -> *nordlet.PostV1CatalogUnitsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogUnitsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.PostV1CatalogUnitsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogUnitsUpdate(request) -> *nordlet.PostV1CatalogUnitsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogUnitsUpdateRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogUnitsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogUnitsDelete(request) -> *nordlet.PostV1CatalogUnitsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogUnitsDeleteRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogUnitsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogUnitsList(request) -> *nordlet.PostV1CatalogUnitsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogUnitsListRequest{}
client.Catalog.PostV1CatalogUnitsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogUnitsOptions(request) -> *nordlet.PostV1CatalogUnitsOptionsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogUnitsOptionsRequest{}
client.Catalog.PostV1CatalogUnitsOptions(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.PostV1CatalogUnitsOptionsRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemGroupsCreate(request) -> *nordlet.PostV1CatalogItemGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemGroupsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.PostV1CatalogItemGroupsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**parentID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemGroupsUpdate(request) -> *nordlet.PostV1CatalogItemGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemGroupsUpdateRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**parentID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemGroupsDelete(request) -> *nordlet.PostV1CatalogItemGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemGroupsDeleteRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemGroupsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemGroupsList(request) -> *nordlet.PostV1CatalogItemGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemGroupsListRequest{}
client.Catalog.PostV1CatalogItemGroupsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsSuppliersUpsert(request) -> *nordlet.PostV1CatalogItemsSuppliersUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsSuppliersUpsertRequest{
        ItemID: "itemId",
        PartnerID: "partnerId",
    }
client.Catalog.PostV1CatalogItemsSuppliersUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**supplierCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsSuppliersList(request) -> *nordlet.PostV1CatalogItemsSuppliersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsSuppliersListRequest{}
client.Catalog.PostV1CatalogItemsSuppliersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogItemsSuppliersDelete(request) -> *nordlet.PostV1CatalogItemsSuppliersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogItemsSuppliersDeleteRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogItemsSuppliersDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsCreate(request) -> *nordlet.PostV1CatalogPriceListsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.PostV1CatalogPriceListsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsUpdate(request) -> *nordlet.PostV1CatalogPriceListsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsUpdateRequest{
        ID: "id",
    }
client.Catalog.PostV1CatalogPriceListsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsList(request) -> *nordlet.PostV1CatalogPriceListsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsListRequest{}
client.Catalog.PostV1CatalogPriceListsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsItemsSet(request) -> *nordlet.PostV1CatalogPriceListsItemsSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsItemsSetRequest{
        PriceListID: "priceListId",
        Items: []*nordlet.PostV1CatalogPriceListsItemsSetRequestItemsItem{
            &nordlet.PostV1CatalogPriceListsItemsSetRequestItemsItem{
                ItemID: "itemId",
                UnitPriceExclVat: "unitPriceExclVat",
            },
        },
    }
client.Catalog.PostV1CatalogPriceListsItemsSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.PostV1CatalogPriceListsItemsSetRequestItemsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsItemsList(request) -> *nordlet.PostV1CatalogPriceListsItemsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsItemsListRequest{
        PriceListID: "priceListId",
    }
client.Catalog.PostV1CatalogPriceListsItemsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PostV1CatalogPriceListsItemsDelete(request) -> *nordlet.PostV1CatalogPriceListsItemsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CatalogPriceListsItemsDeleteRequest{
        PriceListID: "priceListId",
        ItemID: "itemId",
    }
client.Catalog.PostV1CatalogPriceListsItemsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Sales
<details><summary><code>client.Sales.PostV1SalesInvoicesCreate(request) -> *nordlet.PostV1SalesInvoicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesCreateRequest{
        PartnerID: "partnerId",
        Lines: []*nordlet.PostV1SalesInvoicesCreateRequestLinesItem{
            &nordlet.PostV1SalesInvoicesCreateRequestLinesItem{},
        },
    }
client.Sales.PostV1SalesInvoicesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1SalesInvoicesCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**agreementID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `*nordlet.PostV1SalesInvoicesCreateRequestVatScheme` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCountryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**deemedSupplier:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentSeriesID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**seriesLabel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**orderNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1SalesInvoicesCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesGet(request) -> *nordlet.PostV1SalesInvoicesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesGetRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPdf(request) -> *nordlet.PostV1SalesInvoicesPdfResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPdfRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesPdf(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1SalesInvoicesPdfRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesSend(request) -> *nordlet.PostV1SalesInvoicesSendResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesSendRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1SalesInvoicesSendRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPeppolXML(request) -> *nordlet.PostV1SalesInvoicesPeppolXMLResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPeppolXMLRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesPeppolXML(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPeppolSend(request) -> *nordlet.PostV1SalesInvoicesPeppolSendResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPeppolSendRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesPeppolSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesEinvoiceXML(request) -> *nordlet.PostV1SalesInvoicesEinvoiceXMLResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render an issued invoice as the national e-invoicing payload for the company country: FatturaPA (IT), KSeF FA(3) (PL) or UBL CIUS-RO (RO). Review the warnings - data the invoice does not carry is flagged, never invented.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesEinvoiceXMLRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesEinvoiceXML(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesEinvoiceSend(request) -> *nordlet.PostV1SalesInvoicesEinvoiceSendResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the national e-invoicing payload and deliver it over the transport configured for the country gateway in compliance settings. With transport=direct the request talks to the tax authority itself - SdICoop over 2-way TLS for Italy, a KSeF session for Poland, ANAF SPV OAuth for Romania - and returns the national number as soon as the channel assigns one. With transport=bridge the payload goes to the configured bridge endpoint (an accredited intermediary or connector) instead.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesEinvoiceSendRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesEinvoiceSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesEinvoiceStatus(request) -> *nordlet.PostV1SalesInvoicesEinvoiceStatusResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Ask the national e-invoicing channel what happened to an invoice that was already sent, and store the answer. Italy, Poland and Romania return the outcome only on request - none of them calls back - so this is the way the national number and any rejection reason reach the invoice.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesEinvoiceStatusRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesEinvoiceStatus(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesUpdate(request) -> *nordlet.PostV1SalesInvoicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesUpdateRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**agreementID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `*nordlet.PostV1SalesInvoicesUpdateRequestVatScheme` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCountryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**deemedSupplier:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentSeriesID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**seriesLabel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**orderNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1SalesInvoicesUpdateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesDelete(request) -> *nordlet.PostV1SalesInvoicesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesDeleteRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesIssue(request) -> *nordlet.PostV1SalesInvoicesIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesIssueRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesIssue(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesLock(request) -> *nordlet.PostV1SalesInvoicesLockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesLockRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesLock(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesUnlock(request) -> *nordlet.PostV1SalesInvoicesUnlockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesUnlockRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesUnlock(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPaymentLink(request) -> *nordlet.PostV1SalesInvoicesPaymentLinkResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPaymentLinkRequest{
        ID: "id",
    }
client.Sales.PostV1SalesInvoicesPaymentLink(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPaymentSettingsGet(request) -> *nordlet.PostV1SalesInvoicesPaymentSettingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPaymentSettingsGetRequest{}
client.Sales.PostV1SalesInvoicesPaymentSettingsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesPaymentSettingsUpdate(request) -> *nordlet.PostV1SalesInvoicesPaymentSettingsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesPaymentSettingsUpdateRequest{}
client.Sales.PostV1SalesInvoicesPaymentSettingsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**paymentLinkTemplate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionSchedulesList(request) -> *nordlet.PostV1SalesRecognitionSchedulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionSchedulesListRequest{}
client.Sales.PostV1SalesRecognitionSchedulesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1SalesRecognitionSchedulesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1SalesRecognitionSchedulesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesApplyAdvance(request) -> *nordlet.PostV1SalesInvoicesApplyAdvanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesApplyAdvanceRequest{
        AdvanceID: "advanceId",
        InvoiceID: "invoiceId",
    }
client.Sales.PostV1SalesInvoicesApplyAdvance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**advanceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesInvoicesList(request) -> *nordlet.PostV1SalesInvoicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesInvoicesListRequest{}
client.Sales.PostV1SalesInvoicesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1SalesInvoicesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1SalesInvoicesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsCreate(request) -> *nordlet.PostV1SalesActsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsCreateRequest{
        PartnerID: "partnerId",
    }
client.Sales.PostV1SalesActsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1SalesActsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1SalesActsCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsUpdate(request) -> *nordlet.PostV1SalesActsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsUpdateRequest{
        ID: "id",
    }
client.Sales.PostV1SalesActsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1SalesActsUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByTitle:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1SalesActsUpdateRequestLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsIssue(request) -> *nordlet.PostV1SalesActsIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsIssueRequest{
        ID: "id",
    }
client.Sales.PostV1SalesActsIssue(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsCancel(request) -> *nordlet.PostV1SalesActsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsCancelRequest{
        ID: "id",
    }
client.Sales.PostV1SalesActsCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsGet(request) -> *nordlet.PostV1SalesActsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsGetRequest{
        ID: "id",
    }
client.Sales.PostV1SalesActsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsList(request) -> *nordlet.PostV1SalesActsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsListRequest{}
client.Sales.PostV1SalesActsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1SalesActsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1SalesActsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesActsPdf(request) -> *nordlet.PostV1SalesActsPdfResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesActsPdfRequest{
        ID: "id",
    }
client.Sales.PostV1SalesActsPdf(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1SalesActsPdfRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1OperationTypesCreate(request) -> *nordlet.PostV1OperationTypesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OperationTypesCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Sales.PostV1OperationTypesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceType:** `*nordlet.PostV1OperationTypesCreateRequestInvoiceType` 
    
</dd>
</dl>

<dl>
<dd>

**payerPartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**debitAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**creditAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**advanceAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**incomeAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchase:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSale:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isWriteOff:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isInternalMovement:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchaseReturn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSalesReturn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isConsignment:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isProduction:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetIn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetOut:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isCashRegisterSale:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**includeInVatRegister:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**includeInSaft:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1OperationTypesUpdate(request) -> *nordlet.PostV1OperationTypesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OperationTypesUpdateRequest{
        ID: "id",
    }
client.Sales.PostV1OperationTypesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceType:** `*nordlet.PostV1OperationTypesUpdateRequestInvoiceType` 
    
</dd>
</dl>

<dl>
<dd>

**payerPartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**debitAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**creditAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**advanceAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**incomeAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchase:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSale:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isWriteOff:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isInternalMovement:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchaseReturn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isSalesReturn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isConsignment:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isProduction:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetIn:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetOut:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isCashRegisterSale:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**includeInVatRegister:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**includeInSaft:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1OperationTypesGet(request) -> *nordlet.PostV1OperationTypesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OperationTypesGetRequest{
        ID: "id",
    }
client.Sales.PostV1OperationTypesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1OperationTypesDelete(request) -> *nordlet.PostV1OperationTypesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OperationTypesDeleteRequest{
        ID: "id",
    }
client.Sales.PostV1OperationTypesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1OperationTypesList(request) -> *nordlet.PostV1OperationTypesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OperationTypesListRequest{}
client.Sales.PostV1OperationTypesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1OperationTypesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1OperationTypesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1DocumentSeriesCreate(request) -> *nordlet.PostV1DocumentSeriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DocumentSeriesCreateRequest{
        Prefix: "prefix",
    }
client.Sales.PostV1DocumentSeriesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**documentType:** `*nordlet.PostV1DocumentSeriesCreateRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**label:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**numberLength:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**nextNumber:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedFrom:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedTo:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**printSeries:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1DocumentSeriesUpdate(request) -> *nordlet.PostV1DocumentSeriesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DocumentSeriesUpdateRequest{
        ID: "id",
    }
client.Sales.PostV1DocumentSeriesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentType:** `*nordlet.PostV1DocumentSeriesUpdateRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**label:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**numberLength:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**nextNumber:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedFrom:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedTo:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**printSeries:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1DocumentSeriesGet(request) -> *nordlet.PostV1DocumentSeriesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DocumentSeriesGetRequest{
        ID: "id",
    }
client.Sales.PostV1DocumentSeriesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1DocumentSeriesDelete(request) -> *nordlet.PostV1DocumentSeriesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DocumentSeriesDeleteRequest{
        ID: "id",
    }
client.Sales.PostV1DocumentSeriesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1DocumentSeriesList(request) -> *nordlet.PostV1DocumentSeriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DocumentSeriesListRequest{}
client.Sales.PostV1DocumentSeriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1DocumentSeriesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1DocumentSeriesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionCompute(request) -> *nordlet.PostV1SalesRecognitionComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionComputeRequest{}
client.Sales.PostV1SalesRecognitionCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionRun(request) -> *nordlet.PostV1SalesRecognitionRunResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionRunRequest{}
client.Sales.PostV1SalesRecognitionRun(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**postingDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**scheduleIDs:** `[]string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionProgress(request) -> *nordlet.PostV1SalesRecognitionProgressResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionProgressRequest{
        InvoiceLineID: "invoiceLineId",
        PercentComplete: "percentComplete",
    }
client.Sales.PostV1SalesRecognitionProgress(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceLineID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**percentComplete:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionModify(request) -> *nordlet.PostV1SalesRecognitionModifyResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Apply an IFRS 15 contract modification to a deferred invoice line. Prospective: cancel the pending schedule and respread the unrecognized remainder over the new terms. Cumulative catch-up (ratable only): recompute revenue as if the new terms applied from the start and post the difference immediately.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionModifyRequest{
        InvoiceLineID: "invoiceLineId",
        Approach: nordlet.PostV1SalesRecognitionModifyRequestApproachProspective,
    }
client.Sales.PostV1SalesRecognitionModify(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceLineID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**approach:** `*nordlet.PostV1SalesRecognitionModifyRequestApproach` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**newEndDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**newMilestones:** `[]*nordlet.PostV1SalesRecognitionModifyRequestNewMilestonesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionRunsList(request) -> *nordlet.PostV1SalesRecognitionRunsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionRunsListRequest{}
client.Sales.PostV1SalesRecognitionRunsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1SalesRecognitionRunsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1SalesRecognitionRunsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRecognitionSummary(request) -> *nordlet.PostV1SalesRecognitionSummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRecognitionSummaryRequest{}
client.Sales.PostV1SalesRecognitionSummary(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRefundLiabilityList(request) -> *nordlet.PostV1SalesRefundLiabilityListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRefundLiabilityListRequest{}
client.Sales.PostV1SalesRefundLiabilityList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1SalesRefundLiabilityListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1SalesRefundLiabilityListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.PostV1SalesRefundLiabilityTrueUp(request) -> *nordlet.PostV1SalesRefundLiabilityTrueUpResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1SalesRefundLiabilityTrueUpRequest{
        InvoiceID: "invoiceId",
        EstimatedTotal: "estimatedTotal",
    }
client.Sales.PostV1SalesRefundLiabilityTrueUp(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedTotal:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Purchases
<details><summary><code>client.Purchases.PostV1PurchasesInvoicesCreate(request) -> *nordlet.PostV1PurchasesInvoicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesCreateRequest{
        PartnerID: "partnerId",
        DocumentNumber: "documentNumber",
        DocumentDate: "documentDate",
        Lines: []*nordlet.PostV1PurchasesInvoicesCreateRequestLinesItem{
            &nordlet.PostV1PurchasesInvoicesCreateRequestLinesItem{},
        },
    }
client.Purchases.PostV1PurchasesInvoicesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1PurchasesInvoicesCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseOrderID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**einvoiceNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PurchasesInvoicesCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesGet(request) -> *nordlet.PostV1PurchasesInvoicesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesGetRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesInvoicesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesUpdate(request) -> *nordlet.PostV1PurchasesInvoicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesUpdateRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesInvoicesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseOrderID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**einvoiceNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PurchasesInvoicesUpdateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesDelete(request) -> *nordlet.PostV1PurchasesInvoicesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesDeleteRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesInvoicesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesRegister(request) -> *nordlet.PostV1PurchasesInvoicesRegisterResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesRegisterRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesInvoicesRegister(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**registrationDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesList(request) -> *nordlet.PostV1PurchasesInvoicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesListRequest{}
client.Purchases.PostV1PurchasesInvoicesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PurchasesInvoicesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PurchasesInvoicesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersCreate(request) -> *nordlet.PostV1PurchasesOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersCreateRequest{
        PartnerID: "partnerId",
        OrderDate: "orderDate",
        Lines: []*nordlet.PostV1PurchasesOrdersCreateRequestLinesItem{
            &nordlet.PostV1PurchasesOrdersCreateRequestLinesItem{},
        },
    }
client.Purchases.PostV1PurchasesOrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**orderNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**orderDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PurchasesOrdersCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersUpdate(request) -> *nordlet.PostV1PurchasesOrdersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersUpdateRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**orderDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PurchasesOrdersUpdateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersGet(request) -> *nordlet.PostV1PurchasesOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersGetRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersList(request) -> *nordlet.PostV1PurchasesOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersListRequest{}
client.Purchases.PostV1PurchasesOrdersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PurchasesOrdersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PurchasesOrdersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersSubmit(request) -> *nordlet.PostV1PurchasesOrdersSubmitResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersSubmitRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersSubmit(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersApprove(request) -> *nordlet.PostV1PurchasesOrdersApproveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersApproveRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersApprove(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersReject(request) -> *nordlet.PostV1PurchasesOrdersRejectResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersRejectRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersReject(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersCancel(request) -> *nordlet.PostV1PurchasesOrdersCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersCancelRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersClose(request) -> *nordlet.PostV1PurchasesOrdersCloseResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersCloseRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersClose(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesOrdersDelete(request) -> *nordlet.PostV1PurchasesOrdersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesOrdersDeleteRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesOrdersDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesReceiptsCreate(request) -> *nordlet.PostV1PurchasesReceiptsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesReceiptsCreateRequest{
        OrderID: "orderId",
        ReceiptDate: "receiptDate",
        Lines: []*nordlet.PostV1PurchasesReceiptsCreateRequestLinesItem{
            &nordlet.PostV1PurchasesReceiptsCreateRequestLinesItem{
                OrderLineID: "orderLineId",
                Quantity: "quantity",
            },
        },
    }
client.Purchases.PostV1PurchasesReceiptsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**orderID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**receiptDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PurchasesReceiptsCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesReceiptsGet(request) -> *nordlet.PostV1PurchasesReceiptsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesReceiptsGetRequest{
        ID: "id",
    }
client.Purchases.PostV1PurchasesReceiptsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesReceiptsList(request) -> *nordlet.PostV1PurchasesReceiptsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesReceiptsListRequest{}
client.Purchases.PostV1PurchasesReceiptsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PurchasesReceiptsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PurchasesReceiptsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.PostV1PurchasesInvoicesMatch(request) -> *nordlet.PostV1PurchasesInvoicesMatchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PurchasesInvoicesMatchRequest{
        InvoiceID: "invoiceId",
    }
client.Purchases.PostV1PurchasesInvoicesMatch(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**priceTolerancePercent:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Capture
<details><summary><code>client.Capture.PostV1CaptureSettingsGet(request) -> *nordlet.PostV1CaptureSettingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureSettingsGetRequest{}
client.Capture.PostV1CaptureSettingsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.PostV1CaptureSettingsUpdate(request) -> *nordlet.PostV1CaptureSettingsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureSettingsUpdateRequest{}
client.Capture.PostV1CaptureSettingsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**intakeEnabled:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**captureAutoExtract:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.PostV1CaptureSettingsRegenerateIntake(request) -> *nordlet.PostV1CaptureSettingsRegenerateIntakeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureSettingsRegenerateIntakeRequest{}
client.Capture.PostV1CaptureSettingsRegenerateIntake(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.ReceiveAnInboundEmailWithSupplierDocumentsAttachedPostmarkStyleOrGenericJSON(request) -> *nordlet.PostV1CaptureInboundEmailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureInboundEmailRequest{}
client.Capture.ReceiveAnInboundEmailWithSupplierDocumentsAttachedPostmarkStyleOrGenericJSON(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**postmarkTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**toFull:** `[]*nordlet.PostV1CaptureInboundEmailRequestToFullItem` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkSubject:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkAttachments:** `[]*nordlet.PostV1CaptureInboundEmailRequestAttachmentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `*nordlet.PostV1CaptureInboundEmailRequestTo` 
    
</dd>
</dl>

<dl>
<dd>

**from:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**attachments:** `[]*nordlet.PostV1CaptureInboundEmailRequestAttachmentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.ReadAVendorBillOrReceiptAndReturnAnEditablePurchaseInvoiceDraft(request) -> *nordlet.PostV1CaptureDocumentsUploadResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsUploadRequest{
        FileName: "fileName",
        MimeType: "mimeType",
        Content: "content",
    }
client.Capture.ReadAVendorBillOrReceiptAndReturnAnEditablePurchaseInvoiceDraft(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fileName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**mimeType:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `string` — Base64-encoded scan, photo or PDF of the supplier document
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.ReReadAStoredCaptureReplacingThePreviousDraft(request) -> *nordlet.PostV1CaptureDocumentsExtractResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsExtractRequest{
        ID: "id",
    }
client.Capture.ReReadAStoredCaptureReplacingThePreviousDraft(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.PostV1CaptureDocumentsGet(request) -> *nordlet.PostV1CaptureDocumentsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsGetRequest{
        ID: "id",
    }
client.Capture.PostV1CaptureDocumentsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.PostV1CaptureDocumentsList(request) -> *nordlet.PostV1CaptureDocumentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsListRequest{}
client.Capture.PostV1CaptureDocumentsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1CaptureDocumentsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1CaptureDocumentsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.PostV1CaptureDocumentsDelete(request) -> *nordlet.PostV1CaptureDocumentsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsDeleteRequest{
        ID: "id",
    }
client.Capture.PostV1CaptureDocumentsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.SaveTheReviewedDraftAsAPurchaseInvoiceAndAttachTheOriginalDocument(request) -> *nordlet.PostV1CaptureDocumentsConfirmResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CaptureDocumentsConfirmRequest{
        ID: "id",
        DocumentNumber: "documentNumber",
        DocumentDate: "documentDate",
        Lines: []*nordlet.PostV1CaptureDocumentsConfirmRequestLinesItem{
            &nordlet.PostV1CaptureDocumentsConfirmRequestLinesItem{},
        },
    }
client.Capture.SaveTheReviewedDraftAsAPurchaseInvoiceAndAttachTheOriginalDocument(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**newSupplier:** `*nordlet.PostV1CaptureDocumentsConfirmRequestNewSupplier` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1CaptureDocumentsConfirmRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Declarations
<details><summary><code>client.Declarations.PostV1DeclarationsLtIntrastatCompute(request) -> *nordlet.PostV1DeclarationsLtIntrastatComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIntrastatComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        Flow: nordlet.PostV1DeclarationsLtIntrastatComputeRequestFlowArrivals,
    }
client.Declarations.PostV1DeclarationsLtIntrastatCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**flow:** `*nordlet.PostV1DeclarationsLtIntrastatComputeRequestFlow` 
    
</dd>
</dl>

<dl>
<dd>

**transactionNature:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**deliveryTerms:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transportMode:** `*nordlet.PostV1DeclarationsLtIntrastatComputeRequestTransportMode` 
    
</dd>
</dl>

<dl>
<dd>

**regionCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**statisticalValueRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**preparationTimeHours:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**preparationTimeMinutes:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtIvazGenerate(request) -> *nordlet.PostV1DeclarationsLtIvazGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIvazGenerateRequest{
        WaybillIDs: []string{
            "waybillIds",
        },
    }
client.Declarations.PostV1DeclarationsLtIvazGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillIDs:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtIntrastatObligation(request) -> *nordlet.PostV1DeclarationsLtIntrastatObligationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIntrastatObligationRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtIntrastatObligation(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtIsafGenerate(request) -> *nordlet.PostV1DeclarationsLtIsafGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIsafGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtIsafGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.PostV1DeclarationsLtIsafGenerateRequestDataType` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtFr0600Compute(request) -> *nordlet.PostV1DeclarationsLtFr0600ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtFr0600ComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtFr0600Compute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**months:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**deductionPercent:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtGpm313Compute(request) -> *nordlet.PostV1DeclarationsLtGpm313ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtGpm313ComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtGpm313Compute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**payoutTiming:** `*nordlet.PostV1DeclarationsLtGpm313ComputeRequestPayoutTiming` 
    
</dd>
</dl>

<dl>
<dd>

**paymentDay:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtSamCompute(request) -> *nordlet.PostV1DeclarationsLtSamComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtSamComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtSamCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtSdGenerate(request) -> *nordlet.PostV1DeclarationsLtSdGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtSdGenerateRequest{
        Type: nordlet.PostV1DeclarationsLtSdGenerateRequestTypeOneSd,
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Declarations.PostV1DeclarationsLtSdGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1DeclarationsLtSdGenerateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtSaftGenerate(request) -> *nordlet.PostV1DeclarationsLtSaftGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtSaftGenerateRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Declarations.PostV1DeclarationsLtSaftGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.PostV1DeclarationsLtSaftGenerateRequestDataType` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtIvazAmend(request) -> *nordlet.PostV1DeclarationsLtIvazAmendResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIvazAmendRequest{
        WaybillIDs: []string{
            "waybillIds",
        },
    }
client.Declarations.PostV1DeclarationsLtIvazAmend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillIDs:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtIvazCancel(request) -> *nordlet.PostV1DeclarationsLtIvazCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtIvazCancelRequest{
        Entries: []*nordlet.PostV1DeclarationsLtIvazCancelRequestEntriesItem{
            &nordlet.PostV1DeclarationsLtIvazCancelRequestEntriesItem{
                WaybillID: "waybillId",
                Reason: nordlet.PostV1DeclarationsLtIvazCancelRequestEntriesItemReasonOne,
            },
        },
    }
client.Declarations.PostV1DeclarationsLtIvazCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**entries:** `[]*nordlet.PostV1DeclarationsLtIvazCancelRequestEntriesItem` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtFr0564Compute(request) -> *nordlet.PostV1DeclarationsLtFr0564ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtFr0564ComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtFr0564Compute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtGpm312Compute(request) -> *nordlet.PostV1DeclarationsLtGpm312ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtGpm312ComputeRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtGpm312Compute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**payoutTiming:** `*nordlet.PostV1DeclarationsLtGpm312ComputeRequestPayoutTiming` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtPln204Compute(request) -> *nordlet.PostV1DeclarationsLtPln204ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtPln204ComputeRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtPln204Compute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuOssCompute(request) -> *nordlet.PostV1DeclarationsEuOssComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuOssComputeRequest{
        Year: int64(1000000),
        Quarter: int64(1000000),
    }
client.Declarations.PostV1DeclarationsEuOssCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**quarter:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuIossCompute(request) -> *nordlet.PostV1DeclarationsEuIossComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuIossComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsEuIossCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuDistanceSalesThresholdGet(request) -> *nordlet.PostV1DeclarationsEuDistanceSalesThresholdGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuDistanceSalesThresholdGetRequest{}
client.Declarations.PostV1DeclarationsEuDistanceSalesThresholdGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuUnionTurnoverGet(request) -> *nordlet.PostV1DeclarationsEuUnionTurnoverGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuUnionTurnoverGetRequest{}
client.Declarations.PostV1DeclarationsEuUnionTurnoverGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuSmeCrossBorderReportCompute(request) -> *nordlet.PostV1DeclarationsEuSmeCrossBorderReportComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuSmeCrossBorderReportComputeRequest{
        Year: int64(1000000),
        Quarter: int64(1000000),
    }
client.Declarations.PostV1DeclarationsEuSmeCrossBorderReportCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**quarter:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuSmeThresholdsList(request) -> *nordlet.PostV1DeclarationsEuSmeThresholdsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuSmeThresholdsListRequest{}
client.Declarations.PostV1DeclarationsEuSmeThresholdsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuSmeThresholdGet(request) -> *nordlet.PostV1DeclarationsEuSmeThresholdGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuSmeThresholdGetRequest{}
client.Declarations.PostV1DeclarationsEuSmeThresholdGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuVatReturnPacksList(request) -> *nordlet.PostV1DeclarationsEuVatReturnPacksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuVatReturnPacksListRequest{}
client.Declarations.PostV1DeclarationsEuVatReturnPacksList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEuVatReturnCompute(request) -> *nordlet.PostV1DeclarationsEuVatReturnComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEuVatReturnComputeRequest{
        CountryCode: "countryCode",
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsEuVatReturnCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**months:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlJpkV7MGenerate(request) -> *nordlet.PostV1DeclarationsPlJpkV7MGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate the Polish JPK_V7M(3) file (VAT declaration with evidence) for a month, per the MF schema in force since February 2026. Amounts must already be in PLN; rows are marked BFK until a KSeF integration supplies invoice numbers. Review the warnings before submitting via e-dokumenty.mf.gov.pl.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlJpkV7MGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        KodUrzedu: "kodUrzedu",
        Email: "email",
    }
client.Declarations.PostV1DeclarationsPlJpkV7MGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**kodUrzedu:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**celZlozenia:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlVatUeGenerate(request) -> *nordlet.PostV1DeclarationsPlVatUeGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the rows of the Polish recapitulative statement VAT-UE for a month: section C intra-Community supplies of goods, section D intra-Community acquisitions, section E services taxed where the customer is established. Amounts are full złoty per counterparty. The VAT-UE(5) file itself goes out from the EU sales list deadline in the calendar.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlVatUeGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlVatUeGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlIntrastatGenerate(request) -> *nordlet.PostV1DeclarationsPlIntrastatGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the rows of the Polish INTRASTAT declaration for a month, arrivals or dispatches, grouped by CN code, partner country, country of origin, partner VAT number, nature of transaction, transport and delivery terms. Values are whole złoty converted at the invoice rate; credit notes with goods lines are returns (code 21). Goods without a CN code are left out and named in the warnings. The IST message itself goes out from the Intrastat deadline in the calendar.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlIntrastatGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        Flow: nordlet.PostV1DeclarationsPlIntrastatGenerateRequestFlowArrivals,
    }
client.Declarations.PostV1DeclarationsPlIntrastatGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**flow:** `*nordlet.PostV1DeclarationsPlIntrastatGenerateRequestFlow` 
    
</dd>
</dl>

<dl>
<dd>

**transactionNature:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlKsefReceivedList(request) -> *nordlet.PostV1DeclarationsPlKsefReceivedListResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List the invoices KSeF holds for this company as the buyer, for a window of acquisition timestamps. Each row carries the KSeF number and, when the document number matches a registered purchase invoice, the invoice it belongs to.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlKsefReceivedListRequest{
        From: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
        To: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
    }
client.Declarations.PostV1DeclarationsPlKsefReceivedList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageOffset:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlKsefReceivedFetch(request) -> *nordlet.PostV1DeclarationsPlKsefReceivedFetchResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Read one invoice out of KSeF by its national number. With a purchase invoice given, the KSeF number is written onto that invoice, which is what makes the purchase row of JPK_V7M carry NrKSeF instead of the BFK marker.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlKsefReceivedFetchRequest{
        KsefNumber: "ksefNumber",
    }
client.Declarations.PostV1DeclarationsPlKsefReceivedFetch(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ksefNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseInvoiceID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlKsefReceipt(request) -> *nordlet.PostV1DeclarationsPlKsefReceiptResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The UPO for a KSeF session. KSeF issues one receipt per session rather than per invoice, so the session reference number from the send is what identifies it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlKsefReceiptRequest{}
client.Declarations.PostV1DeclarationsPlKsefReceipt(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**sessionReferenceNumber:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.TaxAdjustmentsRecordedForATaxYear(request) -> *nordlet.PostV1DeclarationsTaxAdjustmentsListResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The differences between the accounting result and the taxable profit: non-deductible expenses, income added to or left out of the tax base, extra deductible expenses, donations, losses carried forward, reliefs and tax credits. The annual corporate income tax return is built from them.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxAdjustmentsListRequest{
        Year: int64(1000000),
    }
client.Declarations.TaxAdjustmentsRecordedForATaxYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RecordATaxAdjustmentForATaxYear(request) -> *nordlet.PostV1DeclarationsTaxAdjustmentsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxAdjustmentsCreateRequest{
        Year: int64(1000000),
        Kind: nordlet.PostV1DeclarationsTaxAdjustmentsCreateRequestKindNonDeductible,
        Amount: "amount",
        Description: "description",
    }
client.Declarations.RecordATaxAdjustmentForATaxYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsTaxAdjustmentsCreateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.ChangeARecordedTaxAdjustment(request) -> *nordlet.PostV1DeclarationsTaxAdjustmentsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxAdjustmentsUpdateRequest{
        ID: "id",
    }
client.Declarations.ChangeARecordedTaxAdjustment(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsTaxAdjustmentsUpdateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RemoveARecordedTaxAdjustment(request) -> *nordlet.PostV1DeclarationsTaxAdjustmentsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxAdjustmentsDeleteRequest{
        ID: "id",
    }
client.Declarations.RemoveARecordedTaxAdjustment(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PaymentsAlreadyMadeTowardsATaxOfAYear(request) -> *nordlet.PostV1DeclarationsTaxPaymentsListResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

What the company has paid the administration towards a tax before the return is filed: payments on account, tax withheld at source by others, a final settlement, and a refund received. Returns report these on their own lines, so the amount they ask for is the balance.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxPaymentsListRequest{
        Tax: nordlet.PostV1DeclarationsTaxPaymentsListRequestTaxCorporateIncomeTax,
        Year: int64(1000000),
    }
client.Declarations.PaymentsAlreadyMadeTowardsATaxOfAYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tax:** `*nordlet.PostV1DeclarationsTaxPaymentsListRequestTax` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RecordAPaymentMadeTowardsATax(request) -> *nordlet.PostV1DeclarationsTaxPaymentsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxPaymentsCreateRequest{
        Tax: nordlet.PostV1DeclarationsTaxPaymentsCreateRequestTaxCorporateIncomeTax,
        Year: int64(1000000),
        Kind: nordlet.PostV1DeclarationsTaxPaymentsCreateRequestKindAdvance,
        Amount: "amount",
        PaidOn: "paidOn",
        Description: "description",
    }
client.Declarations.RecordAPaymentMadeTowardsATax(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tax:** `*nordlet.PostV1DeclarationsTaxPaymentsCreateRequestTax` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsTaxPaymentsCreateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.ChangeARecordedTaxPayment(request) -> *nordlet.PostV1DeclarationsTaxPaymentsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxPaymentsUpdateRequest{
        ID: "id",
    }
client.Declarations.ChangeARecordedTaxPayment(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsTaxPaymentsUpdateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RemoveARecordedTaxPayment(request) -> *nordlet.PostV1DeclarationsTaxPaymentsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsTaxPaymentsDeleteRequest{
        ID: "id",
    }
client.Declarations.RemoveARecordedTaxPayment(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.AdoptionAndSigningFactsOfTheAnnualAccountsOfAYear(request) -> *nordlet.PostV1DeclarationsAnnualAccountsGetResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Whether the general meeting adopted the annual accounts and on which date, the date the accounts were prepared, and which directors signed them. The annual accounts filed with the trade register are built from these facts.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsGetRequest{
        Year: int64(1000000),
    }
client.Declarations.AdoptionAndSigningFactsOfTheAnnualAccountsOfAYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RecordTheAdoptionAndPreparationOfTheAnnualAccountsOfAYear(request) -> *nordlet.PostV1DeclarationsAnnualAccountsSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsSetRequest{
        Year: int64(1000000),
        Adopted: true,
        DateOfPreparation: "dateOfPreparation",
    }
client.Declarations.RecordTheAdoptionAndPreparationOfTheAnnualAccountsOfAYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**adopted:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**adoptionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateOfPreparation:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**audited:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**auditReportQualified:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**auditorNotElected:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notesText:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**managementReportText:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorReportText:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorReportDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resultToReserves:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resultToLossCompensation:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resultToRemainder:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RecordWhetherADirectorSignedTheAnnualAccountsOfAYear(request) -> *nordlet.PostV1DeclarationsAnnualAccountsSignaturesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsSignaturesCreateRequest{
        Year: int64(1000000),
        DirectorName: "directorName",
        DirectorType: nordlet.PostV1DeclarationsAnnualAccountsSignaturesCreateRequestDirectorTypeManagingCurrent,
        Signed: true,
    }
client.Declarations.RecordWhetherADirectorSignedTheAnnualAccountsOfAYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**directorName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**directorType:** `*nordlet.PostV1DeclarationsAnnualAccountsSignaturesCreateRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**reasonNotSigned:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.ChangeARecordedDirectorSignature(request) -> *nordlet.PostV1DeclarationsAnnualAccountsSignaturesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsSignaturesUpdateRequest{
        ID: "id",
        DirectorName: "directorName",
        DirectorType: nordlet.PostV1DeclarationsAnnualAccountsSignaturesUpdateRequestDirectorTypeManagingCurrent,
        Signed: true,
    }
client.Declarations.ChangeARecordedDirectorSignature(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**directorName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**directorType:** `*nordlet.PostV1DeclarationsAnnualAccountsSignaturesUpdateRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**reasonNotSigned:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RemoveARecordedDirectorSignature(request) -> *nordlet.PostV1DeclarationsAnnualAccountsSignaturesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsSignaturesDeleteRequest{
        ID: "id",
    }
client.Declarations.RemoveARecordedDirectorSignature(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RecordADecisionToDistributeProfitADividendAnInterimDividendOrAPaymentTreatedAsOne(request) -> *nordlet.PostV1DeclarationsAnnualAccountsDistributionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsDistributionsCreateRequest{
        Year: int64(1000000),
        DecidedOn: "decidedOn",
        Kind: nordlet.PostV1DeclarationsAnnualAccountsDistributionsCreateRequestKindDividend,
        Amount: "amount",
    }
client.Declarations.RecordADecisionToDistributeProfitADividendAnInterimDividendOrAPaymentTreatedAsOne(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**decidedOn:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsAnnualAccountsDistributionsCreateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.ChangeARecordedProfitDistribution(request) -> *nordlet.PostV1DeclarationsAnnualAccountsDistributionsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsDistributionsUpdateRequest{
        ID: "id",
        DecidedOn: "decidedOn",
        Kind: nordlet.PostV1DeclarationsAnnualAccountsDistributionsUpdateRequestKindDividend,
        Amount: "amount",
    }
client.Declarations.ChangeARecordedProfitDistribution(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**decidedOn:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsAnnualAccountsDistributionsUpdateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RemoveARecordedProfitDistribution(request) -> *nordlet.PostV1DeclarationsAnnualAccountsDistributionsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsDistributionsDeleteRequest{
        ID: "id",
    }
client.Declarations.RemoveARecordedProfitDistribution(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.AttachAnUploadedDocumentToTheAnnualAccountsOfAYear(request) -> *nordlet.PostV1DeclarationsAnnualAccountsAttachmentsAddResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Links a file uploaded through files/upload (its storageKey) to the annual accounts of the year as the notes, the management report, the auditor statement, the profit appropriation resolution, the approval certificate, the general data sheet, the full report as a pdf, or another document. Deposits that must carry these documents take them from here.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsAttachmentsAddRequest{
        Year: int64(1000000),
        Kind: nordlet.PostV1DeclarationsAnnualAccountsAttachmentsAddRequestKindFullReport,
        Ref: "ref",
    }
client.Declarations.AttachAnUploadedDocumentToTheAnnualAccountsOfAYear(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1DeclarationsAnnualAccountsAttachmentsAddRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**ref:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.RemoveADocumentAttachedToTheAnnualAccountsAndDeleteItsFile(request) -> *nordlet.PostV1DeclarationsAnnualAccountsAttachmentsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAnnualAccountsAttachmentsDeleteRequest{
        ID: "id",
    }
client.Declarations.RemoveADocumentAttachedToTheAnnualAccountsAndDeleteItsFile(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsCyTd4Generate(request) -> *nordlet.PostV1DeclarationsCyTd4GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the company income tax return TD4 of a tax year from the ledger and the recorded tax adjustments: the accounting profit, the add-backs, deductions, capital allowances and losses brought forward, the chargeable income, the corporation tax at the rate of the year and the double tax relief, as the fields the company keys into TAXISnet or Tax For All. The Tax Department publishes no upload layout for the TD4; the XML is a working file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsCyTd4GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsCyTd4Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsCyHe32Generate(request) -> *nordlet.PostV1DeclarationsCyHe32GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual return HE32 of a year: the figures the Registrar’s e-filing screens ask for (company number, registered office, made-up-to date, share capital, register of members, directors and secretary, annual general meeting date, the accounts summary), the working file, and the printed form HE32(I) filled in as a PDF for signing and for keying into the Registrar’s system, which takes the return only through its own screens.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsCyHe32GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsCyHe32Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDeReturnsGenerate(request) -> *nordlet.PostV1DeclarationsDeReturnsGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build one of the German returns that ELSTER accepts only through a licensed ERiC transmission (E-Bilanz, Körperschaftsteuer, Gewerbesteuer with its Zerlegungserklärung, annual VAT return, Lohnsteuer-Anmeldung, Lohnsteuerbescheinigung) for the company to send through its own ELSTER-capable program. The period is the year, or YYYY-MM for the monthly Lohnsteuer-Anmeldung.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDeReturnsGenerateRequest{
        RuleKey: nordlet.PostV1DeclarationsDeReturnsGenerateRequestRuleKeyDeEBilanz,
        Period: "period",
    }
client.Declarations.PostV1DeclarationsDeReturnsGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ruleKey:** `*nordlet.PostV1DeclarationsDeReturnsGenerateRequestRuleKey` 
    
</dd>
</dl>

<dl>
<dd>

**period:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDeReturnFactsGet(request) -> *nordlet.PostV1DeclarationsDeReturnFactsGetResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The facts of one year that the German annual returns (Körperschaftsteuer, Gewerbesteuer, Umsatzsteuererklärung) need and the ledger does not hold: changes of shareholders, contracts with shareholders, the tax contribution account, loss carry-back, the donation carry-forward, the business premises with the municipalities for the apportionment of the trade tax, the land values or property tax and the participations for the trade tax additions and reductions, the foreign income per country for the Anlage AESt, the date of leaving the small-business scheme and the Anlage UN answers of a company seated abroad. A key that is absent has not been answered.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDeReturnFactsGetRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsDeReturnFactsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDeReturnFactsSet(request) -> *nordlet.PostV1DeclarationsDeReturnFactsSetResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the facts of one year for the German annual returns. The returns built afterwards read them; a key left out stays unanswered.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDeReturnFactsSetRequest{
        Year: int64(1000000),
        Facts: &nordlet.PostV1DeclarationsDeReturnFactsSetRequestFacts{},
    }
client.Declarations.PostV1DeclarationsDeReturnFactsSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**facts:** `*nordlet.PostV1DeclarationsDeReturnFactsSetRequestFacts` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDeDeuevGenerate(request) -> *nordlet.PostV1DeclarationsDeDeuevGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the DEÜV notifications of a month (Anmeldung for every start, Abmeldung for every leaving, in December the Jahresmeldung for everyone employed on 31 December) as DSME records with the DBME, DBNA, DBGB and DBAN blocks of Anlage 4 in force from 2026, from the approved payroll runs and the employee record, for the company's own transmission channel.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDeDeuevGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsDeDeuevGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDeBeitragsnachweisGenerate(request) -> *nordlet.PostV1DeclarationsDeBeitragsnachweisGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the monthly contribution statement to the health insurers (Beitragsnachweis) from the payroll run: one fixed-length record BW02 per insurer, in the record layout in force from 2026, ready for the company's own transmission channel.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDeBeitragsnachweisGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsDeBeitragsnachweisGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsDkSelskabsskatGenerate(request) -> *nordlet.PostV1DeclarationsDkSelskabsskatGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the oplysningsskema for selskaber (selskabsselvangivelsen) of an income year from the ledger and the recorded tax adjustments: accounting result before tax, tax adjustments, losses carried forward, taxable income, the 22 % corporation tax, reliefs and the balance, as the rubrikker the company keys into TastSelv Selskabsskat (DIAS). Skatteforvaltningen publishes no file format for the return; the XML is a working file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsDkSelskabsskatGenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsDkSelskabsskatGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEeEmploymentRegisterSend(request) -> *nordlet.PostV1DeclarationsEeEmploymentRegisterSendResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Send one employment register (töötamise register) entry for an employment contract to e-MTA over X-tee: the start of work, or its end with the reason recorded on the contract.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEeEmploymentRegisterSendRequest{
        ContractID: "contractId",
        Event: nordlet.PostV1DeclarationsEeEmploymentRegisterSendRequestEventStart,
    }
client.Declarations.PostV1DeclarationsEeEmploymentRegisterSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**contractID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**event:** `*nordlet.PostV1DeclarationsEeEmploymentRegisterSendRequestEvent` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsEsVerifactuDeclaracionResponsable(request) -> *nordlet.PostV1DeclarationsEsVerifactuDeclaracionResponsableResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Nordlet's declaración responsable for its VERI*FACTU invoicing system (Orden HAC/1177/2024, art. 15), as a PDF and as plain text.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsEsVerifactuDeclaracionResponsableRequest{}
client.Declarations.PostV1DeclarationsEsVerifactuDeclaracionResponsable(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsIeCt1Generate(request) -> *nordlet.PostV1DeclarationsIeCt1GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the Form CT1 of an accounting year as the ROS version 26 XML and the accompanying financial statements as inline XBRL on the FRS 102 Irish Extension 2026 taxonomy Revenue accepts, both from the ledger, the recorded tax adjustments, the annual accounts record and the officers, for upload through the company’s own ROS account. Says whether the company is above the iXBRL deferral limits (balance sheet total €4.4 million, turnover €8.8 million, 50 employees).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsIeCt1GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsIeCt1Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsIeB1Generate(request) -> *nordlet.PostV1DeclarationsIeB1GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the working paper for the Form B1 annual return of a financial year — company details, registered office, directors and secretary from Settings → Officers, the members from Settings → Shareholders, the issued share capital and the figures of the financial statements — in the order the CORE screens ask for them. The CRO publishes no file format for the B1, so it is keyed into CORE.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsIeB1GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsIeB1Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsItSdiPurchaseSend(request) -> *nordlet.PostV1DeclarationsItSdiPurchaseSendResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the TD16-TD19 integration document for a registered purchase invoice and send it to the Sistema di Interscambio. Since July 2022 a purchase from a supplier established abroad is reported this way instead of the esterometro. The Italian VAT rate to self-assess is a judgement about the supply: pass vatRatePercent unless the purchase lines already carry it, otherwise the request is refused rather than guessed.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsItSdiPurchaseSendRequest{
        PurchaseInvoiceID: "purchaseInvoiceId",
    }
client.Declarations.PostV1DeclarationsItSdiPurchaseSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**purchaseInvoiceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**tipoDocumento:** `*nordlet.PostV1DeclarationsItSdiPurchaseSendRequestTipoDocumento` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsItSdiPurchasePreview(request) -> *nordlet.PostV1DeclarationsItSdiPurchasePreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the TD16-TD19 integration document for a registered purchase invoice without sending it, so the rate and the document type can be checked first.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsItSdiPurchasePreviewRequest{
        PurchaseInvoiceID: "purchaseInvoiceId",
    }
client.Declarations.PostV1DeclarationsItSdiPurchasePreview(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**purchaseInvoiceID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**tipoDocumento:** `*nordlet.PostV1DeclarationsItSdiPurchasePreviewRequestTipoDocumento` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtSaftSend(request) -> *nordlet.PostV1DeclarationsLtSaftSendResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload the SAF-T file to i.SAF-T over the iSAFTUploaderService web service and start its processing. The submission itself is confirmed separately, because after confirmation the file can no longer be corrected.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtSaftSendRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Declarations.PostV1DeclarationsLtSaftSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.PostV1DeclarationsLtSaftSendRequestDataType` 
    
</dd>
</dl>

<dl>
<dd>

**confirm:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtSdFfdata(request) -> *nordlet.PostV1DeclarationsLtSdFfdataResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the Sodra 1-SD or 2-SD notice for the contracts starting or ending in the range as an .ffdata document for EDAS.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtSdFfdataRequest{
        Type: nordlet.PostV1DeclarationsLtSdFfdataRequestTypeOneSd,
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Declarations.PostV1DeclarationsLtSdFfdata(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1DeclarationsLtSdFfdataRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**managerFullName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**preparatorDetails:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLtPln204Ffdata(request) -> *nordlet.PostV1DeclarationsLtPln204FfdataResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the annual corporate income tax return PLN204 as an .ffdata document, including the PLN204S and PLN204Z annexes, from the ledger and the tax adjustments recorded for that year.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLtPln204FfdataRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLtPln204Ffdata(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsMtCompanyTaxGenerate(request) -> *nordlet.PostV1DeclarationsMtCompanyTaxGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the company income tax return and self-assessment of a year of assessment from the ledger and the recorded tax adjustments: the accounting profit before tax, the add-backs and deductions, the approved donations, capital allowances and losses carried forward, the chargeable income, the 35 % charge, the relief against the tax and the allocation of the distributable profit to the five tax accounts. The Malta Tax and Customs Administration issues the return as a personalised spreadsheet to the registered tax practitioner and publishes no layout, so the XML is a working file and the figures are keyed into that spreadsheet.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsMtCompanyTaxGenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsMtCompanyTaxGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsMtAnnualReturnGenerate(request) -> *nordlet.PostV1DeclarationsMtAnnualReturnGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual return of a year: the company number, registered office and made-up-to date, the share capital, the register of members, the directors and the company secretary and the accounts summary, as the figures the Malta Business Registry asks for on its own screens, plus the printed Annual Return Form of the Seventh Schedule filled in as a PDF for signing.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsMtAnnualReturnGenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsMtAnnualReturnGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlJpkFaGenerate(request) -> *nordlet.PostV1DeclarationsPlJpkFaGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_FA(4), the on-demand structure with every sales invoice issued in a period, its VAT bases per rate and one row per invoice line. Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlJpkFaGenerateRequest{
        DateFrom: "dateFrom",
        DateTo: "dateTo",
    }
client.Declarations.PostV1DeclarationsPlJpkFaGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlJpkKrGenerate(request) -> *nordlet.PostV1DeclarationsPlJpkKrGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_KR(1), the on-demand structure with the chart of accounts and its opening balances and turnover, the journal and the double entries behind it. Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlJpkKrGenerateRequest{
        DateFrom: "dateFrom",
        DateTo: "dateTo",
    }
client.Declarations.PostV1DeclarationsPlJpkKrGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlJpkMagGenerate(request) -> *nordlet.PostV1DeclarationsPlJpkMagGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_MAG(2), the on-demand structure with the warehouse documents of one warehouse: goods received from outside (PZ) or internally (PW) and issued to a customer (WZ) or internally (RW). Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlJpkMagGenerateRequest{
        DateFrom: "dateFrom",
        DateTo: "dateTo",
    }
client.Declarations.PostV1DeclarationsPlJpkMagGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlPit11Generate(request) -> *nordlet.PostV1DeclarationsPlPit11GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate PIT-11(29) for every person on the payroll of one year: the pay, the deductible costs, the advance withheld and the social and health contributions taken off it. One document per person, because that is how the form is filed.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlPit11GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlPit11Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlCit8Generate(request) -> *nordlet.PostV1DeclarationsPlCit8GenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate CIT-8(34), the annual corporate income tax return, from the ledger of the year and the recorded tax adjustments. The tax office code and the small-taxpayer setting come from the e-Deklaracje compliance settings, the seat address from the JPK gateway settings. Names the annexes the figures would need, which are not produced.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlCit8GenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlCit8Generate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlZusDraCompute(request) -> *nordlet.PostV1DeclarationsPlZusDraComputeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the monthly ZUS DRA settlement from the payroll run of one month: the pension, disability, sickness, accident and health insurance contributions and the Labour Fund, Solidarity Fund and guaranteed benefits fund charges, each split between the insured person and the payer. The amounts are carried into Płatnik or ePłatnik by hand.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlZusDraComputeRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlZusDraCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlZusDraKedu(request) -> *nordlet.PostV1DeclarationsPlZusDraKeduResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the KEDU file for one month: the ZUS DRA settlement and one ZUS RCA report per person on the payroll, in the schema kedu_5_4 that Płatnik and ePłatnik import. The payer REGON, short name and declaration deadline code come from the ZUS compliance settings; the insurance title code and working time of each person from the employee record.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlZusDraKeduRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlZusDraKedu(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsPlZusDraPdf(request) -> *nordlet.PostV1DeclarationsPlZusDraPdfResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fill the published ZUS DRA form for one month and return it as a PDF. The amounts, the payer identity and the deadline code are the same ones the KEDU file carries; blocks the payroll does not hold (paid benefits, bridging pensions, income declaration of a self-paying person) stay empty.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsPlZusDraPdfRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsPlZusDraPdf(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsRoEtransportBuild(request) -> *nordlet.PostV1DeclarationsRoEtransportBuildResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the RO e-Transport declaration for an issued waybill: goods with their tariff codes and masses, the commercial partner, the route and the vehicle. The XML follows the ANAF eTransport v2 schema and is kept as a file on the waybill. Anything listed in blockers has to be filled in before /etransport/send will accept it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsRoEtransportBuildRequest{
        WaybillID: "waybillId",
    }
client.Declarations.PostV1DeclarationsRoEtransportBuild(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsRoEtransportSubmit(request) -> *nordlet.PostV1DeclarationsRoEtransportSubmitResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Hand the RO e-Transport declaration for an issued waybill to ANAF under the SPV OAuth token in compliance settings, and return the upload index the UIT is read back with. Answers 422 while any field the ANAF validator requires is still missing.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsRoEtransportSubmitRequest{
        WaybillID: "waybillId",
    }
client.Declarations.PostV1DeclarationsRoEtransportSubmit(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsRoEtransportStatus(request) -> *nordlet.PostV1DeclarationsRoEtransportStatusResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Read the outcome of an e-Transport declaration from ANAF by its upload index, under the SPV OAuth token in compliance settings. Returns the UIT code once the declaration validates.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsRoEtransportStatusRequest{
        Reference: "reference",
    }
client.Declarations.PostV1DeclarationsRoEtransportStatus(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reference:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLiLohndeklarationGenerate(request) -> *nordlet.PostV1DeclarationsLiLohndeklarationGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual wage declaration (Lohndeklaration) to the AHV-IV-FAK from the approved payroll runs of the year as the CSV that AHVeasy imports under Lohndeklaration → CSV-Import der Lohndaten: one row per employee with the 18 columns of the AHVeasy template, the AHV-liable wage and the ALV wage.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLiLohndeklarationGenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLiLohndeklarationGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsLiLohnlistenGenerate(request) -> *nordlet.PostV1DeclarationsLiLohnlistenGenerateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual wage list (Lohnliste) of a Liechtenstein employer from the approved payroll runs of the year as the XLSX file the tax administration's eLohnausweis / eLohnlisten application imports: one row per employee with PEID, name, birth date, address, gross wage, wage tax withheld and the settlement period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsLiLohnlistenGenerateRequest{
        Year: int64(1000000),
    }
client.Declarations.PostV1DeclarationsLiLohnlistenGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsConfigsList(request) -> *nordlet.PostV1DeclarationsConfigsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsConfigsListRequest{}
client.Declarations.PostV1DeclarationsConfigsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsConfigsUpdate(request) -> *nordlet.PostV1DeclarationsConfigsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsConfigsUpdateRequest{
        System: "system",
        Config: map[string]string{
            "key": "value",
        },
    }
client.Declarations.PostV1DeclarationsConfigsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**system:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**config:** `map[string]string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.StoreTheCertificateOrPrivateKeyAFilingSystemAuthenticatesWith(request) -> *nordlet.PostV1DeclarationsCertificatesUploadResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsCertificatesUploadRequest{
        System: "system",
        FileName: "fileName",
        Content: "content",
    }
client.Declarations.StoreTheCertificateOrPrivateKeyAFilingSystemAuthenticatesWith(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**system:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fileName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `string` — Base64-encoded PEM or PKCS#12 file
    
</dd>
</dl>

<dl>
<dd>

**passphrase:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsCertificatesList(request) -> *nordlet.PostV1DeclarationsCertificatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsCertificatesListRequest{}
client.Declarations.PostV1DeclarationsCertificatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsCertificatesDelete(request) -> *nordlet.PostV1DeclarationsCertificatesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsCertificatesDeleteRequest{
        System: "system",
        FieldKey: nordlet.PostV1DeclarationsCertificatesDeleteRequestFieldKeyCertificate,
    }
client.Declarations.PostV1DeclarationsCertificatesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**system:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fieldKey:** `*nordlet.PostV1DeclarationsCertificatesDeleteRequestFieldKey` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.WhichDeadlinesNordletCanFileByItselfForThisCompanyAndWhichAreSwitchedOn(request) -> *nordlet.PostV1DeclarationsAutomationListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAutomationListRequest{}
client.Declarations.WhichDeadlinesNordletCanFileByItselfForThisCompanyAndWhichAreSwitchedOn(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsAutomationUpdate(request) -> *nordlet.PostV1DeclarationsAutomationUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsAutomationUpdateRequest{
        RuleKey: "ruleKey",
        Enabled: true,
    }
client.Declarations.PostV1DeclarationsAutomationUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ruleKey:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**enabled:** `bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.SendAFilingWhoseDeliveryFailedOnceMoreWithTheBytesThatWereGenerated(request) -> *nordlet.PostV1DeclarationsSubmissionsRetryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsSubmissionsRetryRequest{
        ID: "id",
    }
client.Declarations.SendAFilingWhoseDeliveryFailedOnceMoreWithTheBytesThatWereGenerated(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsSubmissionsCreate(request) -> *nordlet.PostV1DeclarationsSubmissionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsSubmissionsCreateRequest{
        Obligation: nordlet.PostV1DeclarationsSubmissionsCreateRequestObligationLtIsaf,
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PostV1DeclarationsSubmissionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**obligation:** `*nordlet.PostV1DeclarationsSubmissionsCreateRequestObligation` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.PostV1DeclarationsSubmissionsCreateRequestDataType` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsSubmissionsMark(request) -> *nordlet.PostV1DeclarationsSubmissionsMarkResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsSubmissionsMarkRequest{
        ID: "id",
        Status: nordlet.PostV1DeclarationsSubmissionsMarkRequestStatusSubmitted,
    }
client.Declarations.PostV1DeclarationsSubmissionsMark(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1DeclarationsSubmissionsMarkRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**externalRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**message:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PostV1DeclarationsSubmissionsList(request) -> *nordlet.PostV1DeclarationsSubmissionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1DeclarationsSubmissionsListRequest{}
client.Declarations.PostV1DeclarationsSubmissionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1DeclarationsSubmissionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1DeclarationsSubmissionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ledger
<details><summary><code>client.Ledger.PostV1LedgerAccountsList(request) -> *nordlet.PostV1LedgerAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerAccountsListRequest{}
client.Ledger.PostV1LedgerAccountsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerAccountsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerAccountsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerAccountsCreate(request) -> *nordlet.PostV1LedgerAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerAccountsCreateRequest{
        Code: "code",
        Name: "name",
        Type: nordlet.PostV1LedgerAccountsCreateRequestTypeAsset,
    }
client.Ledger.PostV1LedgerAccountsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1LedgerAccountsCreateRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1LedgerAccountsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**parentID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isPostable:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerAccountsUpdate(request) -> *nordlet.PostV1LedgerAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerAccountsUpdateRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerAccountsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1LedgerAccountsUpdateRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**parentID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isPostable:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerAccountsApplyTemplate(request) -> *nordlet.PostV1LedgerAccountsApplyTemplateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerAccountsApplyTemplateRequest{}
client.Ledger.PostV1LedgerAccountsApplyTemplate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.MoveACompanyThatHasPostedNothingYetToTheChartOfAccountsOfItsCountry(request) -> *nordlet.PostV1LedgerAccountsSwitchChartResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replaces the seeded chart with the chart template of the company country (the Romanian general chart for a company registered in Romania, the Lithuanian standard chart otherwise) and switches the posting defaults with it. Answers 409 when the company already uses that chart, has journal entries, holds accounts created by hand, or has settings that name an account the new chart does not have.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerAccountsSwitchChartRequest{}
client.Ledger.MoveACompanyThatHasPostedNothingYetToTheChartOfAccountsOfItsCountry(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerPeriodsList(request) -> *nordlet.PostV1LedgerPeriodsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerPeriodsListRequest{}
client.Ledger.PostV1LedgerPeriodsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerPeriodsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerPeriodsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerPeriodsLock(request) -> *nordlet.PostV1LedgerPeriodsLockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerPeriodsLockRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Ledger.PostV1LedgerPeriodsLock(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerPeriodsUnlock(request) -> *nordlet.PostV1LedgerPeriodsUnlockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerPeriodsUnlockRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Ledger.PostV1LedgerPeriodsUnlock(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerJournalTransactionsList(request) -> *nordlet.PostV1LedgerJournalTransactionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerJournalTransactionsListRequest{}
client.Ledger.PostV1LedgerJournalTransactionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerJournalTransactionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerJournalTransactionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCentersCreate(request) -> *nordlet.PostV1LedgerCostCentersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCentersCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Ledger.PostV1LedgerCostCentersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCentersUpdate(request) -> *nordlet.PostV1LedgerCostCentersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCentersUpdateRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerCostCentersUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCentersList(request) -> *nordlet.PostV1LedgerCostCentersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCentersListRequest{}
client.Ledger.PostV1LedgerCostCentersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerCostCentersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerCostCentersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCenterGroupsCreate(request) -> *nordlet.PostV1LedgerCostCenterGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCenterGroupsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Ledger.PostV1LedgerCostCenterGroupsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCenterGroupsUpdate(request) -> *nordlet.PostV1LedgerCostCenterGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCenterGroupsUpdateRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerCostCenterGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCenterGroupsDelete(request) -> *nordlet.PostV1LedgerCostCenterGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCenterGroupsDeleteRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerCostCenterGroupsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerCostCenterGroupsList(request) -> *nordlet.PostV1LedgerCostCenterGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerCostCenterGroupsListRequest{}
client.Ledger.PostV1LedgerCostCenterGroupsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerCostCenterGroupsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerCostCenterGroupsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerPostingRulesList(request) -> *nordlet.PostV1LedgerPostingRulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerPostingRulesListRequest{}
client.Ledger.PostV1LedgerPostingRulesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerPostingRulesUpdate(request) -> *nordlet.PostV1LedgerPostingRulesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerPostingRulesUpdateRequest{
        Rules: []*nordlet.PostV1LedgerPostingRulesUpdateRequestRulesItem{
            &nordlet.PostV1LedgerPostingRulesUpdateRequestRulesItem{
                Key: nordlet.PostV1LedgerPostingRulesUpdateRequestRulesItemKeySalesReceivable,
            },
        },
    }
client.Ledger.PostV1LedgerPostingRulesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rules:** `[]*nordlet.PostV1LedgerPostingRulesUpdateRequestRulesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerOwnersCreate(request) -> *nordlet.PostV1LedgerOwnersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerOwnersCreateRequest{
        Name: "name",
    }
client.Ledger.PostV1LedgerOwnersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**equityAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAmount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesType:** `*nordlet.PostV1LedgerOwnersCreateRequestSharesType` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `*nordlet.PostV1LedgerOwnersCreateRequestPartnerLiability` 
    
</dd>
</dl>

<dl>
<dd>

**specialBalanceRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryBalanceRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1LedgerOwnersCreateRequestAddress` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerOwnersUpdate(request) -> *nordlet.PostV1LedgerOwnersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerOwnersUpdateRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerOwnersUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**equityAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAmount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sharesType:** `*nordlet.PostV1LedgerOwnersUpdateRequestSharesType` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `*nordlet.PostV1LedgerOwnersUpdateRequestPartnerLiability` 
    
</dd>
</dl>

<dl>
<dd>

**specialBalanceRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryBalanceRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1LedgerOwnersUpdateRequestAddress` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerOwnersDelete(request) -> *nordlet.PostV1LedgerOwnersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerOwnersDeleteRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerOwnersDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerOwnersList(request) -> *nordlet.PostV1LedgerOwnersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerOwnersListRequest{}
client.Ledger.PostV1LedgerOwnersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1LedgerOwnersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1LedgerOwnersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerJournalTransactionsGet(request) -> *nordlet.PostV1LedgerJournalTransactionsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerJournalTransactionsGetRequest{
        ID: "id",
    }
client.Ledger.PostV1LedgerJournalTransactionsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.PostV1LedgerJournalTransactionsCreate(request) -> *nordlet.PostV1LedgerJournalTransactionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerJournalTransactionsCreateRequest{
        Date: "date",
        Entries: []*nordlet.PostV1LedgerJournalTransactionsCreateRequestEntriesItem{
            &nordlet.PostV1LedgerJournalTransactionsCreateRequestEntriesItem{
                AccountCode: "accountCode",
            },
        },
    }
client.Ledger.PostV1LedgerJournalTransactionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**entries:** `[]*nordlet.PostV1LedgerJournalTransactionsCreateRequestEntriesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.NationalStatementLayoutsAvailableToTheCompany(request) -> *nordlet.PostV1LedgerStatementRowsSchemesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The rows or codes of each return or registry deposit of the company country that are filled from account balances. Accounts fall into a row by the layout defaults for the standard chart of accounts unless mapped under Settings → Statement rows.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerStatementRowsSchemesRequest{}
client.Ledger.NationalStatementLayoutsAvailableToTheCompany(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.AccountsPlacedOnTheRowsOfAStatementLayoutWithTheRowTotalsOfAPeriod(request) -> *nordlet.PostV1LedgerStatementRowsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerStatementRowsListRequest{
        Scheme: "scheme",
    }
client.Ledger.AccountsPlacedOnTheRowsOfAStatementLayoutWithTheRowTotalsOfAPeriod(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**scheme:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.MapAnAccountOrAnAccountCodePrefixToARowOfAStatementLayout(request) -> *nordlet.PostV1LedgerStatementRowsSetResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

A mapping on a code prefix covers every account whose code starts with it; the longest matching prefix wins. An empty rowCode removes the mapping so the layout default applies again.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1LedgerStatementRowsSetRequest{
        Scheme: "scheme",
        AccountCode: "accountCode",
    }
client.Ledger.MapAnAccountOrAnAccountCodePrefixToARowOfAStatementLayout(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**scheme:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**rowCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.OfficersOfTheCompany(request) -> *nordlet.PostV1OfficersListResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Directors, board members, the company secretary, representatives and liquidators, with their personal identifier, appointment and resignation dates and whether they sign the annual accounts. Annual returns and registry deposits are built from this register.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OfficersListRequest{}
client.Ledger.OfficersOfTheCompany(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.RecordAnOfficerOfTheCompany(request) -> *nordlet.PostV1OfficersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OfficersCreateRequest{
        Name: "name",
        Role: nordlet.PostV1OfficersCreateRequestRoleDirector,
    }
client.Ledger.RecordAnOfficerOfTheCompany(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*nordlet.PostV1OfficersCreateRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**appointedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**signsAccounts:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.ChangeARecordedOfficer(request) -> *nordlet.PostV1OfficersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OfficersUpdateRequest{
        ID: "id",
        Name: "name",
        Role: nordlet.PostV1OfficersUpdateRequestRoleDirector,
    }
client.Ledger.ChangeARecordedOfficer(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*nordlet.PostV1OfficersUpdateRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**appointedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**signsAccounts:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.RemoveARecordedOfficer(request) -> *nordlet.PostV1OfficersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1OfficersDeleteRequest{
        ID: "id",
    }
client.Ledger.RemoveARecordedOfficer(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Migration
<details><summary><code>client.Migration.CheckAHistoricalBooksPackageWithoutWritingAnything(request) -> *nordlet.PostV1MigrationBooksValidateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Runs every check the import runs (accounts, partners, balances, open invoices, assets, stock) and returns the same summary and warnings, then rolls everything back. Nothing is stored.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1MigrationBooksValidateRequest{
        CutoverDate: "cutoverDate",
    }
client.Migration.CheckAHistoricalBooksPackageWithoutWritingAnything(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `[]*nordlet.PostV1MigrationBooksValidateRequestAccountsItem` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `[]*nordlet.PostV1MigrationBooksValidateRequestPartnersItem` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.PostV1MigrationBooksValidateRequestItemsItem` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `*nordlet.PostV1MigrationBooksValidateRequestOpeningBalances` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `[]*nordlet.PostV1MigrationBooksValidateRequestJournalItem` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `[]*nordlet.PostV1MigrationBooksValidateRequestOpenReceivablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `[]*nordlet.PostV1MigrationBooksValidateRequestOpenPayablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `[]*nordlet.PostV1MigrationBooksValidateRequestAssetGroupsItem` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `[]*nordlet.PostV1MigrationBooksValidateRequestFixedAssetsItem` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `[]*nordlet.PostV1MigrationBooksValidateRequestStockItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Migration.ImportHistoricalBooksFromAPreviousAccountingSystem(request) -> *nordlet.PostV1MigrationBooksImportResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Brings a company over from another system in one call: chart of accounts, partners, items, opening balances (or the full journal history), open customer and supplier invoices, fixed assets with their accumulated depreciation, and stock on hand. The whole package is written in one database transaction — if any row fails, nothing is stored.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1MigrationBooksImportRequest{
        CutoverDate: "cutoverDate",
    }
client.Migration.ImportHistoricalBooksFromAPreviousAccountingSystem(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `[]*nordlet.PostV1MigrationBooksImportRequestAccountsItem` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `[]*nordlet.PostV1MigrationBooksImportRequestPartnersItem` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.PostV1MigrationBooksImportRequestItemsItem` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `*nordlet.PostV1MigrationBooksImportRequestOpeningBalances` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `[]*nordlet.PostV1MigrationBooksImportRequestJournalItem` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `[]*nordlet.PostV1MigrationBooksImportRequestOpenReceivablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `[]*nordlet.PostV1MigrationBooksImportRequestOpenPayablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `[]*nordlet.PostV1MigrationBooksImportRequestAssetGroupsItem` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `[]*nordlet.PostV1MigrationBooksImportRequestFixedAssetsItem` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `[]*nordlet.PostV1MigrationBooksImportRequestStockItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Assets
<details><summary><code>client.Assets.PostV1AssetsGroupsCreate(request) -> *nordlet.PostV1AssetsGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsGroupsCreateRequest{
        Code: "code",
        Name: "name",
        AssetAccountCode: "assetAccountCode",
        DepreciationAccountCode: "depreciationAccountCode",
    }
client.Assets.PostV1AssetsGroupsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**defaultUsefulLifeMonths:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**assetAccountCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationAccountCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsGroupsList(request) -> *nordlet.PostV1AssetsGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsGroupsListRequest{}
client.Assets.PostV1AssetsGroupsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AssetsGroupsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AssetsGroupsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsCreate(request) -> *nordlet.PostV1AssetsAssetsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsCreateRequest{
        GroupID: "groupId",
        Code: "code",
        Name: "name",
        AcquisitionDate: "acquisitionDate",
        AcquisitionCost: "acquisitionCost",
    }
client.Assets.PostV1AssetsAssetsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionCost:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**salvageValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**usefulLifeMonths:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.PostV1AssetsAssetsCreateRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsUpdate(request) -> *nordlet.PostV1AssetsAssetsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsUpdateRequest{
        ID: "id",
    }
client.Assets.PostV1AssetsAssetsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionCost:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**salvageValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**usefulLifeMonths:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.PostV1AssetsAssetsUpdateRequestDocumentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsInputVat(request) -> *nordlet.PostV1AssetsAssetsInputVatResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Record the input VAT facts of a capital good that the annual VAT return needs for the adjustment of the deduction over the adjustment period (Article 187 of the VAT Directive, § 15a UStG): the input VAT on the acquisition, the date of first use, the share of use for deductible turnover at first use, whether it is land or a building (ten-year period instead of five), and every later year in which the share changed or the good was sold or withdrawn. Allowed also after depreciation has been posted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsInputVatRequest{
        ID: "id",
        InputVatRealEstate: true,
        InputVatUseChanges: []*nordlet.PostV1AssetsAssetsInputVatRequestInputVatUseChangesItem{
            &nordlet.PostV1AssetsAssetsInputVatRequestInputVatUseChangesItem{
                Year: int64(1000000),
                Percent: "percent",
                Reason: nordlet.PostV1AssetsAssetsInputVatRequestInputVatUseChangesItemReasonUseChange,
            },
        },
    }
client.Assets.PostV1AssetsAssetsInputVat(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatAmount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatFirstUseDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatDeductiblePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatRealEstate:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatUseChanges:** `[]*nordlet.PostV1AssetsAssetsInputVatRequestInputVatUseChangesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsGet(request) -> *nordlet.PostV1AssetsAssetsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsGetRequest{
        ID: "id",
    }
client.Assets.PostV1AssetsAssetsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsList(request) -> *nordlet.PostV1AssetsAssetsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsListRequest{}
client.Assets.PostV1AssetsAssetsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AssetsAssetsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AssetsAssetsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsAssetsModernize(request) -> *nordlet.PostV1AssetsAssetsModernizeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsAssetsModernizeRequest{
        ID: "id",
        Date: "date",
        Amount: "amount",
    }
client.Assets.PostV1AssetsAssetsModernize(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**addedLifeMonths:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsDepreciationPreview(request) -> *nordlet.PostV1AssetsDepreciationPreviewResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsDepreciationPreviewRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Assets.PostV1AssetsDepreciationPreview(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.PostV1AssetsDepreciationPost(request) -> *nordlet.PostV1AssetsDepreciationPostResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AssetsDepreciationPostRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Assets.PostV1AssetsDepreciationPost(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Hr
<details><summary><code>client.Hr.PostV1HrPositionsCreate(request) -> *nordlet.PostV1HrPositionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrPositionsCreateRequest{
        Name: "name",
    }
client.Hr.PostV1HrPositionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1HrPositionsCreateRequestTranslationsValue` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrPositionsUpdate(request) -> *nordlet.PostV1HrPositionsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrPositionsUpdateRequest{
        ID: "id",
    }
client.Hr.PostV1HrPositionsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `map[string]*nordlet.PostV1HrPositionsUpdateRequestTranslationsValue` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrPositionsList(request) -> *nordlet.PostV1HrPositionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrPositionsListRequest{}
client.Hr.PostV1HrPositionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1HrPositionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1HrPositionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesCreate(request) -> *nordlet.PostV1HrEmployeesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesCreateRequest{
        FirstName: "firstName",
        LastName: "lastName",
    }
client.Hr.PostV1HrEmployeesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**firstName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**lastName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1HrEmployeesCreateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceStart:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**applyAllowance:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**payrollOptions:** `map[string]string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `[]*nordlet.PostV1HrEmployeesCreateRequestAttributesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesUpdate(request) -> *nordlet.PostV1HrEmployeesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesUpdateRequest{
        ID: "id",
    }
client.Hr.PostV1HrEmployeesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**firstName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lastName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1HrEmployeesUpdateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceStart:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**applyAllowance:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**payrollOptions:** `map[string]string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `[]*nordlet.PostV1HrEmployeesUpdateRequestAttributesItem` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**terminationDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1HrEmployeesUpdateRequestStatus` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesGet(request) -> *nordlet.PostV1HrEmployeesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesGetRequest{
        ID: "id",
    }
client.Hr.PostV1HrEmployeesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.ExtraEmployeeDetailsTheCountryOfTheCompanyAsksFor(request) -> *nordlet.PostV1HrEmployeesFieldsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attributes a filing of the company country needs about a person that the shared employee record does not carry, such as the sex and place of birth an Italian income certificate asks for. Their values are kept in the payrollOptions of the employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesFieldsRequest{}
client.Hr.ExtraEmployeeDetailsTheCountryOfTheCompanyAsksFor(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesList(request) -> *nordlet.PostV1HrEmployeesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesListRequest{}
client.Hr.PostV1HrEmployeesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1HrEmployeesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1HrEmployeesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesDelete(request) -> *nordlet.PostV1HrEmployeesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesDeleteRequest{
        ID: "id",
    }
client.Hr.PostV1HrEmployeesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.BlankAnEmployeesPersonalDataAndHideTheRecord(request) -> *nordlet.PostV1HrEmployeesAnonymizeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replaces the name with a placeholder and removes personal code, birth date, contact details, address, bank account, social-insurance number, notes and sick-leave reasons. Payroll and contract rows stay linked to the record for the statutory retention period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesAnonymizeRequest{
        ID: "id",
    }
client.Hr.BlankAnEmployeesPersonalDataAndHideTheRecord(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrContractsCreate(request) -> *nordlet.PostV1HrContractsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrContractsCreateRequest{
        EmployeeID: "employeeId",
        StartDate: "startDate",
        BaseSalary: "baseSalary",
    }
client.Hr.PostV1HrContractsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**positionID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**departmentID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**scheduleID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**agreementID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**contractNo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1HrContractsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**startDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**baseSalary:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**salaryType:** `*nordlet.PostV1HrContractsCreateRequestSalaryType` 
    
</dd>
</dl>

<dl>
<dd>

**workHours:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrContractsEnd(request) -> *nordlet.PostV1HrContractsEndResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrContractsEndRequest{
        ID: "id",
        EndDate: "endDate",
    }
client.Hr.PostV1HrContractsEnd(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**endReason:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrContractsList(request) -> *nordlet.PostV1HrContractsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrContractsListRequest{}
client.Hr.PostV1HrContractsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1HrContractsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1HrContractsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrLeaveBalancesSet(request) -> *nordlet.PostV1HrLeaveBalancesSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrLeaveBalancesSetRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        EntitledDays: "entitledDays",
    }
client.Hr.PostV1HrLeaveBalancesSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**entitledDays:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**usedDays:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrLeaveBalancesList(request) -> *nordlet.PostV1HrLeaveBalancesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrLeaveBalancesListRequest{}
client.Hr.PostV1HrLeaveBalancesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrIncapacityCertificatesCreate(request) -> *nordlet.PostV1HrIncapacityCertificatesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrIncapacityCertificatesCreateRequest{
        EmployeeID: "employeeId",
        Number: "number",
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Hr.PostV1HrIncapacityCertificatesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**number:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrIncapacityCertificatesList(request) -> *nordlet.PostV1HrIncapacityCertificatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrIncapacityCertificatesListRequest{}
client.Hr.PostV1HrIncapacityCertificatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1HrIncapacityCertificatesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1HrIncapacityCertificatesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesRecordsCreate(request) -> *nordlet.PostV1HrEmployeesRecordsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesRecordsCreateRequest{
        EmployeeID: "employeeId",
        Type: nordlet.PostV1HrEmployeesRecordsCreateRequestTypeEducation,
        Title: "title",
    }
client.Hr.PostV1HrEmployeesRecordsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1HrEmployeesRecordsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**institution:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedAt:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fileID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesRecordsUpdate(request) -> *nordlet.PostV1HrEmployeesRecordsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesRecordsUpdateRequest{
        ID: "id",
    }
client.Hr.PostV1HrEmployeesRecordsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1HrEmployeesRecordsUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**institution:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issuedAt:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fileID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesRecordsDelete(request) -> *nordlet.PostV1HrEmployeesRecordsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesRecordsDeleteRequest{
        ID: "id",
    }
client.Hr.PostV1HrEmployeesRecordsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesRecordsList(request) -> *nordlet.PostV1HrEmployeesRecordsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesRecordsListRequest{}
client.Hr.PostV1HrEmployeesRecordsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1HrEmployeesRecordsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1HrEmployeesRecordsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrEmployeesAttachmentsList(request) -> *nordlet.PostV1HrEmployeesAttachmentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrEmployeesAttachmentsListRequest{
        EmployeeID: "employeeId",
    }
client.Hr.PostV1HrEmployeesAttachmentsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrTimesheetsGenerate(request) -> *nordlet.PostV1HrTimesheetsGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrTimesheetsGenerateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.PostV1HrTimesheetsGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**employeeID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrTimesheetsUpsert(request) -> *nordlet.PostV1HrTimesheetsUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrTimesheetsUpsertRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        Month: int64(1000000),
        Days: []*nordlet.PostV1HrTimesheetsUpsertRequestDaysItem{
            &nordlet.PostV1HrTimesheetsUpsertRequestDaysItem{
                Day: int64(1000000),
                Hours: "hours",
                Type: nordlet.PostV1HrTimesheetsUpsertRequestDaysItemTypeWork,
            },
        },
    }
client.Hr.PostV1HrTimesheetsUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**days:** `[]*nordlet.PostV1HrTimesheetsUpsertRequestDaysItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrTimesheetsGet(request) -> *nordlet.PostV1HrTimesheetsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrTimesheetsGetRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.PostV1HrTimesheetsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrTimesheetsList(request) -> *nordlet.PostV1HrTimesheetsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrTimesheetsListRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.PostV1HrTimesheetsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PostV1HrTimesheetsDelete(request) -> *nordlet.PostV1HrTimesheetsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1HrTimesheetsDeleteRequest{
        ID: "id",
    }
client.Hr.PostV1HrTimesheetsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Fleet
<details><summary><code>client.Fleet.PostV1FleetVehiclesCreate(request) -> *nordlet.PostV1FleetVehiclesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetVehiclesCreateRequest{
        PlateNumber: "plateNumber",
        Make: "make",
        Model: "model",
    }
client.Fleet.PostV1FleetVehiclesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**plateNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**make_:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**vin:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fuelType:** `*nordlet.PostV1FleetVehiclesCreateRequestFuelType` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**marketValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssetID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**technicalInspectionDue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.PostV1FleetVehiclesCreateRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetVehiclesUpdate(request) -> *nordlet.PostV1FleetVehiclesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetVehiclesUpdateRequest{
        ID: "id",
    }
client.Fleet.PostV1FleetVehiclesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**plateNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**make_:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**vin:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fuelType:** `*nordlet.PostV1FleetVehiclesUpdateRequestFuelType` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**marketValue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssetID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**technicalInspectionDue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1FleetVehiclesUpdateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetVehiclesGet(request) -> *nordlet.PostV1FleetVehiclesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetVehiclesGetRequest{
        ID: "id",
    }
client.Fleet.PostV1FleetVehiclesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetVehiclesList(request) -> *nordlet.PostV1FleetVehiclesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetVehiclesListRequest{}
client.Fleet.PostV1FleetVehiclesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1FleetVehiclesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1FleetVehiclesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetAssignmentsCreate(request) -> *nordlet.PostV1FleetAssignmentsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetAssignmentsCreateRequest{
        VehicleID: "vehicleId",
        EmployeeID: "employeeId",
        FromDate: "fromDate",
    }
client.Fleet.PostV1FleetAssignmentsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**vehicleID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**employeeID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**privateUse:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**employerPaysFuel:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetAssignmentsEnd(request) -> *nordlet.PostV1FleetAssignmentsEndResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetAssignmentsEndRequest{
        ID: "id",
        ToDate: "toDate",
    }
client.Fleet.PostV1FleetAssignmentsEnd(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetAssignmentsList(request) -> *nordlet.PostV1FleetAssignmentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetAssignmentsListRequest{}
client.Fleet.PostV1FleetAssignmentsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1FleetAssignmentsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1FleetAssignmentsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.PostV1FleetNaturaPreview(request) -> *nordlet.PostV1FleetNaturaPreviewResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FleetNaturaPreviewRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Fleet.PostV1FleetNaturaPreview(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Payroll
<details><summary><code>client.Payroll.PostV1PayrollDepartmentsCreate(request) -> *nordlet.PostV1PayrollDepartmentsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollDepartmentsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Payroll.PostV1PayrollDepartmentsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollDepartmentsList(request) -> *nordlet.PostV1PayrollDepartmentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollDepartmentsListRequest{}
client.Payroll.PostV1PayrollDepartmentsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollSchedulesCreate(request) -> *nordlet.PostV1PayrollSchedulesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollSchedulesCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Payroll.PostV1PayrollSchedulesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**hoursPerWeek:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollSchedulesList(request) -> *nordlet.PostV1PayrollSchedulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollSchedulesListRequest{}
client.Payroll.PostV1PayrollSchedulesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.CalculateOneEmployeePaymentUnderTheRulesOfTheCompanyCountry(request) -> *nordlet.PostV1PayrollCalcResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollCalcRequest{
        TaxableBase: "taxableBase",
        Date: "date",
    }
client.Payroll.CalculateOneEmployeePaymentUnderTheRulesOfTheCompanyCountry(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**taxableBase:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**applyAllowance:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**fixedTerm:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**benefitInKind:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**options:** `map[string]string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollRunsCreate(request) -> *nordlet.PostV1PayrollRunsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollRunsCreateRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Payroll.PostV1PayrollRunsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**includeNatura:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**grossOverrides:** `[]*nordlet.PostV1PayrollRunsCreateRequestGrossOverridesItem` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1PayrollRunsCreateRequestLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollRunsGet(request) -> *nordlet.PostV1PayrollRunsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollRunsGetRequest{
        ID: "id",
    }
client.Payroll.PostV1PayrollRunsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollRunsList(request) -> *nordlet.PostV1PayrollRunsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollRunsListRequest{}
client.Payroll.PostV1PayrollRunsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PayrollRunsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PayrollRunsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.RecordTheTimeAPersonWorkedInAPayrollLine(request) -> *nordlet.PostV1PayrollLinesAttendanceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The days and hours worked, the days on the register and the average hourly earnings that some countries report per employment. The Czech monthly employer report asks for all four. They can be set while the run is a draft.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollLinesAttendanceRequest{
        ID: "id",
    }
client.Payroll.RecordTheTimeAPersonWorkedInAPayrollLine(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**daysWorked:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**hoursWorked:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**registeredDays:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**averageHourlyEarnings:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollRunsApprove(request) -> *nordlet.PostV1PayrollRunsApproveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollRunsApproveRequest{
        ID: "id",
    }
client.Payroll.PostV1PayrollRunsApprove(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**wageAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**employerAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**payableAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**gpmAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sodraAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**employerSocialAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**deductionAccountCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollRunsCancel(request) -> *nordlet.PostV1PayrollRunsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollRunsCancelRequest{
        ID: "id",
    }
client.Payroll.PostV1PayrollRunsCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.PostV1PayrollPaymentsExport(request) -> *nordlet.PostV1PayrollPaymentsExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PayrollPaymentsExportRequest{
        RunID: "runId",
        BankAccountID: "bankAccountId",
    }
client.Payroll.PostV1PayrollPaymentsExport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**runID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**executionDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Agreements
<details><summary><code>client.Agreements.PostV1AgreementsTypesCreate(request) -> *nordlet.PostV1AgreementsTypesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsTypesCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Agreements.PostV1AgreementsTypesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsTypesList(request) -> *nordlet.PostV1AgreementsTypesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsTypesListRequest{}
client.Agreements.PostV1AgreementsTypesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AgreementsTypesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AgreementsTypesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsCreate(request) -> *nordlet.PostV1AgreementsAgreementsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsCreateRequest{
        Number: "number",
        StartDate: "startDate",
    }
client.Agreements.PostV1AgreementsAgreementsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**typeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1AgreementsAgreementsCreateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**employeeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**number:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**startDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**autoRenew:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**value:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**billingPeriod:** `*nordlet.PostV1AgreementsAgreementsCreateRequestBillingPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1AgreementsAgreementsCreateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.PostV1AgreementsAgreementsCreateRequestItemsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsGet(request) -> *nordlet.PostV1AgreementsAgreementsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsGetRequest{
        ID: "id",
    }
client.Agreements.PostV1AgreementsAgreementsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsUpdate(request) -> *nordlet.PostV1AgreementsAgreementsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsUpdateRequest{
        ID: "id",
    }
client.Agreements.PostV1AgreementsAgreementsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**typeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.PostV1AgreementsAgreementsUpdateRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**autoRenew:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**value:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**billingPeriod:** `*nordlet.PostV1AgreementsAgreementsUpdateRequestBillingPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1AgreementsAgreementsUpdateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsDelete(request) -> *nordlet.PostV1AgreementsAgreementsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsDeleteRequest{
        ID: "id",
    }
client.Agreements.PostV1AgreementsAgreementsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsList(request) -> *nordlet.PostV1AgreementsAgreementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsListRequest{}
client.Agreements.PostV1AgreementsAgreementsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AgreementsAgreementsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AgreementsAgreementsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsGenerateInvoice(request) -> *nordlet.PostV1AgreementsAgreementsGenerateInvoiceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsGenerateInvoiceRequest{
        ID: "id",
    }
client.Agreements.PostV1AgreementsAgreementsGenerateInvoice(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**asOfDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsAgreementsBillingRun(request) -> *nordlet.PostV1AgreementsAgreementsBillingRunResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsAgreementsBillingRunRequest{}
client.Agreements.PostV1AgreementsAgreementsBillingRun(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsInsurancePoliciesCreate(request) -> *nordlet.PostV1AgreementsInsurancePoliciesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsInsurancePoliciesCreateRequest{
        PolicyNumber: "policyNumber",
        InsuredObject: "insuredObject",
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Agreements.PostV1AgreementsInsurancePoliciesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**insurerPartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**policyNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**insuredObject:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**premium:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsInsurancePoliciesList(request) -> *nordlet.PostV1AgreementsInsurancePoliciesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsInsurancePoliciesListRequest{}
client.Agreements.PostV1AgreementsInsurancePoliciesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AgreementsInsurancePoliciesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AgreementsInsurancePoliciesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.PostV1AgreementsInsurancePoliciesDelete(request) -> *nordlet.PostV1AgreementsInsurancePoliciesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AgreementsInsurancePoliciesDeleteRequest{
        ID: "id",
    }
client.Agreements.PostV1AgreementsInsurancePoliciesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Inventory
<details><summary><code>client.Inventory.PostV1InventorySettingsGet(request) -> *nordlet.PostV1InventorySettingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventorySettingsGetRequest{}
client.Inventory.PostV1InventorySettingsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventorySettingsUpdate(request) -> *nordlet.PostV1InventorySettingsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventorySettingsUpdateRequest{
        NegativeStockPolicy: nordlet.PostV1InventorySettingsUpdateRequestNegativeStockPolicyReject,
    }
client.Inventory.PostV1InventorySettingsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**negativeStockPolicy:** `*nordlet.PostV1InventorySettingsUpdateRequestNegativeStockPolicy` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryWarehousesCreate(request) -> *nordlet.PostV1InventoryWarehousesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryWarehousesCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Inventory.PostV1InventoryWarehousesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryWarehousesList(request) -> *nordlet.PostV1InventoryWarehousesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryWarehousesListRequest{}
client.Inventory.PostV1InventoryWarehousesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1InventoryWarehousesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1InventoryWarehousesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockReceive(request) -> *nordlet.PostV1InventoryStockReceiveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockReceiveRequest{
        WarehouseID: "warehouseId",
        ItemID: "itemId",
        Date: "date",
        Quantity: "quantity",
        UnitCost: "unitCost",
    }
client.Inventory.PostV1InventoryStockReceive(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**unitCost:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**lotNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expiryDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockWriteOff(request) -> *nordlet.PostV1InventoryStockWriteOffResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockWriteOffRequest{
        WarehouseID: "warehouseId",
        ItemID: "itemId",
        Date: "date",
        Quantity: "quantity",
    }
client.Inventory.PostV1InventoryStockWriteOff(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**lotNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockTransfer(request) -> *nordlet.PostV1InventoryStockTransferResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockTransferRequest{
        FromWarehouseID: "fromWarehouseId",
        ToWarehouseID: "toWarehouseId",
        ItemID: "itemId",
        Date: "date",
        Quantity: "quantity",
    }
client.Inventory.PostV1InventoryStockTransfer(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromWarehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toWarehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**lotNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockTake(request) -> *nordlet.PostV1InventoryStockTakeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockTakeRequest{
        WarehouseID: "warehouseId",
        Date: "date",
        Lines: []*nordlet.PostV1InventoryStockTakeRequestLinesItem{
            &nordlet.PostV1InventoryStockTakeRequestLinesItem{
                CountedQty: "countedQty",
            },
        },
    }
client.Inventory.PostV1InventoryStockTake(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1InventoryStockTakeRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockLevels(request) -> *nordlet.PostV1InventoryStockLevelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockLevelsRequest{}
client.Inventory.PostV1InventoryStockLevels(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryStockMovementsList(request) -> *nordlet.PostV1InventoryStockMovementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryStockMovementsListRequest{}
client.Inventory.PostV1InventoryStockMovementsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1InventoryStockMovementsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1InventoryStockMovementsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLotsList(request) -> *nordlet.PostV1InventoryLotsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLotsListRequest{}
client.Inventory.PostV1InventoryLotsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1InventoryLotsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1InventoryLotsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLotsGet(request) -> *nordlet.PostV1InventoryLotsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLotsGetRequest{
        ID: "id",
    }
client.Inventory.PostV1InventoryLotsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLotsUpdate(request) -> *nordlet.PostV1InventoryLotsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLotsUpdateRequest{
        ID: "id",
    }
client.Inventory.PostV1InventoryLotsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**expiryDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLandedCostsCreate(request) -> *nordlet.PostV1InventoryLandedCostsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLandedCostsCreateRequest{
        Date: "date",
        Amount: "amount",
    }
client.Inventory.PostV1InventoryLandedCostsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**method:** `*nordlet.PostV1InventoryLandedCostsCreateRequestMethod` 
    
</dd>
</dl>

<dl>
<dd>

**goodsReceiptID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**movementIDs:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**sourceInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLandedCostsGet(request) -> *nordlet.PostV1InventoryLandedCostsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLandedCostsGetRequest{
        ID: "id",
    }
client.Inventory.PostV1InventoryLandedCostsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryLandedCostsList(request) -> *nordlet.PostV1InventoryLandedCostsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryLandedCostsListRequest{}
client.Inventory.PostV1InventoryLandedCostsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1InventoryLandedCostsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1InventoryLandedCostsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryReorderRulesCreate(request) -> *nordlet.PostV1InventoryReorderRulesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryReorderRulesCreateRequest{
        ItemID: "itemId",
        MinQty: "minQty",
    }
client.Inventory.PostV1InventoryReorderRulesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**minQty:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reorderQty:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryReorderRulesUpdate(request) -> *nordlet.PostV1InventoryReorderRulesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryReorderRulesUpdateRequest{
        ID: "id",
    }
client.Inventory.PostV1InventoryReorderRulesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**minQty:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**reorderQty:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryReorderRulesDelete(request) -> *nordlet.PostV1InventoryReorderRulesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryReorderRulesDeleteRequest{
        ID: "id",
    }
client.Inventory.PostV1InventoryReorderRulesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryReorderRulesList(request) -> *nordlet.PostV1InventoryReorderRulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryReorderRulesListRequest{}
client.Inventory.PostV1InventoryReorderRulesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1InventoryReorderRulesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1InventoryReorderRulesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.PostV1InventoryReorderRulesCheck(request) -> *nordlet.PostV1InventoryReorderRulesCheckResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1InventoryReorderRulesCheckRequest{}
client.Inventory.PostV1InventoryReorderRulesCheck(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Production
<details><summary><code>client.Production.PostV1ProductionWorkCentersCreate(request) -> *nordlet.PostV1ProductionWorkCentersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionWorkCentersCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Production.PostV1ProductionWorkCentersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**costPerHour:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**costAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**maintenanceIntervalDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionWorkCentersUpdate(request) -> *nordlet.PostV1ProductionWorkCentersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionWorkCentersUpdateRequest{
        ID: "id",
    }
client.Production.PostV1ProductionWorkCentersUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**costPerHour:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**costAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**maintenanceIntervalDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionWorkCentersList(request) -> *nordlet.PostV1ProductionWorkCentersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionWorkCentersListRequest{}
client.Production.PostV1ProductionWorkCentersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionWorkCentersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionWorkCentersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionRoutingsCreate(request) -> *nordlet.PostV1ProductionRoutingsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionRoutingsCreateRequest{
        Code: "code",
        Name: "name",
        Operations: []*nordlet.PostV1ProductionRoutingsCreateRequestOperationsItem{
            &nordlet.PostV1ProductionRoutingsCreateRequestOperationsItem{
                Sequence: int64(1000000),
                Name: "name",
                WorkCenterID: "workCenterId",
            },
        },
    }
client.Production.PostV1ProductionRoutingsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**operations:** `[]*nordlet.PostV1ProductionRoutingsCreateRequestOperationsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionRoutingsGet(request) -> *nordlet.PostV1ProductionRoutingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionRoutingsGetRequest{
        ID: "id",
    }
client.Production.PostV1ProductionRoutingsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionRoutingsList(request) -> *nordlet.PostV1ProductionRoutingsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionRoutingsListRequest{}
client.Production.PostV1ProductionRoutingsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionRoutingsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionRoutingsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionMaintenanceCreate(request) -> *nordlet.PostV1ProductionMaintenanceCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionMaintenanceCreateRequest{
        WorkCenterID: "workCenterId",
        Type: nordlet.PostV1ProductionMaintenanceCreateRequestTypePreventive,
        PlannedDate: "plannedDate",
    }
client.Production.PostV1ProductionMaintenanceCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workCenterID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1ProductionMaintenanceCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**plannedDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionMaintenanceComplete(request) -> *nordlet.PostV1ProductionMaintenanceCompleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionMaintenanceCompleteRequest{
        ID: "id",
        CompletedDate: "completedDate",
    }
client.Production.PostV1ProductionMaintenanceComplete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**completedDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**downtimeHours:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cost:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionMaintenanceCancel(request) -> *nordlet.PostV1ProductionMaintenanceCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionMaintenanceCancelRequest{
        ID: "id",
    }
client.Production.PostV1ProductionMaintenanceCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionMaintenanceList(request) -> *nordlet.PostV1ProductionMaintenanceListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionMaintenanceListRequest{}
client.Production.PostV1ProductionMaintenanceList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionMaintenanceListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionMaintenanceListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionBomsCreate(request) -> *nordlet.PostV1ProductionBomsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionBomsCreateRequest{
        Code: "code",
        Name: "name",
        FinishedItemID: "finishedItemId",
        Lines: []*nordlet.PostV1ProductionBomsCreateRequestLinesItem{
            &nordlet.PostV1ProductionBomsCreateRequestLinesItem{
                ComponentItemID: "componentItemId",
                Quantity: "quantity",
            },
        },
    }
client.Production.PostV1ProductionBomsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**finishedItemID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**outputQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**routingID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1ProductionBomsCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionBomsGet(request) -> *nordlet.PostV1ProductionBomsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionBomsGetRequest{
        ID: "id",
    }
client.Production.PostV1ProductionBomsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionBomsList(request) -> *nordlet.PostV1ProductionBomsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionBomsListRequest{}
client.Production.PostV1ProductionBomsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionBomsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionBomsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionOrdersCreate(request) -> *nordlet.PostV1ProductionOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionOrdersCreateRequest{
        BomID: "bomId",
        WarehouseID: "warehouseId",
        Quantity: "quantity",
        Date: "date",
    }
client.Production.PostV1ProductionOrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1ProductionOrdersCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**bomID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**routingID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionOrdersRecordOperation(request) -> *nordlet.PostV1ProductionOrdersRecordOperationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionOrdersRecordOperationRequest{
        ID: "id",
        ActualMinutes: "actualMinutes",
    }
client.Production.PostV1ProductionOrdersRecordOperation(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**actualMinutes:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionQualityChecksAdd(request) -> *nordlet.PostV1ProductionQualityChecksAddResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionQualityChecksAddRequest{
        OrderID: "orderId",
        Name: "name",
    }
client.Production.PostV1ProductionQualityChecksAdd(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**orderID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionQualityChecksRecord(request) -> *nordlet.PostV1ProductionQualityChecksRecordResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionQualityChecksRecordRequest{
        ID: "id",
        Result: nordlet.PostV1ProductionQualityChecksRecordRequestResultPassed,
    }
client.Production.PostV1ProductionQualityChecksRecord(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**result:** `*nordlet.PostV1ProductionQualityChecksRecordRequestResult` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionQualityChecksList(request) -> *nordlet.PostV1ProductionQualityChecksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionQualityChecksListRequest{}
client.Production.PostV1ProductionQualityChecksList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionQualityChecksListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionQualityChecksListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionOrdersComplete(request) -> *nordlet.PostV1ProductionOrdersCompleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionOrdersCompleteRequest{
        ID: "id",
    }
client.Production.PostV1ProductionOrdersComplete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**scrappedQuantity:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**componentsAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**finishedAccountCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionOrdersGet(request) -> *nordlet.PostV1ProductionOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionOrdersGetRequest{
        ID: "id",
    }
client.Production.PostV1ProductionOrdersGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.PostV1ProductionOrdersList(request) -> *nordlet.PostV1ProductionOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProductionOrdersListRequest{}
client.Production.PostV1ProductionOrdersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProductionOrdersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProductionOrdersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ecommerce
<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersCreate(request) -> *nordlet.PostV1EcommerceOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersCreateRequest{
        Lines: []*nordlet.PostV1EcommerceOrdersCreateRequestLinesItem{
            &nordlet.PostV1EcommerceOrdersCreateRequestLinesItem{
                Description: "description",
                Quantity: "quantity",
                UnitPriceExclVat: "unitPriceExclVat",
            },
        },
    }
client.Ecommerce.PostV1EcommerceOrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**channel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**externalRef:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partner:** `*nordlet.PostV1EcommerceOrdersCreateRequestPartner` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shipToCountryCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**marketplace:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1EcommerceOrdersCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersGet(request) -> *nordlet.PostV1EcommerceOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersGetRequest{
        ID: "id",
    }
client.Ecommerce.PostV1EcommerceOrdersGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersList(request) -> *nordlet.PostV1EcommerceOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersListRequest{}
client.Ecommerce.PostV1EcommerceOrdersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1EcommerceOrdersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1EcommerceOrdersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersReserve(request) -> *nordlet.PostV1EcommerceOrdersReserveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersReserveRequest{
        ID: "id",
    }
client.Ecommerce.PostV1EcommerceOrdersReserve(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersFulfill(request) -> *nordlet.PostV1EcommerceOrdersFulfillResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersFulfillRequest{
        ID: "id",
    }
client.Ecommerce.PostV1EcommerceOrdersFulfill(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cogsAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceOrdersCancel(request) -> *nordlet.PostV1EcommerceOrdersCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceOrdersCancelRequest{
        ID: "id",
    }
client.Ecommerce.PostV1EcommerceOrdersCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceProductsList(request) -> *nordlet.PostV1EcommerceProductsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceProductsListRequest{}
client.Ecommerce.PostV1EcommerceProductsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**priceListID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**updatedSince:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.PostV1EcommerceStockList(request) -> *nordlet.PostV1EcommerceStockListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1EcommerceStockListRequest{}
client.Ecommerce.PostV1EcommerceStockList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Cash
<details><summary><code>client.Cash.PostV1CashOrdersCreate(request) -> *nordlet.PostV1CashOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CashOrdersCreateRequest{
        Type: nordlet.PostV1CashOrdersCreateRequestTypeReceipt,
        Date: "date",
        Amount: "amount",
        Purpose: "purpose",
        CounterAccountCode: "counterAccountCode",
    }
client.Cash.PostV1CashOrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.PostV1CashOrdersCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**purpose:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**counterAccountCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**cashAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**employeeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Cash.PostV1CashOrdersGet(request) -> *nordlet.PostV1CashOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CashOrdersGetRequest{
        ID: "id",
    }
client.Cash.PostV1CashOrdersGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Cash.PostV1CashOrdersList(request) -> *nordlet.PostV1CashOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CashOrdersListRequest{}
client.Cash.PostV1CashOrdersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1CashOrdersListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1CashOrdersListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Cash.PostV1CashBalance(request) -> *nordlet.PostV1CashBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CashBalanceRequest{}
client.Cash.PostV1CashBalance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cashAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**asOf:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Cash.PostV1CashAdvanceHoldersBalances(request) -> *nordlet.PostV1CashAdvanceHoldersBalancesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CashAdvanceHoldersBalancesRequest{}
client.Cash.PostV1CashAdvanceHoldersBalances(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Projects
<details><summary><code>client.Projects.PostV1ProjectsCreate(request) -> *nordlet.PostV1ProjectsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsCreateRequest{
        Code: "code",
        Name: "name",
    }
client.Projects.PostV1ProjectsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsUpdate(request) -> *nordlet.PostV1ProjectsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsUpdateRequest{
        ID: "id",
    }
client.Projects.PostV1ProjectsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.PostV1ProjectsUpdateRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsGet(request) -> *nordlet.PostV1ProjectsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsGetRequest{
        ID: "id",
    }
client.Projects.PostV1ProjectsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsList(request) -> *nordlet.PostV1ProjectsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsListRequest{}
client.Projects.PostV1ProjectsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProjectsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProjectsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsTimeEntriesCreate(request) -> *nordlet.PostV1ProjectsTimeEntriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsTimeEntriesCreateRequest{
        ProjectID: "projectId",
        Date: "date",
        Hours: "hours",
    }
client.Projects.PostV1ProjectsTimeEntriesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**projectID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**employeeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**hours:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**billable:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsTimeEntriesUpdate(request) -> *nordlet.PostV1ProjectsTimeEntriesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsTimeEntriesUpdateRequest{
        ID: "id",
    }
client.Projects.PostV1ProjectsTimeEntriesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**hours:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**billable:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsTimeEntriesDelete(request) -> *nordlet.PostV1ProjectsTimeEntriesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsTimeEntriesDeleteRequest{
        ID: "id",
    }
client.Projects.PostV1ProjectsTimeEntriesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsTimeEntriesList(request) -> *nordlet.PostV1ProjectsTimeEntriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsTimeEntriesListRequest{}
client.Projects.PostV1ProjectsTimeEntriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ProjectsTimeEntriesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ProjectsTimeEntriesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsTimeEntriesBill(request) -> *nordlet.PostV1ProjectsTimeEntriesBillResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsTimeEntriesBillRequest{
        ProjectID: "projectId",
    }
client.Projects.PostV1ProjectsTimeEntriesBill(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**projectID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**groupBy:** `*nordlet.PostV1ProjectsTimeEntriesBillRequestGroupBy` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Projects.PostV1ProjectsReport(request) -> *nordlet.PostV1ProjectsReportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ProjectsReportRequest{}
client.Projects.PostV1ProjectsReport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**projectID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Transport
<details><summary><code>client.Transport.PostV1TransportWaybillsCreate(request) -> *nordlet.PostV1TransportWaybillsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsCreateRequest{
        ConsigneePartnerID: "consigneePartnerId",
        DispatchAt: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
        LoadAddress: "loadAddress",
        UnloadAddress: "unloadAddress",
    }
client.Transport.PostV1TransportWaybillsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**consigneePartnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**transporterPartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dispatchAt:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedArrivalAt:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**vehiclePlate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**trailerPlate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**driverName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**driverSurname:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loadWarehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loadAddress:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**unloadAddress:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**valueEur:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1TransportWaybillsCreateRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.PostV1TransportWaybillsUpdate(request) -> *nordlet.PostV1TransportWaybillsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsUpdateRequest{
        ID: "id",
    }
client.Transport.PostV1TransportWaybillsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**consigneePartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**transporterPartnerID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dispatchAt:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedArrivalAt:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**vehiclePlate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**trailerPlate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**driverName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**driverSurname:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loadWarehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**loadAddress:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**unloadAddress:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**valueEur:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.PostV1TransportWaybillsUpdateRequestLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.PostV1TransportWaybillsIssue(request) -> *nordlet.PostV1TransportWaybillsIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsIssueRequest{
        ID: "id",
    }
client.Transport.PostV1TransportWaybillsIssue(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.PostV1TransportWaybillsCancel(request) -> *nordlet.PostV1TransportWaybillsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsCancelRequest{
        ID: "id",
    }
client.Transport.PostV1TransportWaybillsCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.PostV1TransportWaybillsGet(request) -> *nordlet.PostV1TransportWaybillsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsGetRequest{
        ID: "id",
    }
client.Transport.PostV1TransportWaybillsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.PostV1TransportWaybillsList(request) -> *nordlet.PostV1TransportWaybillsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1TransportWaybillsListRequest{}
client.Transport.PostV1TransportWaybillsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1TransportWaybillsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1TransportWaybillsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Pos
<details><summary><code>client.Pos.PostV1PosDevicesCreate(request) -> *nordlet.PostV1PosDevicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosDevicesCreateRequest{
        Name: "name",
        SerialNumber: "serialNumber",
    }
client.Pos.PostV1PosDevicesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**serialNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**registrationNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Pos.PostV1PosDevicesUpdate(request) -> *nordlet.PostV1PosDevicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosDevicesUpdateRequest{
        ID: "id",
    }
client.Pos.PostV1PosDevicesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**serialNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**registrationNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Pos.PostV1PosDevicesList(request) -> *nordlet.PostV1PosDevicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosDevicesListRequest{}
client.Pos.PostV1PosDevicesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PosDevicesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PosDevicesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Pos.PostV1PosReportsCreate(request) -> *nordlet.PostV1PosReportsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosReportsCreateRequest{
        ReportNumber: "reportNumber",
        Date: "date",
        VatLines: []*nordlet.PostV1PosReportsCreateRequestVatLinesItem{
            &nordlet.PostV1PosReportsCreateRequestVatLinesItem{
                VatRatePercent: "vatRatePercent",
                NetAmount: "netAmount",
                VatAmount: "vatAmount",
            },
        },
    }
client.Pos.PostV1PosReportsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reportNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**deviceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatLines:** `[]*nordlet.PostV1PosReportsCreateRequestVatLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**cashAmount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cardAmount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**itemLines:** `[]*nordlet.PostV1PosReportsCreateRequestItemLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**cashAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cardAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**revenueAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**cogsAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Pos.PostV1PosReportsGet(request) -> *nordlet.PostV1PosReportsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosReportsGetRequest{
        ID: "id",
    }
client.Pos.PostV1PosReportsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Pos.PostV1PosReportsList(request) -> *nordlet.PostV1PosReportsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PosReportsListRequest{}
client.Pos.PostV1PosReportsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1PosReportsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1PosReportsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Calendar
<details><summary><code>client.Calendar.PostV1CalendarList(request) -> *nordlet.PostV1CalendarListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarListRequest{}
client.Calendar.PostV1CalendarList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**includeDone:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.PostV1CalendarGet(request) -> *nordlet.PostV1CalendarGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarGetRequest{
        Key: "key",
    }
client.Calendar.PostV1CalendarGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.GenerateTheFilingForADeadlineAndSendItToTheAdministration(request) -> *nordlet.PostV1CalendarSubmitResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarSubmitRequest{
        Key: "key",
    }
client.Calendar.GenerateTheFilingForADeadlineAndSendItToTheAdministration(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.GenerateTheFileOfADeadlineForTheCompanyToSendItself(request) -> *nordlet.PostV1CalendarDownloadResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Builds the file of a deadline whose format Nordlet produces but whose administration takes it only through the company's own account or program. Nothing is sent and no filing is recorded.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarDownloadRequest{
        Key: "key",
    }
client.Calendar.GenerateTheFileOfADeadlineForTheCompanyToSendItself(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.PostV1CalendarCreate(request) -> *nordlet.PostV1CalendarCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarCreateRequest{
        Title: "title",
        DueDate: "dueDate",
    }
client.Calendar.PostV1CalendarCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**title:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**done:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.PostV1CalendarUpdate(request) -> *nordlet.PostV1CalendarUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarUpdateRequest{
        Key: "key",
    }
client.Calendar.PostV1CalendarUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**done:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.PostV1CalendarDelete(request) -> *nordlet.PostV1CalendarDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1CalendarDeleteRequest{
        Key: "key",
    }
client.Calendar.PostV1CalendarDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Audit
<details><summary><code>client.Audit.PostV1AuditList(request) -> *nordlet.PostV1AuditListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AuditListRequest{}
client.Audit.PostV1AuditList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1AuditListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1AuditListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Webhooks
<details><summary><code>client.Webhooks.PostV1WebhooksSubscriptionsCreate(request) -> *nordlet.PostV1WebhooksSubscriptionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksSubscriptionsCreateRequest{
        URL: "url",
        Events: []string{
            "events",
        },
    }
client.Webhooks.PostV1WebhooksSubscriptionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**events:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**secret:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Webhooks.PostV1WebhooksSubscriptionsList(request) -> *nordlet.PostV1WebhooksSubscriptionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksSubscriptionsListRequest{}
client.Webhooks.PostV1WebhooksSubscriptionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1WebhooksSubscriptionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1WebhooksSubscriptionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Webhooks.PostV1WebhooksSubscriptionsUpdate(request) -> *nordlet.PostV1WebhooksSubscriptionsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksSubscriptionsUpdateRequest{
        ID: "id",
    }
client.Webhooks.PostV1WebhooksSubscriptionsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**url:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**events:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Webhooks.PostV1WebhooksSubscriptionsDelete(request) -> *nordlet.PostV1WebhooksSubscriptionsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksSubscriptionsDeleteRequest{
        ID: "id",
    }
client.Webhooks.PostV1WebhooksSubscriptionsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Webhooks.PostV1WebhooksDeliveriesList(request) -> *nordlet.PostV1WebhooksDeliveriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksDeliveriesListRequest{}
client.Webhooks.PostV1WebhooksDeliveriesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1WebhooksDeliveriesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1WebhooksDeliveriesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Webhooks.PostV1WebhooksDeliveriesRedeliver(request) -> *nordlet.PostV1WebhooksDeliveriesRedeliverResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1WebhooksDeliveriesRedeliverRequest{
        ID: "id",
    }
client.Webhooks.PostV1WebhooksDeliveriesRedeliver(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Bank
<details><summary><code>client.Bank.PostV1BankAccountsCreate(request) -> *nordlet.PostV1BankAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankAccountsCreateRequest{
        Name: "name",
    }
client.Bank.PostV1BankAccountsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankAccountsList(request) -> *nordlet.PostV1BankAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankAccountsListRequest{}
client.Bank.PostV1BankAccountsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankAccountsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankAccountsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankAccountsUpdate(request) -> *nordlet.PostV1BankAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankAccountsUpdateRequest{
        ID: "id",
    }
client.Bank.PostV1BankAccountsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankTransactionsImport(request) -> *nordlet.PostV1BankTransactionsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankTransactionsImportRequest{
        BankAccountID: "bankAccountId",
        Transactions: []*nordlet.PostV1BankTransactionsImportRequestTransactionsItem{
            &nordlet.PostV1BankTransactionsImportRequestTransactionsItem{
                Date: "date",
                Amount: "amount",
            },
        },
    }
client.Bank.PostV1BankTransactionsImport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**transactions:** `[]*nordlet.PostV1BankTransactionsImportRequestTransactionsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankStatementsImport(request) -> *nordlet.PostV1BankStatementsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankStatementsImportRequest{
        BankAccountID: "bankAccountId",
        Content: "content",
    }
client.Bank.PostV1BankStatementsImport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**templateID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**format:** `*nordlet.PostV1BankStatementsImportRequestFormat` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**transfersCsv:** `*string` — Stripe transfers export (plain CSV or base64) used to post lender payouts and commissions
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankTransactionsList(request) -> *nordlet.PostV1BankTransactionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankTransactionsListRequest{}
client.Bank.PostV1BankTransactionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankTransactionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankTransactionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankTransactionsMatch(request) -> *nordlet.PostV1BankTransactionsMatchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankTransactionsMatchRequest{
        TransactionID: "transactionId",
        DocumentType: nordlet.PostV1BankTransactionsMatchRequestDocumentTypeSaleInvoice,
        DocumentID: "documentId",
    }
client.Bank.PostV1BankTransactionsMatch(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**transactionID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentType:** `*nordlet.PostV1BankTransactionsMatchRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**documentID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankTransactionsRecord(request) -> *nordlet.PostV1BankTransactionsRecordResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankTransactionsRecordRequest{
        BankAccountID: "bankAccountId",
        Date: "date",
        Amount: "amount",
        DocumentType: nordlet.PostV1BankTransactionsRecordRequestDocumentTypeSaleInvoice,
        DocumentID: "documentId",
    }
client.Bank.PostV1BankTransactionsRecord(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documentType:** `*nordlet.PostV1BankTransactionsRecordRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**documentID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankPaymentsExport(request) -> *nordlet.PostV1BankPaymentsExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankPaymentsExportRequest{
        BankAccountID: "bankAccountId",
        PurchaseInvoiceIDs: []string{
            "purchaseInvoiceIds",
        },
    }
client.Bank.PostV1BankPaymentsExport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseInvoiceIDs:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**executionDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.CreateABankImportTemplateFieldsDefaultToTheTypesStandardFieldList(request) -> *nordlet.PostV1BankImportTemplatesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankImportTemplatesCreateRequest{
        Name: "name",
        Type: nordlet.PostV1BankImportTemplatesCreateRequestTypeStripe,
    }
client.Bank.CreateABankImportTemplateFieldsDefaultToTheTypesStandardFieldList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1BankImportTemplatesCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `[]*nordlet.PostV1BankImportTemplatesCreateRequestFieldsItem` 
    
</dd>
</dl>

<dl>
<dd>

**metaFields:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceVatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**companyMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceItemID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**advanceInvoices:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**authorizationOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**payoutOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**commissionOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lenderMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partialRefundLabel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fullRefundLabel:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankImportTemplatesUpdate(request) -> *nordlet.PostV1BankImportTemplatesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankImportTemplatesUpdateRequest{
        ID: "id",
    }
client.Bank.PostV1BankImportTemplatesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.PostV1BankImportTemplatesUpdateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `[]*nordlet.PostV1BankImportTemplatesUpdateRequestFieldsItem` 
    
</dd>
</dl>

<dl>
<dd>

**metaFields:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceVatRatePercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**companyMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceItemID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**advanceInvoices:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**authorizationOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**payoutOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**commissionOperationTypeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**lenderMetaField:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partialRefundLabel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fullRefundLabel:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankImportTemplatesDelete(request) -> *nordlet.PostV1BankImportTemplatesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankImportTemplatesDeleteRequest{
        ID: "id",
    }
client.Bank.PostV1BankImportTemplatesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankImportTemplatesGet(request) -> *nordlet.PostV1BankImportTemplatesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankImportTemplatesGetRequest{
        ID: "id",
    }
client.Bank.PostV1BankImportTemplatesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankImportTemplatesList(request) -> *nordlet.PostV1BankImportTemplatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankImportTemplatesListRequest{}
client.Bank.PostV1BankImportTemplatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankImportTemplatesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankImportTemplatesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMatchRulesCreate(request) -> *nordlet.PostV1BankMatchRulesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMatchRulesCreateRequest{
        Name: "name",
        Pattern: "pattern",
    }
client.Bank.PostV1BankMatchRulesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**provider:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**pattern:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**payoutIDPrefix:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateWindowDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMatchRulesUpdate(request) -> *nordlet.PostV1BankMatchRulesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMatchRulesUpdateRequest{
        ID: "id",
    }
client.Bank.PostV1BankMatchRulesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**provider:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**pattern:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**payoutIDPrefix:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateWindowDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMatchRulesDelete(request) -> *nordlet.PostV1BankMatchRulesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMatchRulesDeleteRequest{
        ID: "id",
    }
client.Bank.PostV1BankMatchRulesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMatchRulesList(request) -> *nordlet.PostV1BankMatchRulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMatchRulesListRequest{}
client.Bank.PostV1BankMatchRulesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMandatesCreate(request) -> *nordlet.PostV1BankMandatesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMandatesCreateRequest{
        PartnerID: "partnerId",
        Iban: "iban",
        SignatureDate: "signatureDate",
    }
client.Bank.PostV1BankMandatesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**scheme:** `*nordlet.PostV1BankMandatesCreateRequestScheme` 
    
</dd>
</dl>

<dl>
<dd>

**sequenceType:** `*nordlet.PostV1BankMandatesCreateRequestSequenceType` 
    
</dd>
</dl>

<dl>
<dd>

**signatureDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**debtorName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMandatesUpdate(request) -> *nordlet.PostV1BankMandatesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMandatesUpdateRequest{
        ID: "id",
    }
client.Bank.PostV1BankMandatesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bic:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**debtorName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMandatesCancel(request) -> *nordlet.PostV1BankMandatesCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMandatesCancelRequest{
        ID: "id",
    }
client.Bank.PostV1BankMandatesCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMandatesGet(request) -> *nordlet.PostV1BankMandatesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMandatesGetRequest{
        ID: "id",
    }
client.Bank.PostV1BankMandatesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankMandatesList(request) -> *nordlet.PostV1BankMandatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankMandatesListRequest{}
client.Bank.PostV1BankMandatesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankMandatesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankMandatesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankDirectDebitsExport(request) -> *nordlet.PostV1BankDirectDebitsExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankDirectDebitsExportRequest{
        BankAccountID: "bankAccountId",
        SaleInvoiceIDs: []string{
            "saleInvoiceIds",
        },
    }
client.Bank.PostV1BankDirectDebitsExport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceIDs:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**collectionDate:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankTransactionsSuggestMatches(request) -> *nordlet.PostV1BankTransactionsSuggestMatchesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankTransactionsSuggestMatchesRequest{
        TransactionID: "transactionId",
    }
client.Bank.PostV1BankTransactionsSuggestMatches(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**transactionID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**limit:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsImport(request) -> *nordlet.PostV1BankSettlementsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsImportRequest{
        BankAccountID: "bankAccountId",
        Content: "content",
    }
client.Bank.PostV1BankSettlementsImport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**provider:** `*nordlet.PostV1BankSettlementsImportRequestProvider` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsList(request) -> *nordlet.PostV1BankSettlementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsListRequest{}
client.Bank.PostV1BankSettlementsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankSettlementsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankSettlementsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsGet(request) -> *nordlet.PostV1BankSettlementsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsGetRequest{
        ID: "id",
    }
client.Bank.PostV1BankSettlementsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsMatch(request) -> *nordlet.PostV1BankSettlementsMatchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsMatchRequest{
        LineID: "lineId",
    }
client.Bank.PostV1BankSettlementsMatch(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**lineID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.SetWhatTheMarketplaceKeepsFromOneSettlementLineAsARateOrAsAnAmount(request) -> *nordlet.PostV1BankSettlementsCommissionResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

A line with its own rate or amount is split with that value when the batch is posted. A line without one falls back to the commissionPercent given to the posting call, and without that the amount goes to the suspense account. Send both fields as null to clear the line back to the fallback.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsCommissionRequest{
        LineID: "lineId",
    }
client.Bank.SetWhatTheMarketplaceKeepsFromOneSettlementLineAsARateOrAsAnAmount(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**lineID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**commissionPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**commissionAmount:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsLink(request) -> *nordlet.PostV1BankSettlementsLinkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attach the incoming bank-statement line that carries this payout to the settlement batch.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsLinkRequest{
        ID: "id",
        BankTransactionID: "bankTransactionId",
    }
client.Bank.PostV1BankSettlementsLink(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bankTransactionID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsUnlink(request) -> *nordlet.PostV1BankSettlementsUnlinkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Detach the bank-statement line from the settlement batch and return the line to unmatched.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsUnlinkRequest{
        ID: "id",
    }
client.Bank.PostV1BankSettlementsUnlink(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankSettlementsPost(request) -> *nordlet.PostV1BankSettlementsPostResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankSettlementsPostRequest{
        ID: "id",
    }
client.Bank.PostV1BankSettlementsPost(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**commissionPercent:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.ListThePsd2BanksAspsPsAvailableToConnect(request) -> *nordlet.PostV1BankFeedsBanksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsBanksListRequest{}
client.Bank.ListThePsd2BanksAspsPsAvailableToConnect(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**country:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.BeginBankAuthorizationRedirectTheUserToTheReturnedURL(request) -> *nordlet.PostV1BankFeedsConnectionsStartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsConnectionsStartRequest{
        AspspName: "aspspName",
        AspspCountry: "aspspCountry",
    }
client.Bank.BeginBankAuthorizationRedirectTheUserToTheReturnedURL(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**aspspName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**aspspCountry:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**psuType:** `*nordlet.PostV1BankFeedsConnectionsStartRequestPsuType` 
    
</dd>
</dl>

<dl>
<dd>

**redirectURL:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**validForDays:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**language:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.ExchangeTheRedirectCodeForASessionAndStoreTheBankAccountsItExposes(request) -> *nordlet.PostV1BankFeedsConnectionsCompleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsConnectionsCompleteRequest{
        Reference: "reference",
        Code: "code",
    }
client.Bank.ExchangeTheRedirectCodeForASessionAndStoreTheBankAccountsItExposes(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reference:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankFeedsConnectionsGet(request) -> *nordlet.PostV1BankFeedsConnectionsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsConnectionsGetRequest{
        ID: "id",
    }
client.Bank.PostV1BankFeedsConnectionsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PostV1BankFeedsConnectionsList(request) -> *nordlet.PostV1BankFeedsConnectionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsConnectionsListRequest{}
client.Bank.PostV1BankFeedsConnectionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1BankFeedsConnectionsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1BankFeedsConnectionsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.RevokeTheConsentAtTheBankAndDropTheStoredConnection(request) -> *nordlet.PostV1BankFeedsConnectionsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsConnectionsDeleteRequest{
        ID: "id",
    }
client.Bank.RevokeTheConsentAtTheBankAndDropTheStoredConnection(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PointABankFeedAccountAtALedgerBankAccountSoItsTransactionsCanBeSynced(request) -> *nordlet.PostV1BankFeedsAccountsLinkResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsAccountsLinkRequest{
        ID: "id",
    }
client.Bank.PointABankFeedAccountAtALedgerBankAccountSoItsTransactionsCanBeSynced(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**createBankAccount:** `*nordlet.PostV1BankFeedsAccountsLinkRequestCreateBankAccount` 
    
</dd>
</dl>

<dl>
<dd>

**syncFrom:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.ChooseTheImportTemplateAppliedOnSyncAndHowOftenTheAccountIsSyncedAutomatically(request) -> *nordlet.PostV1BankFeedsAccountsConfigureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsAccountsConfigureRequest{
        ID: "id",
    }
client.Bank.ChooseTheImportTemplateAppliedOnSyncAndHowOftenTheAccountIsSyncedAutomatically(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**importTemplateID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**syncSchedule:** `*nordlet.PostV1BankFeedsAccountsConfigureRequestSyncSchedule` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.PullNewTransactionsFromTheBankIntoTheLedgerEmitsBankFeedSynced(request) -> *nordlet.PostV1BankFeedsSyncResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BankFeedsSyncRequest{
        ConnectionID: "connectionId",
    }
client.Bank.PullNewTransactionsFromTheBankIntoTheLedgerEmitsBankFeedSynced(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**connectionID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**feedAccountID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Files
<details><summary><code>client.Files.PostV1FilesUpload(request) -> *nordlet.PostV1FilesUploadResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FilesUploadRequest{
        Entity: "entity",
        FileName: "fileName",
        MimeType: "mimeType",
        Content: "content",
    }
client.Files.PostV1FilesUpload(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**entity:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**entityID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**fileName:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**mimeType:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `string` — Base64-encoded file content
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Files.PostV1FilesGet(request) -> *nordlet.PostV1FilesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FilesGetRequest{
        ID: "id",
    }
client.Files.PostV1FilesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Files.PostV1FilesList(request) -> *nordlet.PostV1FilesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FilesListRequest{}
client.Files.PostV1FilesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1FilesListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1FilesListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Files.PostV1FilesDelete(request) -> *nordlet.PostV1FilesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1FilesDeleteRequest{
        ID: "id",
    }
client.Files.PostV1FilesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Reports
<details><summary><code>client.Reports.PostV1ReportsTrialBalance(request) -> *nordlet.PostV1ReportsTrialBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsTrialBalanceRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsTrialBalance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsSizeCategory(request) -> *nordlet.PostV1ReportsSizeCategoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsSizeCategoryRequest{
        Year: int64(1000000),
    }
client.Reports.PostV1ReportsSizeCategory(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsFinancialStatements(request) -> *nordlet.PostV1ReportsFinancialStatementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsFinancialStatementsRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsFinancialStatements(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `*nordlet.PostV1ReportsFinancialStatementsRequestCategory` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsGeneralJournal(request) -> *nordlet.PostV1ReportsGeneralJournalResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsGeneralJournalRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsGeneralJournal(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsGlDetail(request) -> *nordlet.PostV1ReportsGlDetailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsGlDetailRequest{
        AccountCode: "accountCode",
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsGlDetail(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**accountCode:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsPartnerBalances(request) -> *nordlet.PostV1ReportsPartnerBalancesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsPartnerBalancesRequest{}
client.Reports.PostV1ReportsPartnerBalances(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsDebtAging(request) -> *nordlet.PostV1ReportsDebtAgingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsDebtAgingRequest{}
client.Reports.PostV1ReportsDebtAging(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**side:** `*nordlet.PostV1ReportsDebtAgingRequestSide` 
    
</dd>
</dl>

<dl>
<dd>

**asOf:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsMonthlySummary(request) -> *nordlet.PostV1ReportsMonthlySummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsMonthlySummaryRequest{}
client.Reports.PostV1ReportsMonthlySummary(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**months:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsStockBalance(request) -> *nordlet.PostV1ReportsStockBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsStockBalanceRequest{
        AsOf: "asOf",
    }
client.Reports.PostV1ReportsStockBalance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsStockMovement(request) -> *nordlet.PostV1ReportsStockMovementResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsStockMovementRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsStockMovement(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**itemID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsVatSummary(request) -> *nordlet.PostV1ReportsVatSummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsVatSummaryRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsVatSummary(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `*nordlet.PostV1ReportsVatSummaryRequestSide` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsCashFlow(request) -> *nordlet.PostV1ReportsCashFlowResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsCashFlowRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsCashFlow(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsStockAging(request) -> *nordlet.PostV1ReportsStockAgingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsStockAgingRequest{
        AsOf: "asOf",
    }
client.Reports.PostV1ReportsStockAging(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsStockShortage(request) -> *nordlet.PostV1ReportsStockShortageResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsStockShortageRequest{}
client.Reports.PostV1ReportsStockShortage(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsSie(request) -> *nordlet.PostV1ReportsSieResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the ledger of one financial year as an SIE file (the Swedish standard accounting interchange format, specification 4B). The file carries the chart of accounts, the opening and closing balance of every balance sheet account and the turnover of every result account for the year and the year before it, and, when asked for, every posted voucher of the year with its lines. Cost centres travel as dimension 1 and projects as dimension 6. Services that build a Swedish annual report read this file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsSieRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsSie(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**includeTransactions:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsDatev(request) -> *nordlet.PostV1ReportsDatevResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the posted ledger of a period as a DATEV Buchungsstapel file (DATEV format, category 21, version 700). Every transaction becomes one or more bookings of an amount between an account and a contra account; a transaction with more than two lines is split into pairs whose totals match it. The file is semicolon separated and written in the Windows-1252 character set DATEV expects.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsDatevRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsDatev(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**consultantNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**clientNumber:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsFec(request) -> *nordlet.PostV1ReportsFecResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the posted ledger of a period as a French FEC file (fichier des écritures comptables, order of 29 July 2013). One line per journal entry line, with the eighteen fields the order names, in their order, after a header line. Tab separated, UTF-8, comma as the decimal separator.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsFecRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsFec(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsEuPurchases(request) -> *nordlet.PostV1ReportsEuPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsEuPurchasesRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsEuPurchases(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsVatDetail(request) -> *nordlet.PostV1ReportsVatDetailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsVatDetailRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsVatDetail(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `*nordlet.PostV1ReportsVatDetailRequestSide` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsPosSales(request) -> *nordlet.PostV1ReportsPosSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsPosSalesRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsPosSales(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsOnlineSales(request) -> *nordlet.PostV1ReportsOnlineSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsOnlineSalesRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsOnlineSales(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsOss(request) -> *nordlet.PostV1ReportsOssResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsOssRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsOss(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsAdvanceReconciliation(request) -> *nordlet.PostV1ReportsAdvanceReconciliationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsAdvanceReconciliationRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsAdvanceReconciliation(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsWriteOffActs(request) -> *nordlet.PostV1ReportsWriteOffActsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsWriteOffActsRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsWriteOffActs(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsCostCenters(request) -> *nordlet.PostV1ReportsCostCentersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsCostCentersRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsCostCenters(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsCostCenterActivity(request) -> *nordlet.PostV1ReportsCostCenterActivityResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsCostCenterActivityRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
        CostCenterID: "costCenterId",
    }
client.Reports.PostV1ReportsCostCenterActivity(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**costCenterID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsCostCenterItems(request) -> *nordlet.PostV1ReportsCostCenterItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsCostCenterItemsRequest{
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Reports.PostV1ReportsCostCenterItems(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**costCenterID:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsJobsCreate(request) -> *nordlet.PostV1ReportsJobsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsJobsCreateRequest{
        ReportType: "reportType",
    }
client.Reports.PostV1ReportsJobsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reportType:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**params:** `map[string]any` 
    
</dd>
</dl>

<dl>
<dd>

**formats:** `[]*nordlet.PostV1ReportsJobsCreateRequestFormatsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsJobsGet(request) -> *nordlet.PostV1ReportsJobsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsJobsGetRequest{
        ID: "id",
    }
client.Reports.PostV1ReportsJobsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PostV1ReportsJobsList(request) -> *nordlet.PostV1ReportsJobsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ReportsJobsListRequest{}
client.Reports.PostV1ReportsJobsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `[]*nordlet.PostV1ReportsJobsListRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PostV1ReportsJobsListRequestFilterItem` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `[]string` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Consolidation
<details><summary><code>client.Consolidation.PostV1ConsolidationGroupsCreate(request) -> *nordlet.PostV1ConsolidationGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationGroupsCreateRequest{
        Name: "name",
    }
client.Consolidation.PostV1ConsolidationGroupsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**presentationCurrency:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationGroupsList(request) -> *nordlet.PostV1ConsolidationGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationGroupsListRequest{}
client.Consolidation.PostV1ConsolidationGroupsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationGroupsGet(request) -> *nordlet.PostV1ConsolidationGroupsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationGroupsGetRequest{
        GroupID: "groupId",
    }
client.Consolidation.PostV1ConsolidationGroupsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationGroupsUpdate(request) -> *nordlet.PostV1ConsolidationGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationGroupsUpdateRequest{
        GroupID: "groupId",
    }
client.Consolidation.PostV1ConsolidationGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**presentationCurrency:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationGroupsDelete(request) -> *nordlet.PostV1ConsolidationGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationGroupsDeleteRequest{
        GroupID: "groupId",
    }
client.Consolidation.PostV1ConsolidationGroupsDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationMembersAdd(request) -> *nordlet.PostV1ConsolidationMembersAddResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationMembersAddRequest{
        GroupID: "groupId",
        MemberCompanyID: "memberCompanyId",
    }
client.Consolidation.PostV1ConsolidationMembersAdd(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**memberCompanyID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**ownershipPercent:** `*float64` 
    
</dd>
</dl>

<dl>
<dd>

**method:** `*nordlet.PostV1ConsolidationMembersAddRequestMethod` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationMembersRemove(request) -> *nordlet.PostV1ConsolidationMembersRemoveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationMembersRemoveRequest{
        GroupID: "groupId",
        MemberCompanyID: "memberCompanyId",
    }
client.Consolidation.PostV1ConsolidationMembersRemove(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**memberCompanyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationIntercompanyCandidates(request) -> *nordlet.PostV1ConsolidationIntercompanyCandidatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Partners in member companies that look like other members of the same group (matched on company code or VAT code), with any existing intercompany link. Confirming a candidate via intercompany/links/set enables invoice mirroring.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationIntercompanyCandidatesRequest{
        GroupID: "groupId",
    }
client.Consolidation.PostV1ConsolidationIntercompanyCandidates(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationIntercompanyLinksSet(request) -> *nordlet.PostV1ConsolidationIntercompanyLinksSetResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Confirm that a partner record in one member company represents another member company of the group. Once links exist in both directions, issuing an intercompany sale invoice automatically creates the matching draft purchase invoice in the counterparty.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationIntercompanyLinksSetRequest{
        GroupID: "groupId",
        PartnerID: "partnerId",
        CounterpartyCompanyID: "counterpartyCompanyId",
    }
client.Consolidation.PostV1ConsolidationIntercompanyLinksSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**counterpartyCompanyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationIntercompanyLinksList(request) -> *nordlet.PostV1ConsolidationIntercompanyLinksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationIntercompanyLinksListRequest{
        GroupID: "groupId",
    }
client.Consolidation.PostV1ConsolidationIntercompanyLinksList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationIntercompanyLinksRemove(request) -> *nordlet.PostV1ConsolidationIntercompanyLinksRemoveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationIntercompanyLinksRemoveRequest{
        GroupID: "groupId",
        ID: "id",
    }
client.Consolidation.PostV1ConsolidationIntercompanyLinksRemove(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationIntercompanyReport(request) -> *nordlet.PostV1ConsolidationIntercompanyReportResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Intercompany reconciliation for a period: every issued intercompany sale invoice with its mirrored or manually recorded counterpart, unmatched documents on both sides, and per-currency totals with differences. Confirmed pairs are the basis for consolidation eliminations.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationIntercompanyReportRequest{
        GroupID: "groupId",
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Consolidation.PostV1ConsolidationIntercompanyReport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.PostV1ConsolidationReport(request) -> *nordlet.PostV1ConsolidationReportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1ConsolidationReportRequest{
        GroupID: "groupId",
        FromDate: "fromDate",
        ToDate: "toDate",
    }
client.Consolidation.PostV1ConsolidationReport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `*nordlet.PostV1ConsolidationReportRequestCategory` 
    
</dd>
</dl>

<dl>
<dd>

**eliminations:** `[]*nordlet.PostV1ConsolidationReportRequestEliminationsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Public
<details><summary><code>client.Public.PostV1PublicIntegrationRequests(request) -> *nordlet.PostV1PublicIntegrationRequestsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1PublicIntegrationRequestsRequest{
        Integration: "integration",
        Name: "name",
        Email: "email",
    }
client.Public.PostV1PublicIntegrationRequests(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**integration:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**company:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**details:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Public.GetV1PublicPayToken(Token) -> error</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetV1PublicPayTokenRequest{
        Token: "token",
    }
client.Public.GetV1PublicPayToken(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Billing
<details><summary><code>client.Billing.PostV1BillingAccountGet(request) -> *nordlet.PostV1BillingAccountGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingAccountGetRequest{}
client.Billing.PostV1BillingAccountGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PostV1BillingAccountSetPlan(request) -> *nordlet.PostV1BillingAccountSetPlanResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingAccountSetPlanRequest{
        Plan: nordlet.PostV1BillingAccountSetPlanRequestPlanStarter,
    }
client.Billing.PostV1BillingAccountSetPlan(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**plan:** `*nordlet.PostV1BillingAccountSetPlanRequestPlan` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PostV1BillingTopupCreate(request) -> *nordlet.PostV1BillingTopupCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingTopupCreateRequest{
        AmountCents: int64(1000000),
    }
client.Billing.PostV1BillingTopupCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**amountCents:** `int64` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1BillingTopupCreateRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PostV1BillingPortalCreate(request) -> *nordlet.PostV1BillingPortalCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingPortalCreateRequest{}
client.Billing.PostV1BillingPortalCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.PostV1BillingPortalCreateRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PostV1BillingTransactionsList(request) -> *nordlet.PostV1BillingTransactionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingTransactionsListRequest{}
client.Billing.PostV1BillingTransactionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**limit:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PostV1BillingUsageList(request) -> *nordlet.PostV1BillingUsageListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1BillingUsageListRequest{
        From: "from",
        To: "to",
    }
client.Billing.PostV1BillingUsageList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Account
<details><summary><code>client.Account.PostV1AccountLoginLinkRequest(request) -> *nordlet.PostV1AccountLoginLinkRequestResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountLoginLinkRequestRequest{
        Email: "email",
    }
client.Account.PostV1AccountLoginLinkRequest(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**email:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1AccountLoginLinkRequestRequestLocale` 
    
</dd>
</dl>

<dl>
<dd>

**acceptTerms:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**referralCode:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountLoginLinkConsume(request) -> *nordlet.PostV1AccountLoginLinkConsumeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountLoginLinkConsumeRequest{
        Token: "token",
    }
client.Account.PostV1AccountLoginLinkConsume(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountLogout(request) -> *nordlet.PostV1AccountLogoutResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountLogoutRequest{}
client.Account.PostV1AccountLogout(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountMe(request) -> *nordlet.PostV1AccountMeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountMeRequest{}
client.Account.PostV1AccountMe(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountMembersList(request) -> *nordlet.PostV1AccountMembersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountMembersListRequest{}
client.Account.PostV1AccountMembersList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountMembersSetRole(request) -> *nordlet.PostV1AccountMembersSetRoleResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountMembersSetRoleRequest{
        UserID: "userId",
        Role: nordlet.PostV1AccountMembersSetRoleRequestRoleAdmin,
    }
client.Account.PostV1AccountMembersSetRole(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**userID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*nordlet.PostV1AccountMembersSetRoleRequestRole` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountMembersTransferOwnership(request) -> *nordlet.PostV1AccountMembersTransferOwnershipResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountMembersTransferOwnershipRequest{
        UserID: "userId",
    }
client.Account.PostV1AccountMembersTransferOwnership(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**userID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**movePayer:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountMembersRemove(request) -> *nordlet.PostV1AccountMembersRemoveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountMembersRemoveRequest{
        UserID: "userId",
    }
client.Account.PostV1AccountMembersRemove(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**userID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountInvitesCreate(request) -> *nordlet.PostV1AccountInvitesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountInvitesCreateRequest{
        Email: "email",
        Role: nordlet.PostV1AccountInvitesCreateRequestRoleAdmin,
    }
client.Account.PostV1AccountInvitesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**email:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `*nordlet.PostV1AccountInvitesCreateRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1AccountInvitesCreateRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountInvitesList(request) -> *nordlet.PostV1AccountInvitesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountInvitesListRequest{}
client.Account.PostV1AccountInvitesList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountInvitesRevoke(request) -> *nordlet.PostV1AccountInvitesRevokeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountInvitesRevokeRequest{
        ID: "id",
    }
client.Account.PostV1AccountInvitesRevoke(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountInvitesGet(request) -> *nordlet.PostV1AccountInvitesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountInvitesGetRequest{
        Token: "token",
    }
client.Account.PostV1AccountInvitesGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountInvitesAccept(request) -> *nordlet.PostV1AccountInvitesAcceptResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountInvitesAcceptRequest{
        Token: "token",
    }
client.Account.PostV1AccountInvitesAccept(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1AccountInvitesAcceptRequestLocale` 
    
</dd>
</dl>

<dl>
<dd>

**acceptTerms:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountLocaleSet(request) -> *nordlet.PostV1AccountLocaleSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountLocaleSetRequest{
        Locale: nordlet.PostV1AccountLocaleSetRequestLocaleEn,
    }
client.Account.PostV1AccountLocaleSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.PostV1AccountLocaleSetRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesCreate(request) -> *nordlet.PostV1AccountCompaniesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesCreateRequest{
        Name: "name",
    }
client.Account.PostV1AccountCompaniesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**smeExemptionNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**vatPeriod:** `*nordlet.PostV1AccountCompaniesCreateRequestVatPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**fiscalYearEndMonth:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**timeZone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**filingOptions:** `map[string]string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1AccountCompaniesCreateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**peppolID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sepaCreditorID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**legalForm:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**registryName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**incorporatedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `*nordlet.PostV1AccountCompaniesCreateRequestAccountsKeptBy` 
    
</dd>
</dl>

<dl>
<dd>

**bookkeeperName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorRegistrationNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `*nordlet.PostV1AccountCompaniesCreateRequestCountryCode` — Jurisdiction the company is registered in (immutable after creation)
    
</dd>
</dl>

<dl>
<dd>

**isSandbox:** `*bool` — Sandbox companies hold test data and are purged immediately on delete (immutable after creation)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesSelect(request) -> *nordlet.PostV1AccountCompaniesSelectResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesSelectRequest{
        CompanyID: "companyId",
    }
client.Account.PostV1AccountCompaniesSelect(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesProfile(request) -> *nordlet.PostV1AccountCompaniesProfileResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesProfileRequest{}
client.Account.PostV1AccountCompaniesProfile(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesUpdate(request) -> *nordlet.PostV1AccountCompaniesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesUpdateRequest{}
client.Account.PostV1AccountCompaniesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**smeExemptionNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**vatPeriod:** `*nordlet.PostV1AccountCompaniesUpdateRequestVatPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**fiscalYearEndMonth:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**timeZone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**filingOptions:** `map[string]*string` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `*nordlet.PostV1AccountCompaniesUpdateRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**peppolID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**sepaCreditorID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**legalForm:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**registryName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**incorporatedOn:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `*nordlet.PostV1AccountCompaniesUpdateRequestAccountsKeptBy` 
    
</dd>
</dl>

<dl>
<dd>

**bookkeeperName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorName:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditorRegistrationNumber:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**auditRequired:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**logo:** `*nordlet.PostV1AccountCompaniesUpdateRequestLogo` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesArchive(request) -> *nordlet.PostV1AccountCompaniesArchiveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesArchiveRequest{
        CompanyID: "companyId",
    }
client.Account.PostV1AccountCompaniesArchive(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesDelete(request) -> *nordlet.PostV1AccountCompaniesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesDeleteRequest{
        CompanyID: "companyId",
    }
client.Account.PostV1AccountCompaniesDelete(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountCompaniesActivate(request) -> *nordlet.PostV1AccountCompaniesActivateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountCompaniesActivateRequest{
        CompanyID: "companyId",
    }
client.Account.PostV1AccountCompaniesActivate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyID:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountAPIKeysCreate(request) -> *nordlet.PostV1AccountAPIKeysCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountAPIKeysCreateRequest{
        Name: "name",
    }
client.Account.PostV1AccountAPIKeysCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**scopes:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**expiresInDays:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountAPIKeysList(request) -> *nordlet.PostV1AccountAPIKeysListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountAPIKeysListRequest{}
client.Account.PostV1AccountAPIKeysList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.IssueAReplacementForAnAPIKeyAndSetTheOldOneToStopWorkingAfterAShortOverlap(request) -> *nordlet.PostV1AccountAPIKeysRotateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountAPIKeysRotateRequest{
        ID: "id",
    }
client.Account.IssueAReplacementForAnAPIKeyAndSetTheOldOneToStopWorkingAfterAShortOverlap(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**overlapHours:** `*int64` 
    
</dd>
</dl>

<dl>
<dd>

**expiresInDays:** `*int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountAPIKeysRevoke(request) -> *nordlet.PostV1AccountAPIKeysRevokeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountAPIKeysRevokeRequest{
        ID: "id",
    }
client.Account.PostV1AccountAPIKeysRevoke(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountConsentAccept(request) -> *nordlet.PostV1AccountConsentAcceptResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountConsentAcceptRequest{
        AcceptTerms: true,
        AcceptDpa: true,
    }
client.Account.PostV1AccountConsentAccept(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**acceptTerms:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountProfileUpdate(request) -> *nordlet.PostV1AccountProfileUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountProfileUpdateRequest{}
client.Account.PostV1AccountProfileUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountEmailChangeRequest(request) -> *nordlet.PostV1AccountEmailChangeRequestResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountEmailChangeRequestRequest{
        NewEmail: "newEmail",
    }
client.Account.PostV1AccountEmailChangeRequest(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**newEmail:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PostV1AccountEmailChangeRequestRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountSessionsList(request) -> *nordlet.PostV1AccountSessionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountSessionsListRequest{}
client.Account.PostV1AccountSessionsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountSessionsRevoke(request) -> *nordlet.PostV1AccountSessionsRevokeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountSessionsRevokeRequest{
        ID: "id",
    }
client.Account.PostV1AccountSessionsRevoke(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountSessionsRevokeOthers(request) -> *nordlet.PostV1AccountSessionsRevokeOthersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountSessionsRevokeOthersRequest{}
client.Account.PostV1AccountSessionsRevokeOthers(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.DownloadEverythingNordletStoresAboutTheSignedInUser(request) -> *nordlet.PostV1AccountExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountExportRequest{}
client.Account.DownloadEverythingNordletStoresAboutTheSignedInUser(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.DeleteTheSignedInUserAccount(request) -> *nordlet.PostV1AccountDeleteResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes the user: sessions, sign-in links, memberships and pending invitations are deleted at once; the email and name are replaced by an anonymous placeholder immediately and the remaining row is removed after 30 days. Refused while the user still owns or pays for a company that is not deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountDeleteRequest{
        ConfirmEmail: "confirmEmail",
    }
client.Account.DeleteTheSignedInUserAccount(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**confirmEmail:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountReferralGet(request) -> *nordlet.PostV1AccountReferralGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountReferralGetRequest{}
client.Account.PostV1AccountReferralGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountReferralConvert(request) -> *nordlet.PostV1AccountReferralConvertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountReferralConvertRequest{
        Points: int64(1000000),
    }
client.Account.PostV1AccountReferralConvert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**points:** `int64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountTableSettingsGet(request) -> *nordlet.PostV1AccountTableSettingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountTableSettingsGetRequest{
        TableKey: "tableKey",
    }
client.Account.PostV1AccountTableSettingsGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tableKey:** `string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountTableSettingsSet(request) -> *nordlet.PostV1AccountTableSettingsSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountTableSettingsSetRequest{
        TableKey: "tableKey",
    }
client.Account.PostV1AccountTableSettingsSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tableKey:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**columns:** `[]string` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `*float64` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.PostV1AccountTableSettingsList(request) -> *nordlet.PostV1AccountTableSettingsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostV1AccountTableSettingsListRequest{}
client.Account.PostV1AccountTableSettingsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

