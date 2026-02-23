# Mintlify Starter Documentation Repo

This repository is a starter template for **Mintlify documentation**
with:

-   Regular MDX documentation pages
-   Two separate OpenAPI 3.1 specifications
    -   Billing Service API
    -   Inventory Service API
-   Preconfigured navigation using `docs.json`

------------------------------------------------------------------------

## 📁 Project Structure

    mintlify-starter/
    ├─ docs.json
    ├─ index.mdx
    ├─ quickstart.mdx
    ├─ guides/
    │  ├─ auth.mdx
    │  └─ errors.mdx
    └─ openapi/
       ├─ billing.openapi.yaml
       └─ inventory.openapi.yaml

------------------------------------------------------------------------

## 🚀 Getting Started

### 1. Install Mintlify CLI

``` bash
npm install -g mintlify
```

### 2. Run Locally

From the root of the project:

``` bash
mintlify dev
```

This starts a local development server.

------------------------------------------------------------------------

## 🔎 OpenAPI Validation

You can validate the OpenAPI specifications:

``` bash
mint openapi-check openapi/billing.openapi.yaml
mint openapi-check openapi/inventory.openapi.yaml
```

------------------------------------------------------------------------

## 📚 What This Template Demonstrates

-   Multiple OpenAPI specs in one Mintlify project
-   Separate navigation tabs for each service
-   Shared authentication and error documentation
-   Clean and minimal starter structure

------------------------------------------------------------------------

## 🧩 Customization

You can:

-   Modify `docs.json` to adjust navigation
-   Add more MDX pages under `/guides`
-   Expand OpenAPI specs with schemas, authentication, and examples
-   Add versioning if needed

------------------------------------------------------------------------

## 🌍 Deployment

Push this repository to GitHub, GitLab, or Bitbucket and connect it to
Mintlify.

Mintlify will: 1. Clone the repository 2. Parse `docs.json` 3. Generate
API reference pages from OpenAPI files 4. Deploy your documentation site

------------------------------------------------------------------------

## 🛠 Recommended Next Steps

-   Add proper response schemas to OpenAPI specs
-   Add authentication security schemes
-   Configure branding (logo, colors) in `docs.json`
-   Set up CI validation for OpenAPI linting

------------------------------------------------------------------------

## 📄 License

This is an example template intended for learning and bootstrapping
documentation projects.
