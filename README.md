# Salesforce External Client App (ECA) Metadata

A Salesforce DX project demonstrating how to retrieve, manage, and deploy *External Client Application (ExternalClientApplication)* metadata using the Salesforce Metadata API and Salesforce CLI.

## Overview

External Client Apps are the next-generation framework for connected apps in Salesforce, designed to encapsulate OAuth configurations, security policies, and application settings as source-driven metadata. This repository contains the Salesforce DX project configuration and manifest setup used to track and deploy External Client App metadata across Salesforce environments.

## Project Structure

```text
ecaViaMetadata/
├── config/
│   └── project-scratch-def.json    # Scratch org definition file
├── force-app/
│   └── main/default/               # Retrieved and deployable ECA metadata source
├── manifest/
│   └── package.xml                 # Package manifest targeting ExternalClientApplication
├── .forceignore                    # Metadata exclusions for Salesforce CLI deployments
├── .gitignore                      # Local and environment exclusions for Git
└── sfdx-project.json               # Salesforce DX project configuration