# Pulsar

## Case Study

Pulsar is a private financial decision intelligence project focused on combining deterministic software with governed AI capabilities.

This repository is a portfolio case study. It does not contain the private source code or the internal technical artifacts of the product.

## The Problem

Financial software cannot treat probabilistic model output as authoritative truth.

The project explores how AI can assist interpretation, structured decision workflows and explanation while deterministic software remains responsible for validation, financial rules and system authority.

The core engineering challenge is not simply adding an LLM to a product.

It is defining exactly where probabilistic behavior is useful, where it must stop, and what evidence is required before an output can be accepted.

## My Role

I direct the product and engineering process using AI coding agents as implementation collaborators.

My responsibilities include:

* Product definition
* System decomposition
* Architecture decisions
* Domain boundaries
* Technical specifications
* Agent task design
* Acceptance criteria
* Review and validation
* Evaluation strategy
* Governance rules
* Iterative correction

The implementation workflow is AI assisted, but architectural responsibility and acceptance remain human directed.

## Engineering Approach

Pulsar separates probabilistic AI capabilities from deterministic system authority.

A simplified public representation is:

```text
User Intent
    |
    v
AI Assisted Interpretation
    |
    v
Structured Candidate
    |
    v
Deterministic Validation
    |
    v
Domain Rules
    |
    v
Accepted or Rejected Result
```

The private implementation contains additional boundaries, contracts and governance mechanisms that are intentionally not reproduced here.

## What This Project Demonstrates

### AI Application Engineering

The project includes AI capabilities designed around structured outputs, explicit failure handling, abstention and validation.

### LLM Evaluation

Model behavior is evaluated through repeatable scenarios and governed review rather than informal prompt inspection alone.

### Deterministic Boundaries

Probabilistic model output does not receive authority over financial calculations or canonical state.

### Domain Modeling

Business concepts are modeled explicitly rather than being embedded directly into prompts or interface code.

### Architecture Governance

System boundaries and engineering constraints are treated as enforceable parts of development rather than documentation only.

### Agent Directed Development

Coding agents execute substantial implementation work from specifications, constraints and acceptance criteria, followed by review and evidence based validation.

## Engineering Principles

The project is built around several principles:

* AI output must be treated as untrusted until validated
* Deterministic rules remain authoritative where correctness is required
* Invalid or unsupported model output should fail safely
* Architecture should constrain implementation, including agent generated implementation
* Evaluation should produce reproducible evidence
* Product behavior should be explainable without exposing internal reasoning traces
* Human responsibility remains explicit

## Technology Areas

The private implementation currently includes work across:

* TypeScript
* React
* Node.js
* Fastify
* PostgreSQL foundations
* Runtime validation
* Automated testing
* Architecture fitness checks
* Contract validation
* Dependency and secret scanning
* LLM integration
* Structured model output
* Evaluation tooling
* AI governance

This list describes demonstrated engineering areas. It is not intended to expose the private repository structure.

## Current Boundaries

Pulsar is an active development project.

The current work demonstrates domain foundations, AI application services, evaluation governance and automated engineering controls.

It should not be interpreted as evidence of:

* Production scale usage
* Autonomous financial execution
* Real money movement
* Production banking infrastructure
* Public customer deployment
* A fully completed user interface

## Why This Case Is Public

The goal of this repository is to demonstrate how I approach complex AI enabled products without publishing the intellectual property required to reproduce them.

The private implementation, prompts, internal schemas, evaluation datasets, detailed architecture records and proprietary business logic are intentionally excluded.

## Portfolio Context

Pulsar demonstrates one side of my work: building AI capabilities that operate inside explicit engineering constraints.

For a complementary example focused on conventional product engineering, APIs, persistence and commerce workflows, see the RestaurantZero case study in my GitHub profile.
