# SharePoint - Use different options to access SharePoint data
## Summary

This sample SPFx web part demonstrates multiple ways to read data from a SharePoint list/library. It includes side‑by‑side implementations using the native Fetch API, `SPHttpClient`, Microsoft Graph, and PnPjs. Configure `SITEID`, `SOURCELIBRARY`, and `SOURCELIBRARYID` in `src/Core/DataAccessOptions.ts`, then run and compare each approach with a single click in the UI.

![UI of the App](/docs/ui-webpart.png)

*UI of the App*

![Overview about the data access options](/docs/Access-SharePoint_Data_EN_v1.jpg)

*Overview about the data access options*


## Used SharePoint Framework Version
![version](https://img.shields.io/badge/version-1.21-green.svg)

## Applies to

- [SharePoint Framework](https://aka.ms/spfx)
- [Microsoft 365 tenant](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/o365devprogram)

## Prerequisites

> Check the file DataAccessOptions and set the variables: SITEID, SOURCELIBRARY and SOURCELIBRARYID
> Install the App and add the App to a page OR use the workbench.

## Solution

| Solution    | Author(s)                                                   |
| ----------- | ----------------------------------------------------------- |
| Repository  | Marc André Schröder-Zhou (https://github.com/maschroeder-z) |

## Version history

| Version | Date             | Comments              |
| ------- | ---------------- | --------------------- |
| 1.0     | 02.10.2025       | Initial Release       |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- Ensure that you are at the solution folder
- in the command-line run:
  - **npm install**
  - **gulp serve**

> Check your currenr Node version and installed SPFx-Framework version.

## Features
- Automatic creation of a list of stored links.
- Linked content can be opened directly in a dialog, making it easy to integrate additional information.
- Built-in search function for quickly finding links.
- Various tile effects on mouseover.
- Background colors can be specified for each link.
- Automatically ensures readable text by automatically setting a contrasting color for the text color.

## Help
Please contact me for further help or information about the sample.

## References

- [Getting started with SharePoint Framework](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [Building for Microsoft teams](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/build-for-teams-overview)
- [Use Microsoft Graph in your solution](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-microsoft-graph-apis)
- [Publish SharePoint Framework applications to the Marketplace](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/publish-to-marketplace-overview)
- [Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp) - Guidance, tooling, samples and open-source controls for your Microsoft 365 development
