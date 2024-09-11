# demo-app-int-it-automation

## Prerequisites

All of the samples of this repo require Application Integration to be active at a given GCP project. Please follow this (guide)[https://cloud.google.com/application-integration/docs/setup-application-integration] for setting it up.

It also requires (integrationcli)[https://github.com/GoogleCloudPlatform/application-integration-management-toolkit] for automated deployment.

## apigee-app-creation-custom-creds

### [apigee-app-creation-custom-creds](apigee-app-creation-custom-creds)

This simple integration leverages service accounts and the Apigee REST API to create a new developer app with the inputs being the desired key and secret. It automatically deletes the auto-generated credentials that Apigee sets when the app is created.

This is helpful in scenarios of migration from other APIM solutions towards Apigee, synchronization with IdPs, etc.

# Support

This is not an officially supported Google product
