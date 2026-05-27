# Distributed Energy Resources (DER) Application

## Project Overview
A scoped ServiceNow application designed to ingest, parse, and process Distributed Energy Resources (DER) telemetry payloads. This application automates data handling from external energy grids into structured ServiceNow tables for monitoring and reporting.

## Key Features
* **Automated Payload Parsing:** Built custom JavaScript logic (`DERPayloadParser`) to handle incoming integration data.
* **Custom Schema Design:** Designed foundational database tables, dictionary entries, and data relationships within a scoped architecture.
* **Granular Security:** Implemented Access Control Lists (ACLs) to secure energy data records according to least-privilege principles.

## Tech Stack & Architecture
* **Platform:** ServiceNow (Zurich Release)
* **Languages:** JavaScript (ServiceNow Legacy/ES6+), XML
* **Components:** Script Includes, Business Rules, Access Controls (ACLs), Scoped Tables
