# Google Ads API Manager

An internal Python application that integrates multiple AI services, including the OpenAI API, to create Google Ads customer accounts, generate and submit advertising campaigns, analyze performance data, and automatically apply validated optimization changes.

## Workflow

1. Create and configure customer accounts under an authorized Google Ads manager account.
2. Use multiple configured AI services to generate campaign structures, keywords, headlines, descriptions, and optimization recommendations.
3. Validate AI-generated advertising content against predefined formatting, account, brand, budget, and policy rules.
4. Create and submit validated campaigns, ad groups, ads, keywords, bids, and budgets through the Google Ads API.
5. Retrieve campaign metadata and aggregated performance data through the Google Ads API.
6. Send selected non-sensitive advertising data to configured AI APIs for performance analysis.
7. Receive structured optimization recommendations from the AI models.
8. Validate the recommendations against account permissions, policy rules, budget limits, bid limits, and change thresholds.
9. Automatically apply eligible changes through the Google Ads API.
10. Log all account creation, advertising, and optimization actions.

## Planned Functionality

* Creating and configuring authorized Google Ads customer accounts
* Automatically generating campaign structures and advertising content
* Creating and submitting campaigns, ad groups, ads, keywords, bids, and budgets
* Retrieving campaign and performance data
* Integrating multiple AI API providers, including OpenAI
* AI-assisted campaign performance analysis
* Automatically updating, pausing, or enabling advertising resources
* Managing bids, budgets, keywords, and delivery statuses
* Generating internal reports and change logs
* Monitoring account, campaign, and advertisement status

## Intended Users

This application is for internal use by the repository owner only. It will only access Google Ads accounts owned by or explicitly authorized to the developer. The application will not be offered as a public service or made available to third-party users.

## Automated Advertising Safeguards

AI-generated advertising content and optimization recommendations will be validated by the Python application before submission or application.

The validation process will check formatting requirements, advertising content rules, account permissions, budget and bid limits, predefined change thresholds, and configured safety rules. All automated actions will be recorded in change logs.

Submitting an advertisement through the API does not bypass Google Ads review or guarantee that the advertisement will be approved or served.

## Data and Security

Only the campaign metadata and aggregated performance metrics required for advertising generation and optimization will be sent to configured AI API providers.

Google Ads developer tokens, OAuth credentials, private keys, refresh tokens, passwords, payment information, and personally identifiable information will not be sent to AI providers or committed to this repository.

All API credentials will be stored securely outside the source code.

## Development Status

This project is currently in the initial development and configuration stage.

## Compliance

The application is intended to operate in accordance with the Google Ads API Terms and Conditions, Google Ads API policies, the policies of configured AI API providers, and applicable advertising policies.

The application will not be used to bypass Google Ads account limits, advertisement review, enforcement systems, suspensions, or advertising policies.
