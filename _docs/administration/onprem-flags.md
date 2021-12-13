---
title: "Codefresh On-Premises Features Flags"
description: "List and description of the different feature flags"
group: administration
redirect_from:
  - /docs/enterprise/codefresh-flags/
toc: true
---

## Introduction

This manual will describe the different feature flags available for the [Codefresh on-prem](codefresh-on-prem.md) instance.

{: .table .table-bordered .table-hover}
| Name | Description | Introduced in Version | Default Value | Note |
| ---------------------------- | ------------------------------------ | -------- | ----- | ------------------------------------ |
| azureNestedGroupSync | Enables ability to sync nested groups from Azure AD | 1.0.194 | FALSE | does it sync sub-groups as well into team or just users in sub-groups |
| credsInArgsForHttpChartRepos | set CREDENTIALS_IN_ARGUMENTS to true for http/https charts repositories | 1.0.194 | FALSE | how is it used? |
| imageRegexp | Use new regexp for searching image during annotation | 1.0.194 | FALSE | add info on what is new regexp by opposition to "old" |
| log-throttle | Enables improved log throttling in logs terminal component | 1.0.194 | FALSE | what are log terminal component? |
