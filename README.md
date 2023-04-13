# JanisonConfigToolsSelenium

# 1. Installation

To install the tool [click here](https://github.com/seanhaydongriffin/JanisonConfigToolsSelenium/releases).

# 2. PBTS tenants

## 2.1 Exporting PBTS SIT tenant

`AssessmentConfigExport.exe /config:PBTS_SIT.config`

## 2.2 Creating a new PBTS SIT tenant

_Change "smita" and "xx" below to name the tenant as desired_

- Copy `newpbts_sit.config` as `smitapbtsxx_sit.config`
- Edit `smitapbtsxx_sit.config` and change __appSettings.Datapool Merged Folder__ to the path of the datapools to update and __LocalTenant.Url__ to the Url for the new tenant
- `AssessmentTenantCreate.exe /config:smitapbtsxx_sit.config`
- `AssessmentConfigUpdate.exe /config:smitapbtsxx_sit.config`

## 2.2 Creating a new PBTS ALPHA tenant

_Change "smita" and "xx" below to name the tenant as desired_

- Copy `newpbts_alpha.config` as `smitapbtsxx_alpha.config`
- Edit `smitapbtsxx_alpha.config` and change __appSettings.Datapool Merged Folder__ to the path of the datapools to update and __LocalTenant.Url__ to the Url for the new tenant
- `AssessmentTenantCreate.exe /config:smitapbtsxx_alpha.config`
- `AssessmentConfigUpdate.exe /config:smitapbtsxx_alpha.config`

