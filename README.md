![Only Filipinas project cover](assets/showcase/cover.png)

*Concept illustration created for this showcase.*

<div align="center">

<h1>Only Filipinas</h1>
<p><strong>A creator-platform prototype for publishing, access and community.</strong></p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Jinja2-B41717?style=flat-square&amp;logo=jinja&amp;logoColor=white" alt="Jinja2" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&amp;logo=sqlite&amp;logoColor=white" alt="SQLite" />
</p>

</div>

## Purpose

Only Filipinas brings creator publishing, content access and audience interactions into a single web-application prototype. It explores the workflows on both sides of a creator platform: managing a publication and finding, accessing and organizing content.

## Features

- Creator studio with publishing tools and post previews.
- Subscription and individual-content access workflows.
- A digital library for organizing accessible content.
- Messaging with media attachments.
- Moderation and administrative review tools.

## Visual overview

![Only Filipinas feature overview](assets/showcase/overview.png)

## High-level workflow

```mermaid
flowchart LR
    A["Creator studio"] --> B["Prepare and preview posts"]
    B --> C["Publishing and content access"]
    C --> D["Audience library"]
    C --> E["Messaging"]
    F["Moderation and review"] -.-> C
    F -.-> E

    classDef stage fill:#f1f5f9,stroke:#64748b,color:#0f172a
    classDef experience fill:#fce7f3,stroke:#db2777,color:#831843
    class A,B,C,F stage
    class D,E experience
```

The prototype connects publishing, access management and communication, with administrative workflows supporting moderation and review.

## Stack

Python and FastAPI provide the application backend, with Jinja2 templates and SQLite for local use. The project also includes optional PostgreSQL support and Docker packaging.

## Development status

Local prototype covering creator, subscriber and moderation workflows. Public launch depends on connecting and validating external services and operational processes.

## About this repository

This repository is a public showcase. Only presentation material is published; source code and private data remain private.

**Last showcase review:** 2026-09-12 (Europe/Paris).
