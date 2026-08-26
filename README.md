# Google Ads API Manager

An internal Python-based tool for managing, monitoring, and reporting on authorized Google Ads accounts through the Google Ads API.

## Purpose

This project is intended to simplify routine Google Ads account management tasks for accounts owned by or explicitly authorized to the developer.

Planned functionality includes:

* Retrieving campaign, ad group, ad, keyword, and performance data
* Creating and updating campaigns, ad groups, ads, and keywords
* Managing campaign budgets and delivery status
* Pausing or enabling authorized advertising resources
* Generating internal campaign performance reports
* Monitoring account and campaign status

## Intended Users

This tool is for internal use by the repository owner only. It is not offered as a public service, and third parties will not be given access to the tool or its Google Ads API credentials.

## Authentication and Security

Authentication will use Google-supported OAuth 2.0 or service account credentials.

API credentials, developer tokens, private keys, refresh tokens, and account data will never be committed to this public repository. Sensitive configuration will be stored securely outside the source code.

## Data Use

Google Ads data retrieved through the API will only be used for authorized campaign management and internal reporting. The data will not be sold, shared, or transferred to unauthorized third parties.

## Development Status

This project is currently in the initial development and configuration stage.

## Compliance

The tool is intended to operate in accordance with the Google Ads API Terms and Conditions, Google Ads API policies, and applicable Google Ads advertising policies.
