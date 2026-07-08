# SecureAI Gateway - Security Overview

## Purpose

This document summarises SecureAI Gateway security-relevant design areas for enterprise evaluation, focused pilot and security review discussions.

## Product security scope

SecureAI Gateway is designed to support AI access governance, approved-model access, prompt inspection, sensitive-data handling, model routing and audit evidence.

## Control Plane and Data Plane separation

The Control Plane manages policies, routing configuration, tenant metadata and audit views. The Data Plane processes AI requests according to the selected deployment model.

## Customer-Controlled Data Plane option

The Data Plane can be deployed in a customer-controlled environment for selected review and deployment patterns.

## Prompt inspection and sensitive-data handling

The platform can inspect prompts and apply sensitive-data masking or blocking policies before requests reach approved AI models.

## Approved-model access and routing controls

Tenant administrators can review which model routes are available for selected users, departments, tasks and use cases.

## Audit logging and Trace ID

Governed requests can retain audit evidence including Trace ID, policy decision, model route, matched rule and request metadata.

## Administrative access and tenant separation

Administrative access is role-based. Tenant-scoped records should be separated by tenant configuration and role.

## Security review questions this document helps answer

- Where is policy configured?
- Where is request inspection performed?
- What audit evidence is retained?
- How are approved models controlled?
- Which deployment model is being evaluated?

## Current limitations and non-claims

SecureAI Gateway does not currently claim ISO27001 certification, HKMA certification, AI Verify certification, bank-grade certification or regulator approval.

## Customer responsibilities

Customers remain responsible for enterprise security policy, identity integration, network controls, provider selection, production monitoring, backup requirements and legal compliance review.
