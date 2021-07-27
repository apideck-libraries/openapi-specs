## v4.3.2 - (2021-07-23)

### Vault API

- Connection.json#updated_at is nullable
- `vault/logs` filter for exclude_unified_apis has been refactored to be comma separated string

## v4.3.1 - (2021-07-15)

### Vault API

- Added ability to filter log results in vault.

## v4.3.0 - (2021-07-14)

### Vault API

- New `/vault/logs` endpoint released to enable fetching paginated list of request logs scoped to application and consumer.

## v4.2.0 - (2021-07-07)

### Vault API

- Added a `services` array to list all active services when listing all consumers.

## v4.1.1 - (2021-07-05)

### CRM API & Lead API & Vault API

- extend examples for fields that allow `anyOf` (in this case errors that allow strings or objects)

## v4.1.0 - (2021-07-02)

### CRM API

- Added sorting support to Leads, Companies and Opportunities. To sort results, use the `sort[by]` and `sort[direction]` query parameters.
  - **Leads**: available `sort[by]` values are `name`, `first_name`, `last_name`, `email`, `created_at` and `updated_at`.
  - **Companies**: available `sort[by]` values are `name`, `created_at` and `updated_at`.
  - **Opportunities**: available `sort[by]` values are `title`, `status`, `monetary_amount`, `win_probability`,`created_at` and `updated_at`.

## v4.0.0 - (2021-07-01)

### CRM API

- Added `note` and `task` as allowed values for `type` on the activity resource
- `activity_datetime` and `duration_seconds` are no longer required on the activity resource

### ACTION REQUIRED

<span className='tag'>CRM API</span>

Beta users should note the following breaking changes that may affect existing integrations implementing the `CRM` API:

- On the activity resource, following fields were removed:
  - `recurrence_activity_id`
  - `recurrence_start_datetime`
  - `recurrence_end_date`
  - `recurrence_timezone`
  - `recurrence_interval`
  - `recurrence_day_of_week_mask`
  - `recurrence_day_of_month`
  - `recurrence_instance`
  - `recurrence_month_of_year`
  - `recurrence_end_date_only`
  - `recurrence_type`

## v3.0.3 - (2021-07-01)

### CRM API & Lead API & Vault API

- `detail` property on all errors can be a string _or_ and object

## v3.0.2 - (2021-06-29)

### CRM API & Lead API & Vault API

- all required fields are validated with `minLength: 1`

## v3.0.1 - (2021-06-28)

### CRM API & Lead API

- `lead_source` and `language` added to Lead resource
- `account_id` and `duration_in_minutes` added to Activity resource

## v3.0.0 - (2021-06-18)

### ACTION REQUIRED

<span className='tag'>Vault API</span>

Beta users should note the following breaking changes that may affect existing integrations implementing the `Vault` API:

- Moved `api_key` field from the root in the request body to the settings object when creating/updating connections.

## v2.4.0 - (2021-06-08)

### CRM API

- Added sorting support to Contacts. To sort Contacts, use the `sort[by]` and `sort[direction]` query parameters. Available `sort[by]` values are `name`, `first_name`, `last_name`, `email`, `created_at` and `updated_at`.

## v2.3.0 - (2021-06-07)

### CRM API & Lead API

- Remove connectors table

## v2.2.0 - (2021-06-07)

### Proxy API

- Documented `static IP` and `limitations`

## v2.1.0 - (2021-05-31)

### Vault API

- Undocumented `connectionsAdd` added
- Normalized reponses for `getConnectionSettings` and `updateConnectionSettings`

## v2.0.0 - (2021-05-28)

### Vault/Proxy API

- Deprecated [/vault/proxy](apis/vault/reference#tag/Proxy) and moved to the [Proxy API](apis/proxy)

## v1.10.0 - (2021-05-28)

### CRM API

- Added filter query parameter for opportunity

## v1.9.0 - (2021-05-26)

### CRM API

- Added filter query parameter for lead

## v1.8.0 - (2021-05-24)

### CRM API

- Added [Activities](apis/crm/reference#tag/Activities) resource

## v1.7.0 - (2021-05-21)

### CRM API

- Added [Users](apis/crm/reference#tag/Users) resource

## v1.6.0 - (2021-05-20)

### CRM API

- Added Notes resource

## v1.5.0 - (2021-05-19)

- Configuration options per resource extended to fetch dynamic options when configuring settings.

### Vault API

- Added `filter-type` to `FormField.type` that allows configuration options to be filtered by the value of a separate setting.
- `FormFieldOptionGroup` schema added to define grouping of options within a FormField

<span className='tag'>1.4.0</span>

## v1.4.0 - (2021-05-18)

Added configuration options per resource.

<span className='tag'>1.4.0</span>

### Vault API

- Renamed `schema_support` to `resource_schema_support` and introduced `resource_settings_support` to the [connection settings endpoint](apis/vault/reference#operation/deleteConnection)
- Add `configurable_resources` to the [connections endpoint](apis/vault/reference#operation/connectionsAll)

## v1.3.0 - (2021-05-13)

Apideck APIs now use a single semver version for clarity.

<span className='tag'>1.3.0</span>

### CRM API & Lead API

- `SpecRequestValidationError` was replaced by 2 more helpful errors. [`RequestBodyValidationError`](errors#requestbodyvalidationerror) and [`RequestParametersValidationError`](errors#requestparametersvalidationerror) are more readable, informative and provide suggestions.

## v1.2.0 - (2021-05-12)

New consumer endpoints added to the Vault API providing a list and aggregate data on the type of requests consumers are making.

<span className='tag'>Vault 1.2.0</span>

- [`/vault/consumers`](apis/vault/reference#operation/consumersAll) added to provide paginated [list of consumers](apis/vault/reference#operation/consumersAll) scoped to application
- [`/vault/consumers/{consumer_id}`](apis/vault/reference#operation/consumersOne) added to provide consumer detail including `aggregated_request_count` and request counts across the Unified APIs.
- [`/vault/consumers/{consumer_id}/stats`](apis/vault/reference#operation/consumerRequestCounts) added to provide request count aggregation data within a datetime range.

## v1.1.1 - (2021-05-10)

Initial spec of new Vault Consumers API drafted for upcoming release.

<span className='tag'>Vault 1.1.1</span>

## v1.1.0 - (2021-04-23)

We switched to a dynamic way of using filters instead of fixed query parameters.

### ACTION REQUIRED

<span className='tag'>CRM 1.1.0</span>

Beta users should note the following breaking changes that may affect existing integrations implementing the `CRM` API:

- Filtering on contacts has now a dedicated `filter` query parameter instead of seperated query parameters per field

- Filtering on opportunities has now a dedicated `filter` query parameter instead of seperated query parameters per field

## v1.0.0 - (2021-04-21)

Moving towards widespread public release, we're updating our specs to version `1.0.0` across the board. This acts as a starting point to officially implement semantic versioning
across all of our specs.

From here on in, we'll be tracking, documenting and broadcasting implemented or upcoming API changes within this document.

### ACTION REQUIRED

<span className='tag'>CRM 1.0.0</span> <span className='tag'>Lead 1.0.0</span>

Beta users should note the following breaking changes that may affect existing integrations implementing either `Lead` or `CRM` API:

- `Address.type` enum updated to `["primary", "secondary", "home", "office", "shipping", "billing", "other"]`

- `Website.category` has been renamed to `Website.type` and is now an `enum`. Now accepts: `["primary", "secondary", "work", "personal", "other"]`

- `Email.type` migrated from string to `enum`. Now accepts: `["primary", "secondary", "work", "personal", "billing", "other"]`

- `PhoneNumber.phone_type` changed to `PhoneNumber.type` and `enum` now accepts: `["primary", "secondary", "home", "office", "mobile", "assistant", "fax", "other"]`.

> Note: All enums that previously accepted `default` now expect `primary`!
