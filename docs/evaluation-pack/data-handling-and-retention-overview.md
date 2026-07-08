# SecureAI Gateway - Data Handling and Retention Overview

## Purpose

This document explains data handling considerations for SecureAI Gateway enterprise evaluation and focused pilot discussions.

## Types of data handled

The platform may handle tenant metadata, user and department context, model route settings, policy decisions, Trace ID, audit metadata, token usage and selected request metadata.

## Public demo data boundary

The public demo uses sample data only and must not be used to submit real customer information, credentials, secrets, API keys or confidential business data.

## Production deployment options

Deployment options may include SaaS Control Plane, hybrid deployment and customer-controlled Data Plane patterns, subject to customer requirements.

## Prompt and model output handling

Prompts and model outputs may be processed by the Data Plane for inspection, masking, blocking and routing decisions according to policy configuration.

## Sensitive-data detection, masking and blocking

SecureAI Gateway is designed to support sensitive-data detection and policy actions such as masking or blocking for governed AI traffic.

## Logs and audit metadata

Audit metadata may include Trace ID, tenant, user, department, model, route, policy decision, matched rule and timestamps.

## Data retention considerations

Retention should be agreed during enterprise evaluation and configured according to customer policy, contract requirements and applicable law.

## Customer-Controlled Data Plane option

A customer-controlled Data Plane can be considered where customers require selected processing to occur in their own environment.

## Data that should not be entered into the public demo

Do not enter real personal data, customer records, credentials, API keys, secrets, regulated data or confidential business information into the public demo.

## Current limitations and non-claims

This document is not a legal opinion, compliance certification, regulator approval or data protection impact assessment.

## Customer responsibilities

Customers remain responsible for data classification, privacy notices, lawful basis, retention policy, access control, provider selection and production approval.
