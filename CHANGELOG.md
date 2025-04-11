## v10.15.1 - (2025-04-11)

### CRM API

- Added [Odoo](connectors/odoo) connector for the CRM API

## v10.15.0 - (2025-04-10)

### Accounting API

- Added virtual webhook support for [Netsuite](connectors/netsuite)

## v10.14.1 - (2025-04-02)

### Accounting API

- Added [myob-acumatica](connectors/myob-acumatica) connector for the Accounting API

## v10.14.0 - (2025-03-28)

### CRM API

- Added [Attio](connectors/attio) connector for the CRM API
- Added [Webhooks](apis/crm/reference#tag/Webhooks) support for [Attio](connectors/attio) connector in the CRM API

## v10.12.4 - (2025-03-20)

### HRIS API

- Added [Acerta](connectors/acerta) connector for the HRIS API

## v10.13.0 - (2025-03-17)

### Accounting API

- Added `time-off-requests` coverage to [People-hr](connectors/people-hr)
- Added `time-off-requests` coverage to [Employment Hero](connectors/employmenthero)

## v10.12.3 - (2025-03-11)

### Accounting API

- Added new filter for `supplier_id` to [Customers](apis/accounting/reference#tag/Customers)

## v10.12.2 - (2025-03-11)

### Accounting API

- Addded `cost_of_goods_sold`, `other_income`, `other_expenses`, `uncategorized_categories` support to [Profit And Loss](apis/accounting/reference#tag/Profit-And-Loss)

## v10.12.1 - (2025-03-07)

### Accounting API

- Added `expenses` support for [Netsuite](connectors/netsuite)

## v10.12.0 - (2025-03-04)

### ATS API

- Added Bullhorn [connectors/bullhorn-ats] connector for the ATS API

## v10.11.5 - (2025-02-17)

### File Storage API

- Added `raw` parameter to [Files Search](apis/file-storage/reference#tag/Files)

## v10.11.4 - (2025-02-14)

### Accounting API

- Added credit-note webhooks support for [Quickbooks](connectors/quickbooks)

## v10.11.3 - (2025-02-11)

### Ecommerce API

- Added [Etsy](connectors/etsy) connector

## v10.11.2 - (2025-01-30)

### CRM API

- Added gotchas for [Planhat connector](connectors/planhat)

## v10.11.1 - (2025-01-30)

### HRIS API

- Added `companies` coverage to [BambooHR](connectors/bamboohr)

## v10.11.0 - (2025-01-25)

### Ecommerce API

- Added new webhook events for [Ecommerce](apis/ecommerce/reference#tag/Webhook-Events)
- Added native webhook support for [Shopify](connectors/shopify) which api_managed (both delete and creation).

## v10.10.1 - (2025-01-23)

### Accounting API

- Added `sort` parameter to [Invoice Items](apis/accounting/reference#tag/Invoice-Items)

## v10.10.0 - (2025-01-16)

- Added `Users` resource to [Microsoft Dynamics CRM](connectors/microsoft-dynamics).

## v10.9.1 - (2025-01-13)

- Added `custom_fields` to [Journal Entry](apis/accounting/reference#tag/Journal-Entries)

## v10.9.0 - (2024-12-11)

## Accounting API

- Added [Aged Creditors](apis/accounting/reference#tag/Aged-Creditors) schema.
- Added [Aged Debtors](apis/accounting/reference#tag/Aged-Debtors) schema.

## v10.8.3 - (2024-12-05)

### Accounting API

- Added `subsidiaries` field to [Tax Rates](apis/accounting/reference#tag/Tax-Rates) schema.
- Added `subsidiaries` field to [Tracking Categories](apis/accounting/reference#tag/Tracking-Categories) schema.
- Added `subsidiary_id` field to [Suppliers](apis/accounting/reference#tag/Suppliers) schema.

## v10.8.2 - (2024-12-05)

### Accounting API

- Added `payment_type` field to [Expenses](apis/accounting/reference#tag/Expenses) schema.

## v10.8.1 - (2024-11-12)

### HRIS API

- Added `status` field to jobs for [Employee](apis/hris/reference#tag/Employees) schema.

## v10.8.0 - (2024-10-30)

### Vault API

- Added `createCallbackState` endpoint to [Create Callback State](/apis/vault/reference#operation/createCallbackState) to create a short-lived state for callback requests.

## v10.7.7 - (2024-10-22)

### Accounting API

- Added new field `subsidiaries` to Ledger Accounts, including support for [Netsuite](connectors/netsuite) and [Sage Intacct](connectors/sage-intacct) connectors.

## v10.7.6 - (2024-09-26)

### Vault API

- Added `/vault/connections/:unified_api/:service_id/:resource/custom-mappings` endpoint to retrieve all custom mappings for a connection.
- Added `/vault/custom-mappings/:unified_api/:service_id` endpoint to retrieve all custom mappings for a service.

## v10.7.5 - (2024-09-24)

### Lead API

- Removed min length for the field `name` on Unify Lead

### HRIS API

- Early-access release of the [Keka](connectors/keka) connector with support for the Employee resource

## v10.7.4 - (2024-09-23)

### Accounting API

- Added `number` filter to [Invoices](apis/accounting/reference#tag/Invoices)
- Added `number` filter support for [Quickbooks](connectors/quickbooks), [Xero](connectors/xero), [MYOB](apis/accounting/myob), [Zoho-Books](apis/accounting/zoho-books) and [FreshBooks](apis/accounting/freshbooks) connectors.

## v10.7.3 - (2024-09-17)

### Accounting API

- Added [Expenses](apis/accounting/reference#tag/Expenses) schema.
- Added [Expenses](apis/accounting/reference#tag/Expenses) support for [Quickbooks](connectors/quickbooks) and [Xero](connectors/xero) connector.

## v10.7.2 - (2024-09-03)

### Accounting API

- Added [Bill Payments](apis/accounting/reference#tag/Bill-Payments) schema.
- Added [Bill Payments](apis/accounting/reference#tag/Bill-Payments) support for [Quickbooks](connectors/quickbooks) connector.

## v10.7.1 - (2024-08-28)

### CRM API

- Added type filter in [Activities](apis/crm/reference#tag/Activities)
- Added `owner_name` to [Leads](apis/crm/reference#tag/Leads) schema.

### HRIS API

- Added pass_through property to HRIS API.
- Added `id` as optional field in [Employee](apis/hris/reference#tag/Employees) schema.

### Accounting API

- Added accounting_period in [Bill](apis/accounting/reference#tag/Bills) and [Journal Entry](apis/accounting/reference#tag/Journal-Entries) schema.
- Added `line_number` to Invoice Line Items and Journal Entry Line Items.
- Added supplier_id filter to [Purchase Orders](apis/accounting/reference#tag/Purchase-Orders).
- Added code in [Tracking Categories](apis/accounting/reference#tag/Tracking-Categories) schema.

## v10.7.0 - (2024-07-16)

### Accounting API

- Added [Tracking Categories](apis/accounting/reference#tag/Tracking-Categories) schema.
- Added [Tracking Categories](apis/accounting/reference#tag/Tracking-Categories) support for [Quickbooks](connectors/quickbook) connector.

## v10.6.3 - (2024-07-11)

### Vault API

- Added `validate` [Validate Connection State](/apis/vault/reference#operation/validateConnectionState) to validate the state of a connection is set to 'callable'.

## v10.6.2 - (2024-06-25)

### Accounting API

- Updated [Balance Sheet](apis/accounting/reference#tag/Balance-Sheet) schema.

## v10.6.1 - (2024-06-24)

### Accounting API

- Updated [Balance Sheet](apis/accounting/reference#tag/Balance-Sheet) schema.

## v10.6.0 - (2024-06-19)

### HRIS and ATS API

- Added support for OAuth 2.0 for [SAP SuccessFactors](connectors/sap-successfactors)

## v10.5.0 - (2024-06-19)

### Unify

- Introduction of the `pass_though` property as part of the [Unified Pass Through](https://developers.apideck.com/guides/pass-through) feature

## v10.4.2 - (2024-05-10)

### Ecommerce API

- Added `updated_since` and `created_since` filter support for [Orders](apis/ecommerce/reference#tag/EcommerceOrders).

### Accounting API

- Added `created_since` filter support for [Invoices](apis/accounting/reference#tag/Invoices).

## v10.4.1 - (2024-05-06)

### Accounting API

- Added `opportunity_ids` field to [Contacts](apis/accounting/reference#tag/Contacts)
- Updated Balance Sheet schema.

## v10.4.0 - (2024-03-26)

### Accounting API

- Add endpoints for Attachments (all, one, delete, download, upload)
- Add support for attachments to [Quickbooks](connectors/quickbooks)
- Add support for attachments to [Xero](connectors/xero)

## v10.3.6 - (2024-03-07)

### Vault API

- Remove required `refresh_token` when calling [Import Connection](apis/vault/reference#operation/connectionsImport) operation. This allows import of ApiKey based connections as well as those with long lived tokens, or tokens that are obtained via client credentials.

## v10.3.5 - (2024-03-01)

### HRIS

- Employee job `is_manager` field is now supported for [Hibob](connectors/hibob)

## v10.3.4 - (2024-02-26)

### Proxy

- Schema description for Proxy request bodies [`POST`, `PUT`, `PATCH`] extended to allow for `object`, `string` or `array`.

## v10.3.3 - (2024-02-23)

### Vault

- Including the [connectionsToken](apis/vault/reference#operation/connectionsToken) in SDK supported operations.
- Only connections with `auth_type` `oauth2` and `grant_type` `authorization_code` will have the `authorize_url` and `revoke_url` in the response.

## v10.3.2 - (2024-02-21)

### Accounting API

- Added [Microsoft Dynamics Business Central](connectors/microsoft-dynamics-365-business-central) connector
- Added filtering resources by update_since support for [Quickbooks](connectors/quickbooks) connector
- Added `company_id` field to [Bill](apis/accounting/reference#tag/Bills), [Credit Note](apis/accounting/reference#tag/Credit-Notes), [Customer](apis/accounting/reference#tag/Customers), [Invoice](apis/accounting/reference#tag/Invoices), [Journal Entry](apis/accounting/reference#tag/Journal-Entries), [Payment](apis/accounting/reference#tag/Payments), [Purchase Order](apis/accounting/reference#tag/Purchase-Orders), [Supplier](apis/accounting/reference#tag/Suppliers),

### Ecommerce API

- Added sorting orders support for [Wix](connectors/wix) connector

## v10.3.1 - (2024-02-20)

### Unify

- When a `ConnectorExecutionError` occurs, we attempt to proxy as much detail from downstream as we can. An update to the UnauthorizedError Schema now correctly reflects that the downstream error can be provided as a string OR an object.

## v10.3.0 - (2024-01-31)

### Accounting API

- Added all, one, create, update and delete Departments and Locations endpoint
- Release Departments and Locations endpoint for [Netsuite](connectors/netsuite)

## v10.2.2 - (2024-01-19)

### Accounting API

- Added create, update and delete Subsidiaries endpoint
- Release Subsidiaries endpoint for [Netsuite](connectors/sage-netsuite)

## v10.2.1 - (2024-01-18)

### Proxy API

- Added 2 new `static IPs`

## v10.2.0 - (2024-01-05)

### Accounting API

- Added get and list Subsidiaries endpoint
- Release Subsidiaries endpoint for [Sage Intacct](connectors/sage-intacct)

### HRIS API

- Added of the [Kenjo](connectors/kenjo) connector as early-access
- Added of the [Sesame HR](connectors/kenjo) connector as early-access
- Added of the [Cezanne HR](connectors/cezannehr) connector as early-access
- Improved mapping manager for employee for [AFAS](connectors/afas)

- Added and improved of the mapping for departments for integrations: [AFAS](connectors/afas), [AlexisHR](connectors/alexishr), [BambooHR](connectors/bamboohr), [Breathe HR](connectors/breathehr), [Deel](connectors/deel), [Loket](connectors/loket-nl), [Lucca HR](connectors/lucca-hr), Rippling, [NMBRS](connectors/nmbrs), [Officient](connectors/officient-io),

### Issue tracking

- Added [Shortcut](connectors/shortcut) as an auth-only connector

### CRM API

- Updated filtering & sorting for Activities for [Salesforce](connectors/salesforce)
- Updated filtering & sorting for Opportunities for [Salesforce](connectors/salesforce)
- Added filtering for Activities for [Pipedrive](connectors/pipedrive)

### Ecommerce API

- Added [Amazon Seller Central](connectors/amazon-seller-central) with resources: orders, products

## v10.1.3 - (2023-12-18)

### HRIS API

- Release of the [Holded](connectors/holded) connector with support for the Employee resources
- Added manager info for an employee for [AFAS](connectors/afas)
- Improved employee mapping for [BambooHR](connectors/bamboohr)
- Improved employee mapping for [NMBRS](connectors/nmbrs)

### Issue tracking

- Added [Basecamp](connectors/basecamp) as an auth-only connector

### Connector API

- Fix [Connector Resource](apis/connector/reference#operation/connectorResourcesOne) to describe supported_properties as circular reference

## v10.1.2 - (2023-12-12)

### Accounting API

- Improved the write Journal Entry mapping for [Netsuite](connectors/netsuite)
- Added `company_id` to the Journal Entry model
- Added the option to enter Sender ID & Password in Vault for [Sage Intacct](connectors/sage-intacct)

### CRM API

- Added additional filtering for Contacts for [Microsoft Dynamics CRM](connectors/microsoft-dynamics)
- Added mapping for reading/writing Notes for [Zoho CRM](connectors/zoho-crm)
- Added mapping for Users for [Zoho CRM](connectors/zoho-crm)
- Added mapping for Users for [Pipedrive](connectors/pipedrive)
- Added filtering for Contacts for [Pipedrive](connectors/pipedrive)

## v10.1.1 - (2023-12-06)

### HRIS API

- Overall improvements of the coverage for department properties for integrations: Gusto, [Cascade HR](connectors/cascade-hr)

### CRM API

- Added sorting capabilities for the Unify Activities
- Added filtering by `company_id`, `owner_id`, `contact_id` for the Unify resource Activity
- Added filtering by `owner_id`, `primary_contact_id` for the Unify resource Opportunity
- Added sorting & filtering for Opportunities and Activities for [Microsoft Dynamics CRM](connectors/microsoft-dynamics)
- Added mapping for reading/writing Notes for [Microsoft Dynamics CRM](connectors/microsoft-dynamics)
- Added mapping for reading/writing Notes for [Close](connectors/close)
- Removed minLength for a Unify Contact

### Accounting API

- Added the option to write Journal Entries for [Netsuite](connectors/netsuite)
- Added the option to write Journal Entries for [Sage Intacct](connectors/sage-intacct)
- Improved the [Xero](connectors/xero) mapping for Bills

## v10.1.0 - (2023-12-04)

### Ecommerce API

- Added `customer_id` filter to E-Commerce: [Orders](apis/ecommerce/reference#tag/Orders)

### HRIS API

- Improved employee mapping & pagination for [UKG Pro](connectors/ukg-pro)
- Deprecated API key authentication & "people" endpoint for [Hibob](connectors/hibob) in favor a new faster "people/search" endpoint and Service User authentication.
- Improved employee mapping for [Hibob](connectors/hibob)
- Extended the employee mapping for [Ceridian Dayforce](connectors/ceridian-dayforce)
- Overall improvements of the coverage for employee properties for integrations: [Officient](connectors/officient-io), [Namely](connectors/namely), [Paychex](connectors/paychex), [PayFit](connectors/payfit), [Ceridian Dayforce](connectors/ceridian-dayforce), [Cegid talentsoft](connectors/cegid-talentsoft), [Employment Hero](connectors/employmenthero)
- Employee model `leaving_reason` can be null

### Accounting API

- Added write support for Journal Entries for [Exact Online](connectors/exact-online)
- Added filtering & sorting options for [Netsuite](connectors/netsuite)

### Proxy API

- Added automatic HMAC authentication for [Netsuite](connectors/netsuite)

### Ecommerce API

- Added orders filter by customer_id on [Shopify](connectors/shopify), [Picqer](connectors/picqer), [Shopware](connectors/shopware), [BigCommerce](connectors/bigcommerce), [Prestashop](connectors/prestashop), [Magento](connectors/woocommerce)

### ATS API

- Added support for writing Job applications for [Teamtailor](connectors/teamtailor)

### CRM API

- Added [Attio](connectors/attio) as auth-only integration

## v10.0.1 - (2023-10-31)

### Accounting API

- remove `custom_mappings` from `InvoiceLineItem` as only belongs on root of resources

### HRIS API

- Release of the [Charlie HR](connectors/charliehr) connector with support for the resources: Employee, Department, Time-off
- The [Humaans](connectors/humaans-io) includes inactive employees by default.
- Overall improvements of the coverage for employee properties for integrations: [Google Workspace](connectors/google-workspace), [Lucca HR](connectors/lucca-hr), [Rippling](connectors/rippling) ,[SD Worx](connectors/sdworx), [ADP run](connectors/adp-run), [ADP Workforce Now](connectors/adp-workforce-now), [Breathe HR](connectors/breathehr), [Deel](connectors/deel), [Freshteam](connectors/freshteam), [Loket](connectors/loket-nl), [Paylocity](connectors/paylocity), [NMBRS](connectors/nmbrs), [Sage HR](connectors/sage-hr), [Zenefits](connectors/zenefits)

### Filestorage API

- Improved the filtering for [Dropbox](connectors/dropbox)
- Reviewed the for [OneDrive](connectors/onedrive) & [Sharepoint](connectors/sharepoint) connectors

## v10.0.0 - (2023-10-24)

### Unify

- Introduction of the `custom_mappings` property as part of the Custom Mapping field feature

## v9.9.3 - (2023-10-23)

### Accounting API

- Extended [Journal Entries](https://developers.apideck.com/apis/accounting/reference#tag/Journal-Entries) with customer.

### HRIS API

- Release of the [CatalystOne](connectors/catalystone) connector with support for the resources: Employee, Department
- Improvement of the employment status for [People HR](connectors/people-hr)
- Extended [Rippling](connectors/rippling) mapping with custom_fields and company information
- Added custom_fields mapping for [Lucca HR](connectors/lucca-hr)
- Added custom_fields mapping for [Google Workspace](connectors/google-workspace)

### File Storage API

- Fix for the search operation for the [Dropbox](connectors/dropbox) connector

## v9.9.2 - (2023-09-29)

### HRIS API

- Corrected employees model for GetEmployeesResponse, which impacted the SDKs

## v9.9.1 - (2023-09-25)

### HRIS API

- Added a new property `ethnicity` to the [Employee](apis/hris/reference#tag/Employees) resource

- Added jobs fields mappings for [SD Worx](connectors/sdworx)
- Added support for custom fields for [Sage HR](connectors/sage-hr)
- Improved pagination for [UKG Pro](connectors/ukg-pro)
- Extended [Cascade HR](connectors/cascade-hr) mapping with middle_name, preferred_name, initials, marital_status, division, department, team, company, employment_role, manager, jobs, compensations information
- Extended [AlexisHR](connectors/alexishr) mapping with initials, company_name, pronouns, custom_fields, compensation information
- Extended [Humaans](connectors/humaans-io) mapping with display_name, initials, department, team, manager, ssn, pronouns, languages, photo_url, jobs, custom_fields, compensation information
- Added custom_fields mapping for [SAP Successfactors](connectors/sap-successfactors)
- Added custom_fields mapping for [Okta](connectors/okta)
- Added departments resource mapping for [SAP Successfactors](connectors/sap-successfactors)
- Added departments resource mapping for [Azure AD](connectors/azure-active-directory)
- Added departments resource mapping for [Humaans](connectors/humaans-io)
- Added departments resource mapping for [Google Workspace](connectors/google-workspace)

- Mapped the ethnicity field for the connectors that support it: [ADP run](connectors/adp-run), [ADP Workforce Now](connectors/adp-workforce-now), [BambooHR](connectors/bamboohr), [Breathe HR](connectors/breathehr), [Cascade HR](connectors/cascade-hr), [Ceridian Dayforce](connectors/ceridian-dayforce), [Hibob](connectors/hibob), [Justworks](connectors/justworks), [Namely](connectors/namely), [Paychex](connectors/paychex), [Trinet](connectors/trinet), [UKG Pro](connectors/ukg-pro), [Workday](connectors/workday)

### Accounting API

- Added option to write journal entries and improved pagination for journal entries for [Xero](connectors/xero)
- Improved bills, tax rate, company & suppliers mapping for [Quickbooks](connectors/quickbooks)
- Improved bill_number mapping for [Sage Business Cloud](connectors/sage-business-cloud-accounting)
- Improved bill_number mapping for [Sage Intacct](connectors/sage-intacct)
- Added the option to create and update invoices for [Sage Business Cloud](connectors/sage-business-cloud-accounting)

### CRM API

- Added filter contacts by Company ID for [Salesforce](connectors/salesforce)
- Improved custom fields logic for companies, contacts/leads for [Hubspot](connectors/hubspot)
- Improved address mapping for companies for [Pipedrive](connectors/pipedrive)

### ATS API

- Added custom job board URL setting for [Greenhouse](connectors/greenhouse)

### Issue tracking API

- Added [Zendesk](connectors/zendesk) as auth-only integration
- Added [Linear](connectors/linear) as auth-only integration
- Added [ClickUp](connectors/clickup) as auth-only integration
- Added [Asana](connectors/asana) as auth-only integration
- Added [Intercom](connectors/intercom) as auth-only integration
- Added [Monday](connectors/monday) as auth-only integration

## v9.9.0 - (2023-08-21)

### HRIS API

- Release of the [Paycheck](/apis/hris/paychex) connector with support for the resources: Employee, Department, Company
- Early-access release of the Silae connector with support for the Employee resource
- Early-access release of the [Cegid talentsoft](connectors/cegid-talentsoft) connector with support for the Employee resource
- Early-access release of the [Justworks](connectors/justworks) connector with support for the Employee resource
- Early-access release of the [Trinet](connectors/trinet) connector with support for the Employee resource

- Enhanced additional employee resource properties with null support
- Improved employee_status logic for [Personio](connectors/personio)
- Improved country field mapping for [SD Worx](connectors/sdworx)
- Extended mapping of [Workday](connectors/workday) with custom fields and locations
- Added employee_status mapping for [Paylocity](connectors/paylocity)
- Added custom field support for [Sage HR](connectors/sage-hr)

### Issue Tracking API

- Improved handling of null values for the Issue Tracking API

### CRM API

- Improved handling of null values for the Issue Tracking API

### File Storage API

- Improved calculation of the downloadable detection
- Improved handling of null values for the File Storage API

### E-commerce API

- Improved handling of null values for the Ecommerce API

### ATS API

- Added the job description field to the [Job](apis/ats/reference#tag/Jobs) resource for [Greenhouse](connectors/greenhouse)

### Accounting API

- Added category tracking support and improved the supplier mapping for [Quickbooks](connectors/quickbooks)

## v9.8.1 - (2023-08-02)

### ACCOUNTING API

- Released [Netsuite](connectors/netsuite) with additional resources: Invoices, Customers, Payments, Suppliers, Journal Entries, Ledger Accounts, Bills, Products, Credit notes, Purchase Orders

### HRIS API

- Released [People HR](connectors/people-hr) connector with support for Employees
- Released [Deel](connectors/deel) connector with support for Employees
- Released [Employment Hero](connectors/employmenthero) connector with support for Employees
- Overall improvements of the coverage for employee properties for integrations: ADP Run, ADP Workforce Now, Afas, Alexis HR, BambooHr, BeatheHr, Cascade HR, Ceridian Dayforce, Deel, Employment hero, Factorial HR, Freshteam, Google Workspace, Gusto, Hibob, Humaans, Lokket, Lucca HR, Namely, Nmbrs, Officient, Payfit, Paylocity, People-hr, Personio, Rippling, Sage-hr, Sap-successfactors, Sapling, SD Worx, UKG Pro, Workday, Zenefits, Zoho-people

- Extended employee resource properties with nullable
- Improved employees [SAP SuccessFactors](connectors/sap-successfactors) mapping
- Enhanced employees [Workday](connectors/workday) mapping
- Performance & employee mapping improvements + updated the connection guide for [HiBob](connectors/hibob)
- Introduced write (create,update, delete) support for [HiBob](connectors/hibob)
- Extended [Breathe HR](connectors/breathehr) mapping for employees
- Implemented native webhook events for [Okta](connectors/okta)

### Ecommmerce API

- Changed the authentication for [Shopify](connectors/shopify) from OAuth to API key

### CRM

- Improved updating leads & contacts for [Salesforce](connectors/salesforce)

## v9.8.0 - (2023-07-19)

### File Storage API

- Added [Export File](apis/file-storage/reference#operation/filesExport) endpoint. This endpoint lets you convert files into other formats and download them. Handy for working with Google Docs, Slides, and Sheets. Right now, it's only supported for Google Drive.

## v9.7.6 - (2023-07-10)

- Add `bank_accounts` support to the [Employee](apis/hris/reference#tag/Employees) resource.

## v9.7.5 - (2023-07-05)

- Add the `payment_frequency` field on the [Employee](apis/hris/reference#tag/Employees) compensations resource.

## v9.7.4 - (2023-06-06)

- Adding properties object to PassThroughQuery as it is required for OpenAPI Generator.

## v9.7.3 - (2023-06-06)

### Vault API

- New webhook event `vault.connection.revoked` is now available to subscribe to. Event is broadcast when a call to revoke an access token down stream is successful.

## v9.7.2 - (2023-06-05)

- Fix webhook schema object names to align across APIs

## v9.7.1 - (2023-06-03)

### ACCOUNTING API

- Added `status` filter to [Quickbooks](connectors/quickbooks).

## v9.7.0 - (2023-05-31)

### Accounting API

### Resources

- [Purchase Orders](apis/accounting/reference#tag/Purchase-Orders)

### Connectors

- Added new [Procountor](connectors/procountor-fi) connector
- Added new [Netvisor](connectors/visma-netvisor) connector
- Updated [Quickbooks](connectors/quickbooks) connector with Purchase Order support
- Updated [Xero](connectors/xero) connector with Purchase Order support

### ATS API

### Connectors

- Updated [Lever](connectors/lever) connector
- Updated [Teamtailor](connectors/teamtailor) connector
- Updated [Workable](connectors/workable) connector
- Updated [Greenhouse](connectors/greenhouse) connector
- Updated [Workday](connectors/workday) connector
- Updated [SAP-Successfactors](connectors/sap-successfactors) connector
- Updated [Freshteam](connectors/freshteam) connector
- Updated [Sage HR](connectors/sage-hr) connector
- Updated [Recruitee](connectors/recruitee) connector

## v9.6.0 - (2023-05-25)

### HRIS API

- Add the `probation_period` field on the [Employee](apis/hris/reference#tag/Employees) resource.

## v9.5.0 - (2023-05-15)

### Accounting API

- Added new connectors for [Kashflow](connectors/kashflow) and [Clearbooks](connectors/clearbooks-uk)
- Updated [Exact Online](connectors/exact-online) connector

### HRIS API

- Added [Employee Terminated](/apis/hris/reference#operation/employeeTerminated) event.

## v9.4.0 - (2023-05-09)

### ATS API

- Added [Create Applicant](/apis/ats/reference#operation/applicantsCreate) and added [Delete Applicant](/apis/ats/reference#operation/applicantsUpdate)

## v9.3.1 - (2023-05-07)

### ATS API

- Added `job_id` filter to [Teamtailor](connectors/teamtailor).

## v9.3.0 - (2023-04-18)

### Vault API

- Added new `invalid` state and new `validation_support` field on [Connections](apis/vault/reference#tag/Connections) to support connection validation.
- Added `prefix` and `suffix` to `form_fields` on [Connections](apis/vault/reference#tag/Connections)

## v9.2.0 - (2023-04-17)

### HRIS API

- Deprecate the `department` field in favor of the dedicated `department_id` and `department_name` field on the [Employee](apis/hris/reference#tag/Employees) resource.

## v9.1.5 - (2023-04-17)

### HRIS API

- Improved Sage-HR mapping

### Unify

- Updated Unify specs by referencing the PassThrough query parameter required for the Unify SDKs

## v9.1.4 - (2023-04-14)

### Accounting API

- added optional `payment_method_id` to [Payments](apis/accounting/reference#tag/Payments) resource.
- added `taxable` to [InvoiceItems](apis/accounting/reference#tag/InvoiceItems) resource.

## v9.1.3 - (2023-04-13)

- Unify shared field representing `currency` enum extended to include `ETH`

## v9.1.2 - (2023-03-24)

### Accounting API

- pass_through parameter is now available on all list endpoints.
- added `terms` to [Credit Notes](apis/accounting/reference#tag/Credit-Notes) resource.
- added `rate` to [Tax Rates](apis/accounting/reference#tag/Tax-Rates) resource.

## v9.1.1 - (2023-03-13)

### Accounting API

- Added `discount_amount` to [Invoices](apis/accounting/reference#tag/Invoices) resource and it's Line Items.

## v9.1.0 - (2023-02-28)

- Added `List Tags` endpoint to [Issue Tracking API](apis/issue-tracking/reference).

## v9.0.0 - (2023-02-24)

### Connector API

- Removed `resource` property in `supported_events` of a [Connector](https://developers.apideck.com/apis/connector/reference).
- Added `resources` and `entity_type` property in `supported_events` of a [Connector](https://developers.apideck.com/apis/connector/reference).

## v8.93.0 - (2023-02-23)

### Issue Tracking API

Added the [Issue Tracking API](apis/issue-tracking/reference).

### Resources

- [Tickets](apis/issue-tracking/reference#tag/Tickets)
- [Collections](apis/issue-tracking/reference#tag/Collections)
- [Users](apis/issue-tracking/reference#tag/Users)
- [Comments](apis/issue-tracking/reference#tag/Comments)

### Webhooks

- [Webhook Events](apis/issue-tracking/reference#tag/Webhook-Events)

### Connectors

- [GitLab](connectors/gitlab)
- [GitHub](connectors/github)
- [Jira](connectors/jira)

## v8.92.0 - (2023-02-22)

### File Storage API

- Added [Rename or move File](apis/file-storage/reference#operation/filesUpdate).

## v8.91.1 - (2023-02-22)

### Ecommerce API

- [Product](apis/ecommerce/reference#tag/Product) `inventory` property is now a string instead of number.

### Connectors

- [Magento](connectors/magento)

## v8.91.0 - (2023-02-15)

- Added `parent` and `project` fields to the [Customer](apis/accounting/reference#tag/Customer) schema on Accounting.

## v8.90.0 - (2023-02-15)

### Ecommerce API

Added the [Ecommerce API](apis/ecommerce/reference).

### Resources

- [Orders](apis/ecommerce/reference#tag/Orders)
- [Customers](apis/ecommerce/reference#tag/Customers)
- [Products](apis/ecommerce/reference#tag/Products)
- [Store](apis/ecommerce/reference#tag/Stores)

### Connectors

- [BigCommerce](connectors/bigcommerce)
- [Lightspeed](connectors/lightspeed)
- [Picqer](connectors/picqer)
- [Shopify](connectors/shopify)
- [Shopware](connectors/shopware)
- [Wix](connectors/wix)
- [Magento](connectors/woocommerce)
- [Prestashop](connectors/prestashop)

## v8.89.0 - (2023-02-07)

### Accounting API

- Added the [Journal Entries](apis/accounting/reference#tag/JournalEntries) resource.

## v8.88.0 - (2023-02-07)

### CRM API

- Added the [Users](apis/crm/reference#tag/Users) resource to [HubSpot](connectors/hubspot).

## v8.87.0 - (2023-01-24)

### CRM API

- Added `filter[updated_since]` to [Activities](apis/crm/reference#tag/Activities)

## v8.86.0 - (2023-01-11)

### Vault API

- Added [Create Consumer](/apis/vault/reference#operation/consumersCreate)
- Added [Update Consumer](/apis/vault/reference#operation/consumersUpdate)
- Added [Delete Consumer](/apis/vault/reference#operation/consumersDelete)

## v8.85.1 - (2022-12-19)

### Webhooks API

- Added `disabled_reason` to [Webhook](apis/webhooks/reference#tag/Webhooks) to reflect when a webhook has been automatically disabled.

## v8.85.0 - (2022-11-15)

### Connector API

- Added `free_trial_available`, `signup_url` and `webhook_support` to [Connector](apis/connector/reference#tag/Connectors)

### CRM API

- Added `company_id` filter to [Opportunities](apis/crm/reference#tag/Opportunities)

## v8.84.0 - (2022-11-12)

### ATS API

- Added [Jobs](apis/ats/reference#tag/Jobs) and [Applicants](apis/ats/reference#tag/Applicants) resource to [SAP SuccessFactors](connectors/sap-successfactors).
- Added `created_by` and `updated_by` fields to the Applicant schema.

## v8.83.0 - (2022-11-10)

- Added [Mollie](/connectors/mollie) and [monday.com](/connectors/monday) auth-only connector

## v8.82.0 - (2022-11-09)

- Added [Calendly](/connectors/calendly) and [Google Contacts](/connectors/google-contacts) auth-only connector

## v8.81.0 - (2022-11-09)

### HRIS API

- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [ADP Workforce Now](connectors/adp-workforce-now).
- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [BambooHR](connectors/bamboohr).
- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [Personio](connectors/personio).
- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [Sage Hr](connectors/sage-hr).
- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [SAP SuccessFactors](connectors/sap-successfactors).
- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource to [Workday](connectors/workday).

### ATS API

- Added `job_id` filter to [Recruitee](connectors/recruitee).

## v8.80.0 - (2022-11-07)

### ATS API

- Added `jobs` resource to [Greenhouse](connectors/greenhouse).

## v8.79.0 - (2022-11-07)

### Procurement API

- Added [Portt](/connectors/portt) auth-only connector

### Expense management API

- Moved the [Web Expenses](/connectors/webexpenses) auth-only settings to connection level

### Connector API

- Added `custom_scopes` to [Connector](apis/connector/reference#tag/Connectors)

## v8.78.0 - (2022-11-07)

- Added webhooksResolve operation to the Webhooks API to provide a shorter route.

## v8.77.0 - (2022-11-03)

- Updated Orders [Clover](apis/pos) on POS with additional modifier fields on line items.

## v8.76.0 - (2022-10-31)

- Added Connection Hooks
- Added support cor Connection based Webhooks
- Added Connection webhook support [FactorialHR](/connectors/factorialhr)

### Vault API

- Added subscriptions prop to [Connections](apis/vault/reference#tag/Connections)

## v8.75.0 - (2022-10-28)

### ACCOUNTING API

- Added `credit-notes` resource to [Sage Intacct](/connectors/sage-intacct).
- Added create, update and delete operations to payments resource in [Sage Intacct](/connectors/sage-intacct).
- Added workflows to separate between receivable payments and payable payments in [Sage Intacct](/connectors/sage-intacct).
- Expanded `invoices` resource mapping in [Sage Intacct](/connectors/sage-intacct).
- Expanded fields to `Bill`, `BillLineItem`, `CreditNote`, `InvoiceLineItem` and `Payment` schemas.
- Updated workflow client to support `unified_metadata`.

## v8.74.0 - (2022-10-27)

### Connector API

- Added `downstream_unsupported_operations` to [ConnectorResource](apis/connector/reference#tag/ConnectorResource)
- # Added `unified_apis[].downstream_unsupported_resources` to [Connector](apis/connector/reference#tag/Connectors)

## v8.73.0 - (2022-10-27)

- Added [Google Calendar](/connectors/google-calendar) auth-only connector
- Added [Microsoft Outlook Calendar](/connectors/microsoft-outlook-calendar) auth-only connector

## v8.72.1 - (2022-10-24)

### Accounting API

- Updated Ledger accounts, invoice items, payments, suppliers to use [QuickBooks] SyncToken

## v8.72.0 - (2022-10-18)

### Accounting API

- Added `bill`, resource for [Sage Intacct](/connectors/sage-intacct).
- Improved array mappings for xml cases.
- Added new fields to the Bill schema.

## v8.71.0 - (2022-10-17)

### Connector API

- Added `unified_apis[].name` and `unified_apis[].supported_resources` to [Connector](apis/connector/reference#tag/Connectors)
- Added `?unified_api` parameter to [ConnectorResource](apis/connector/reference#tag/Connector-Resources)

## v8.70.2 - (2022-10-14)

### Vault API

- Add `show_sidebar` to settings on [create session](apis/vault/reference#tag/Sessions).

## v8.70.1 - (2022-10-13)

### Accounting API

- Added `discount_percentage` to root of [Invoice](apis/accounting/reference#tag/Invoices) object. Quickbooks has limited support for LineItem discounts, so this is a workaround to support discounts on invoices.

## v8.70.0 - (2022-10-11)

### HRIS API

- Reworked [Workday](/connectors/workday) auth + mapping to use SOAP API

### Expense management API

- Added [Web Expenses](/connectors/webexpenses) auth-only connector

## v8.69.0 - (2022-10-07)

### HRIS API

- Added [Ceridian Dayforce](connectors/ceridian-dayforce) connector

## v8.68.0 - (2022-10-06)

- Added `create`, `update` and `delete` operations to `credit-notes` resource for [QuickBooks].

## v8.67.1 - (2022-09-30)

### Connector API

- extended connector API to return nested filed level coverage

## v8.67.0 - (2022-09-29)

### Accounting API

- Added `display_id`, `created_by` and `updated_by` fields to the Payment schema.

## v8.66.0 - (2022-09-28)

- Added filter support for employees in [Loket](connectors/loket-nl) connector.
- Added support to filter employees by employee number.
- Added [Lucca HR](connectors/lucca-hr) connector

## v8.65.0 - (2022-09-28)

### HRIS API

- Added [SDWorx](connectors/sdworx) as an auth-only connector.

## v8.64.0 - (2022-09-28)

### Accounting API

- Added [NetSuite](connectors/netsuite) as an auth-only connector.

## v8.63.0 - (2022-09-27)

- Added the Project Management API for auth-only connectors.
- Added [JIRA](connectors/jira) as an auth-only connector.

## v8.62.0 - (2022-09-27)

### HRIS API

- Added Jobs support for [Officient](connectors/officient-io).

## v8.61.0 - (2022-09-26)

### HRIS API

- Added filter support for employees in [ADP Workforce Now](connectors/adp-workforce-now) connector.

## v8.60.0 - (2022-09-23)

### HRIS API

- Added [Time Off Requests](apis/hris/reference#tag/TimeOffRequests) resource.

## v8.59.0 - (2022-09-22)

### Team Messaging API

- Added [Microsoft Teams](connectors/microsoft-teams) connector

## v8.58.0 - (2022-09-19)

### Connector API

- Added `blind_mapping` to [Connector](apis/connector/reference#tag/Connectors)

## v8.57.0 - (2022-09-13)

### HRIS API

- Added [PayFit](connectors/payfit) connector

## v8.56.0 - (2022-09-12)

### HRIS API

- Added [Okta](connectors/okta) connector

## v8.55.0 - (2022-09-12)

### HRIS API

- Added [Alexis HR](connectors/alexishr) connector

## v8.54.0 - (2022-09-12)

### HRIS API

- Added [Microsoft Dynamics HR](connectors/microsoft-dynamics-hr) connector

## v8.53.0 - (2022-09-09)

### HRIS API

- Added [Namely](connectors/namely) connector.

## v8.52.1 - (2022-09-09)

- Generalize example detail for Unprocessable Entity Error to prevent confusing when using the Mock API (sunsetted).

## v8.52.0 - (2022-09-07)

- Added [Paylocity](connectors/paylocity) connector

## v8.51.0 - (2022-09-06)

- Expanded support for `Employees` for the [UKG Pro](connectors/ukg-pro) connector

## v8.50.0 - (2022-09-06)

- Added [Zoho People](connectors/zoho-people) connector

## v8.49.0 - (2022-09-05)

### ACTION REQUIRED

Beta users should note the following breaking changes that may affect existing integrations implementing the `POS` API:

- The schema description for a `bank_account` on the `Payments` object has been defined as `PosBankAccount` to avoid confusion with the `BankAccount` object in other APIs.
- This change is backwards compatible, but we recommend updating your integrations to use the new name if you are using typed definitions.
- **Note:** the properties on the `PosBankAccount` object have not changed. [PosPayments](apis/pos/reference#tag/Payments)

## v8.48.0 - (2022-09-05)

- Added [UKG Pro](connectors/ukg-pro) connector

## v8.47.0 - (2022-09-05)

- Added [ADP Workforce Now](connectors/adp-workforce-now) connector
- extended gender enum to include `not-specified`
- Added `tls_support` to [Connector](apis/connector/reference#tag/Connectors)

## v8.46.0 - (2022-09-02)

### HRIS API

- Added [Zenefits](connectors/zenefits) connector

## v8.45.0 - (2022-09-02)

### HRIS API

- Added [Factorial](connectors/factorial) connector.

## v8.44.0 - (2022-09-01)

### HRIS API

- Added [Sapling](connectors/sapling) connector

## v8.43.0 - (2022-08-30)

### HRIS API

- Added [Freshteam](connectors/freshteam) connector

## v8.42.0 - (2022-08-24)

### Accounting API

- Added sorting support to [Invoices](apis/accounting/reference#tag/Invoices). To sort results, use the `sort[by]` and `sort[direction]` query parameters. First available `sort[by]` value is `updated_at`. Supported for [Xero](connectors/xero) and [Quickbooks](connectors/quickbooks).

## v8.41.1 - (2022-08-24)

### Accounting API

- Make `invoice_date` and `due_date` nullable on [Invoices](apis/accounting/reference#tag/Invoices)

## v8.41.0 - (2022-08-17)

### Accounting API

- Added [Credit Note](apis/accounting/reference#tag/Credit-Notes) support.
- Added Credit Notes support for [Xero](connectors/xero).
- Added Credit Notes readOnly support for [Quickbooks](connectors/quickbooks).

## v8.40.1 - (2022-08-16)

### Accounting API

- Added `filter[start_date]`, `filter[end_date]` to [Customers](apis/accounting/reference#tag/Balance-Sheet)

## v8.40.0 - (2022-08-15)

- Added Mock API and SDKs to documentation for all APIs.

## v8.39.1 - (2022-08-10)

### Accounting API

- Added [Bills](apis/accounting/reference#tag/Bills)

## v8.39.0 - (2022-08-09)

### Connector API

- Added `supported_list_fields` to [ConnectorResource](apis/connector/reference#tag/ConnectorResource)

## v8.38.0 - (2022-08-03)

- Added [Drives](apis/file-storage/reference#tag/Drives) resource on the File Storage API.
- Added [Drive Groups](apis/file-storage/reference#tag/DriveGroups) resource on the File Storage API.

## v8.37.1 - (2022-07-25)

- Mapped `price_amount` property on variations to [Items](apis/pos/reference#tag/Items) on the POS API for the [Square](connectors/square) connector.

## v8.37.0 - (2022-07-20)

- Added `modifier_groups` property to [Items](apis/pos/reference#tag/Items) on the POS API.

## v8.36.0 - (2022-07-20)

- Added `status` property to [Company info](apis/accounting/reference#tag/Company-Info) on the Accounting API and for the [MYOB](connectors/myob) connector.

## v8.35.1 - (2022-07-20)

- Added docs for [QuickBooks](connectors/quickbooks) as supported connector for [Profit And Loss](apis/accounting/reference#tag/Profit-and-Loss) resource on the Accounting API.

## v8.35.0 - (2022-07-20)

- Added [Profit And Loss](apis/accounting/reference#tag/Profit-and-Loss) resource on the Accounting API.

## v8.34.0 - (2022-07-06)

- Added [Jobs](apis/hris/reference#tag/Employees) on the HRIS API

## v8.33.0 - (2022-07-02)

- Added `deceased_on` and `partner` to [Employee](apis/hris/reference#tag/Employees) on the HRIS API.
- Added new resource [EmployeeSchedules](https://developers.apideck.com/apis/hris/reference#tag/Employee-Schedules) on the HRIS API.

## v8.32.6 - (2022-06-24)

- Fix faulty examples

## v8.32.5 - (2022-06-21)

- Updated Orders and Payments for the [Clover](connectors/clover) connector

## v8.32.4 - (2022-06-16)

- Added `filter[first_name]` and `filter[display_name`] to to [Customers](apis/accounting/reference#tag/Customer)
- Added `automated_sales_tax` to [CompanyInfo](apis/accounting/reference#tag/CompanyInfo)

## v8.32.3 - (2022-06-15)

- Added `country`, `sales_tax_enabled` and `default_sales_tax` to [CompanyInfo](apis/accounting/reference#tag/CompanyInfo)

## v8.32.2 - (2022-06-15)

### Accounting API

- Added `filter[company_name]`, `filter[last_name]`, `filter[email]` to [Customers](apis/accounting/reference#tag/Customer)

## v8.32.1 - (2022-06-08)

### [ATS API](apis/ats/reference)

- Extended `department` properties on [Jobs](apis/ats/reference#tag/Job)

## v8.32.0 - (2022-06-03)

### [HRIS API](apis/hris/reference)

- Added [Humaans](connectors/humaans-io)

## v8.31.3 - (2022-06-02)

### Accounting API

- Added filter[name] to [InvoiceItems](apis/accounting/reference#tag/InvoiceItem)

## v8.31.2 - (2022-06-01)

- Added `row_type` [Companies](apis/crm/reference#tag/Company)

## v8.31.1 - (2022-05-31)

- Added [`ConnectorOperationUnsupportedError`](errors#connectoroperationunsupportederror) to provide detail when a Unify call is made that the downstream connector does not support.

### Accounting API

### ACTION REQUIRED

Beta users should note the following breaking changes that may affect existing integrations implementing the `Accounting` API:

- [LedgerAccount](apis/accounting/reference#tag/LedgerAccount) `nominal_code` has been deprecated in favour of `code`.

## v8.31.0 - (2022-05-26)

### CRM API

- Added `pipelines` [Pipelines](apis/crm/reference#tag/Pipelines) for [Salesforce](connectors/salesforce)

## v8.30.1 - (2022-05-24)

### Accounting API

- Added `bank_accounts` [Suppliers](apis/accounting/reference#tag/Supplier)

## v8.30.0 - (2022-05-23)

### [ATS API](apis/ats/reference)

- Added [Freshteam](connectors/freshteam) and [Recruitee](connectors/recruitee)

## v8.29.5 - (2022-05-19)

### Accounting API

- Added [Balance Sheet](apis/accounting/reference#tag/Balance-Sheet)

## v8.29.4 - (2022-05-16)

- Made `is_primary` optional for [Employee](apis/hris/reference#tag/Employees) jobs of HRIS API.

## v8.29.3 - (2022-05-10)

- Extended [Bills](apis/accounting/reference#tag/Bills) with `paid_date`, `deposit`, `sub_total`, and `total_tax`. If these properties are available in downstream connector response, they will be mapped returned.

## v8.29.2 - (2022-05-10)

- Added optional `inventory_date` to [InvoiceItem](apis/accounting/reference#tag/InvoiceItems)

## v8.29.1 - (2022-05-06)

### Accounting API

- Added [Bills](apis/accounting/reference#tag/Bills)

## v8.29.0 - (2022-05-05)

### Accounting API

- Added [Suppliers](apis/accounting/reference#tag/Suppliers)

## v8.28.2 - (2022-05-05)

### Accounting API

- Added optional `tax_code` to [Invoice](apis/accounting/reference#tag/Invoices)

## v8.28.1 - (2022-05-03)

### POS API

- Added [Square](connectors/square) Locations

## v8.28.0 - (2022-05-03)

### HRIS API

- Added [Personio](connectors/personio) connector to HRIS

## v8.27.2 - (2022-04-29)

### HRIS API

- Added [Webhook Support](/apis/hris/reference#tag/Webhook-Events)

## v8.27.1 - (2022-04-27)

### Vault API

- Added docs for `authorize_url` and `revoke_url` to [Connections](apis/vault/reference#tag/Connections)

## v8.27.0 - (2022-04-27)

- Added [`ConnectorRateLimitError`](errors#connectorratelimiterror)

## v8.26.1 - (2022-04-26)

### Vault API

- Include connectionsImport when running sdk generation.

## v8.26.0 - (2022-04-25)

### HRIS API

- Added [Payrolls](apis/hris/reference#tag/Payrolls) and [EmployeePayrolls](apis/hris/reference#tag/EmployeePayrolls)to HRIS

## v8.25.0 - (2022-04-22)

### ATS API

- Added [Workable](connectors/workable) connector to ATS

## v8.24.1 - (2022-04-21)

### Accounting API

- Updated [TaxRates](apis/accounting/reference#tag/TaxRates) components.id to be `string`

## v8.24.0 - (2022-04-20)

- Add [Company info](apis/accounting/reference#tag/Company-Info) to [QuickBooks](connectors/quickbooks) connector

## v8.23.0 - (2022-04-19)

- Added [`Tenders`](apis/pos/reference#tag/Tenders) to [Clover](connectors/clover) connector

## v8.22.0 - (2022-04-17)

- Added `Order Types` and `Modifier Groups` to [Clover](connectors/clover) connector

## v8.21.0 - (2022-04-14)

- Added `Orders` to [Clover](connectors/clover) connector

## v8.20.0 - (2022-04-12)

## Connector API

- Added `oauth_scopes` to [Connector](apis/connector/reference#tag/Connectors)

## v8.19.3 - (2022-04-11)

### Vault API

- Added TokenRefreshFailed to Vault spec to include in docs

## v8.19.2 - (2022-04-08)

- Bump version to initialize PHP SDK

## v8.19.1 - (2022-04-08)

- Removed `minLength: 1` limitation because responses can contain empty strings.
- Set default value of `raw` parameter to `false`, it was `true`.

## v8.19.0 - (2022-04-04)

### Vault API

- Added [Import Connection](/apis/vault/reference#operation/connectionsImport)

## v8.18.0 - (2022-04-04)

### Connector API

- Added `docs` to [Connector](apis/connector/reference#tag/Connectors)
- Added endpoint to get the content of a Connector Doc
- Added `events`, to [API](apis/connector/reference#tag/APIs)

## v8.17.0 - (2022-03-24)

### Connector API

- Added `oauth_grant_type`, `oauth_credentials_source` and `has_sandbox_credentials` to [Connector](apis/connector/reference#tag/Connectors)

## v8.16.0 - (2022-03-24)

### HRIS API

- Added [Departments](apis/hris/reference#tag/Departments) to HRIS
- Fixed Nmbrs birthday date format on Employees

## v8.15.0 - (2022-03-23)

- Added [Greenhouse](connectors/greenhouse) connector to ATS
- Added Merchant ID to [Clover](connectors/clover) connector

## v8.14.0 - (2022-03-18)

### Accounting API

- Added [Sage Intacct](connectors/sage-intacct) connector
- [LedgerAccounts](apis/accounting/reference#tag/LedgerAccounts)
  - `LedgerAccount.type` enum extended to include `balancesheet`
  - Added `categories` property
- [AccountingCustomer](apis/accounting/reference#tag/AccountingCustomer)
  - `AccountingCustomer.status` enum extended to include `inactive`
- [Payment](apis/accounting/reference#tag/Payment)
  - `Payment` extended with optional `payment_method` string

### Vault API

- Extended [Connections](apis/vault/reference#tag/Connection) `auth_type` enum to include `custom`.

## v8.13.0 - (2022-03-09)

- Added `Items` and `Orders` POS mapping to [Square](connectors/square`)

## v8.12.1 - (2022-02-18)

### Accounting API

- Added `taxRatesFilter` filter to [TaxRates](apis/accounting/reference#tag/TaxRates)

## v8.12.0 - (2022-02-16)

### Vault API

- Added `oauth_grant_type` property to [Connections](apis/vault/reference#tag/Connection).
- Added [Token](apis/vault/reference#operation/connectionsToken) endpoint to support the `client_credentials` OAuth flow.

### HRIS API

- Added [Workday](connectors/workday) and [Paylocity](connectors/paylocity) connectors.

## v8.11.1 - (2022-02-09)

### Accounting API

- optional `report_tax_type` property added to [TaxRates](apis/accounting/reference#tag/TaxRates)

## v8.11.0 - (2022-01-15)

### POS API

- Added [Square](connectors/square) connector.

## v8.10.2 - (2022-01-12)

### HRIS API

- Moved compensations out of jobs array on [Employees](apis/hris/reference#tag/Employee)

## v8.10.1 - (2021-12-14)

### Accounting API

- Shared Schema `Address` extended with optional `line3` and `line4` properties
- [LedgerAccounts](apis/accounting/reference#tag/LedgerAccounts)

  - `LedgerAccount.type` enum extended to include `other_income`

- [AccountingCustomer](apis/accounting/reference#tag/AccountingCustomer)

  - `AccountingCustomer` extended with `websites`, `title`, `display_name`, `middle_name`, `last_name`, and `suffix` properties

- [Invoice](apis/accounting/reference#tag/Invoice)

  - `Invoice` extended with optional `terms` string

- [Payment](apis/accounting/reference#tag/Payment)
  - `Payment` extended with optional `note` string

## v8.10.0 - (2021-12-05)

### File Storage API

- Added [Upload Sessions](apis/file-storage/reference#tag/UploadSessions) resource.
- Added File Upload to the [Google Drive](connectors/google-drive) connector.

### HRIS API

- Added [BambooHR](connectors/bamboohr) connector.

## v8.9.0 - (2021-12-03)

### ATS API

- Added [Lever](connectors/lever) connector.

## v8.8.1 - (2021-11-24)

### Accounting API

- [Payments](apis/accounting/reference#tag/Payments)
  - `Payment.reconciled` added to reflect reconciliation state
  - `Payment.status` enum added to reflect payment state [`authorised`, `paid`, `voided`, `deleted`]
  - `Payment.type` enum added
    [
    `accounts_receivable`,
    `accounts_payable`,
    `accounts_receivable_credit`,
    `accounts_payable_credit`,
    `accounts_receivable_overpayment`,
    `accounts_payable_overpayment`,
    `accounts_receivable_prepayment`,
    `accounts_payable_prepayment`
    ]

### ACTION REQUIRED

<span className='tag'>Accounting API</span>

Beta users should note the following breaking changes that may affect existing integrations implementing the `Accounting` API:

- [Payments](apis/accounting/reference#tag/Payments) `accounts_receivable_account_type` and `accounts_receivable_account_id` have been deprecated in favour of a single `account` object.

## v8.8.0 - (2021-11-18)

### File Storage API

- Added [Shared Links](apis/file-storage/reference#tag/SharedLinks) resource.

## v8.7.1 - (2021-11-16)

### Accounting API

- added `BankAccount.account_type` and `BankAccount.currency`. Account type is an enum [`bank_account`, `credit_card`, `other`]

- [LedgerAccounts](apis/accounting/reference#tag/LedgerAccounts)

  - `LedgerAccount.type` enum extended to include `fixed_asset` and `revenue`
  - `LedgerAccount.status` added to reflect downstream provider who allow different states (soft delete) [`active`, `inactive`, `archived`]

- [InvoiceItems](apis/accounting/reference#tag/InvoiceItems)
  - `InvoiceItem.purchase_details` added to reflect purchase cost detail on an item
  - `InvoiceItem.tracked` added to indicate whether or not the item is tracked via inventory
  - `InvoiceItem.asset_account` added to reflect the asset account that this item should be related to.
  - `InvoiceItem.purchased` boolean added to indicate whether or not the item is available for purchase transactions

## v8.7.0 - (2021-11-15)

### File Storage API

- Added [File Upload](apis/file-storage/reference#operation/filesUpload).

## v8.6.0 - (2021-11-11)

### ACTION REQUIRED

<span className='tag'>Accounting API</span>

Beta users should note the following breaking changes that may affect existing integrations implementing the `Accounting` API:

- Type of [TaxRates](apis/accounting/reference#tag/TaxRates) `tax_type` has been deprecated to facilitate migrating from an enum to string using new `TaxRate.type`. Values sent via `TaxRate.type` should be aligned with any downstream connector requirements.

## v8.5.0 - (2021-11-09)

### File Storage API

- Added [Folders](apis/file-storage/reference#tag/Folders) resource.

## v8.4.1 - (2021-11-08)

### File Storage API

- Added sorting support to Files. To sort results, use the `sort[by]` and `sort[direction]` query parameters. Available `sort[by]` values are `name` and `updated_at`.

## v8.4.0 - (2021-11-04)

- Added [Connector API](apis/connector/reference).

## v8.3.2 - (2021-11-03)

### Accounting API

- Extend [InvoiceItems](apis/accounting/reference#tag/InvoiceItems) to include `income_account` and `expense_account`.

## v8.3.1 - (2021-11-02)

### Accounting API

- Ensure Customer is shared model between Invoice and Payment

## v8.3.0 - (2021-11-02)

### Accounting API

- Added [Payments](apis/accounting/reference#tag/Payments)
- Added `downstream_id` to [Invoices](apis/accounting/reference#tag/Invoices) allowing for single endpoint fanning out to multiple downstream endpoints for Invoices.

## v8.2.0 - (2021-11-01)

### SMS API

- Added [MessageBird](connectors/messagebird) and [Vonage](connectors/vonage) messages.

## v8.1.0 - (2021-10-26)

### SMS API

- Added [Twilio](connectors/twilio) and [Plivo](connectors/plivo) messages.

## v8.0.0 - (2021-10-25)

- Added [SMS API](apis/sms/reference).

## v7.2.0 - (2021-10-23)

### CRM API

- Added [users](apis/crm/reference#tag/Users) support for the [Salesforce connector](connectors/salesforce).

## v7.1.0 - (2021-10-22)

### Webhook API

- Rename `url` to `delivery_url`.

## v7.0.0 - (2021-10-19)

### Customer Support API

- Added the [Kustomer connector](connectors/kustomer) to the [Customer Support API](apis/customer-support/reference).

### CRM & Lead API

- Added the [Flexmail connector](connectors/flexmail) to the [CRM API](apis/crm/reference).

## v6.0.0 - (2021-10-14)

### Webhook API

- Added beta version of the [Webhook API](apis/webhook/reference).

## v5.12.1 - (2021-10-13)

### Vault API

- Connection.form_fields is readOnly. The values should be sent via Connection.settings when mutating a connection.

## v5.12.0 - (2021-09-16)

- Extended phone number resource with `country_code`, `area_code`, and new `direct-dial-in` type

### Accounting API

- Mapped Xero [customers](/apis/accounting/reference#Customers)

### File Storage API

- Added the [Dropbox](connectors/dropbox) and [Box](connectors/box) connectors

## v5.11.0 - (2021-09-15)

### File Storage API

- Added `/file-storage/files/search` endpoint.
- Added the [Sharepoint](connectors/sharepoint) and [OneDrive](connectors/onedrive) connectors

## v5.10.0 - (2021-09-13)

### File Storage API

- Renamed `folderId` filter to `folder_id`
- Add `shared` filter to the Files resource

## v5.9.1 - (2021-09-08)

### File Storage API

- Added filter on `folderId` to the Files resource.

## v5.8.1 - (2021-09-08)

## Proxy API

- Added support for responses larger than 6MB. For more information, see the [Proxy API docs](/apis/proxy/reference#limitations).

## v5.8.0 - (2021-09-08)

### File Storage API

- Added beta version of the [File Storage API](apis/file-storage/reference) and the [Google Drive connector](connectors/google-drive).

## v5.7.0 - (2021-09-06)

- Add [Company info](apis/accounting/reference#tag/Company-Info) resource. Replace Contact and Company resource by [Customer](apis/accounting/reference#tag/Customers) resource.

## v5.6.0 - (2021-09-06)

### Accounting API

- Add [Customers](apis/accounting/reference#tag/Customers) resource.

## v5.5.1 - (2021-08-29)

### Accounting API

- Rename `general_ledger_account` to `ledger_account` read-only on [Invoices](apis/accounting/reference#tag/Invoices).

## v5.4.1 - (2021-08-27)

### Accounting, CRM, Lead & Vault API

- normlized the naming of definitions
- fixed response descriptions to match shared definitions and avoid duplicates

## v5.4.0 - (2021-08-25)

### CRM API

- Make `duration_minutes` read-only on [Activities](apis/crm/reference#tag/Activities).

## v5.3.0 - (2021-08-19)

### Vault API

- Add `custom_consumer_settings` to [create session](apis/vault/reference#tag/Sessions). Allow wildcard objects to be passed through the `metadata` field on a connection.

## v5.2.0 - (2021-08-15)

### CRM API

- Add `contact_id`, `company_id`, `opportunity_id`, `lead_id`, and `active` to [Notes](apis/crm/reference#tag/Notes).

## v5.1.0 - (2021-08-13)

### Accounting API

- Added alpha version of the [Accounting API](apis/accounting/reference) and the [MYOB connector](connectors/myob).

Supported resources:

- Ledger Accounts
- Tax Rates
- Invoices
- Contacts
- Companies

## v5.0.1 - (2021-08-11)

### CRM, Lead & Vault API

- For all error responses, `typeName` was renamed to `type_name` for consistency.

## v5.0.0 - (2021-08-01)

### CRM & Lead API

- `expected_revenue`, `type`, `last_activity_at`, `lead_source`, and `stage_last_changed_at` added to Opportunity resource
- `annual_revenue`, `number_of_employees`, `industry`, `last_activity_at`, `ownership`, and `parent_id` added to Company resource
- Renamed `image_url` to `image` on the Company resource
- Remove `tax` on the Company resource, since it's already present in `phone_numbers`
- `image`, `last_activity_at`, `first_email_at`, and `first_call_at` added to Contact resource

## v4.3.3 - (2021-07-29)

### Vault API

- `vault/callback`: Added `code` parameter

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
- Normalized reponses for `connectionsGetSettings` and `connectionsUpdateSettings`

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

- Renamed `schema_support` to `resource_schema_support` and introduced `resource_settings_support` to the [connection settings endpoint](apis/vault/reference#operation/connectionsDelete)
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
- [`/vault/consumers/{consumer_id}/stats`](apis/vault/reference#operation/consumersRequestCounts) added to provide request count aggregation data within a datetime range.

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
