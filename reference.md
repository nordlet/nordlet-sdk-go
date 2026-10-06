# Reference
## reference
<details><summary><code>client.Reference.ExchangeRatesSync(request) -> *nordlet.ExchangeRatesSyncReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExchangeRatesSyncReferenceRequest{}
client.Reference.ExchangeRatesSync(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.ExchangeRatesList(request) -> *nordlet.ExchangeRatesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExchangeRatesListReferenceRequest{}
client.Reference.ExchangeRatesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ExchangeRatesListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ExchangeRatesListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.ExchangeRatesSet(request) -> *nordlet.ExchangeRatesSetReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExchangeRatesSetReferenceRequest{
        Currency: "currency",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Rate: "121.00000000",
    }
client.Reference.ExchangeRatesSet(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Reference.ExchangeRatesOverridesList(request) -> *nordlet.ExchangeRatesOverridesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExchangeRatesOverridesListReferenceRequest{}
client.Reference.ExchangeRatesOverridesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ExchangeRatesOverridesListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ExchangeRatesOverridesListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.ExchangeRatesOverridesDelete(request) -> *nordlet.ExchangeRatesOverridesDeleteReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExchangeRatesOverridesDeleteReferenceRequest{
        Currency: "currency",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reference.ExchangeRatesOverridesDelete(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.CountriesList(request) -> *nordlet.CountriesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CountriesListReferenceRequest{}
client.Reference.CountriesList(
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

<details><summary><code>client.Reference.LtCountiesList(request) -> *nordlet.LtCountiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtCountiesListReferenceRequest{}
client.Reference.LtCountiesList(
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

<details><summary><code>client.Reference.LtMunicipalitiesList(request) -> *nordlet.LtMunicipalitiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtMunicipalitiesListReferenceRequest{}
client.Reference.LtMunicipalitiesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reference.LtCitiesList(request) -> *nordlet.LtCitiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtCitiesListReferenceRequest{}
client.Reference.LtCitiesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reference.BanksList(request) -> *nordlet.BanksListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BanksListReferenceRequest{}
client.Reference.BanksList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.BanksListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.BanksListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.BanksUpsert(request) -> *nordlet.BanksUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BanksUpsertReferenceRequest{
        CountryCode: "countryCode",
        Name: "name",
        Bic: "bic",
    }
client.Reference.BanksUpsert(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reference.LtRegionsList(request) -> *nordlet.LtRegionsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtRegionsListReferenceRequest{}
client.Reference.LtRegionsList(
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

<details><summary><code>client.Reference.CurrenciesList(request) -> *nordlet.CurrenciesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CurrenciesListReferenceRequest{}
client.Reference.CurrenciesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.CurrenciesListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.CurrenciesListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.VatClassifiersList(request) -> *nordlet.VatClassifiersListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatClassifiersListReferenceRequest{}
client.Reference.VatClassifiersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.VatClassifiersListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.VatClassifiersListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.VatClassifiersUpsert(request) -> *nordlet.VatClassifiersUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatClassifiersUpsertReferenceRequest{
        Rows: []*nordlet.VatClassifiersUpsertReferenceRequestRowsItem{
            &nordlet.VatClassifiersUpsertReferenceRequestRowsItem{
                Code: "code",
                Name: "name",
            },
        },
    }
client.Reference.VatClassifiersUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `[]*nordlet.VatClassifiersUpsertReferenceRequestRowsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.EuVatRatesList(request) -> *nordlet.EuVatRatesListReferenceResponse</code></summary>
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
request := &nordlet.EuVatRatesListReferenceRequest{}
client.Reference.EuVatRatesList(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.EuVatRatesSetOverrides(request) -> *nordlet.EuVatRatesSetOverridesReferenceResponse</code></summary>
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
request := &nordlet.EuVatRatesSetOverridesReferenceRequest{
        CountryCode: "countryCode",
        Rates: []*nordlet.EuVatRatesSetOverridesReferenceRequestRatesItem{
            &nordlet.EuVatRatesSetOverridesReferenceRequestRatesItem{
                Category: nordlet.EuVatRatesSetOverridesReferenceRequestRatesItemCategoryStandard,
                RatePercent: "121.00",
            },
        },
    }
client.Reference.EuVatRatesSetOverrides(
        context.TODO(),
        request,
    )
}
```
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

**rates:** `[]*nordlet.EuVatRatesSetOverridesReferenceRequestRatesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.VatResolve(request) -> *nordlet.VatResolveReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatResolveReferenceRequest{}
client.Reference.VatResolve(
        context.TODO(),
        request,
    )
}
```
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

**supplyType:** `*nordlet.VatResolveReferenceRequestSupplyType` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*time.Time` 
    
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

<details><summary><code>client.Reference.CnCodesList(request) -> *nordlet.CnCodesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CnCodesListReferenceRequest{}
client.Reference.CnCodesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.CnCodesListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.CnCodesListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.CnCodesUpsert(request) -> *nordlet.CnCodesUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CnCodesUpsertReferenceRequest{
        Rows: []*nordlet.CnCodesUpsertReferenceRequestRowsItem{
            &nordlet.CnCodesUpsertReferenceRequestRowsItem{
                Code: "code",
                Name: "name",
            },
        },
    }
client.Reference.CnCodesUpsert(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `[]*nordlet.CnCodesUpsertReferenceRequestRowsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reference.ComplianceVersionsList(request) -> *nordlet.ComplianceVersionsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ComplianceVersionsListReferenceRequest{}
client.Reference.ComplianceVersionsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reference.IntrastatThresholdsList(request) -> *nordlet.IntrastatThresholdsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IntrastatThresholdsListReferenceRequest{}
client.Reference.IntrastatThresholdsList(
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

<details><summary><code>client.Reference.UnitsList(request) -> *nordlet.UnitsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsListReferenceRequest{}
client.Reference.UnitsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.UnitsListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.UnitsListReferenceRequestFilterItem` 
    
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

<details><summary><code>client.Reference.SeriesCreate(request) -> *nordlet.SeriesCreateReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SeriesCreateReferenceRequest{
        DocumentType: "documentType",
        Year: int64(1000000),
    }
client.Reference.SeriesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reference.SeriesList(request) -> *nordlet.SeriesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SeriesListReferenceRequest{}
client.Reference.SeriesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.SeriesListReferenceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.SeriesListReferenceRequestFilterItem` 
    
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

## partners
<details><summary><code>client.Partners.AddressesCreate(request) -> *nordlet.AddressesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AddressesCreatePartnersRequest{
        PartnerID: "partnerId",
    }
client.Partners.AddressesCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.AddressesCreatePartnersRequestType` 
    
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

<details><summary><code>client.Partners.AddressesUpdate(request) -> *nordlet.AddressesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AddressesUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.AddressesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.AddressesUpdatePartnersRequestType` 
    
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

<details><summary><code>client.Partners.AddressesDelete(request) -> *nordlet.AddressesDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AddressesDeletePartnersRequest{
        ID: "id",
    }
client.Partners.AddressesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.AddressesList(request) -> *nordlet.AddressesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AddressesListPartnersRequest{}
client.Partners.AddressesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AddressesListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AddressesListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.ContactsCreate(request) -> *nordlet.ContactsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContactsCreatePartnersRequest{
        Name: "name",
        PartnerID: "partnerId",
    }
client.Partners.ContactsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.ContactsUpdate(request) -> *nordlet.ContactsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContactsUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.ContactsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.ContactsDelete(request) -> *nordlet.ContactsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContactsDeletePartnersRequest{
        ID: "id",
    }
client.Partners.ContactsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.ContactsList(request) -> *nordlet.ContactsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContactsListPartnersRequest{}
client.Partners.ContactsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ContactsListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ContactsListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.BankAccountsCreate(request) -> *nordlet.BankAccountsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BankAccountsCreatePartnersRequest{
        Iban: "iban",
        PartnerID: "partnerId",
    }
client.Partners.BankAccountsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.BankAccountsUpdate(request) -> *nordlet.BankAccountsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BankAccountsUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.BankAccountsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.BankAccountsDelete(request) -> *nordlet.BankAccountsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BankAccountsDeletePartnersRequest{
        ID: "id",
    }
client.Partners.BankAccountsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.BankAccountsList(request) -> *nordlet.BankAccountsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BankAccountsListPartnersRequest{}
client.Partners.BankAccountsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.BankAccountsListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.BankAccountsListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.FilesList(request) -> *nordlet.FilesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FilesListPartnersRequest{
        PartnerID: "partnerId",
    }
client.Partners.FilesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.DebtRemindersPreview(request) -> *nordlet.DebtRemindersPreviewPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DebtRemindersPreviewPartnersRequest{}
client.Partners.DebtRemindersPreview(
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

<details><summary><code>client.Partners.DebtRemindersList(request) -> *nordlet.DebtRemindersListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DebtRemindersListPartnersRequest{}
client.Partners.DebtRemindersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.DebtRemindersListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.DebtRemindersListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.ValidateVat(request) -> *nordlet.ValidateVatPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ValidateVatPartnersRequest{}
client.Partners.ValidateVat(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.VatReviewsList(request) -> *nordlet.VatReviewsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatReviewsListPartnersRequest{}
client.Partners.VatReviewsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.VatReviewsListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.VatReviewsListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.VatReviewsResolve(request) -> *nordlet.VatReviewsResolvePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatReviewsResolvePartnersRequest{
        ID: "id",
        Resolution: nordlet.VatReviewsResolvePartnersRequestResolutionConfirmedValid,
    }
client.Partners.VatReviewsResolve(
        context.TODO(),
        request,
    )
}
```
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

**resolution:** `*nordlet.VatReviewsResolvePartnersRequestResolution` 
    
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

<details><summary><code>client.Partners.Create(request) -> *nordlet.CreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreatePartnersRequest{
        Name: "name",
    }
client.Partners.Create(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.CreatePartnersRequestType` 
    
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

**birthDate:** `*time.Time` 
    
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

**address:** `*nordlet.CreatePartnersRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.CreatePartnersRequestCorrespondenceAddress` 
    
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

**firstCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*time.Time` 
    
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

**legalCountryClass:** `*nordlet.CreatePartnersRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.FindOrCreate(request) -> *nordlet.FindOrCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FindOrCreatePartnersRequest{
        Name: "name",
    }
client.Partners.FindOrCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.FindOrCreatePartnersRequestType` 
    
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

**birthDate:** `*time.Time` 
    
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

**address:** `*nordlet.FindOrCreatePartnersRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.FindOrCreatePartnersRequestCorrespondenceAddress` 
    
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

**firstCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*time.Time` 
    
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

**legalCountryClass:** `*nordlet.FindOrCreatePartnersRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.Get(request) -> *nordlet.GetPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetPartnersRequest{
        ID: "id",
    }
client.Partners.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.Update(request) -> *nordlet.UpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdatePartnersRequest{
        ID: "id",
    }
client.Partners.Update(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.UpdatePartnersRequestType` 
    
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

**birthDate:** `*time.Time` 
    
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

**address:** `*nordlet.UpdatePartnersRequestAddress` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `*nordlet.UpdatePartnersRequestCorrespondenceAddress` 
    
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

**firstCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `*time.Time` 
    
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

**legalCountryClass:** `*nordlet.UpdatePartnersRequestLegalCountryClass` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Partners.Delete(request) -> *nordlet.DeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeletePartnersRequest{
        ID: "id",
    }
client.Partners.Delete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.Anonymize(request) -> *nordlet.AnonymizePartnersResponse</code></summary>
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
request := &nordlet.AnonymizePartnersRequest{
        ID: "id",
    }
client.Partners.Anonymize(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.List(request) -> *nordlet.ListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListPartnersRequest{}
client.Partners.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.GroupsCreate(request) -> *nordlet.GroupsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsCreatePartnersRequest{
        Code: "code",
        Name: "name",
    }
client.Partners.GroupsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.GroupsUpdate(request) -> *nordlet.GroupsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.GroupsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.GroupsDelete(request) -> *nordlet.GroupsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsDeletePartnersRequest{
        ID: "id",
    }
client.Partners.GroupsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.GroupsList(request) -> *nordlet.GroupsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsListPartnersRequest{}
client.Partners.GroupsList(
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

<details><summary><code>client.Partners.StatusesCreate(request) -> *nordlet.StatusesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatusesCreatePartnersRequest{
        Code: "code",
        Name: "name",
    }
client.Partners.StatusesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.StatusesUpdate(request) -> *nordlet.StatusesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatusesUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.StatusesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.StatusesDelete(request) -> *nordlet.StatusesDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatusesDeletePartnersRequest{
        ID: "id",
    }
client.Partners.StatusesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.StatusesList(request) -> *nordlet.StatusesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatusesListPartnersRequest{}
client.Partners.StatusesList(
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

<details><summary><code>client.Partners.InquiriesCreate(request) -> *nordlet.InquiriesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InquiriesCreatePartnersRequest{
        Subject: "subject",
    }
client.Partners.InquiriesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.InquiriesUpdate(request) -> *nordlet.InquiriesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InquiriesUpdatePartnersRequest{
        ID: "id",
    }
client.Partners.InquiriesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**status:** `*nordlet.InquiriesUpdatePartnersRequestStatus` 
    
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

<details><summary><code>client.Partners.InquiriesGet(request) -> *nordlet.InquiriesGetPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InquiriesGetPartnersRequest{
        ID: "id",
    }
client.Partners.InquiriesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Partners.InquiriesList(request) -> *nordlet.InquiriesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InquiriesListPartnersRequest{}
client.Partners.InquiriesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.InquiriesListPartnersRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.InquiriesListPartnersRequestFilterItem` 
    
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

<details><summary><code>client.Partners.CreditCheck(request) -> *nordlet.CreditCheckPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreditCheckPartnersRequest{
        PartnerID: "partnerId",
    }
client.Partners.CreditCheck(
        context.TODO(),
        request,
    )
}
```
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

## Leads
<details><summary><code>client.Leads.Create(request) -> *nordlet.CreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateLeadsRequest{
        Name: "name",
    }
client.Leads.Create(
        context.TODO(),
        request,
    )
}
```
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

**typeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.CreateLeadsRequestStatus` 
    
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

**documents:** `[]*nordlet.CreateLeadsRequestDocumentsItem` 
    
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

<details><summary><code>client.Leads.Get(request) -> *nordlet.GetLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetLeadsRequest{
        ID: "id",
    }
client.Leads.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.Update(request) -> *nordlet.UpdateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateLeadsRequest{
        ID: "id",
    }
client.Leads.Update(
        context.TODO(),
        request,
    )
}
```
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

**typeID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.UpdateLeadsRequestStatus` 
    
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

**documents:** `[]*nordlet.UpdateLeadsRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Leads.Delete(request) -> *nordlet.DeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteLeadsRequest{
        ID: "id",
    }
client.Leads.Delete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.List(request) -> *nordlet.ListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListLeadsRequest{}
client.Leads.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListLeadsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListLeadsRequestFilterItem` 
    
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

<details><summary><code>client.Leads.NotesCreate(request) -> *nordlet.NotesCreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.NotesCreateLeadsRequest{
        LeadID: "leadId",
        Body: "body",
    }
client.Leads.NotesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.NotesDelete(request) -> *nordlet.NotesDeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.NotesDeleteLeadsRequest{
        ID: "id",
    }
client.Leads.NotesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.NotesList(request) -> *nordlet.NotesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.NotesListLeadsRequest{
        LeadID: "leadId",
    }
client.Leads.NotesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.FilesList(request) -> *nordlet.FilesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FilesListLeadsRequest{
        LeadID: "leadId",
    }
client.Leads.FilesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.SourcesCreate(request) -> *nordlet.SourcesCreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SourcesCreateLeadsRequest{
        Name: "name",
    }
client.Leads.SourcesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.SourcesUpdate(request) -> *nordlet.SourcesUpdateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SourcesUpdateLeadsRequest{
        ID: "id",
    }
client.Leads.SourcesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.SourcesDelete(request) -> *nordlet.SourcesDeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SourcesDeleteLeadsRequest{
        ID: "id",
    }
client.Leads.SourcesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.SourcesList(request) -> *nordlet.SourcesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SourcesListLeadsRequest{}
client.Leads.SourcesList(
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

<details><summary><code>client.Leads.SourcesOptions(request) -> *nordlet.SourcesOptionsLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SourcesOptionsLeadsRequest{}
client.Leads.SourcesOptions(
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

<details><summary><code>client.Leads.TypesCreate(request) -> *nordlet.TypesCreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesCreateLeadsRequest{
        Name: "name",
    }
client.Leads.TypesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.TypesUpdate(request) -> *nordlet.TypesUpdateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesUpdateLeadsRequest{
        ID: "id",
    }
client.Leads.TypesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.TypesDelete(request) -> *nordlet.TypesDeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesDeleteLeadsRequest{
        ID: "id",
    }
client.Leads.TypesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Leads.TypesList(request) -> *nordlet.TypesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesListLeadsRequest{}
client.Leads.TypesList(
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

<details><summary><code>client.Leads.TypesOptions(request) -> *nordlet.TypesOptionsLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesOptionsLeadsRequest{}
client.Leads.TypesOptions(
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

<details><summary><code>client.Leads.Convert(request) -> *nordlet.ConvertLeadsResponse</code></summary>
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
request := &nordlet.ConvertLeadsRequest{
        ID: "id",
    }
client.Leads.Convert(
        context.TODO(),
        request,
    )
}
```
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

**partnerType:** `*nordlet.ConvertLeadsRequestPartnerType` 
    
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

## catalog
<details><summary><code>client.Catalog.ItemsCreate(request) -> *nordlet.ItemsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsCreateCatalogRequest{
        Name: "name",
    }
client.Catalog.ItemsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.ItemsCreateCatalogRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `*nordlet.ItemsCreateCatalogRequestTracking` 
    
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

**translations:** `map[string]*nordlet.ItemsCreateCatalogRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `[]*nordlet.ItemsCreateCatalogRequestComponentsItem` 
    
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

**priceFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `*time.Time` 
    
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

**certificateDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `*time.Time` 
    
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

<details><summary><code>client.Catalog.ItemsGet(request) -> *nordlet.ItemsGetCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsGetCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsUpdate(request) -> *nordlet.ItemsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsUpdateCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ItemsUpdateCatalogRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `*nordlet.ItemsUpdateCatalogRequestTracking` 
    
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

**translations:** `map[string]*nordlet.ItemsUpdateCatalogRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `[]*nordlet.ItemsUpdateCatalogRequestComponentsItem` 
    
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

**priceFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `*time.Time` 
    
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

**certificateDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `*time.Time` 
    
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

<details><summary><code>client.Catalog.ItemsDelete(request) -> *nordlet.ItemsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsDeleteCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsList(request) -> *nordlet.ItemsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsListCatalogRequest{}
client.Catalog.ItemsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ItemsListCatalogRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ItemsListCatalogRequestFilterItem` 
    
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

<details><summary><code>client.Catalog.ItemsFilesList(request) -> *nordlet.ItemsFilesListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsFilesListCatalogRequest{
        ItemID: "itemId",
    }
client.Catalog.ItemsFilesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsKindsCreate(request) -> *nordlet.ItemsKindsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsKindsCreateCatalogRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.ItemsKindsCreate(
        context.TODO(),
        request,
    )
}
```
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

**saftType:** `*nordlet.ItemsKindsCreateCatalogRequestSaftType` 
    
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

<details><summary><code>client.Catalog.ItemsKindsUpdate(request) -> *nordlet.ItemsKindsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsKindsUpdateCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsKindsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**saftType:** `*nordlet.ItemsKindsUpdateCatalogRequestSaftType` 
    
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

<details><summary><code>client.Catalog.ItemsKindsDelete(request) -> *nordlet.ItemsKindsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsKindsDeleteCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsKindsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsKindsList(request) -> *nordlet.ItemsKindsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsKindsListCatalogRequest{}
client.Catalog.ItemsKindsList(
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

<details><summary><code>client.Catalog.UnitsCreate(request) -> *nordlet.UnitsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsCreateCatalogRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.UnitsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.UnitsUpdate(request) -> *nordlet.UnitsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsUpdateCatalogRequest{
        ID: "id",
    }
client.Catalog.UnitsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.UnitsDelete(request) -> *nordlet.UnitsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsDeleteCatalogRequest{
        ID: "id",
    }
client.Catalog.UnitsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.UnitsList(request) -> *nordlet.UnitsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsListCatalogRequest{}
client.Catalog.UnitsList(
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

<details><summary><code>client.Catalog.UnitsOptions(request) -> *nordlet.UnitsOptionsCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UnitsOptionsCatalogRequest{}
client.Catalog.UnitsOptions(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.UnitsOptionsCatalogRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.ItemGroupsCreate(request) -> *nordlet.ItemGroupsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemGroupsCreateCatalogRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.ItemGroupsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemGroupsUpdate(request) -> *nordlet.ItemGroupsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemGroupsUpdateCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemGroupsDelete(request) -> *nordlet.ItemGroupsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemGroupsDeleteCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemGroupsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemGroupsList(request) -> *nordlet.ItemGroupsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemGroupsListCatalogRequest{}
client.Catalog.ItemGroupsList(
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

<details><summary><code>client.Catalog.ItemsSuppliersUpsert(request) -> *nordlet.ItemsSuppliersUpsertCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsSuppliersUpsertCatalogRequest{
        ItemID: "itemId",
        PartnerID: "partnerId",
    }
client.Catalog.ItemsSuppliersUpsert(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsSuppliersList(request) -> *nordlet.ItemsSuppliersListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsSuppliersListCatalogRequest{}
client.Catalog.ItemsSuppliersList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.ItemsSuppliersDelete(request) -> *nordlet.ItemsSuppliersDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ItemsSuppliersDeleteCatalogRequest{
        ID: "id",
    }
client.Catalog.ItemsSuppliersDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.PriceListsCreate(request) -> *nordlet.PriceListsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsCreateCatalogRequest{
        Code: "code",
        Name: "name",
    }
client.Catalog.PriceListsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.PriceListsUpdate(request) -> *nordlet.PriceListsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsUpdateCatalogRequest{
        ID: "id",
    }
client.Catalog.PriceListsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.PriceListsList(request) -> *nordlet.PriceListsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsListCatalogRequest{}
client.Catalog.PriceListsList(
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

<details><summary><code>client.Catalog.PriceListsItemsSet(request) -> *nordlet.PriceListsItemsSetCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsItemsSetCatalogRequest{
        PriceListID: "priceListId",
        Items: []*nordlet.PriceListsItemsSetCatalogRequestItemsItem{
            &nordlet.PriceListsItemsSetCatalogRequestItemsItem{
                ItemID: "itemId",
                UnitPriceExclVat: "121.0000",
            },
        },
    }
client.Catalog.PriceListsItemsSet(
        context.TODO(),
        request,
    )
}
```
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

**items:** `[]*nordlet.PriceListsItemsSetCatalogRequestItemsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Catalog.PriceListsItemsList(request) -> *nordlet.PriceListsItemsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsItemsListCatalogRequest{
        PriceListID: "priceListId",
    }
client.Catalog.PriceListsItemsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Catalog.PriceListsItemsDelete(request) -> *nordlet.PriceListsItemsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PriceListsItemsDeleteCatalogRequest{
        PriceListID: "priceListId",
        ItemID: "itemId",
    }
client.Catalog.PriceListsItemsDelete(
        context.TODO(),
        request,
    )
}
```
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

## sales
<details><summary><code>client.Sales.InvoicesCreate(request) -> *nordlet.InvoicesCreateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesCreateSalesRequest{
        PartnerID: "partnerId",
        Lines: []*nordlet.InvoicesCreateSalesRequestLinesItem{
            &nordlet.InvoicesCreateSalesRequestLinesItem{},
        },
    }
client.Sales.InvoicesCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.InvoicesCreateSalesRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceReference:** `*string` — Number of an original invoice issued outside Nordlet; give it with creditedInvoiceDate
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceDate:** `*time.Time` — Issue date of the original invoice issued outside Nordlet
    
</dd>
</dl>

<dl>
<dd>

**agreementID:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `*nordlet.InvoicesCreateSalesRequestVatScheme` 
    
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

**lines:** `[]*nordlet.InvoicesCreateSalesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.InvoicesGet(request) -> *nordlet.InvoicesGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesGetSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesPdf(request) -> *nordlet.InvoicesPdfSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPdfSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesPdf(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.InvoicesPdfSalesRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.InvoicesSend(request) -> *nordlet.InvoicesSendSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesSendSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesSend(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.InvoicesSendSalesRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.InvoicesPeppolXML(request) -> *nordlet.InvoicesPeppolXMLSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPeppolXMLSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesPeppolXML(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesPeppolSend(request) -> *nordlet.InvoicesPeppolSendSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPeppolSendSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesPeppolSend(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesEinvoiceXML(request) -> *nordlet.InvoicesEinvoiceXMLSalesResponse</code></summary>
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
request := &nordlet.InvoicesEinvoiceXMLSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesEinvoiceXML(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesEinvoiceSend(request) -> *nordlet.InvoicesEinvoiceSendSalesResponse</code></summary>
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
request := &nordlet.InvoicesEinvoiceSendSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesEinvoiceSend(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesEinvoiceStatus(request) -> *nordlet.InvoicesEinvoiceStatusSalesResponse</code></summary>
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
request := &nordlet.InvoicesEinvoiceStatusSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesEinvoiceStatus(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesUpdate(request) -> *nordlet.InvoicesUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesUpdateSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**issueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `*nordlet.InvoicesUpdateSalesRequestVatScheme` 
    
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

**lines:** `[]*nordlet.InvoicesUpdateSalesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.InvoicesDelete(request) -> *nordlet.InvoicesDeleteSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesDeleteSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesIssue(request) -> *nordlet.InvoicesIssueSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesIssueSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesIssue(
        context.TODO(),
        request,
    )
}
```
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

**issueDate:** `*time.Time` 
    
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

<details><summary><code>client.Sales.InvoicesLock(request) -> *nordlet.InvoicesLockSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesLockSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesLock(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesUnlock(request) -> *nordlet.InvoicesUnlockSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesUnlockSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesUnlock(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesPaymentLink(request) -> *nordlet.InvoicesPaymentLinkSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPaymentLinkSalesRequest{
        ID: "id",
    }
client.Sales.InvoicesPaymentLink(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.InvoicesPaymentSettingsGet(request) -> *nordlet.InvoicesPaymentSettingsGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPaymentSettingsGetSalesRequest{}
client.Sales.InvoicesPaymentSettingsGet(
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

<details><summary><code>client.Sales.InvoicesPaymentSettingsUpdate(request) -> *nordlet.InvoicesPaymentSettingsUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesPaymentSettingsUpdateSalesRequest{}
client.Sales.InvoicesPaymentSettingsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.RecognitionSchedulesList(request) -> *nordlet.RecognitionSchedulesListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionSchedulesListSalesRequest{}
client.Sales.RecognitionSchedulesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.RecognitionSchedulesListSalesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.RecognitionSchedulesListSalesRequestFilterItem` 
    
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

<details><summary><code>client.Sales.InvoicesApplyAdvance(request) -> *nordlet.InvoicesApplyAdvanceSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesApplyAdvanceSalesRequest{
        AdvanceID: "advanceId",
        InvoiceID: "invoiceId",
    }
client.Sales.InvoicesApplyAdvance(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.InvoicesList(request) -> *nordlet.InvoicesListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesListSalesRequest{}
client.Sales.InvoicesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.InvoicesListSalesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.InvoicesListSalesRequestFilterItem` 
    
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

<details><summary><code>client.Sales.ActsCreate(request) -> *nordlet.ActsCreateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsCreateSalesRequest{
        PartnerID: "partnerId",
    }
client.Sales.ActsCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ActsCreateSalesRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.ActsCreateSalesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.ActsUpdate(request) -> *nordlet.ActsUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsUpdateSalesRequest{
        ID: "id",
    }
client.Sales.ActsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ActsUpdateSalesRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.ActsUpdateSalesRequestLinesItem` 
    
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

<details><summary><code>client.Sales.ActsIssue(request) -> *nordlet.ActsIssueSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsIssueSalesRequest{
        ID: "id",
    }
client.Sales.ActsIssue(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.ActsCancel(request) -> *nordlet.ActsCancelSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsCancelSalesRequest{
        ID: "id",
    }
client.Sales.ActsCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.ActsGet(request) -> *nordlet.ActsGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsGetSalesRequest{
        ID: "id",
    }
client.Sales.ActsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.ActsList(request) -> *nordlet.ActsListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsListSalesRequest{}
client.Sales.ActsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ActsListSalesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ActsListSalesRequestFilterItem` 
    
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

<details><summary><code>client.Sales.ActsPdf(request) -> *nordlet.ActsPdfSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ActsPdfSalesRequest{
        ID: "id",
    }
client.Sales.ActsPdf(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.ActsPdfSalesRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.RecognitionCompute(request) -> *nordlet.RecognitionComputeSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionComputeSalesRequest{}
client.Sales.RecognitionCompute(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.RecognitionRun(request) -> *nordlet.RecognitionRunSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionRunSalesRequest{}
client.Sales.RecognitionRun(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**postingDate:** `*time.Time` 
    
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

<details><summary><code>client.Sales.RecognitionProgress(request) -> *nordlet.RecognitionProgressSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionProgressSalesRequest{
        InvoiceLineID: "invoiceLineId",
        PercentComplete: "121.00",
    }
client.Sales.RecognitionProgress(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.RecognitionModify(request) -> *nordlet.RecognitionModifySalesResponse</code></summary>
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
request := &nordlet.RecognitionModifySalesRequest{
        InvoiceLineID: "invoiceLineId",
        Approach: nordlet.RecognitionModifySalesRequestApproachProspective,
    }
client.Sales.RecognitionModify(
        context.TODO(),
        request,
    )
}
```
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

**approach:** `*nordlet.RecognitionModifySalesRequestApproach` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**newEndDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**newMilestones:** `[]*nordlet.RecognitionModifySalesRequestNewMilestonesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Sales.RecognitionRunsList(request) -> *nordlet.RecognitionRunsListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionRunsListSalesRequest{}
client.Sales.RecognitionRunsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.RecognitionRunsListSalesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.RecognitionRunsListSalesRequestFilterItem` 
    
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

<details><summary><code>client.Sales.RecognitionSummary(request) -> *nordlet.RecognitionSummarySalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RecognitionSummarySalesRequest{}
client.Sales.RecognitionSummary(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Sales.RefundLiabilityList(request) -> *nordlet.RefundLiabilityListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RefundLiabilityListSalesRequest{}
client.Sales.RefundLiabilityList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.RefundLiabilityListSalesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.RefundLiabilityListSalesRequestFilterItem` 
    
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

<details><summary><code>client.Sales.RefundLiabilityTrueUp(request) -> *nordlet.RefundLiabilityTrueUpSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RefundLiabilityTrueUpSalesRequest{
        InvoiceID: "invoiceId",
        EstimatedTotal: "121.0000",
    }
client.Sales.RefundLiabilityTrueUp(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## OperationTypes
<details><summary><code>client.OperationTypes.Create(request) -> *nordlet.CreateOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateOperationTypesRequest{
        Code: "code",
        Name: "name",
    }
client.OperationTypes.Create(
        context.TODO(),
        request,
    )
}
```
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

**invoiceType:** `*nordlet.CreateOperationTypesRequestInvoiceType` 
    
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

<details><summary><code>client.OperationTypes.Update(request) -> *nordlet.UpdateOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateOperationTypesRequest{
        ID: "id",
    }
client.OperationTypes.Update(
        context.TODO(),
        request,
    )
}
```
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

**invoiceType:** `*nordlet.UpdateOperationTypesRequestInvoiceType` 
    
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

<details><summary><code>client.OperationTypes.Get(request) -> *nordlet.GetOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetOperationTypesRequest{
        ID: "id",
    }
client.OperationTypes.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.OperationTypes.Delete(request) -> *nordlet.DeleteOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteOperationTypesRequest{
        ID: "id",
    }
client.OperationTypes.Delete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.OperationTypes.List(request) -> *nordlet.ListOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListOperationTypesRequest{}
client.OperationTypes.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListOperationTypesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListOperationTypesRequestFilterItem` 
    
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

## DocumentSeries
<details><summary><code>client.DocumentSeries.Create(request) -> *nordlet.CreateDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateDocumentSeriesRequest{
        Prefix: "prefix",
    }
client.DocumentSeries.Create(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**documentType:** `*nordlet.CreateDocumentSeriesRequestDocumentType` 
    
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

<details><summary><code>client.DocumentSeries.Update(request) -> *nordlet.UpdateDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateDocumentSeriesRequest{
        ID: "id",
    }
client.DocumentSeries.Update(
        context.TODO(),
        request,
    )
}
```
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

**documentType:** `*nordlet.UpdateDocumentSeriesRequestDocumentType` 
    
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

<details><summary><code>client.DocumentSeries.Get(request) -> *nordlet.GetDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetDocumentSeriesRequest{
        ID: "id",
    }
client.DocumentSeries.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.DocumentSeries.Delete(request) -> *nordlet.DeleteDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteDocumentSeriesRequest{
        ID: "id",
    }
client.DocumentSeries.Delete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.DocumentSeries.List(request) -> *nordlet.ListDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListDocumentSeriesRequest{}
client.DocumentSeries.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListDocumentSeriesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListDocumentSeriesRequestFilterItem` 
    
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

## purchases
<details><summary><code>client.Purchases.InvoicesCreate(request) -> *nordlet.InvoicesCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesCreatePurchasesRequest{
        PartnerID: "partnerId",
        DocumentNumber: "documentNumber",
        DocumentDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Lines: []*nordlet.InvoicesCreatePurchasesRequestLinesItem{
            &nordlet.InvoicesCreatePurchasesRequestLinesItem{},
        },
    }
client.Purchases.InvoicesCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.InvoicesCreatePurchasesRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.InvoicesCreatePurchasesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.InvoicesGet(request) -> *nordlet.InvoicesGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesGetPurchasesRequest{
        ID: "id",
    }
client.Purchases.InvoicesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.InvoicesUpdate(request) -> *nordlet.InvoicesUpdatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesUpdatePurchasesRequest{
        ID: "id",
    }
client.Purchases.InvoicesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**documentDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.InvoicesUpdatePurchasesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.InvoicesDelete(request) -> *nordlet.InvoicesDeletePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesDeletePurchasesRequest{
        ID: "id",
    }
client.Purchases.InvoicesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.InvoicesRegister(request) -> *nordlet.InvoicesRegisterPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesRegisterPurchasesRequest{
        ID: "id",
    }
client.Purchases.InvoicesRegister(
        context.TODO(),
        request,
    )
}
```
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

**registrationDate:** `*time.Time` 
    
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

<details><summary><code>client.Purchases.InvoicesList(request) -> *nordlet.InvoicesListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesListPurchasesRequest{}
client.Purchases.InvoicesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.InvoicesListPurchasesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.InvoicesListPurchasesRequestFilterItem` 
    
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

<details><summary><code>client.Purchases.OrdersCreate(request) -> *nordlet.OrdersCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCreatePurchasesRequest{
        PartnerID: "partnerId",
        OrderDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Lines: []*nordlet.OrdersCreatePurchasesRequestLinesItem{
            &nordlet.OrdersCreatePurchasesRequestLinesItem{},
        },
    }
client.Purchases.OrdersCreate(
        context.TODO(),
        request,
    )
}
```
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

**orderDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.OrdersCreatePurchasesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.OrdersUpdate(request) -> *nordlet.OrdersUpdatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersUpdatePurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersUpdate(
        context.TODO(),
        request,
    )
}
```
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

**orderDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.OrdersUpdatePurchasesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.OrdersGet(request) -> *nordlet.OrdersGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersGetPurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersList(request) -> *nordlet.OrdersListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersListPurchasesRequest{}
client.Purchases.OrdersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.OrdersListPurchasesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.OrdersListPurchasesRequestFilterItem` 
    
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

<details><summary><code>client.Purchases.OrdersSubmit(request) -> *nordlet.OrdersSubmitPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersSubmitPurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersSubmit(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersApprove(request) -> *nordlet.OrdersApprovePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersApprovePurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersApprove(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersReject(request) -> *nordlet.OrdersRejectPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersRejectPurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersReject(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersCancel(request) -> *nordlet.OrdersCancelPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCancelPurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersClose(request) -> *nordlet.OrdersClosePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersClosePurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersClose(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.OrdersDelete(request) -> *nordlet.OrdersDeletePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersDeletePurchasesRequest{
        ID: "id",
    }
client.Purchases.OrdersDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.ReceiptsCreate(request) -> *nordlet.ReceiptsCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReceiptsCreatePurchasesRequest{
        OrderID: "orderId",
        ReceiptDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Lines: []*nordlet.ReceiptsCreatePurchasesRequestLinesItem{
            &nordlet.ReceiptsCreatePurchasesRequestLinesItem{
                OrderLineID: "orderLineId",
                Quantity: "121.0000",
            },
        },
    }
client.Purchases.ReceiptsCreate(
        context.TODO(),
        request,
    )
}
```
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

**receiptDate:** `time.Time` 
    
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

**lines:** `[]*nordlet.ReceiptsCreatePurchasesRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Purchases.ReceiptsGet(request) -> *nordlet.ReceiptsGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReceiptsGetPurchasesRequest{
        ID: "id",
    }
client.Purchases.ReceiptsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Purchases.ReceiptsList(request) -> *nordlet.ReceiptsListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReceiptsListPurchasesRequest{}
client.Purchases.ReceiptsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ReceiptsListPurchasesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ReceiptsListPurchasesRequestFilterItem` 
    
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

<details><summary><code>client.Purchases.InvoicesMatch(request) -> *nordlet.InvoicesMatchPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvoicesMatchPurchasesRequest{
        InvoiceID: "invoiceId",
    }
client.Purchases.InvoicesMatch(
        context.TODO(),
        request,
    )
}
```
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

## capture
<details><summary><code>client.Capture.SettingsGet(request) -> *nordlet.SettingsGetCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettingsGetCaptureRequest{}
client.Capture.SettingsGet(
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

<details><summary><code>client.Capture.SettingsUpdate(request) -> *nordlet.SettingsUpdateCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettingsUpdateCaptureRequest{}
client.Capture.SettingsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Capture.SettingsRegenerateIntake(request) -> *nordlet.SettingsRegenerateIntakeCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettingsRegenerateIntakeCaptureRequest{}
client.Capture.SettingsRegenerateIntake(
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

<details><summary><code>client.Capture.InboundEmail(request) -> *nordlet.InboundEmailCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InboundEmailCaptureRequest{}
client.Capture.InboundEmail(
        context.TODO(),
        request,
    )
}
```
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

**toFull:** `[]*nordlet.InboundEmailCaptureRequestToFullItem` 
    
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

**postmarkAttachments:** `[]*nordlet.InboundEmailCaptureRequestAttachmentsItem` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `*nordlet.InboundEmailCaptureRequestTo` 
    
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

**attachments:** `[]*nordlet.InboundEmailCaptureRequestAttachmentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Capture.DocumentsUpload(request) -> *nordlet.DocumentsUploadCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsUploadCaptureRequest{
        FileName: "fileName",
        MimeType: "mimeType",
        Content: "content",
    }
client.Capture.DocumentsUpload(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Capture.DocumentsExtract(request) -> *nordlet.DocumentsExtractCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsExtractCaptureRequest{
        ID: "id",
    }
client.Capture.DocumentsExtract(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Capture.DocumentsGet(request) -> *nordlet.DocumentsGetCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsGetCaptureRequest{
        ID: "id",
    }
client.Capture.DocumentsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Capture.DocumentsList(request) -> *nordlet.DocumentsListCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsListCaptureRequest{}
client.Capture.DocumentsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.DocumentsListCaptureRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.DocumentsListCaptureRequestFilterItem` 
    
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

<details><summary><code>client.Capture.DocumentsDelete(request) -> *nordlet.DocumentsDeleteCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsDeleteCaptureRequest{
        ID: "id",
    }
client.Capture.DocumentsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Capture.DocumentsConfirm(request) -> *nordlet.DocumentsConfirmCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DocumentsConfirmCaptureRequest{
        ID: "id",
        DocumentNumber: "documentNumber",
        DocumentDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Lines: []*nordlet.DocumentsConfirmCaptureRequestLinesItem{
            &nordlet.DocumentsConfirmCaptureRequestLinesItem{},
        },
    }
client.Capture.DocumentsConfirm(
        context.TODO(),
        request,
    )
}
```
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

**newSupplier:** `*nordlet.DocumentsConfirmCaptureRequestNewSupplier` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.DocumentsConfirmCaptureRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## declarations
<details><summary><code>client.Declarations.LtIntrastatCompute(request) -> *nordlet.LtIntrastatComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIntrastatComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        Flow: nordlet.LtIntrastatComputeDeclarationsRequestFlowArrivals,
    }
client.Declarations.LtIntrastatCompute(
        context.TODO(),
        request,
    )
}
```
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

**flow:** `*nordlet.LtIntrastatComputeDeclarationsRequestFlow` 
    
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

**transportMode:** `*nordlet.LtIntrastatComputeDeclarationsRequestTransportMode` 
    
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

<details><summary><code>client.Declarations.LtIvazGenerate(request) -> *nordlet.LtIvazGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIvazGenerateDeclarationsRequest{
        WaybillIDs: []string{
            "waybillIds",
        },
    }
client.Declarations.LtIvazGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtIntrastatObligation(request) -> *nordlet.LtIntrastatObligationDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIntrastatObligationDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LtIntrastatObligation(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtIsafGenerate(request) -> *nordlet.LtIsafGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIsafGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.LtIsafGenerate(
        context.TODO(),
        request,
    )
}
```
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

**dataType:** `*nordlet.LtIsafGenerateDeclarationsRequestDataType` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.LtFr0600Compute(request) -> *nordlet.LtFr0600ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtFr0600ComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.LtFr0600Compute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtGpm313Compute(request) -> *nordlet.LtGpm313ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtGpm313ComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.LtGpm313Compute(
        context.TODO(),
        request,
    )
}
```
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

**payoutTiming:** `*nordlet.LtGpm313ComputeDeclarationsRequestPayoutTiming` 
    
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

<details><summary><code>client.Declarations.LtSamCompute(request) -> *nordlet.LtSamComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtSamComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.LtSamCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtSdGenerate(request) -> *nordlet.LtSdGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtSdGenerateDeclarationsRequest{
        Type: nordlet.LtSdGenerateDeclarationsRequestTypeOneSd,
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.LtSdGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.LtSdGenerateDeclarationsRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.LtSaftGenerate(request) -> *nordlet.LtSaftGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtSaftGenerateDeclarationsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.LtSaftGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.LtSaftGenerateDeclarationsRequestDataType` 
    
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

<details><summary><code>client.Declarations.LtIvazAmend(request) -> *nordlet.LtIvazAmendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIvazAmendDeclarationsRequest{
        WaybillIDs: []string{
            "waybillIds",
        },
    }
client.Declarations.LtIvazAmend(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtIvazCancel(request) -> *nordlet.LtIvazCancelDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtIvazCancelDeclarationsRequest{
        Entries: []*nordlet.LtIvazCancelDeclarationsRequestEntriesItem{
            &nordlet.LtIvazCancelDeclarationsRequestEntriesItem{
                WaybillID: "waybillId",
                Reason: nordlet.LtIvazCancelDeclarationsRequestEntriesItemReasonOne,
            },
        },
    }
client.Declarations.LtIvazCancel(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**entries:** `[]*nordlet.LtIvazCancelDeclarationsRequestEntriesItem` 
    
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

<details><summary><code>client.Declarations.LtFr0564Compute(request) -> *nordlet.LtFr0564ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtFr0564ComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.LtFr0564Compute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LtGpm312Compute(request) -> *nordlet.LtGpm312ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtGpm312ComputeDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LtGpm312Compute(
        context.TODO(),
        request,
    )
}
```
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

**payoutTiming:** `*nordlet.LtGpm312ComputeDeclarationsRequestPayoutTiming` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.LtPln204Compute(request) -> *nordlet.LtPln204ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LtPln204ComputeDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LtPln204Compute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.EuOssCompute(request) -> *nordlet.EuOssComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuOssComputeDeclarationsRequest{
        Year: int64(1000000),
        Quarter: int64(1000000),
    }
client.Declarations.EuOssCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.EuIossCompute(request) -> *nordlet.EuIossComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuIossComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.EuIossCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.EuDistanceSalesThresholdGet(request) -> *nordlet.EuDistanceSalesThresholdGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuDistanceSalesThresholdGetDeclarationsRequest{}
client.Declarations.EuDistanceSalesThresholdGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.EuUnionTurnoverGet(request) -> *nordlet.EuUnionTurnoverGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuUnionTurnoverGetDeclarationsRequest{}
client.Declarations.EuUnionTurnoverGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.EuSmeCrossBorderReportCompute(request) -> *nordlet.EuSmeCrossBorderReportComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuSmeCrossBorderReportComputeDeclarationsRequest{
        Year: int64(1000000),
        Quarter: int64(1000000),
    }
client.Declarations.EuSmeCrossBorderReportCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.EuSmeThresholdsList(request) -> *nordlet.EuSmeThresholdsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuSmeThresholdsListDeclarationsRequest{}
client.Declarations.EuSmeThresholdsList(
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

<details><summary><code>client.Declarations.EuSmeThresholdGet(request) -> *nordlet.EuSmeThresholdGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuSmeThresholdGetDeclarationsRequest{}
client.Declarations.EuSmeThresholdGet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.EuVatReturnPacksList(request) -> *nordlet.EuVatReturnPacksListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuVatReturnPacksListDeclarationsRequest{}
client.Declarations.EuVatReturnPacksList(
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

<details><summary><code>client.Declarations.EuVatReturnCompute(request) -> *nordlet.EuVatReturnComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuVatReturnComputeDeclarationsRequest{
        CountryCode: "countryCode",
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.EuVatReturnCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlJpkV7MGenerate(request) -> *nordlet.PlJpkV7MGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlJpkV7MGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        KodUrzedu: "kodUrzedu",
        Email: "email",
    }
client.Declarations.PlJpkV7MGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlVatUeGenerate(request) -> *nordlet.PlVatUeGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlVatUeGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PlVatUeGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlIntrastatGenerate(request) -> *nordlet.PlIntrastatGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlIntrastatGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
        Flow: nordlet.PlIntrastatGenerateDeclarationsRequestFlowArrivals,
    }
client.Declarations.PlIntrastatGenerate(
        context.TODO(),
        request,
    )
}
```
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

**flow:** `*nordlet.PlIntrastatGenerateDeclarationsRequestFlow` 
    
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

<details><summary><code>client.Declarations.PlKsefReceivedList(request) -> *nordlet.PlKsefReceivedListDeclarationsResponse</code></summary>
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
request := &nordlet.PlKsefReceivedListDeclarationsRequest{
        From: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
        To: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
    }
client.Declarations.PlKsefReceivedList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlKsefReceivedFetch(request) -> *nordlet.PlKsefReceivedFetchDeclarationsResponse</code></summary>
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
request := &nordlet.PlKsefReceivedFetchDeclarationsRequest{
        KsefNumber: "ksefNumber",
    }
client.Declarations.PlKsefReceivedFetch(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlKsefReceipt(request) -> *nordlet.PlKsefReceiptDeclarationsResponse</code></summary>
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
request := &nordlet.PlKsefReceiptDeclarationsRequest{}
client.Declarations.PlKsefReceipt(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.TaxAdjustmentsList(request) -> *nordlet.TaxAdjustmentsListDeclarationsResponse</code></summary>
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
request := &nordlet.TaxAdjustmentsListDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.TaxAdjustmentsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.TaxAdjustmentsCreate(request) -> *nordlet.TaxAdjustmentsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxAdjustmentsCreateDeclarationsRequest{
        Year: int64(1000000),
        Kind: nordlet.TaxAdjustmentsCreateDeclarationsRequestKindNonDeductible,
        Amount: "121.00",
        Description: "description",
    }
client.Declarations.TaxAdjustmentsCreate(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.TaxAdjustmentsCreateDeclarationsRequestKind` 
    
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

<details><summary><code>client.Declarations.TaxAdjustmentsUpdate(request) -> *nordlet.TaxAdjustmentsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxAdjustmentsUpdateDeclarationsRequest{
        ID: "id",
    }
client.Declarations.TaxAdjustmentsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.TaxAdjustmentsUpdateDeclarationsRequestKind` 
    
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

<details><summary><code>client.Declarations.TaxAdjustmentsDelete(request) -> *nordlet.TaxAdjustmentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxAdjustmentsDeleteDeclarationsRequest{
        ID: "id",
    }
client.Declarations.TaxAdjustmentsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.TaxPaymentsList(request) -> *nordlet.TaxPaymentsListDeclarationsResponse</code></summary>
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
request := &nordlet.TaxPaymentsListDeclarationsRequest{
        Tax: nordlet.TaxPaymentsListDeclarationsRequestTaxCorporateIncomeTax,
        Year: int64(1000000),
    }
client.Declarations.TaxPaymentsList(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tax:** `*nordlet.TaxPaymentsListDeclarationsRequestTax` 
    
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

<details><summary><code>client.Declarations.TaxPaymentsCreate(request) -> *nordlet.TaxPaymentsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxPaymentsCreateDeclarationsRequest{
        Tax: nordlet.TaxPaymentsCreateDeclarationsRequestTaxCorporateIncomeTax,
        Year: int64(1000000),
        Kind: nordlet.TaxPaymentsCreateDeclarationsRequestKindAdvance,
        Amount: "121.00",
        PaidOn: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Description: "description",
    }
client.Declarations.TaxPaymentsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tax:** `*nordlet.TaxPaymentsCreateDeclarationsRequestTax` 
    
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

**kind:** `*nordlet.TaxPaymentsCreateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `time.Time` 
    
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

<details><summary><code>client.Declarations.TaxPaymentsUpdate(request) -> *nordlet.TaxPaymentsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxPaymentsUpdateDeclarationsRequest{
        ID: "id",
    }
client.Declarations.TaxPaymentsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.TaxPaymentsUpdateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `*time.Time` 
    
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

<details><summary><code>client.Declarations.TaxPaymentsDelete(request) -> *nordlet.TaxPaymentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TaxPaymentsDeleteDeclarationsRequest{
        ID: "id",
    }
client.Declarations.TaxPaymentsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.AnnualAccountsGet(request) -> *nordlet.AnnualAccountsGetDeclarationsResponse</code></summary>
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
request := &nordlet.AnnualAccountsGetDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.AnnualAccountsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.AnnualAccountsSet(request) -> *nordlet.AnnualAccountsSetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsSetDeclarationsRequest{
        Year: int64(1000000),
        Adopted: true,
        DateOfPreparation: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.AnnualAccountsSet(
        context.TODO(),
        request,
    )
}
```
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

**adoptionDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateOfPreparation:** `time.Time` 
    
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

**auditorReportDate:** `*time.Time` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsSignaturesCreate(request) -> *nordlet.AnnualAccountsSignaturesCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsSignaturesCreateDeclarationsRequest{
        Year: int64(1000000),
        DirectorName: "directorName",
        DirectorType: nordlet.AnnualAccountsSignaturesCreateDeclarationsRequestDirectorTypeManagingCurrent,
        Signed: true,
    }
client.Declarations.AnnualAccountsSignaturesCreate(
        context.TODO(),
        request,
    )
}
```
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

**directorType:** `*nordlet.AnnualAccountsSignaturesCreateDeclarationsRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `*time.Time` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsSignaturesUpdate(request) -> *nordlet.AnnualAccountsSignaturesUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsSignaturesUpdateDeclarationsRequest{
        ID: "id",
        DirectorName: "directorName",
        DirectorType: nordlet.AnnualAccountsSignaturesUpdateDeclarationsRequestDirectorTypeManagingCurrent,
        Signed: true,
    }
client.Declarations.AnnualAccountsSignaturesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**directorType:** `*nordlet.AnnualAccountsSignaturesUpdateDeclarationsRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `*time.Time` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsSignaturesDelete(request) -> *nordlet.AnnualAccountsSignaturesDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsSignaturesDeleteDeclarationsRequest{
        ID: "id",
    }
client.Declarations.AnnualAccountsSignaturesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.AnnualAccountsDistributionsCreate(request) -> *nordlet.AnnualAccountsDistributionsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsDistributionsCreateDeclarationsRequest{
        Year: int64(1000000),
        DecidedOn: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Kind: nordlet.AnnualAccountsDistributionsCreateDeclarationsRequestKindDividend,
        Amount: "121.00",
    }
client.Declarations.AnnualAccountsDistributionsCreate(
        context.TODO(),
        request,
    )
}
```
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

**decidedOn:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.AnnualAccountsDistributionsCreateDeclarationsRequestKind` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsDistributionsUpdate(request) -> *nordlet.AnnualAccountsDistributionsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsDistributionsUpdateDeclarationsRequest{
        ID: "id",
        DecidedOn: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Kind: nordlet.AnnualAccountsDistributionsUpdateDeclarationsRequestKindDividend,
        Amount: "121.00",
    }
client.Declarations.AnnualAccountsDistributionsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**decidedOn:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `*nordlet.AnnualAccountsDistributionsUpdateDeclarationsRequestKind` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsDistributionsDelete(request) -> *nordlet.AnnualAccountsDistributionsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsDistributionsDeleteDeclarationsRequest{
        ID: "id",
    }
client.Declarations.AnnualAccountsDistributionsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.AnnualAccountsAttachmentsAdd(request) -> *nordlet.AnnualAccountsAttachmentsAddDeclarationsResponse</code></summary>
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
request := &nordlet.AnnualAccountsAttachmentsAddDeclarationsRequest{
        Year: int64(1000000),
        Kind: nordlet.AnnualAccountsAttachmentsAddDeclarationsRequestKindFullReport,
        Ref: "ref",
    }
client.Declarations.AnnualAccountsAttachmentsAdd(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.AnnualAccountsAttachmentsAddDeclarationsRequestKind` 
    
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

<details><summary><code>client.Declarations.AnnualAccountsAttachmentsDelete(request) -> *nordlet.AnnualAccountsAttachmentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AnnualAccountsAttachmentsDeleteDeclarationsRequest{
        ID: "id",
    }
client.Declarations.AnnualAccountsAttachmentsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.CyTd4Generate(request) -> *nordlet.CyTd4GenerateDeclarationsResponse</code></summary>
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
request := &nordlet.CyTd4GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.CyTd4Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.CyHe32Generate(request) -> *nordlet.CyHe32GenerateDeclarationsResponse</code></summary>
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
request := &nordlet.CyHe32GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.CyHe32Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.DeReturnsGenerate(request) -> *nordlet.DeReturnsGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.DeReturnsGenerateDeclarationsRequest{
        RuleKey: nordlet.DeReturnsGenerateDeclarationsRequestRuleKeyDeEBilanz,
        Period: "period",
    }
client.Declarations.DeReturnsGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ruleKey:** `*nordlet.DeReturnsGenerateDeclarationsRequestRuleKey` 
    
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

<details><summary><code>client.Declarations.DeReturnFactsGet(request) -> *nordlet.DeReturnFactsGetDeclarationsResponse</code></summary>
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
request := &nordlet.DeReturnFactsGetDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.DeReturnFactsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.DeReturnFactsSet(request) -> *nordlet.DeReturnFactsSetDeclarationsResponse</code></summary>
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
request := &nordlet.DeReturnFactsSetDeclarationsRequest{
        Year: int64(1000000),
        Facts: &nordlet.DeReturnFactsSetDeclarationsRequestFacts{},
    }
client.Declarations.DeReturnFactsSet(
        context.TODO(),
        request,
    )
}
```
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

**facts:** `*nordlet.DeReturnFactsSetDeclarationsRequestFacts` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.DeDeuevGenerate(request) -> *nordlet.DeDeuevGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.DeDeuevGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.DeDeuevGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.DeBeitragsnachweisGenerate(request) -> *nordlet.DeBeitragsnachweisGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.DeBeitragsnachweisGenerateDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.DeBeitragsnachweisGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.DkSelskabsskatGenerate(request) -> *nordlet.DkSelskabsskatGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.DkSelskabsskatGenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.DkSelskabsskatGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.EeEmploymentRegisterSend(request) -> *nordlet.EeEmploymentRegisterSendDeclarationsResponse</code></summary>
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
request := &nordlet.EeEmploymentRegisterSendDeclarationsRequest{
        ContractID: "contractId",
        Event: nordlet.EeEmploymentRegisterSendDeclarationsRequestEventStart,
    }
client.Declarations.EeEmploymentRegisterSend(
        context.TODO(),
        request,
    )
}
```
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

**event:** `*nordlet.EeEmploymentRegisterSendDeclarationsRequestEvent` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.EsVerifactuDeclaracionResponsable(request) -> *nordlet.EsVerifactuDeclaracionResponsableDeclarationsResponse</code></summary>
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
request := &nordlet.EsVerifactuDeclaracionResponsableDeclarationsRequest{}
client.Declarations.EsVerifactuDeclaracionResponsable(
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

<details><summary><code>client.Declarations.IeCt1Generate(request) -> *nordlet.IeCt1GenerateDeclarationsResponse</code></summary>
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
request := &nordlet.IeCt1GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.IeCt1Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.IeB1Generate(request) -> *nordlet.IeB1GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the working paper for the Form B1 annual return of a financial year - company details, registered office, directors and secretary from Settings → Officers, the members from Settings → Shareholders, the issued share capital and the figures of the financial statements - in the order the CORE screens ask for them. The CRO publishes no file format for the B1, so it is keyed into CORE.
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
request := &nordlet.IeB1GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.IeB1Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.ItSdiPurchaseSend(request) -> *nordlet.ItSdiPurchaseSendDeclarationsResponse</code></summary>
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
request := &nordlet.ItSdiPurchaseSendDeclarationsRequest{
        PurchaseInvoiceID: "purchaseInvoiceId",
    }
client.Declarations.ItSdiPurchaseSend(
        context.TODO(),
        request,
    )
}
```
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

**tipoDocumento:** `*nordlet.ItSdiPurchaseSendDeclarationsRequestTipoDocumento` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.ItSdiPurchasePreview(request) -> *nordlet.ItSdiPurchasePreviewDeclarationsResponse</code></summary>
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
request := &nordlet.ItSdiPurchasePreviewDeclarationsRequest{
        PurchaseInvoiceID: "purchaseInvoiceId",
    }
client.Declarations.ItSdiPurchasePreview(
        context.TODO(),
        request,
    )
}
```
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

**tipoDocumento:** `*nordlet.ItSdiPurchasePreviewDeclarationsRequestTipoDocumento` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.LtSaftSend(request) -> *nordlet.LtSaftSendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload the SAF-T file to i.SAF-T over the iSAFTUploaderService web service and start its processing. The file, the case reference and the status are kept as a declaration submission (submissionId), whose outcome Nordlet then checks with i.SAF-T. The submission itself is confirmed separately, because after confirmation the file can no longer be corrected. A range and data type already sent is sent again only with amend: true.
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
request := &nordlet.LtSaftSendDeclarationsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.LtSaftSend(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `*nordlet.LtSaftSendDeclarationsRequestDataType` 
    
</dd>
</dl>

<dl>
<dd>

**confirm:** `*bool` 
    
</dd>
</dl>

<dl>
<dd>

**amend:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.LtSdFfdata(request) -> *nordlet.LtSdFfdataDeclarationsResponse</code></summary>
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
request := &nordlet.LtSdFfdataDeclarationsRequest{
        Type: nordlet.LtSdFfdataDeclarationsRequestTypeOneSd,
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.LtSdFfdata(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.LtSdFfdataDeclarationsRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Declarations.LtPln204Ffdata(request) -> *nordlet.LtPln204FfdataDeclarationsResponse</code></summary>
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
request := &nordlet.LtPln204FfdataDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LtPln204Ffdata(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.MtCompanyTaxGenerate(request) -> *nordlet.MtCompanyTaxGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.MtCompanyTaxGenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.MtCompanyTaxGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.MtAnnualReturnGenerate(request) -> *nordlet.MtAnnualReturnGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.MtAnnualReturnGenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.MtAnnualReturnGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlJpkFaGenerate(request) -> *nordlet.PlJpkFaGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlJpkFaGenerateDeclarationsRequest{
        DateFrom: nordlet.MustParseDate(
            "2026-07-01",
        ),
        DateTo: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.PlJpkFaGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PlJpkKrGenerate(request) -> *nordlet.PlJpkKrGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlJpkKrGenerateDeclarationsRequest{
        DateFrom: nordlet.MustParseDate(
            "2026-07-01",
        ),
        DateTo: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.PlJpkKrGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.PlJpkMagGenerate(request) -> *nordlet.PlJpkMagGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlJpkMagGenerateDeclarationsRequest{
        DateFrom: nordlet.MustParseDate(
            "2026-07-01",
        ),
        DateTo: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Declarations.PlJpkMagGenerate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `time.Time` 
    
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

<details><summary><code>client.Declarations.PlPit11Generate(request) -> *nordlet.PlPit11GenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlPit11GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.PlPit11Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlCit8Generate(request) -> *nordlet.PlCit8GenerateDeclarationsResponse</code></summary>
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
request := &nordlet.PlCit8GenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.PlCit8Generate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlZusDraCompute(request) -> *nordlet.PlZusDraComputeDeclarationsResponse</code></summary>
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
request := &nordlet.PlZusDraComputeDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PlZusDraCompute(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlZusDraKedu(request) -> *nordlet.PlZusDraKeduDeclarationsResponse</code></summary>
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
request := &nordlet.PlZusDraKeduDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PlZusDraKedu(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.PlZusDraPdf(request) -> *nordlet.PlZusDraPdfDeclarationsResponse</code></summary>
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
request := &nordlet.PlZusDraPdfDeclarationsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.PlZusDraPdf(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.RoEtransportBuild(request) -> *nordlet.RoEtransportBuildDeclarationsResponse</code></summary>
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
request := &nordlet.RoEtransportBuildDeclarationsRequest{
        WaybillID: "waybillId",
    }
client.Declarations.RoEtransportBuild(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.RoEtransportSubmit(request) -> *nordlet.RoEtransportSubmitDeclarationsResponse</code></summary>
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
request := &nordlet.RoEtransportSubmitDeclarationsRequest{
        WaybillID: "waybillId",
    }
client.Declarations.RoEtransportSubmit(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.RoEtransportStatus(request) -> *nordlet.RoEtransportStatusDeclarationsResponse</code></summary>
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
request := &nordlet.RoEtransportStatusDeclarationsRequest{
        Reference: "reference",
    }
client.Declarations.RoEtransportStatus(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LiLohndeklarationGenerate(request) -> *nordlet.LiLohndeklarationGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.LiLohndeklarationGenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LiLohndeklarationGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.LiLohnlistenGenerate(request) -> *nordlet.LiLohnlistenGenerateDeclarationsResponse</code></summary>
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
request := &nordlet.LiLohnlistenGenerateDeclarationsRequest{
        Year: int64(1000000),
    }
client.Declarations.LiLohnlistenGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.ConfigsList(request) -> *nordlet.ConfigsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ConfigsListDeclarationsRequest{}
client.Declarations.ConfigsList(
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

<details><summary><code>client.Declarations.ConfigsUpdate(request) -> *nordlet.ConfigsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ConfigsUpdateDeclarationsRequest{
        System: "system",
        Config: map[string]string{
            "key": "value",
        },
    }
client.Declarations.ConfigsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.CertificatesUpload(request) -> *nordlet.CertificatesUploadDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CertificatesUploadDeclarationsRequest{
        System: "system",
        FileName: "fileName",
        Content: "content",
    }
client.Declarations.CertificatesUpload(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.CertificatesList(request) -> *nordlet.CertificatesListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CertificatesListDeclarationsRequest{}
client.Declarations.CertificatesList(
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

<details><summary><code>client.Declarations.CertificatesDelete(request) -> *nordlet.CertificatesDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CertificatesDeleteDeclarationsRequest{
        System: "system",
        FieldKey: nordlet.CertificatesDeleteDeclarationsRequestFieldKeyCertificate,
    }
client.Declarations.CertificatesDelete(
        context.TODO(),
        request,
    )
}
```
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

**fieldKey:** `*nordlet.CertificatesDeleteDeclarationsRequestFieldKey` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.AutomationList(request) -> *nordlet.AutomationListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AutomationListDeclarationsRequest{}
client.Declarations.AutomationList(
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

<details><summary><code>client.Declarations.AutomationUpdate(request) -> *nordlet.AutomationUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AutomationUpdateDeclarationsRequest{
        RuleKey: "ruleKey",
        Enabled: true,
    }
client.Declarations.AutomationUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.SubmissionsRetry(request) -> *nordlet.SubmissionsRetryDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubmissionsRetryDeclarationsRequest{
        ID: "id",
    }
client.Declarations.SubmissionsRetry(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Declarations.SubmissionsCreate(request) -> *nordlet.SubmissionsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubmissionsCreateDeclarationsRequest{
        Obligation: nordlet.SubmissionsCreateDeclarationsRequestObligationLtIsaf,
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Declarations.SubmissionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**obligation:** `*nordlet.SubmissionsCreateDeclarationsRequestObligation` 
    
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

**dataType:** `*nordlet.SubmissionsCreateDeclarationsRequestDataType` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Declarations.SubmissionsMark(request) -> *nordlet.SubmissionsMarkDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubmissionsMarkDeclarationsRequest{
        ID: "id",
        Status: nordlet.SubmissionsMarkDeclarationsRequestStatusSubmitted,
    }
client.Declarations.SubmissionsMark(
        context.TODO(),
        request,
    )
}
```
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

**status:** `*nordlet.SubmissionsMarkDeclarationsRequestStatus` 
    
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

<details><summary><code>client.Declarations.SubmissionsList(request) -> *nordlet.SubmissionsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubmissionsListDeclarationsRequest{}
client.Declarations.SubmissionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.SubmissionsListDeclarationsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.SubmissionsListDeclarationsRequestFilterItem` 
    
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

## ledger
<details><summary><code>client.Ledger.AccountsList(request) -> *nordlet.AccountsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsListLedgerRequest{}
client.Ledger.AccountsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AccountsListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AccountsListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.AccountsCreate(request) -> *nordlet.AccountsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsCreateLedgerRequest{
        Code: "code",
        Name: "name",
        Type: nordlet.AccountsCreateLedgerRequestTypeAsset,
    }
client.Ledger.AccountsCreate(
        context.TODO(),
        request,
    )
}
```
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

**translations:** `map[string]*nordlet.AccountsCreateLedgerRequestTranslationsValue` 
    
</dd>
</dl>

<dl>
<dd>

**type_:** `*nordlet.AccountsCreateLedgerRequestType` 
    
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

<details><summary><code>client.Ledger.AccountsUpdate(request) -> *nordlet.AccountsUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsUpdateLedgerRequest{
        ID: "id",
    }
client.Ledger.AccountsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**translations:** `map[string]*nordlet.AccountsUpdateLedgerRequestTranslationsValue` 
    
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

<details><summary><code>client.Ledger.AccountsApplyTemplate(request) -> *nordlet.AccountsApplyTemplateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsApplyTemplateLedgerRequest{}
client.Ledger.AccountsApplyTemplate(
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

<details><summary><code>client.Ledger.AccountsSwitchChart(request) -> *nordlet.AccountsSwitchChartLedgerResponse</code></summary>
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
request := &nordlet.AccountsSwitchChartLedgerRequest{}
client.Ledger.AccountsSwitchChart(
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

<details><summary><code>client.Ledger.PeriodsList(request) -> *nordlet.PeriodsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PeriodsListLedgerRequest{}
client.Ledger.PeriodsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.PeriodsListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PeriodsListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.PeriodsLock(request) -> *nordlet.PeriodsLockLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PeriodsLockLedgerRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Ledger.PeriodsLock(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.PeriodsUnlock(request) -> *nordlet.PeriodsUnlockLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PeriodsUnlockLedgerRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Ledger.PeriodsUnlock(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.JournalTransactionsList(request) -> *nordlet.JournalTransactionsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JournalTransactionsListLedgerRequest{}
client.Ledger.JournalTransactionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.JournalTransactionsListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.JournalTransactionsListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.CostCentersCreate(request) -> *nordlet.CostCentersCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCentersCreateLedgerRequest{
        Code: "code",
        Name: "name",
    }
client.Ledger.CostCentersCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.CostCentersUpdate(request) -> *nordlet.CostCentersUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCentersUpdateLedgerRequest{
        ID: "id",
    }
client.Ledger.CostCentersUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.CostCentersList(request) -> *nordlet.CostCentersListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCentersListLedgerRequest{}
client.Ledger.CostCentersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.CostCentersListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.CostCentersListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.CostCenterGroupsCreate(request) -> *nordlet.CostCenterGroupsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterGroupsCreateLedgerRequest{
        Code: "code",
        Name: "name",
    }
client.Ledger.CostCenterGroupsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.CostCenterGroupsUpdate(request) -> *nordlet.CostCenterGroupsUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterGroupsUpdateLedgerRequest{
        ID: "id",
    }
client.Ledger.CostCenterGroupsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.CostCenterGroupsDelete(request) -> *nordlet.CostCenterGroupsDeleteLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterGroupsDeleteLedgerRequest{
        ID: "id",
    }
client.Ledger.CostCenterGroupsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.CostCenterGroupsList(request) -> *nordlet.CostCenterGroupsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterGroupsListLedgerRequest{}
client.Ledger.CostCenterGroupsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.CostCenterGroupsListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.CostCenterGroupsListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.PostingRulesList(request) -> *nordlet.PostingRulesListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostingRulesListLedgerRequest{}
client.Ledger.PostingRulesList(
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

<details><summary><code>client.Ledger.PostingRulesUpdate(request) -> *nordlet.PostingRulesUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PostingRulesUpdateLedgerRequest{
        Rules: []*nordlet.PostingRulesUpdateLedgerRequestRulesItem{
            &nordlet.PostingRulesUpdateLedgerRequestRulesItem{
                Key: nordlet.PostingRulesUpdateLedgerRequestRulesItemKeySalesReceivable,
            },
        },
    }
client.Ledger.PostingRulesUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rules:** `[]*nordlet.PostingRulesUpdateLedgerRequestRulesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.OwnersCreate(request) -> *nordlet.OwnersCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OwnersCreateLedgerRequest{
        Name: "name",
    }
client.Ledger.OwnersCreate(
        context.TODO(),
        request,
    )
}
```
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

**sharesType:** `*nordlet.OwnersCreateLedgerRequestSharesType` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `*nordlet.OwnersCreateLedgerRequestPartnerLiability` 
    
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

**address:** `*nordlet.OwnersCreateLedgerRequestAddress` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.OwnersUpdate(request) -> *nordlet.OwnersUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OwnersUpdateLedgerRequest{
        ID: "id",
    }
client.Ledger.OwnersUpdate(
        context.TODO(),
        request,
    )
}
```
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

**sharesType:** `*nordlet.OwnersUpdateLedgerRequestSharesType` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `*nordlet.OwnersUpdateLedgerRequestPartnerLiability` 
    
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

**address:** `*nordlet.OwnersUpdateLedgerRequestAddress` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.OwnersDelete(request) -> *nordlet.OwnersDeleteLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OwnersDeleteLedgerRequest{
        ID: "id",
    }
client.Ledger.OwnersDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.OwnersList(request) -> *nordlet.OwnersListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OwnersListLedgerRequest{}
client.Ledger.OwnersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.OwnersListLedgerRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.OwnersListLedgerRequestFilterItem` 
    
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

<details><summary><code>client.Ledger.JournalTransactionsGet(request) -> *nordlet.JournalTransactionsGetLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JournalTransactionsGetLedgerRequest{
        ID: "id",
    }
client.Ledger.JournalTransactionsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ledger.JournalTransactionsCreate(request) -> *nordlet.JournalTransactionsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JournalTransactionsCreateLedgerRequest{
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Entries: []*nordlet.JournalTransactionsCreateLedgerRequestEntriesItem{
            &nordlet.JournalTransactionsCreateLedgerRequestEntriesItem{
                AccountCode: "accountCode",
            },
        },
    }
client.Ledger.JournalTransactionsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**entries:** `[]*nordlet.JournalTransactionsCreateLedgerRequestEntriesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.StatementRowsSchemes(request) -> *nordlet.StatementRowsSchemesLedgerResponse</code></summary>
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
request := &nordlet.StatementRowsSchemesLedgerRequest{}
client.Ledger.StatementRowsSchemes(
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

<details><summary><code>client.Ledger.StatementRowsList(request) -> *nordlet.StatementRowsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatementRowsListLedgerRequest{
        Scheme: "scheme",
    }
client.Ledger.StatementRowsList(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ledger.StatementRowsSet(request) -> *nordlet.StatementRowsSetLedgerResponse</code></summary>
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
request := &nordlet.StatementRowsSetLedgerRequest{
        Scheme: "scheme",
        AccountCode: "accountCode",
    }
client.Ledger.StatementRowsSet(
        context.TODO(),
        request,
    )
}
```
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

## Officers
<details><summary><code>client.Officers.List(request) -> *nordlet.ListOfficersResponse</code></summary>
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
request := &nordlet.ListOfficersRequest{}
client.Officers.List(
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

<details><summary><code>client.Officers.Create(request) -> *nordlet.CreateOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateOfficersRequest{
        Name: "name",
        Role: nordlet.CreateOfficersRequestRoleDirector,
    }
client.Officers.Create(
        context.TODO(),
        request,
    )
}
```
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

**role:** `*nordlet.CreateOfficersRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**appointedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `*time.Time` 
    
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

<details><summary><code>client.Officers.Update(request) -> *nordlet.UpdateOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateOfficersRequest{
        ID: "id",
        Name: "name",
        Role: nordlet.UpdateOfficersRequestRoleDirector,
    }
client.Officers.Update(
        context.TODO(),
        request,
    )
}
```
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

**role:** `*nordlet.UpdateOfficersRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**appointedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `*time.Time` 
    
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

<details><summary><code>client.Officers.Delete(request) -> *nordlet.DeleteOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteOfficersRequest{
        ID: "id",
    }
client.Officers.Delete(
        context.TODO(),
        request,
    )
}
```
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

## migration
<details><summary><code>client.Migration.BooksValidate(request) -> *nordlet.BooksValidateMigrationResponse</code></summary>
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
request := &nordlet.BooksValidateMigrationRequest{
        CutoverDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Migration.BooksValidate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `[]*nordlet.BooksValidateMigrationRequestAccountsItem` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `[]*nordlet.BooksValidateMigrationRequestPartnersItem` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.BooksValidateMigrationRequestItemsItem` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `*nordlet.BooksValidateMigrationRequestOpeningBalances` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `[]*nordlet.BooksValidateMigrationRequestJournalItem` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `[]*nordlet.BooksValidateMigrationRequestOpenReceivablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `[]*nordlet.BooksValidateMigrationRequestOpenPayablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `[]*nordlet.BooksValidateMigrationRequestAssetGroupsItem` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `[]*nordlet.BooksValidateMigrationRequestFixedAssetsItem` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `[]*nordlet.BooksValidateMigrationRequestStockItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Migration.BooksImport(request) -> *nordlet.BooksImportMigrationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Brings a company over from another system in one call: chart of accounts, partners, items, opening balances (or the full journal history), open customer and supplier invoices, fixed assets with their accumulated depreciation, and stock on hand. The whole package is written in one database transaction - if any row fails, nothing is stored.
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
request := &nordlet.BooksImportMigrationRequest{
        CutoverDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Migration.BooksImport(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `[]*nordlet.BooksImportMigrationRequestAccountsItem` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `[]*nordlet.BooksImportMigrationRequestPartnersItem` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `[]*nordlet.BooksImportMigrationRequestItemsItem` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `*nordlet.BooksImportMigrationRequestOpeningBalances` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `[]*nordlet.BooksImportMigrationRequestJournalItem` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `[]*nordlet.BooksImportMigrationRequestOpenReceivablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `[]*nordlet.BooksImportMigrationRequestOpenPayablesItem` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `[]*nordlet.BooksImportMigrationRequestAssetGroupsItem` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `[]*nordlet.BooksImportMigrationRequestFixedAssetsItem` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `[]*nordlet.BooksImportMigrationRequestStockItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## assets
<details><summary><code>client.Assets.GroupsCreate(request) -> *nordlet.GroupsCreateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsCreateAssetsRequest{
        Code: "code",
        Name: "name",
        AssetAccountCode: "assetAccountCode",
        DepreciationAccountCode: "depreciationAccountCode",
    }
client.Assets.GroupsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Assets.GroupsList(request) -> *nordlet.GroupsListAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsListAssetsRequest{}
client.Assets.GroupsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.GroupsListAssetsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.GroupsListAssetsRequestFilterItem` 
    
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

<details><summary><code>client.Assets.AssetsCreate(request) -> *nordlet.AssetsCreateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssetsCreateAssetsRequest{
        GroupID: "groupId",
        Code: "code",
        Name: "name",
        AcquisitionDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        AcquisitionCost: "121.0000",
    }
client.Assets.AssetsCreate(
        context.TODO(),
        request,
    )
}
```
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

**acquisitionDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `*time.Time` 
    
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

**documents:** `[]*nordlet.AssetsCreateAssetsRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.AssetsUpdate(request) -> *nordlet.AssetsUpdateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssetsUpdateAssetsRequest{
        ID: "id",
    }
client.Assets.AssetsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**acquisitionDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `*time.Time` 
    
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

**documents:** `[]*nordlet.AssetsUpdateAssetsRequestDocumentsItem` 
    
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

<details><summary><code>client.Assets.AssetsInputVat(request) -> *nordlet.AssetsInputVatAssetsResponse</code></summary>
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
request := &nordlet.AssetsInputVatAssetsRequest{
        ID: "id",
        InputVatRealEstate: true,
        InputVatUseChanges: []*nordlet.AssetsInputVatAssetsRequestInputVatUseChangesItem{
            &nordlet.AssetsInputVatAssetsRequestInputVatUseChangesItem{
                Year: int64(1000000),
                Percent: "121.00",
                Reason: nordlet.AssetsInputVatAssetsRequestInputVatUseChangesItemReasonUseChange,
            },
        },
    }
client.Assets.AssetsInputVat(
        context.TODO(),
        request,
    )
}
```
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

**inputVatFirstUseDate:** `*time.Time` 
    
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

**inputVatUseChanges:** `[]*nordlet.AssetsInputVatAssetsRequestInputVatUseChangesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Assets.AssetsGet(request) -> *nordlet.AssetsGetAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssetsGetAssetsRequest{
        ID: "id",
    }
client.Assets.AssetsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Assets.AssetsList(request) -> *nordlet.AssetsListAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssetsListAssetsRequest{}
client.Assets.AssetsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AssetsListAssetsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AssetsListAssetsRequestFilterItem` 
    
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

<details><summary><code>client.Assets.AssetsModernize(request) -> *nordlet.AssetsModernizeAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssetsModernizeAssetsRequest{
        ID: "id",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Amount: "121.0000",
    }
client.Assets.AssetsModernize(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Assets.AssetsDispose(request) -> *nordlet.AssetsDisposeAssetsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Dispose of a fixed asset (sold, scrapped or written off). Removes its cost and accumulated depreciation, books the net book value as a disposal loss and the proceeds as a disposal gain (posting rules assets.disposalLoss, assets.disposalGain, assets.disposalProceeds), and stops its depreciation. Depreciation must be posted for every month before the disposal month.
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
request := &nordlet.AssetsDisposeAssetsRequest{
        ID: "id",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Reason: nordlet.AssetsDisposeAssetsRequestReasonSold,
    }
client.Assets.AssetsDispose(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `*nordlet.AssetsDisposeAssetsRequestReason` 
    
</dd>
</dl>

<dl>
<dd>

**proceeds:** `*string` — Sale price excluding VAT; 0 when scrapped or written off
    
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

<details><summary><code>client.Assets.DepreciationPreview(request) -> *nordlet.DepreciationPreviewAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DepreciationPreviewAssetsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Assets.DepreciationPreview(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Assets.DepreciationPost(request) -> *nordlet.DepreciationPostAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DepreciationPostAssetsRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Assets.DepreciationPost(
        context.TODO(),
        request,
    )
}
```
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

## hr
<details><summary><code>client.Hr.PositionsCreate(request) -> *nordlet.PositionsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PositionsCreateHrRequest{
        Name: "name",
    }
client.Hr.PositionsCreate(
        context.TODO(),
        request,
    )
}
```
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

**translations:** `map[string]*nordlet.PositionsCreateHrRequestTranslationsValue` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PositionsUpdate(request) -> *nordlet.PositionsUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PositionsUpdateHrRequest{
        ID: "id",
    }
client.Hr.PositionsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**translations:** `map[string]*nordlet.PositionsUpdateHrRequestTranslationsValue` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.PositionsList(request) -> *nordlet.PositionsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PositionsListHrRequest{}
client.Hr.PositionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.PositionsListHrRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.PositionsListHrRequestFilterItem` 
    
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

<details><summary><code>client.Hr.EmployeesCreate(request) -> *nordlet.EmployeesCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesCreateHrRequest{
        FirstName: "firstName",
        LastName: "lastName",
    }
client.Hr.EmployeesCreate(
        context.TODO(),
        request,
    )
}
```
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

**birthDate:** `*time.Time` 
    
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

**address:** `*nordlet.EmployeesCreateHrRequestAddress` 
    
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

**socialInsuranceStart:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `*time.Time` 
    
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

**attributes:** `[]*nordlet.EmployeesCreateHrRequestAttributesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.EmployeesUpdate(request) -> *nordlet.EmployeesUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesUpdateHrRequest{
        ID: "id",
    }
client.Hr.EmployeesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**birthDate:** `*time.Time` 
    
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

**address:** `*nordlet.EmployeesUpdateHrRequestAddress` 
    
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

**socialInsuranceStart:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `*time.Time` 
    
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

**attributes:** `[]*nordlet.EmployeesUpdateHrRequestAttributesItem` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**terminationDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.EmployeesUpdateHrRequestStatus` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.EmployeesGet(request) -> *nordlet.EmployeesGetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesGetHrRequest{
        ID: "id",
    }
client.Hr.EmployeesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.EmployeesFields(request) -> *nordlet.EmployeesFieldsHrResponse</code></summary>
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
request := &nordlet.EmployeesFieldsHrRequest{}
client.Hr.EmployeesFields(
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

<details><summary><code>client.Hr.EmployeesList(request) -> *nordlet.EmployeesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesListHrRequest{}
client.Hr.EmployeesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.EmployeesListHrRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.EmployeesListHrRequestFilterItem` 
    
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

<details><summary><code>client.Hr.EmployeesDelete(request) -> *nordlet.EmployeesDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesDeleteHrRequest{
        ID: "id",
    }
client.Hr.EmployeesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.EmployeesAnonymize(request) -> *nordlet.EmployeesAnonymizeHrResponse</code></summary>
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
request := &nordlet.EmployeesAnonymizeHrRequest{
        ID: "id",
    }
client.Hr.EmployeesAnonymize(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.ContractsCreate(request) -> *nordlet.ContractsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContractsCreateHrRequest{
        EmployeeID: "employeeId",
        StartDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        BaseSalary: "121.0000",
    }
client.Hr.ContractsCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ContractsCreateHrRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**startDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**baseSalary:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**salaryType:** `*nordlet.ContractsCreateHrRequestSalaryType` 
    
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

<details><summary><code>client.Hr.ContractsEnd(request) -> *nordlet.ContractsEndHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContractsEndHrRequest{
        ID: "id",
        EndDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Hr.ContractsEnd(
        context.TODO(),
        request,
    )
}
```
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

**endDate:** `time.Time` 
    
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

<details><summary><code>client.Hr.ContractsList(request) -> *nordlet.ContractsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ContractsListHrRequest{}
client.Hr.ContractsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ContractsListHrRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ContractsListHrRequestFilterItem` 
    
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

<details><summary><code>client.Hr.LeaveBalancesSet(request) -> *nordlet.LeaveBalancesSetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LeaveBalancesSetHrRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        EntitledDays: "121.00",
    }
client.Hr.LeaveBalancesSet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.LeaveBalancesList(request) -> *nordlet.LeaveBalancesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LeaveBalancesListHrRequest{}
client.Hr.LeaveBalancesList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.IncapacityCertificatesCreate(request) -> *nordlet.IncapacityCertificatesCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IncapacityCertificatesCreateHrRequest{
        EmployeeID: "employeeId",
        Number: "number",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Hr.IncapacityCertificatesCreate(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Hr.IncapacityCertificatesList(request) -> *nordlet.IncapacityCertificatesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IncapacityCertificatesListHrRequest{}
client.Hr.IncapacityCertificatesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.IncapacityCertificatesListHrRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.IncapacityCertificatesListHrRequestFilterItem` 
    
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

<details><summary><code>client.Hr.EmployeesRecordsCreate(request) -> *nordlet.EmployeesRecordsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesRecordsCreateHrRequest{
        EmployeeID: "employeeId",
        Type: nordlet.EmployeesRecordsCreateHrRequestTypeEducation,
        Title: "title",
    }
client.Hr.EmployeesRecordsCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.EmployeesRecordsCreateHrRequestType` 
    
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

**issuedAt:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `*time.Time` 
    
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

<details><summary><code>client.Hr.EmployeesRecordsUpdate(request) -> *nordlet.EmployeesRecordsUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesRecordsUpdateHrRequest{
        ID: "id",
    }
client.Hr.EmployeesRecordsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.EmployeesRecordsUpdateHrRequestType` 
    
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

**issuedAt:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `*time.Time` 
    
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

<details><summary><code>client.Hr.EmployeesRecordsDelete(request) -> *nordlet.EmployeesRecordsDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesRecordsDeleteHrRequest{
        ID: "id",
    }
client.Hr.EmployeesRecordsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.EmployeesRecordsList(request) -> *nordlet.EmployeesRecordsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesRecordsListHrRequest{}
client.Hr.EmployeesRecordsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.EmployeesRecordsListHrRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.EmployeesRecordsListHrRequestFilterItem` 
    
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

<details><summary><code>client.Hr.EmployeesAttachmentsList(request) -> *nordlet.EmployeesAttachmentsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmployeesAttachmentsListHrRequest{
        EmployeeID: "employeeId",
    }
client.Hr.EmployeesAttachmentsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.TimesheetsGenerate(request) -> *nordlet.TimesheetsGenerateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimesheetsGenerateHrRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.TimesheetsGenerate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.TimesheetsUpsert(request) -> *nordlet.TimesheetsUpsertHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimesheetsUpsertHrRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        Month: int64(1000000),
        Days: []*nordlet.TimesheetsUpsertHrRequestDaysItem{
            &nordlet.TimesheetsUpsertHrRequestDaysItem{
                Day: int64(1000000),
                Hours: "121.00",
                Type: nordlet.TimesheetsUpsertHrRequestDaysItemTypeWork,
            },
        },
    }
client.Hr.TimesheetsUpsert(
        context.TODO(),
        request,
    )
}
```
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

**days:** `[]*nordlet.TimesheetsUpsertHrRequestDaysItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Hr.TimesheetsGet(request) -> *nordlet.TimesheetsGetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimesheetsGetHrRequest{
        EmployeeID: "employeeId",
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.TimesheetsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.TimesheetsList(request) -> *nordlet.TimesheetsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimesheetsListHrRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Hr.TimesheetsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Hr.TimesheetsDelete(request) -> *nordlet.TimesheetsDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimesheetsDeleteHrRequest{
        ID: "id",
    }
client.Hr.TimesheetsDelete(
        context.TODO(),
        request,
    )
}
```
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

## fleet
<details><summary><code>client.Fleet.VehiclesCreate(request) -> *nordlet.VehiclesCreateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VehiclesCreateFleetRequest{
        PlateNumber: "plateNumber",
        Make: "make",
        Model: "model",
    }
client.Fleet.VehiclesCreate(
        context.TODO(),
        request,
    )
}
```
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

**fuelType:** `*nordlet.VehiclesCreateFleetRequestFuelType` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `*time.Time` 
    
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

**technicalInspectionDue:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `[]*nordlet.VehiclesCreateFleetRequestDocumentsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.VehiclesUpdate(request) -> *nordlet.VehiclesUpdateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VehiclesUpdateFleetRequest{
        ID: "id",
    }
client.Fleet.VehiclesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**fuelType:** `*nordlet.VehiclesUpdateFleetRequestFuelType` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `*time.Time` 
    
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

**technicalInspectionDue:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.VehiclesUpdateFleetRequestStatus` 
    
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

<details><summary><code>client.Fleet.VehiclesGet(request) -> *nordlet.VehiclesGetFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VehiclesGetFleetRequest{
        ID: "id",
    }
client.Fleet.VehiclesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Fleet.VehiclesList(request) -> *nordlet.VehiclesListFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VehiclesListFleetRequest{}
client.Fleet.VehiclesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.VehiclesListFleetRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.VehiclesListFleetRequestFilterItem` 
    
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

<details><summary><code>client.Fleet.AssignmentsCreate(request) -> *nordlet.AssignmentsCreateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssignmentsCreateFleetRequest{
        VehicleID: "vehicleId",
        EmployeeID: "employeeId",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Fleet.AssignmentsCreate(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `*time.Time` 
    
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

<details><summary><code>client.Fleet.AssignmentsEnd(request) -> *nordlet.AssignmentsEndFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssignmentsEndFleetRequest{
        ID: "id",
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Fleet.AssignmentsEnd(
        context.TODO(),
        request,
    )
}
```
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

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Fleet.AssignmentsList(request) -> *nordlet.AssignmentsListFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AssignmentsListFleetRequest{}
client.Fleet.AssignmentsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AssignmentsListFleetRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AssignmentsListFleetRequestFilterItem` 
    
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

<details><summary><code>client.Fleet.NaturaPreview(request) -> *nordlet.NaturaPreviewFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.NaturaPreviewFleetRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Fleet.NaturaPreview(
        context.TODO(),
        request,
    )
}
```
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

## payroll
<details><summary><code>client.Payroll.DepartmentsCreate(request) -> *nordlet.DepartmentsCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DepartmentsCreatePayrollRequest{
        Code: "code",
        Name: "name",
    }
client.Payroll.DepartmentsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.DepartmentsList(request) -> *nordlet.DepartmentsListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DepartmentsListPayrollRequest{}
client.Payroll.DepartmentsList(
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

<details><summary><code>client.Payroll.SchedulesCreate(request) -> *nordlet.SchedulesCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SchedulesCreatePayrollRequest{
        Code: "code",
        Name: "name",
    }
client.Payroll.SchedulesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.SchedulesList(request) -> *nordlet.SchedulesListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SchedulesListPayrollRequest{}
client.Payroll.SchedulesList(
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

<details><summary><code>client.Payroll.Calc(request) -> *nordlet.CalcPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CalcPayrollRequest{
        TaxableBase: "121.00",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Payroll.Calc(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Payroll.RunsCreate(request) -> *nordlet.RunsCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RunsCreatePayrollRequest{
        Year: int64(1000000),
        Month: int64(1000000),
    }
client.Payroll.RunsCreate(
        context.TODO(),
        request,
    )
}
```
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

**grossOverrides:** `[]*nordlet.RunsCreatePayrollRequestGrossOverridesItem` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `[]*nordlet.RunsCreatePayrollRequestLinesItem` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**payDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Payroll.RunsGet(request) -> *nordlet.RunsGetPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RunsGetPayrollRequest{
        ID: "id",
    }
client.Payroll.RunsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.RunsList(request) -> *nordlet.RunsListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RunsListPayrollRequest{}
client.Payroll.RunsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.RunsListPayrollRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.RunsListPayrollRequestFilterItem` 
    
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

<details><summary><code>client.Payroll.LinesAttendance(request) -> *nordlet.LinesAttendancePayrollResponse</code></summary>
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
request := &nordlet.LinesAttendancePayrollRequest{
        ID: "id",
    }
client.Payroll.LinesAttendance(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.RunsApprove(request) -> *nordlet.RunsApprovePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RunsApprovePayrollRequest{
        ID: "id",
    }
client.Payroll.RunsApprove(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.RunsCancel(request) -> *nordlet.RunsCancelPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RunsCancelPayrollRequest{
        ID: "id",
    }
client.Payroll.RunsCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Payroll.PaymentsExport(request) -> *nordlet.PaymentsExportPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PaymentsExportPayrollRequest{
        RunID: "runId",
        BankAccountID: "bankAccountId",
    }
client.Payroll.PaymentsExport(
        context.TODO(),
        request,
    )
}
```
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

**executionDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.PaymentsExportPayrollRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## agreements
<details><summary><code>client.Agreements.TypesCreate(request) -> *nordlet.TypesCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesCreateAgreementsRequest{
        Code: "code",
        Name: "name",
    }
client.Agreements.TypesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Agreements.TypesList(request) -> *nordlet.TypesListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TypesListAgreementsRequest{}
client.Agreements.TypesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.TypesListAgreementsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.TypesListAgreementsRequestFilterItem` 
    
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

<details><summary><code>client.Agreements.AgreementsCreate(request) -> *nordlet.AgreementsCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsCreateAgreementsRequest{
        Number: "number",
        StartDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Agreements.AgreementsCreate(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.AgreementsCreateAgreementsRequestKind` 
    
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

**startDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*time.Time` 
    
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

**billingPeriod:** `*nordlet.AgreementsCreateAgreementsRequestBillingPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.AgreementsCreateAgreementsRequestStatus` 
    
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

**items:** `[]*nordlet.AgreementsCreateAgreementsRequestItemsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.AgreementsGet(request) -> *nordlet.AgreementsGetAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsGetAgreementsRequest{
        ID: "id",
    }
client.Agreements.AgreementsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Agreements.AgreementsUpdate(request) -> *nordlet.AgreementsUpdateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsUpdateAgreementsRequest{
        ID: "id",
    }
client.Agreements.AgreementsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**kind:** `*nordlet.AgreementsUpdateAgreementsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `*time.Time` 
    
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

**billingPeriod:** `*nordlet.AgreementsUpdateAgreementsRequestBillingPeriod` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `*nordlet.AgreementsUpdateAgreementsRequestStatus` 
    
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

<details><summary><code>client.Agreements.AgreementsDelete(request) -> *nordlet.AgreementsDeleteAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsDeleteAgreementsRequest{
        ID: "id",
    }
client.Agreements.AgreementsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Agreements.AgreementsList(request) -> *nordlet.AgreementsListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsListAgreementsRequest{}
client.Agreements.AgreementsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AgreementsListAgreementsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AgreementsListAgreementsRequestFilterItem` 
    
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

<details><summary><code>client.Agreements.AgreementsGenerateInvoice(request) -> *nordlet.AgreementsGenerateInvoiceAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsGenerateInvoiceAgreementsRequest{
        ID: "id",
    }
client.Agreements.AgreementsGenerateInvoice(
        context.TODO(),
        request,
    )
}
```
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

**asOfDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.AgreementsBillingRun(request) -> *nordlet.AgreementsBillingRunAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AgreementsBillingRunAgreementsRequest{}
client.Agreements.AgreementsBillingRun(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOfDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Agreements.InsurancePoliciesCreate(request) -> *nordlet.InsurancePoliciesCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InsurancePoliciesCreateAgreementsRequest{
        PolicyNumber: "policyNumber",
        InsuredObject: "insuredObject",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Agreements.InsurancePoliciesCreate(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Agreements.InsurancePoliciesList(request) -> *nordlet.InsurancePoliciesListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InsurancePoliciesListAgreementsRequest{}
client.Agreements.InsurancePoliciesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.InsurancePoliciesListAgreementsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.InsurancePoliciesListAgreementsRequestFilterItem` 
    
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

<details><summary><code>client.Agreements.InsurancePoliciesDelete(request) -> *nordlet.InsurancePoliciesDeleteAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InsurancePoliciesDeleteAgreementsRequest{
        ID: "id",
    }
client.Agreements.InsurancePoliciesDelete(
        context.TODO(),
        request,
    )
}
```
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

## inventory
<details><summary><code>client.Inventory.SettingsGet(request) -> *nordlet.SettingsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettingsGetInventoryRequest{}
client.Inventory.SettingsGet(
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

<details><summary><code>client.Inventory.SettingsUpdate(request) -> *nordlet.SettingsUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettingsUpdateInventoryRequest{
        NegativeStockPolicy: nordlet.SettingsUpdateInventoryRequestNegativeStockPolicyReject,
    }
client.Inventory.SettingsUpdate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**negativeStockPolicy:** `*nordlet.SettingsUpdateInventoryRequestNegativeStockPolicy` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.WarehousesCreate(request) -> *nordlet.WarehousesCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WarehousesCreateInventoryRequest{
        Code: "code",
        Name: "name",
    }
client.Inventory.WarehousesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.WarehousesList(request) -> *nordlet.WarehousesListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WarehousesListInventoryRequest{}
client.Inventory.WarehousesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.WarehousesListInventoryRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.WarehousesListInventoryRequestFilterItem` 
    
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

<details><summary><code>client.Inventory.StockReceive(request) -> *nordlet.StockReceiveInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockReceiveInventoryRequest{
        WarehouseID: "warehouseId",
        ItemID: "itemId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Quantity: "121.0000",
        UnitCost: "121.000000",
    }
client.Inventory.StockReceive(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

**expiryDate:** `*time.Time` 
    
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

<details><summary><code>client.Inventory.StockWriteOff(request) -> *nordlet.StockWriteOffInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockWriteOffInventoryRequest{
        WarehouseID: "warehouseId",
        ItemID: "itemId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Quantity: "121.0000",
    }
client.Inventory.StockWriteOff(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Inventory.StockTransfer(request) -> *nordlet.StockTransferInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockTransferInventoryRequest{
        FromWarehouseID: "fromWarehouseId",
        ToWarehouseID: "toWarehouseId",
        ItemID: "itemId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Quantity: "121.0000",
    }
client.Inventory.StockTransfer(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Inventory.StockTake(request) -> *nordlet.StockTakeInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockTakeInventoryRequest{
        WarehouseID: "warehouseId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Lines: []*nordlet.StockTakeInventoryRequestLinesItem{
            &nordlet.StockTakeInventoryRequestLinesItem{
                CountedQty: "121.0000",
            },
        },
    }
client.Inventory.StockTake(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

**lines:** `[]*nordlet.StockTakeInventoryRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Inventory.StockLevels(request) -> *nordlet.StockLevelsInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockLevelsInventoryRequest{}
client.Inventory.StockLevels(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.StockMovementsList(request) -> *nordlet.StockMovementsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockMovementsListInventoryRequest{}
client.Inventory.StockMovementsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.StockMovementsListInventoryRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.StockMovementsListInventoryRequestFilterItem` 
    
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

<details><summary><code>client.Inventory.LotsList(request) -> *nordlet.LotsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LotsListInventoryRequest{}
client.Inventory.LotsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.LotsListInventoryRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.LotsListInventoryRequestFilterItem` 
    
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

<details><summary><code>client.Inventory.LotsGet(request) -> *nordlet.LotsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LotsGetInventoryRequest{
        ID: "id",
    }
client.Inventory.LotsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.LotsUpdate(request) -> *nordlet.LotsUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LotsUpdateInventoryRequest{
        ID: "id",
    }
client.Inventory.LotsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**expiryDate:** `*time.Time` 
    
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

<details><summary><code>client.Inventory.LandedCostsCreate(request) -> *nordlet.LandedCostsCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LandedCostsCreateInventoryRequest{
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Amount: "121.000000",
    }
client.Inventory.LandedCostsCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**method:** `*nordlet.LandedCostsCreateInventoryRequestMethod` 
    
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

<details><summary><code>client.Inventory.LandedCostsGet(request) -> *nordlet.LandedCostsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LandedCostsGetInventoryRequest{
        ID: "id",
    }
client.Inventory.LandedCostsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.LandedCostsList(request) -> *nordlet.LandedCostsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LandedCostsListInventoryRequest{}
client.Inventory.LandedCostsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.LandedCostsListInventoryRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.LandedCostsListInventoryRequestFilterItem` 
    
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

<details><summary><code>client.Inventory.ReorderRulesCreate(request) -> *nordlet.ReorderRulesCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReorderRulesCreateInventoryRequest{
        ItemID: "itemId",
        MinQty: "121.0000",
    }
client.Inventory.ReorderRulesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.ReorderRulesUpdate(request) -> *nordlet.ReorderRulesUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReorderRulesUpdateInventoryRequest{
        ID: "id",
    }
client.Inventory.ReorderRulesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.ReorderRulesDelete(request) -> *nordlet.ReorderRulesDeleteInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReorderRulesDeleteInventoryRequest{
        ID: "id",
    }
client.Inventory.ReorderRulesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Inventory.ReorderRulesList(request) -> *nordlet.ReorderRulesListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReorderRulesListInventoryRequest{}
client.Inventory.ReorderRulesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ReorderRulesListInventoryRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ReorderRulesListInventoryRequestFilterItem` 
    
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

<details><summary><code>client.Inventory.ReorderRulesCheck(request) -> *nordlet.ReorderRulesCheckInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReorderRulesCheckInventoryRequest{}
client.Inventory.ReorderRulesCheck(
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

## production
<details><summary><code>client.Production.WorkCentersCreate(request) -> *nordlet.WorkCentersCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WorkCentersCreateProductionRequest{
        Code: "code",
        Name: "name",
    }
client.Production.WorkCentersCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.WorkCentersUpdate(request) -> *nordlet.WorkCentersUpdateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WorkCentersUpdateProductionRequest{
        ID: "id",
    }
client.Production.WorkCentersUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.WorkCentersList(request) -> *nordlet.WorkCentersListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WorkCentersListProductionRequest{}
client.Production.WorkCentersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.WorkCentersListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.WorkCentersListProductionRequestFilterItem` 
    
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

<details><summary><code>client.Production.RoutingsCreate(request) -> *nordlet.RoutingsCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RoutingsCreateProductionRequest{
        Code: "code",
        Name: "name",
        Operations: []*nordlet.RoutingsCreateProductionRequestOperationsItem{
            &nordlet.RoutingsCreateProductionRequestOperationsItem{
                Sequence: int64(1000000),
                Name: "name",
                WorkCenterID: "workCenterId",
            },
        },
    }
client.Production.RoutingsCreate(
        context.TODO(),
        request,
    )
}
```
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

**operations:** `[]*nordlet.RoutingsCreateProductionRequestOperationsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.RoutingsGet(request) -> *nordlet.RoutingsGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RoutingsGetProductionRequest{
        ID: "id",
    }
client.Production.RoutingsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.RoutingsList(request) -> *nordlet.RoutingsListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.RoutingsListProductionRequest{}
client.Production.RoutingsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.RoutingsListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.RoutingsListProductionRequestFilterItem` 
    
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

<details><summary><code>client.Production.MaintenanceCreate(request) -> *nordlet.MaintenanceCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MaintenanceCreateProductionRequest{
        WorkCenterID: "workCenterId",
        Type: nordlet.MaintenanceCreateProductionRequestTypePreventive,
        PlannedDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Production.MaintenanceCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.MaintenanceCreateProductionRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**plannedDate:** `time.Time` 
    
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

<details><summary><code>client.Production.MaintenanceComplete(request) -> *nordlet.MaintenanceCompleteProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MaintenanceCompleteProductionRequest{
        ID: "id",
        CompletedDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Production.MaintenanceComplete(
        context.TODO(),
        request,
    )
}
```
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

**completedDate:** `time.Time` 
    
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

<details><summary><code>client.Production.MaintenanceCancel(request) -> *nordlet.MaintenanceCancelProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MaintenanceCancelProductionRequest{
        ID: "id",
    }
client.Production.MaintenanceCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.MaintenanceList(request) -> *nordlet.MaintenanceListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MaintenanceListProductionRequest{}
client.Production.MaintenanceList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.MaintenanceListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.MaintenanceListProductionRequestFilterItem` 
    
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

<details><summary><code>client.Production.BomsCreate(request) -> *nordlet.BomsCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BomsCreateProductionRequest{
        Code: "code",
        Name: "name",
        FinishedItemID: "finishedItemId",
        Lines: []*nordlet.BomsCreateProductionRequestLinesItem{
            &nordlet.BomsCreateProductionRequestLinesItem{
                ComponentItemID: "componentItemId",
                Quantity: "121.0000",
            },
        },
    }
client.Production.BomsCreate(
        context.TODO(),
        request,
    )
}
```
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

**lines:** `[]*nordlet.BomsCreateProductionRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Production.BomsGet(request) -> *nordlet.BomsGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BomsGetProductionRequest{
        ID: "id",
    }
client.Production.BomsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.BomsList(request) -> *nordlet.BomsListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BomsListProductionRequest{}
client.Production.BomsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.BomsListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.BomsListProductionRequestFilterItem` 
    
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

<details><summary><code>client.Production.OrdersCreate(request) -> *nordlet.OrdersCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCreateProductionRequest{
        BomID: "bomId",
        WarehouseID: "warehouseId",
        Quantity: "121.0000",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Production.OrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.OrdersCreateProductionRequestType` 
    
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Production.OrdersRecordOperation(request) -> *nordlet.OrdersRecordOperationProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersRecordOperationProductionRequest{
        ID: "id",
        ActualMinutes: "121.00",
    }
client.Production.OrdersRecordOperation(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.QualityChecksAdd(request) -> *nordlet.QualityChecksAddProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.QualityChecksAddProductionRequest{
        OrderID: "orderId",
        Name: "name",
    }
client.Production.QualityChecksAdd(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.QualityChecksRecord(request) -> *nordlet.QualityChecksRecordProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.QualityChecksRecordProductionRequest{
        ID: "id",
        Result: nordlet.QualityChecksRecordProductionRequestResultPassed,
    }
client.Production.QualityChecksRecord(
        context.TODO(),
        request,
    )
}
```
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

**result:** `*nordlet.QualityChecksRecordProductionRequestResult` 
    
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

<details><summary><code>client.Production.QualityChecksList(request) -> *nordlet.QualityChecksListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.QualityChecksListProductionRequest{}
client.Production.QualityChecksList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.QualityChecksListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.QualityChecksListProductionRequestFilterItem` 
    
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

<details><summary><code>client.Production.OrdersComplete(request) -> *nordlet.OrdersCompleteProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCompleteProductionRequest{
        ID: "id",
    }
client.Production.OrdersComplete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.OrdersGet(request) -> *nordlet.OrdersGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersGetProductionRequest{
        ID: "id",
    }
client.Production.OrdersGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Production.OrdersList(request) -> *nordlet.OrdersListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersListProductionRequest{}
client.Production.OrdersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.OrdersListProductionRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.OrdersListProductionRequestFilterItem` 
    
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

## ecommerce
<details><summary><code>client.Ecommerce.OrdersCreate(request) -> *nordlet.OrdersCreateEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCreateEcommerceRequest{
        Lines: []*nordlet.OrdersCreateEcommerceRequestLinesItem{
            &nordlet.OrdersCreateEcommerceRequestLinesItem{
                Description: "description",
                Quantity: "121.0000",
                UnitPriceExclVat: "121.0000",
            },
        },
    }
client.Ecommerce.OrdersCreate(
        context.TODO(),
        request,
    )
}
```
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

**partner:** `*nordlet.OrdersCreateEcommerceRequestPartner` 
    
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

**lines:** `[]*nordlet.OrdersCreateEcommerceRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Ecommerce.OrdersGet(request) -> *nordlet.OrdersGetEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersGetEcommerceRequest{
        ID: "id",
    }
client.Ecommerce.OrdersGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ecommerce.OrdersList(request) -> *nordlet.OrdersListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersListEcommerceRequest{}
client.Ecommerce.OrdersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.OrdersListEcommerceRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.OrdersListEcommerceRequestFilterItem` 
    
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

<details><summary><code>client.Ecommerce.OrdersReserve(request) -> *nordlet.OrdersReserveEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersReserveEcommerceRequest{
        ID: "id",
    }
client.Ecommerce.OrdersReserve(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ecommerce.OrdersFulfill(request) -> *nordlet.OrdersFulfillEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersFulfillEcommerceRequest{
        ID: "id",
    }
client.Ecommerce.OrdersFulfill(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
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

<details><summary><code>client.Ecommerce.OrdersCancel(request) -> *nordlet.OrdersCancelEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCancelEcommerceRequest{
        ID: "id",
    }
client.Ecommerce.OrdersCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ecommerce.ProductsList(request) -> *nordlet.ProductsListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ProductsListEcommerceRequest{}
client.Ecommerce.ProductsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Ecommerce.StockList(request) -> *nordlet.StockListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockListEcommerceRequest{}
client.Ecommerce.StockList(
        context.TODO(),
        request,
    )
}
```
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

## cash
<details><summary><code>client.Cash.OrdersCreate(request) -> *nordlet.OrdersCreateCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersCreateCashRequest{
        Type: nordlet.OrdersCreateCashRequestTypeReceipt,
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Amount: "121.0000",
        Purpose: "purpose",
        CounterAccountCode: "counterAccountCode",
    }
client.Cash.OrdersCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type_:** `*nordlet.OrdersCreateCashRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `time.Time` 
    
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

<details><summary><code>client.Cash.OrdersGet(request) -> *nordlet.OrdersGetCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersGetCashRequest{
        ID: "id",
    }
client.Cash.OrdersGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Cash.OrdersList(request) -> *nordlet.OrdersListCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OrdersListCashRequest{}
client.Cash.OrdersList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.OrdersListCashRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.OrdersListCashRequestFilterItem` 
    
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

<details><summary><code>client.Cash.Balance(request) -> *nordlet.BalanceCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.BalanceCashRequest{}
client.Cash.Balance(
        context.TODO(),
        request,
    )
}
```
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

**asOf:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Cash.AdvanceHoldersBalances(request) -> *nordlet.AdvanceHoldersBalancesCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AdvanceHoldersBalancesCashRequest{}
client.Cash.AdvanceHoldersBalances(
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

## projects
<details><summary><code>client.Projects.Create(request) -> *nordlet.CreateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateProjectsRequest{
        Code: "code",
        Name: "name",
    }
client.Projects.Create(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Projects.Update(request) -> *nordlet.UpdateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateProjectsRequest{
        ID: "id",
    }
client.Projects.Update(
        context.TODO(),
        request,
    )
}
```
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

**status:** `*nordlet.UpdateProjectsRequestStatus` 
    
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

<details><summary><code>client.Projects.Get(request) -> *nordlet.GetProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetProjectsRequest{
        ID: "id",
    }
client.Projects.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Projects.List(request) -> *nordlet.ListProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListProjectsRequest{}
client.Projects.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListProjectsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListProjectsRequestFilterItem` 
    
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

<details><summary><code>client.Projects.TimeEntriesCreate(request) -> *nordlet.TimeEntriesCreateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimeEntriesCreateProjectsRequest{
        ProjectID: "projectId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Hours: "121.00",
    }
client.Projects.TimeEntriesCreate(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

<details><summary><code>client.Projects.TimeEntriesUpdate(request) -> *nordlet.TimeEntriesUpdateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimeEntriesUpdateProjectsRequest{
        ID: "id",
    }
client.Projects.TimeEntriesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
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

<details><summary><code>client.Projects.TimeEntriesDelete(request) -> *nordlet.TimeEntriesDeleteProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimeEntriesDeleteProjectsRequest{
        ID: "id",
    }
client.Projects.TimeEntriesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Projects.TimeEntriesList(request) -> *nordlet.TimeEntriesListProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimeEntriesListProjectsRequest{}
client.Projects.TimeEntriesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.TimeEntriesListProjectsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.TimeEntriesListProjectsRequestFilterItem` 
    
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

<details><summary><code>client.Projects.TimeEntriesBill(request) -> *nordlet.TimeEntriesBillProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TimeEntriesBillProjectsRequest{
        ProjectID: "projectId",
    }
client.Projects.TimeEntriesBill(
        context.TODO(),
        request,
    )
}
```
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

**dateFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*time.Time` 
    
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

**issueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**groupBy:** `*nordlet.TimeEntriesBillProjectsRequestGroupBy` 
    
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

<details><summary><code>client.Projects.Report(request) -> *nordlet.ReportProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReportProjectsRequest{}
client.Projects.Report(
        context.TODO(),
        request,
    )
}
```
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

**dateFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## transport
<details><summary><code>client.Transport.WaybillsCreate(request) -> *nordlet.WaybillsCreateTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsCreateTransportRequest{
        ConsigneePartnerID: "consigneePartnerId",
        DispatchAt: nordlet.MustParseDateTime(
            "2024-01-15T09:30:00Z",
        ),
        LoadAddress: "loadAddress",
        UnloadAddress: "unloadAddress",
    }
client.Transport.WaybillsCreate(
        context.TODO(),
        request,
    )
}
```
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

**documentDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.WaybillsCreateTransportRequestLinesItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Transport.WaybillsUpdate(request) -> *nordlet.WaybillsUpdateTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsUpdateTransportRequest{
        ID: "id",
    }
client.Transport.WaybillsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**documentDate:** `*time.Time` 
    
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

**lines:** `[]*nordlet.WaybillsUpdateTransportRequestLinesItem` 
    
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

<details><summary><code>client.Transport.WaybillsIssue(request) -> *nordlet.WaybillsIssueTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsIssueTransportRequest{
        ID: "id",
    }
client.Transport.WaybillsIssue(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Transport.WaybillsCancel(request) -> *nordlet.WaybillsCancelTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsCancelTransportRequest{
        ID: "id",
    }
client.Transport.WaybillsCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Transport.WaybillsGet(request) -> *nordlet.WaybillsGetTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsGetTransportRequest{
        ID: "id",
    }
client.Transport.WaybillsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Transport.WaybillsList(request) -> *nordlet.WaybillsListTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WaybillsListTransportRequest{}
client.Transport.WaybillsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.WaybillsListTransportRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.WaybillsListTransportRequestFilterItem` 
    
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

## pos
<details><summary><code>client.Pos.DevicesCreate(request) -> *nordlet.DevicesCreatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DevicesCreatePosRequest{
        Name: "name",
        SerialNumber: "serialNumber",
    }
client.Pos.DevicesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Pos.DevicesUpdate(request) -> *nordlet.DevicesUpdatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DevicesUpdatePosRequest{
        ID: "id",
    }
client.Pos.DevicesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Pos.DevicesList(request) -> *nordlet.DevicesListPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DevicesListPosRequest{}
client.Pos.DevicesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.DevicesListPosRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.DevicesListPosRequestFilterItem` 
    
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

<details><summary><code>client.Pos.ReportsCreate(request) -> *nordlet.ReportsCreatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReportsCreatePosRequest{
        ReportNumber: "reportNumber",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        VatLines: []*nordlet.ReportsCreatePosRequestVatLinesItem{
            &nordlet.ReportsCreatePosRequestVatLinesItem{
                VatRatePercent: "121.00",
                NetAmount: "121.0000",
                VatAmount: "121.0000",
            },
        },
    }
client.Pos.ReportsCreate(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

**vatLines:** `[]*nordlet.ReportsCreatePosRequestVatLinesItem` 
    
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

**itemLines:** `[]*nordlet.ReportsCreatePosRequestItemLinesItem` 
    
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

<details><summary><code>client.Pos.ReportsGet(request) -> *nordlet.ReportsGetPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReportsGetPosRequest{
        ID: "id",
    }
client.Pos.ReportsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Pos.ReportsList(request) -> *nordlet.ReportsListPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReportsListPosRequest{}
client.Pos.ReportsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ReportsListPosRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ReportsListPosRequestFilterItem` 
    
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

## calendar
<details><summary><code>client.Calendar.List(request) -> *nordlet.ListCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListCalendarRequest{}
client.Calendar.List(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `*time.Time` 
    
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

<details><summary><code>client.Calendar.Get(request) -> *nordlet.GetCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetCalendarRequest{
        Key: "key",
    }
client.Calendar.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Calendar.Submit(request) -> *nordlet.SubmitCalendarResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

With amend: true the return is filed again as a correction of the one already submitted or accepted for the period; only returns whose format has a correction mark accept it.
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
request := &nordlet.SubmitCalendarRequest{
        Key: "key",
    }
client.Calendar.Submit(
        context.TODO(),
        request,
    )
}
```
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

**amend:** `*bool` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Calendar.Download(request) -> *nordlet.DownloadCalendarResponse</code></summary>
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
request := &nordlet.DownloadCalendarRequest{
        Key: "key",
    }
client.Calendar.Download(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Calendar.Create(request) -> *nordlet.CreateCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CreateCalendarRequest{
        Title: "title",
        DueDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Calendar.Create(
        context.TODO(),
        request,
    )
}
```
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

**dueDate:** `time.Time` 
    
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

<details><summary><code>client.Calendar.Update(request) -> *nordlet.UpdateCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UpdateCalendarRequest{
        Key: "key",
    }
client.Calendar.Update(
        context.TODO(),
        request,
    )
}
```
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

**dueDate:** `*time.Time` 
    
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

<details><summary><code>client.Calendar.Delete(request) -> *nordlet.DeleteCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteCalendarRequest{
        Key: "key",
    }
client.Calendar.Delete(
        context.TODO(),
        request,
    )
}
```
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

## audit
<details><summary><code>client.Audit.List(request) -> *nordlet.ListAuditResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListAuditRequest{}
client.Audit.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListAuditRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListAuditRequestFilterItem` 
    
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

## webhooks
<details><summary><code>client.Webhooks.SubscriptionsCreate(request) -> *nordlet.SubscriptionsCreateWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubscriptionsCreateWebhooksRequest{
        URL: "url",
        Events: []nordlet.SubscriptionsCreateWebhooksRequestEventsItem{
            nordlet.SubscriptionsCreateWebhooksRequestEventsItemAgreementInvoiceGenerated,
        },
    }
client.Webhooks.SubscriptionsCreate(
        context.TODO(),
        request,
    )
}
```
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

**events:** `[]*nordlet.SubscriptionsCreateWebhooksRequestEventsItem` 
    
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

<details><summary><code>client.Webhooks.SubscriptionsList(request) -> *nordlet.SubscriptionsListWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubscriptionsListWebhooksRequest{}
client.Webhooks.SubscriptionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.SubscriptionsListWebhooksRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.SubscriptionsListWebhooksRequestFilterItem` 
    
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

<details><summary><code>client.Webhooks.SubscriptionsUpdate(request) -> *nordlet.SubscriptionsUpdateWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubscriptionsUpdateWebhooksRequest{
        ID: "id",
    }
client.Webhooks.SubscriptionsUpdate(
        context.TODO(),
        request,
    )
}
```
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

**events:** `[]*nordlet.SubscriptionsUpdateWebhooksRequestEventsItem` 
    
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

<details><summary><code>client.Webhooks.SubscriptionsDelete(request) -> *nordlet.SubscriptionsDeleteWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SubscriptionsDeleteWebhooksRequest{
        ID: "id",
    }
client.Webhooks.SubscriptionsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Webhooks.DeliveriesList(request) -> *nordlet.DeliveriesListWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeliveriesListWebhooksRequest{}
client.Webhooks.DeliveriesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.DeliveriesListWebhooksRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.DeliveriesListWebhooksRequestFilterItem` 
    
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

<details><summary><code>client.Webhooks.DeliveriesRedeliver(request) -> *nordlet.DeliveriesRedeliverWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeliveriesRedeliverWebhooksRequest{
        ID: "id",
    }
client.Webhooks.DeliveriesRedeliver(
        context.TODO(),
        request,
    )
}
```
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

## bank
<details><summary><code>client.Bank.AccountsCreate(request) -> *nordlet.AccountsCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsCreateBankRequest{
        Name: "name",
    }
client.Bank.AccountsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.AccountsList(request) -> *nordlet.AccountsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsListBankRequest{}
client.Bank.AccountsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.AccountsListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.AccountsListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.AccountsUpdate(request) -> *nordlet.AccountsUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountsUpdateBankRequest{
        ID: "id",
    }
client.Bank.AccountsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.TransactionsImport(request) -> *nordlet.TransactionsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsImportBankRequest{
        BankAccountID: "bankAccountId",
        Transactions: []*nordlet.TransactionsImportBankRequestTransactionsItem{
            &nordlet.TransactionsImportBankRequestTransactionsItem{
                Date: nordlet.MustParseDate(
                    "2026-07-01",
                ),
                Amount: "-121.0000",
            },
        },
    }
client.Bank.TransactionsImport(
        context.TODO(),
        request,
    )
}
```
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

**transactions:** `[]*nordlet.TransactionsImportBankRequestTransactionsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.StatementsImport(request) -> *nordlet.StatementsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StatementsImportBankRequest{
        BankAccountID: "bankAccountId",
        Content: "content",
    }
client.Bank.StatementsImport(
        context.TODO(),
        request,
    )
}
```
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

**format:** `*nordlet.StatementsImportBankRequestFormat` 
    
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

<details><summary><code>client.Bank.TransactionsList(request) -> *nordlet.TransactionsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsListBankRequest{}
client.Bank.TransactionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.TransactionsListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.TransactionsListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.TransactionsMatch(request) -> *nordlet.TransactionsMatchBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsMatchBankRequest{
        TransactionID: "transactionId",
        DocumentType: nordlet.TransactionsMatchBankRequestDocumentTypeSaleInvoice,
        DocumentID: "documentId",
    }
client.Bank.TransactionsMatch(
        context.TODO(),
        request,
    )
}
```
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

**documentType:** `*nordlet.TransactionsMatchBankRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**documentID:** `string` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceAmount:** `*string` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.TransactionsUnmatch(request) -> *nordlet.TransactionsUnmatchBankResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Undo a match. A payment matched to an invoice, or a line posted by an import template, gets a reversing journal transaction dated date (default: today) and the invoice paid amount and payment status are restored; a line linked to a payment-provider settlement is only unlinked. The line returns to status new.
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
request := &nordlet.TransactionsUnmatchBankRequest{
        TransactionID: "transactionId",
    }
client.Bank.TransactionsUnmatch(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.TransactionsRecord(request) -> *nordlet.TransactionsRecordBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsRecordBankRequest{
        BankAccountID: "bankAccountId",
        Date: nordlet.MustParseDate(
            "2026-07-01",
        ),
        Amount: "121.0000",
        DocumentType: nordlet.TransactionsRecordBankRequestDocumentTypeSaleInvoice,
        DocumentID: "documentId",
    }
client.Bank.TransactionsRecord(
        context.TODO(),
        request,
    )
}
```
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

**date:** `time.Time` 
    
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

**documentType:** `*nordlet.TransactionsRecordBankRequestDocumentType` 
    
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

<details><summary><code>client.Bank.PaymentsExport(request) -> *nordlet.PaymentsExportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PaymentsExportBankRequest{
        BankAccountID: "bankAccountId",
        PurchaseInvoiceIDs: []string{
            "purchaseInvoiceIds",
        },
    }
client.Bank.PaymentsExport(
        context.TODO(),
        request,
    )
}
```
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

**executionDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.ImportTemplatesCreate(request) -> *nordlet.ImportTemplatesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ImportTemplatesCreateBankRequest{
        Name: "name",
        Type: nordlet.ImportTemplatesCreateBankRequestTypeStripe,
    }
client.Bank.ImportTemplatesCreate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ImportTemplatesCreateBankRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `[]*nordlet.ImportTemplatesCreateBankRequestFieldsItem` 
    
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

<details><summary><code>client.Bank.ImportTemplatesUpdate(request) -> *nordlet.ImportTemplatesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ImportTemplatesUpdateBankRequest{
        ID: "id",
    }
client.Bank.ImportTemplatesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**type_:** `*nordlet.ImportTemplatesUpdateBankRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `[]*nordlet.ImportTemplatesUpdateBankRequestFieldsItem` 
    
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

<details><summary><code>client.Bank.ImportTemplatesDelete(request) -> *nordlet.ImportTemplatesDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ImportTemplatesDeleteBankRequest{
        ID: "id",
    }
client.Bank.ImportTemplatesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.ImportTemplatesGet(request) -> *nordlet.ImportTemplatesGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ImportTemplatesGetBankRequest{
        ID: "id",
    }
client.Bank.ImportTemplatesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.ImportTemplatesList(request) -> *nordlet.ImportTemplatesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ImportTemplatesListBankRequest{}
client.Bank.ImportTemplatesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ImportTemplatesListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ImportTemplatesListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.MatchRulesCreate(request) -> *nordlet.MatchRulesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MatchRulesCreateBankRequest{
        Name: "name",
        Pattern: "pattern",
    }
client.Bank.MatchRulesCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MatchRulesUpdate(request) -> *nordlet.MatchRulesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MatchRulesUpdateBankRequest{
        ID: "id",
    }
client.Bank.MatchRulesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MatchRulesDelete(request) -> *nordlet.MatchRulesDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MatchRulesDeleteBankRequest{
        ID: "id",
    }
client.Bank.MatchRulesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MatchRulesList(request) -> *nordlet.MatchRulesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MatchRulesListBankRequest{}
client.Bank.MatchRulesList(
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

<details><summary><code>client.Bank.MandatesCreate(request) -> *nordlet.MandatesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MandatesCreateBankRequest{
        PartnerID: "partnerId",
        Iban: "iban",
        SignatureDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Bank.MandatesCreate(
        context.TODO(),
        request,
    )
}
```
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

**scheme:** `*nordlet.MandatesCreateBankRequestScheme` 
    
</dd>
</dl>

<dl>
<dd>

**sequenceType:** `*nordlet.MandatesCreateBankRequestSequenceType` 
    
</dd>
</dl>

<dl>
<dd>

**signatureDate:** `time.Time` 
    
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

<details><summary><code>client.Bank.MandatesUpdate(request) -> *nordlet.MandatesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MandatesUpdateBankRequest{
        ID: "id",
    }
client.Bank.MandatesUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MandatesCancel(request) -> *nordlet.MandatesCancelBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MandatesCancelBankRequest{
        ID: "id",
    }
client.Bank.MandatesCancel(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MandatesGet(request) -> *nordlet.MandatesGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MandatesGetBankRequest{
        ID: "id",
    }
client.Bank.MandatesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.MandatesList(request) -> *nordlet.MandatesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MandatesListBankRequest{}
client.Bank.MandatesList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.MandatesListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.MandatesListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.DirectDebitsCandidates(request) -> *nordlet.DirectDebitsCandidatesBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DirectDebitsCandidatesBankRequest{}
client.Bank.DirectDebitsCandidates(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.DirectDebitsCandidatesBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.DirectDebitsCandidatesBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.DirectDebitsExport(request) -> *nordlet.DirectDebitsExportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DirectDebitsExportBankRequest{
        BankAccountID: "bankAccountId",
        SaleInvoiceIDs: []string{
            "saleInvoiceIds",
        },
    }
client.Bank.DirectDebitsExport(
        context.TODO(),
        request,
    )
}
```
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

**collectionDate:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.TransactionsSuggestMatches(request) -> *nordlet.TransactionsSuggestMatchesBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsSuggestMatchesBankRequest{
        TransactionID: "transactionId",
    }
client.Bank.TransactionsSuggestMatches(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsImport(request) -> *nordlet.SettlementsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettlementsImportBankRequest{
        BankAccountID: "bankAccountId",
        Content: "content",
    }
client.Bank.SettlementsImport(
        context.TODO(),
        request,
    )
}
```
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

**provider:** `*nordlet.SettlementsImportBankRequestProvider` 
    
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

<details><summary><code>client.Bank.SettlementsList(request) -> *nordlet.SettlementsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettlementsListBankRequest{}
client.Bank.SettlementsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.SettlementsListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.SettlementsListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.SettlementsGet(request) -> *nordlet.SettlementsGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettlementsGetBankRequest{
        ID: "id",
    }
client.Bank.SettlementsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsMatch(request) -> *nordlet.SettlementsMatchBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettlementsMatchBankRequest{
        LineID: "lineId",
    }
client.Bank.SettlementsMatch(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsCommission(request) -> *nordlet.SettlementsCommissionBankResponse</code></summary>
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
request := &nordlet.SettlementsCommissionBankRequest{
        LineID: "lineId",
    }
client.Bank.SettlementsCommission(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsLink(request) -> *nordlet.SettlementsLinkBankResponse</code></summary>
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
request := &nordlet.SettlementsLinkBankRequest{
        ID: "id",
        BankTransactionID: "bankTransactionId",
    }
client.Bank.SettlementsLink(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsUnlink(request) -> *nordlet.SettlementsUnlinkBankResponse</code></summary>
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
request := &nordlet.SettlementsUnlinkBankRequest{
        ID: "id",
    }
client.Bank.SettlementsUnlink(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.SettlementsPost(request) -> *nordlet.SettlementsPostBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SettlementsPostBankRequest{
        ID: "id",
    }
client.Bank.SettlementsPost(
        context.TODO(),
        request,
    )
}
```
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

**date:** `*time.Time` 
    
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

<details><summary><code>client.Bank.FeedsBanksList(request) -> *nordlet.FeedsBanksListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsBanksListBankRequest{}
client.Bank.FeedsBanksList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.FeedsConnectionsStart(request) -> *nordlet.FeedsConnectionsStartBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsConnectionsStartBankRequest{
        AspspName: "aspspName",
        AspspCountry: "aspspCountry",
    }
client.Bank.FeedsConnectionsStart(
        context.TODO(),
        request,
    )
}
```
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

**psuType:** `*nordlet.FeedsConnectionsStartBankRequestPsuType` 
    
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

<details><summary><code>client.Bank.FeedsConnectionsComplete(request) -> *nordlet.FeedsConnectionsCompleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsConnectionsCompleteBankRequest{
        Reference: "reference",
        Code: "code",
    }
client.Bank.FeedsConnectionsComplete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.FeedsConnectionsGet(request) -> *nordlet.FeedsConnectionsGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsConnectionsGetBankRequest{
        ID: "id",
    }
client.Bank.FeedsConnectionsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.FeedsConnectionsList(request) -> *nordlet.FeedsConnectionsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsConnectionsListBankRequest{}
client.Bank.FeedsConnectionsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.FeedsConnectionsListBankRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.FeedsConnectionsListBankRequestFilterItem` 
    
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

<details><summary><code>client.Bank.FeedsConnectionsDelete(request) -> *nordlet.FeedsConnectionsDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsConnectionsDeleteBankRequest{
        ID: "id",
    }
client.Bank.FeedsConnectionsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Bank.FeedsAccountsLink(request) -> *nordlet.FeedsAccountsLinkBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsAccountsLinkBankRequest{
        ID: "id",
    }
client.Bank.FeedsAccountsLink(
        context.TODO(),
        request,
    )
}
```
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

**createBankAccount:** `*nordlet.FeedsAccountsLinkBankRequestCreateBankAccount` 
    
</dd>
</dl>

<dl>
<dd>

**syncFrom:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.FeedsAccountsConfigure(request) -> *nordlet.FeedsAccountsConfigureBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsAccountsConfigureBankRequest{
        ID: "id",
    }
client.Bank.FeedsAccountsConfigure(
        context.TODO(),
        request,
    )
}
```
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

**syncSchedule:** `*nordlet.FeedsAccountsConfigureBankRequestSyncSchedule` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Bank.FeedsSync(request) -> *nordlet.FeedsSyncBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FeedsSyncBankRequest{
        ConnectionID: "connectionId",
    }
client.Bank.FeedsSync(
        context.TODO(),
        request,
    )
}
```
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

**dateFrom:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## files
<details><summary><code>client.Files.Upload(request) -> *nordlet.UploadFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UploadFilesRequest{
        Entity: "entity",
        FileName: "fileName",
        MimeType: "mimeType",
        Content: "content",
    }
client.Files.Upload(
        context.TODO(),
        request,
    )
}
```
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

**mimeType:** `string` — Stored as the bare media type; only PNG, JPEG, GIF, WebP and PDF files are shown in the browser, every other type is downloaded
    
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

<details><summary><code>client.Files.Get(request) -> *nordlet.GetFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GetFilesRequest{
        ID: "id",
    }
client.Files.Get(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Files.List(request) -> *nordlet.ListFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ListFilesRequest{}
client.Files.List(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.ListFilesRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.ListFilesRequestFilterItem` 
    
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

<details><summary><code>client.Files.Delete(request) -> *nordlet.DeleteFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DeleteFilesRequest{
        ID: "id",
    }
client.Files.Delete(
        context.TODO(),
        request,
    )
}
```
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

## reports
<details><summary><code>client.Reports.TrialBalance(request) -> *nordlet.TrialBalanceReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TrialBalanceReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.TrialBalance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.SizeCategory(request) -> *nordlet.SizeCategoryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SizeCategoryReportsRequest{
        Year: int64(1000000),
    }
client.Reports.SizeCategory(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reports.FinancialStatements(request) -> *nordlet.FinancialStatementsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.FinancialStatementsReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.FinancialStatements(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `*nordlet.FinancialStatementsReportsRequestCategory` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.GeneralJournal(request) -> *nordlet.GeneralJournalReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GeneralJournalReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.GeneralJournal(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.GlDetail(request) -> *nordlet.GlDetailReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GlDetailReportsRequest{
        AccountCode: "accountCode",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.GlDetail(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PartnerBalances(request) -> *nordlet.PartnerBalancesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PartnerBalancesReportsRequest{}
client.Reports.PartnerBalances(
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

<details><summary><code>client.Reports.DebtAging(request) -> *nordlet.DebtAgingReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.DebtAgingReportsRequest{}
client.Reports.DebtAging(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**side:** `*nordlet.DebtAgingReportsRequestSide` 
    
</dd>
</dl>

<dl>
<dd>

**asOf:** `*time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.MonthlySummary(request) -> *nordlet.MonthlySummaryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MonthlySummaryReportsRequest{}
client.Reports.MonthlySummary(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reports.StockBalance(request) -> *nordlet.StockBalanceReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockBalanceReportsRequest{
        AsOf: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.StockBalance(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `time.Time` 
    
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

<details><summary><code>client.Reports.StockMovement(request) -> *nordlet.StockMovementReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockMovementReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.StockMovement(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.VatSummary(request) -> *nordlet.VatSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatSummaryReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.VatSummary(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `*nordlet.VatSummaryReportsRequestSide` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.CashFlow(request) -> *nordlet.CashFlowReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CashFlowReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.CashFlow(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.StockAging(request) -> *nordlet.StockAgingReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockAgingReportsRequest{
        AsOf: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.StockAging(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `time.Time` 
    
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

<details><summary><code>client.Reports.StockShortage(request) -> *nordlet.StockShortageReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.StockShortageReportsRequest{}
client.Reports.StockShortage(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reports.Sie(request) -> *nordlet.SieReportsResponse</code></summary>
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
request := &nordlet.SieReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.Sie(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.Datev(request) -> *nordlet.DatevReportsResponse</code></summary>
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
request := &nordlet.DatevReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.Datev(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.Fec(request) -> *nordlet.FecReportsResponse</code></summary>
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
request := &nordlet.FecReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.Fec(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.EuPurchases(request) -> *nordlet.EuPurchasesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EuPurchasesReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.EuPurchases(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.VatDetail(request) -> *nordlet.VatDetailReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.VatDetailReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.VatDetail(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `*nordlet.VatDetailReportsRequestSide` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.PosSales(request) -> *nordlet.PosSalesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PosSalesReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.PosSales(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.OnlineSales(request) -> *nordlet.OnlineSalesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OnlineSalesReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.OnlineSales(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.Oss(request) -> *nordlet.OssReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.OssReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.Oss(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.AdvanceReconciliation(request) -> *nordlet.AdvanceReconciliationReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AdvanceReconciliationReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.AdvanceReconciliation(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.WriteOffActs(request) -> *nordlet.WriteOffActsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.WriteOffActsReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.WriteOffActs(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.CostCenters(request) -> *nordlet.CostCentersReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCentersReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.CostCenters(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.CostCenterActivity(request) -> *nordlet.CostCenterActivityReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterActivityReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        CostCenterID: "costCenterId",
    }
client.Reports.CostCenterActivity(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.CostCenterItems(request) -> *nordlet.CostCenterItemsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CostCenterItemsReportsRequest{
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Reports.CostCenterItems(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
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

<details><summary><code>client.Reports.JobsCreate(request) -> *nordlet.JobsCreateReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JobsCreateReportsRequest{
        ReportType: "reportType",
    }
client.Reports.JobsCreate(
        context.TODO(),
        request,
    )
}
```
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

**formats:** `[]*nordlet.JobsCreateReportsRequestFormatsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Reports.JobsGet(request) -> *nordlet.JobsGetReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JobsGetReportsRequest{
        ID: "id",
    }
client.Reports.JobsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Reports.JobsList(request) -> *nordlet.JobsListReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.JobsListReportsRequest{}
client.Reports.JobsList(
        context.TODO(),
        request,
    )
}
```
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

**sort:** `[]*nordlet.JobsListReportsRequestSortItem` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `[]*nordlet.JobsListReportsRequestFilterItem` 
    
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

## consolidation
<details><summary><code>client.Consolidation.GroupsCreate(request) -> *nordlet.GroupsCreateConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsCreateConsolidationRequest{
        Name: "name",
    }
client.Consolidation.GroupsCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.GroupsList(request) -> *nordlet.GroupsListConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsListConsolidationRequest{}
client.Consolidation.GroupsList(
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

<details><summary><code>client.Consolidation.GroupsGet(request) -> *nordlet.GroupsGetConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsGetConsolidationRequest{
        GroupID: "groupId",
    }
client.Consolidation.GroupsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.GroupsUpdate(request) -> *nordlet.GroupsUpdateConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsUpdateConsolidationRequest{
        GroupID: "groupId",
    }
client.Consolidation.GroupsUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.GroupsDelete(request) -> *nordlet.GroupsDeleteConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.GroupsDeleteConsolidationRequest{
        GroupID: "groupId",
    }
client.Consolidation.GroupsDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.MembersAdd(request) -> *nordlet.MembersAddConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersAddConsolidationRequest{
        GroupID: "groupId",
        MemberCompanyID: "memberCompanyId",
    }
client.Consolidation.MembersAdd(
        context.TODO(),
        request,
    )
}
```
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

**method:** `*nordlet.MembersAddConsolidationRequestMethod` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.MembersRemove(request) -> *nordlet.MembersRemoveConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersRemoveConsolidationRequest{
        GroupID: "groupId",
        MemberCompanyID: "memberCompanyId",
    }
client.Consolidation.MembersRemove(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.IntercompanyCandidates(request) -> *nordlet.IntercompanyCandidatesConsolidationResponse</code></summary>
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
request := &nordlet.IntercompanyCandidatesConsolidationRequest{
        GroupID: "groupId",
    }
client.Consolidation.IntercompanyCandidates(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.IntercompanyLinksSet(request) -> *nordlet.IntercompanyLinksSetConsolidationResponse</code></summary>
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
request := &nordlet.IntercompanyLinksSetConsolidationRequest{
        GroupID: "groupId",
        PartnerID: "partnerId",
        CounterpartyCompanyID: "counterpartyCompanyId",
    }
client.Consolidation.IntercompanyLinksSet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.IntercompanyLinksList(request) -> *nordlet.IntercompanyLinksListConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IntercompanyLinksListConsolidationRequest{
        GroupID: "groupId",
    }
client.Consolidation.IntercompanyLinksList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.IntercompanyLinksRemove(request) -> *nordlet.IntercompanyLinksRemoveConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IntercompanyLinksRemoveConsolidationRequest{
        GroupID: "groupId",
        ID: "id",
    }
client.Consolidation.IntercompanyLinksRemove(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Consolidation.IntercompanyReport(request) -> *nordlet.IntercompanyReportConsolidationResponse</code></summary>
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
request := &nordlet.IntercompanyReportConsolidationRequest{
        GroupID: "groupId",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Consolidation.IntercompanyReport(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Consolidation.Report(request) -> *nordlet.ReportConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReportConsolidationRequest{
        GroupID: "groupId",
        FromDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
        ToDate: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Consolidation.Report(
        context.TODO(),
        request,
    )
}
```
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

**fromDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `*nordlet.ReportConsolidationRequestCategory` 
    
</dd>
</dl>

<dl>
<dd>

**eliminations:** `[]*nordlet.ReportConsolidationRequestEliminationsItem` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## public
<details><summary><code>client.Public.IntegrationRequests(request) -> *nordlet.IntegrationRequestsPublicResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.IntegrationRequestsPublicRequest{
        Integration: "integration",
        Name: "name",
        Email: "email",
    }
client.Public.IntegrationRequests(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Public.Pay(Token) -> error</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PayPublicRequest{
        Token: "token",
    }
client.Public.Pay(
        context.TODO(),
        request,
    )
}
```
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

## billing
<details><summary><code>client.Billing.AccountGet(request) -> *nordlet.AccountGetBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountGetBillingRequest{}
client.Billing.AccountGet(
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

<details><summary><code>client.Billing.AccountSetPlan(request) -> *nordlet.AccountSetPlanBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.AccountSetPlanBillingRequest{
        Plan: nordlet.AccountSetPlanBillingRequestPlanStarter,
    }
client.Billing.AccountSetPlan(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**plan:** `*nordlet.AccountSetPlanBillingRequestPlan` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.TopupCreate(request) -> *nordlet.TopupCreateBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TopupCreateBillingRequest{
        AmountCents: int64(1000000),
    }
client.Billing.TopupCreate(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.TopupCreateBillingRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.PortalCreate(request) -> *nordlet.PortalCreateBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.PortalCreateBillingRequest{}
client.Billing.PortalCreate(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.PortalCreateBillingRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Billing.TransactionsList(request) -> *nordlet.TransactionsListBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TransactionsListBillingRequest{}
client.Billing.TransactionsList(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Billing.UsageList(request) -> *nordlet.UsageListBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.UsageListBillingRequest{
        From: nordlet.MustParseDate(
            "2026-07-01",
        ),
        To: nordlet.MustParseDate(
            "2026-07-01",
        ),
    }
client.Billing.UsageList(
        context.TODO(),
        request,
    )
}
```
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
</dd>
</dl>


</dd>
</dl>
</details>

## account
<details><summary><code>client.Account.LoginLinkRequest(request) -> *nordlet.LoginLinkRequestAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LoginLinkRequestAccountRequest{
        Email: "email",
    }
client.Account.LoginLinkRequest(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.LoginLinkRequestAccountRequestLocale` 
    
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

<details><summary><code>client.Account.LoginLinkConsume(request) -> *nordlet.LoginLinkConsumeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LoginLinkConsumeAccountRequest{
        Token: "token",
    }
client.Account.LoginLinkConsume(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.Logout(request) -> *nordlet.LogoutAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LogoutAccountRequest{}
client.Account.Logout(
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

<details><summary><code>client.Account.Me(request) -> *nordlet.MeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MeAccountRequest{}
client.Account.Me(
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

<details><summary><code>client.Account.MembersList(request) -> *nordlet.MembersListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersListAccountRequest{}
client.Account.MembersList(
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

<details><summary><code>client.Account.MembersSetRole(request) -> *nordlet.MembersSetRoleAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersSetRoleAccountRequest{
        UserID: "userId",
        Role: nordlet.MembersSetRoleAccountRequestRoleAdmin,
    }
client.Account.MembersSetRole(
        context.TODO(),
        request,
    )
}
```
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

**role:** `*nordlet.MembersSetRoleAccountRequestRole` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.MembersTransferOwnership(request) -> *nordlet.MembersTransferOwnershipAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersTransferOwnershipAccountRequest{
        UserID: "userId",
    }
client.Account.MembersTransferOwnership(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.MembersRemove(request) -> *nordlet.MembersRemoveAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.MembersRemoveAccountRequest{
        UserID: "userId",
    }
client.Account.MembersRemove(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.InvitesCreate(request) -> *nordlet.InvitesCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvitesCreateAccountRequest{
        Email: "email",
        Role: nordlet.InvitesCreateAccountRequestRoleAdmin,
    }
client.Account.InvitesCreate(
        context.TODO(),
        request,
    )
}
```
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

**role:** `*nordlet.InvitesCreateAccountRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `*nordlet.InvitesCreateAccountRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.InvitesList(request) -> *nordlet.InvitesListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvitesListAccountRequest{}
client.Account.InvitesList(
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

<details><summary><code>client.Account.InvitesRevoke(request) -> *nordlet.InvitesRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvitesRevokeAccountRequest{
        ID: "id",
    }
client.Account.InvitesRevoke(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.InvitesGet(request) -> *nordlet.InvitesGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvitesGetAccountRequest{
        Token: "token",
    }
client.Account.InvitesGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.InvitesAccept(request) -> *nordlet.InvitesAcceptAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.InvitesAcceptAccountRequest{
        Token: "token",
    }
client.Account.InvitesAccept(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.InvitesAcceptAccountRequestLocale` 
    
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

<details><summary><code>client.Account.LocaleSet(request) -> *nordlet.LocaleSetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.LocaleSetAccountRequest{
        Locale: nordlet.LocaleSetAccountRequestLocaleEn,
    }
client.Account.LocaleSet(
        context.TODO(),
        request,
    )
}
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `*nordlet.LocaleSetAccountRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.CompaniesCreate(request) -> *nordlet.CompaniesCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesCreateAccountRequest{
        Name: "name",
    }
client.Account.CompaniesCreate(
        context.TODO(),
        request,
    )
}
```
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

**vatPeriod:** `*nordlet.CompaniesCreateAccountRequestVatPeriod` 
    
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

**address:** `*nordlet.CompaniesCreateAccountRequestAddress` 
    
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

**incorporatedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `*nordlet.CompaniesCreateAccountRequestAccountsKeptBy` 
    
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

**countryCode:** `*nordlet.CompaniesCreateAccountRequestCountryCode` — Jurisdiction the company is registered in (immutable after creation)
    
</dd>
</dl>

<dl>
<dd>

**baseCurrency:** `*string` — Currency the ledger is kept in; defaults to the national currency of countryCode (immutable after creation)
    
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

<details><summary><code>client.Account.CompaniesSelect(request) -> *nordlet.CompaniesSelectAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesSelectAccountRequest{
        CompanyID: "companyId",
    }
client.Account.CompaniesSelect(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.CompaniesProfile(request) -> *nordlet.CompaniesProfileAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesProfileAccountRequest{}
client.Account.CompaniesProfile(
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

<details><summary><code>client.Account.CompaniesUpdate(request) -> *nordlet.CompaniesUpdateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesUpdateAccountRequest{}
client.Account.CompaniesUpdate(
        context.TODO(),
        request,
    )
}
```
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

**vatPeriod:** `*nordlet.CompaniesUpdateAccountRequestVatPeriod` 
    
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

**address:** `*nordlet.CompaniesUpdateAccountRequestAddress` 
    
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

**incorporatedOn:** `*time.Time` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `*string` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `*nordlet.CompaniesUpdateAccountRequestAccountsKeptBy` 
    
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

**logo:** `*nordlet.CompaniesUpdateAccountRequestLogo` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.CompaniesArchive(request) -> *nordlet.CompaniesArchiveAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesArchiveAccountRequest{
        CompanyID: "companyId",
    }
client.Account.CompaniesArchive(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.CompaniesDelete(request) -> *nordlet.CompaniesDeleteAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesDeleteAccountRequest{
        CompanyID: "companyId",
    }
client.Account.CompaniesDelete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.CompaniesActivate(request) -> *nordlet.CompaniesActivateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.CompaniesActivateAccountRequest{
        CompanyID: "companyId",
    }
client.Account.CompaniesActivate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.APIKeysCreate(request) -> *nordlet.APIKeysCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.APIKeysCreateAccountRequest{
        Name: "name",
    }
client.Account.APIKeysCreate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.APIKeysList(request) -> *nordlet.APIKeysListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.APIKeysListAccountRequest{}
client.Account.APIKeysList(
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

<details><summary><code>client.Account.APIKeysRotate(request) -> *nordlet.APIKeysRotateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.APIKeysRotateAccountRequest{
        ID: "id",
    }
client.Account.APIKeysRotate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.APIKeysRevoke(request) -> *nordlet.APIKeysRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.APIKeysRevokeAccountRequest{
        ID: "id",
    }
client.Account.APIKeysRevoke(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.ConsentAccept(request) -> *nordlet.ConsentAcceptAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ConsentAcceptAccountRequest{
        AcceptTerms: true,
        AcceptDpa: true,
    }
client.Account.ConsentAccept(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.ProfileUpdate(request) -> *nordlet.ProfileUpdateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ProfileUpdateAccountRequest{}
client.Account.ProfileUpdate(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.EmailChangeRequest(request) -> *nordlet.EmailChangeRequestAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.EmailChangeRequestAccountRequest{
        NewEmail: "newEmail",
    }
client.Account.EmailChangeRequest(
        context.TODO(),
        request,
    )
}
```
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

**locale:** `*nordlet.EmailChangeRequestAccountRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.Account.SessionsList(request) -> *nordlet.SessionsListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SessionsListAccountRequest{}
client.Account.SessionsList(
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

<details><summary><code>client.Account.SessionsRevoke(request) -> *nordlet.SessionsRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SessionsRevokeAccountRequest{
        ID: "id",
    }
client.Account.SessionsRevoke(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.SessionsRevokeOthers(request) -> *nordlet.SessionsRevokeOthersAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.SessionsRevokeOthersAccountRequest{}
client.Account.SessionsRevokeOthers(
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

<details><summary><code>client.Account.Export(request) -> *nordlet.ExportAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ExportAccountRequest{}
client.Account.Export(
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

<details><summary><code>client.Account.Delete(request) -> *nordlet.DeleteAccountResponse</code></summary>
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
request := &nordlet.DeleteAccountRequest{
        ConfirmEmail: "confirmEmail",
    }
client.Account.Delete(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.ReferralGet(request) -> *nordlet.ReferralGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReferralGetAccountRequest{}
client.Account.ReferralGet(
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

<details><summary><code>client.Account.ReferralConvert(request) -> *nordlet.ReferralConvertAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.ReferralConvertAccountRequest{
        Points: int64(1000000),
    }
client.Account.ReferralConvert(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.TableSettingsGet(request) -> *nordlet.TableSettingsGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TableSettingsGetAccountRequest{
        TableKey: "tableKey",
    }
client.Account.TableSettingsGet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.TableSettingsSet(request) -> *nordlet.TableSettingsSetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TableSettingsSetAccountRequest{
        TableKey: "tableKey",
    }
client.Account.TableSettingsSet(
        context.TODO(),
        request,
    )
}
```
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

<details><summary><code>client.Account.TableSettingsList(request) -> *nordlet.TableSettingsListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```go
request := &nordlet.TableSettingsListAccountRequest{}
client.Account.TableSettingsList(
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

