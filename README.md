# Welcome to our project

## Project info
HireUP
HireUP is a minimalist job‑matching application focused on a mobile‑first experience, helping job seekers quickly find relevant vacancies and employers receive real, meaningful applications instead of spam.

## What HireUP solves
Job seekers don’t need to spend time on complex filters – they swipe or browse structured job posts with clear fields.

Employers create job postings using a strict form, which makes it easier to search for and filter candidates.

The platform is designed from the start to protect against low‑quality and scam job posts (validation, text length limits, and, in the future, employer verification).

Current capabilities
Roles (current)
Jobseeker – candidate.

Employer – company representative.

Jobseeker
Profile: full name, job title, short bio, skills, years of experience, city, salary range.

Clear placeholders and helper texts, plus character limits and live character counters.

Viewing jobs (swipe / list) and applying to selected positions with proper statuses and toast notifications.

Employer
Creating jobs using a structured form:

title, description, skills, location, salary range, required experience, job type.

Text length limits, inline validation, and clear error messages.

List of their own jobs with statuses (draft / active / paused / closed) and display of the number of applications (if implemented in the current repository version).

Employer verification
At the moment, company verification and document checks are not yet implemented.

## Planned: 

add paid document submission and manual review via public registries (for example, eGov in Kazakhstan) before assigning the “Verified employer” status.

Future development (planned / upcoming roles)
In future versions, the ecosystem is planned to be expanded with additional user types and scenarios:

UGC – a role for bloggers and content creators who need advertising and sponsorship integrations.

Quick Jobs – a mode for short‑term gigs (1 day, 1 week) with fast creation of “micro‑tasks” and quick applications.

Student – a separate flow for students focused on internships and first jobs.

These roles and scenarios are currently in the design stage and are not yet available in production.

## Architecture (high‑level)
Client: SPA / PWA with a mobile‑first interface (tabs: Swipe, Saved, Matches, Profile).

## Roles:
 jobseeker, employer (and future ugc, quick_job, student).

Backend/DB: tables for users, profiles, jobs, and applications; strict data validation and text length limits on key fields.

## Roadmap
Currently in progress / near‑term MVP:

Stable flow: Jobseeker → profile → browse jobs → apply → Employer views applications.

Basic monitoring via an admin panel (lists of jobs, users, and recent applications).

## Planned:

Employer verification and a “Verified employer” badge.

Support for additional roles: UGC, Quick Jobs, Student.

Monetization (paid postings, job boosting, paid verification).

A public landing page and social media integrations.

## Role

## Ibragim Zholamanov QA & Testing Engineer (Junior) + Frontend + UI/UX Contributor
worked on end‑to‑end manual testing of the core user flows, including registration, profile creation and editing, job posting, and the application process from both the Jobseeker and Employer side. He systematically reproduced issues, documented bugs, and reported edge cases that affected usability and data consistency.

On the frontend side, he contributed small but important UI changes such as layout tweaks, spacing and alignment fixes, text and label corrections, and improvements to button states and error messages. He also helped refine UX details on selected screens (for example, clearer field descriptions, more intuitive button wording, and better empty states), making the interface easier to understand for first‑time users. 

## Yskakov Nartay — Backend 

Designed the overall product concept and user flows for Jobseeker and Employer.

Designed and implemented the SQL database schema (users, profiles, jobs, applications/matches, settings) and data validation rules.
​

Implemented backend logic for job creation, editing, status changes, and secure server‑side validation to prevent spam and low‑quality postings.
​

Implemented backend logic for applications/matches, connecting Jobseeker profiles with Employer job posts and preparing data for future analytics.

Developed the main frontend for Jobseeker: profile screen, swipe/browse jobs, apply flow with proper states, toasts, and input limits.

Developed the main frontend for Employer: job creation form with validation and character limits, jobs list with statuses, and initial applicants view.

Set up integration with Supabase (auth, database, environment configuration) and local development workflow.
​

## Tools & AI Assistance

Parts of HireUP were built and refined with the help of AI tools, including **Lovable** (for code generation and UI implementation) and **Claude** (for architecture decisions, feature design, and documentation drafting).