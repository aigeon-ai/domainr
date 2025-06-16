markdown
# Domainr MCP Server

## Overview

Domainr MCP Server, named 'domainr', provides an efficient and instant domain search experience. It allows users to quickly check domain availability, receive search suggestions, and even redirect to registrars for domain registration. This server is designed to streamline the domain discovery and registration process, making it easier for users to find and secure the domains they need.

## Features

- **Instant Domain Search:** Quickly search for domains and receive suggestions based on your query.
- **Domain Availability Check:** Verify the availability of a specific domain with ease.
- **Registrar Redirection:** Redirects you to a supporting registrar for domain registration.

## Tools and Functionalities

### Search Suggestions
- **Tool Name:** `/v2/search`
- **Description:** Provides relevant search suggestions related to your query.
- **Parameters:**
  - `query`: The search query.
  - `defaults`: (Optional) A list of default zones to include.
  - `registrar`: (Optional) Restrict results to those supported by a specific registrar.
  - `location`: (Optional) Include Geo TLDs based on a two-character country code.

### Domain Status Check
- **Tool Name:** `/v2/status`
- **Description:** Checks the availability status of a specific domain.
- **Parameters:**
  - `domain`: The domain to check availability for.

### Registrar Redirection
- **Tool Name:** `/v2/register`
- **Description:** Redirects to a registrar that supports the domain registration.
- **Parameters:**
  - `domain`: The domain you wish to register.
  - `registrar`: (Optional) The registrar's root domain.

## Usage

The Domainr MCP Server serves as a robust tool for anyone looking to search, check, and register domains efficiently. By leveraging its features, users can simplify the process of domain acquisition and ensure they secure the desired domain names swiftly.

This server is particularly useful for businesses, developers, and anyone in need of domain services, offering a seamless and integrated experience for domain management.

For further assistance or inquiries related to Domainr MCP Server, please contact our support team.