# Tresume ATS Overview

**Tresume** is an **AI-powered Applicant Tracking System (ATS)** and recruitment workflow platform designed to help organizations manage the complete hiring lifecycle — from candidate sourcing and matching to onboarding, communication, support, and AI-powered productivity workflows.

This repository is the **master product overview / case-study repository** for the Tresume platform. It brings together the key modules, workflows, architecture, and screenshots of the ATS ecosystem built across the product.

---

# 🚀 What is Tresume?

Tresume is a modular recruitment and onboarding platform built to centralize recruiter operations, candidate workflows, onboarding automation, internal support, and AI-powered hiring tools in one system.

The platform combines:

- **candidate sourcing and management**
- **candidate matching and recruiter workflows**
- **AI-powered resume analysis and resume generation**
- **AI onboarding checklist generation**
- **document checklist and onboarding bundle management**
- **bulk recruiter communication**
- **support tickets and live chat**
- **developer / recruiter dashboards**
- **login activity and user session monitoring**

Tresume is designed as a product ecosystem rather than a single isolated feature.

---

# 🎯 Product Goal

The goal of Tresume is to simplify and modernize recruitment operations by giving organizations a single platform to:

- manage candidate data and recruiter workflows
- improve hiring productivity with AI
- automate onboarding documents and checklist creation
- streamline candidate communication
- support internal collaboration between users and developers
- monitor platform usage and recruiter activity

---

# 🧩 Full Product Modules

# 1) Candidate Hub / Candidate Management
Candidate management is one of the core ATS workflows in Tresume.

## Features
- candidate listing and profile management
- recruiter-side candidate views
- candidate filtering and searching
- candidate status handling
- candidate detail workflows
- shortlist / recruiter actions
- integration with matching and communication workflows

---

# 2) Candidate Matching
Tresume includes a candidate matching workflow to help recruiters find the right candidates for a role.

## Features
- job-to-candidate matching
- recruiter review of matched candidates
- match score / matching workflow support
- shortlist candidates from match results
- select candidates for follow-up workflows
- integrate selected candidates into bulk email communication

---

# 3) Recruiter Hub / Recruiter Workflow Tools
Recruiters interact with candidate, job, communication, and onboarding workflows through recruiter-focused screens.

## Features
- recruiter-side candidate actions
- workflow access for matching, candidate review, and communication
- integration with onboarding and checklist workflows
- ATS operational workflow support

---

# 4) AI Resume Builder / Resume Generator
Tresume includes an AI-powered resume optimization workflow.

## Features
- upload an existing resume
- select target role
- paste target job description
- AI-based ATS match score generation
- matched keyword detection
- missing keyword detection
- resume improvement suggestions
- improved resume generation
- editable resume output
- export as PDF / DOCX

## Workflow
1. Upload resume
2. Enter target role
3. Paste job description
4. Analyze score
5. Review suggestions
6. Generate improved resume
7. Edit and export

---

# 5) Resume Builder / Resume Editor
Tresume also includes a resume creation and editing experience with multiple templates.

## Features
- create resume from scratch
- template-based resume builder
- live resume preview
- edit personal details, summary, education, experience, skills, certifications
- choose resume templates
- save and export final resume

---

# 6) AI Onboarding Checklist Generator
Tresume includes an AI onboarding assistant that generates onboarding document checklists.

## Features
- AI-generated onboarding checklist templates
- save generated templates
- reuse onboarding templates
- edit generated checklist items
- create onboarding documents faster with AI assistance

---

# 7) Document Checklist Manager
The document checklist module manages reusable onboarding document bundles and checklist templates.

## Features
- create checklist
- update checklist
- delete checklist
- create custom documents
- select multiple onboarding documents
- save checklist templates
- view checklist cards with file/document count
- reuse onboarding bundles

---

# 8) Onboarding Bundle / Onboarding Document Flow
Tresume supports onboarding workflows for candidates after selection.

## Features
- onboarding checklist assignment
- document bundle workflows
- reusable onboarding templates
- candidate onboarding document handling
- AI + manual checklist support

---

# 9) Bulk Email Broadcast
Recruiters can communicate with multiple selected candidates using bulk email workflows.

## Features
- select group
- list candidates in selected group
- checkbox-based candidate selection
- filter by mail status
- send emails to only selected candidates
- auto-populate selected emails in BCC
- include job details in email payload
- broadcast recruiter communication efficiently

---

# 10) Support Tickets
Tresume includes an internal support system where users can raise platform issues.

## Features
- multi-step support ticket submission
- issue title and description
- optional category selection
- additional details section
- attachment upload
- ticket list view
- ticket detail view
- ticket status tracking
- work progress / developer update sections

---

# 11) Live Chat Support
Tresume support tickets are integrated with live communication workflows.

## User-side features
- chat from ticket detail page
- send text messages
- upload screenshots / files
- communicate with support / developer team

## Developer-side features
- support chat inbox
- conversation list
- reply to users
- issue follow-up workflow
- ticket-linked support communication

---

# 12) Developer Dashboard / Support Dashboard
Developers and support team members can manage incoming support tickets and respond to users.

## Features
- support ticket list
- recent ticket overview
- support conversation handling
- chat response workflow
- ticket follow-up and updates

---

# 13) Login Activity Dashboard
Tresume also includes activity tracking and session monitoring workflows.

## Features
- login time tracking
- logout time tracking
- daily activity timeline
- first login / last logout display
- session history
- total active hours
- user activity dashboard cards

---

# 14) Corporate Documents / Handbooks / Internal Resources
The platform also includes supporting onboarding and document management features.

## Features
- corporate document storage
- reusable handbook/document flows
- onboarding-related supporting resources
- organization-level documentation workflows

---

# 🏗️ Product Architecture

Tresume follows a modular full-stack architecture.

## High-level architecture
```text
Angular Frontend
   ↓
Node.js / Express API Layer
   ↓
Business Logic & Workflow Services
   ↓
SQL Server Database
   ↓
AI / Matching / Resume / Checklist Services
