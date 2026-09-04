# ADAPTIA Website

This repository contains the public website for the ADAPTIA research project.

Its scope is project communication and dissemination, including, when implemented:

- Public project information.
- Project objectives and consortium information.
- Public news and updates.
- Public dissemination materials.
- Public project outputs and publication links.
- Other content required by the project dissemination plan.

It is NOT:

- The ADAPTIA clinical platform.
- The clinician dashboard.
- The patient application.
- The research repository.
- The canonical source for project decisions or governance.

Canonical project governance and status remain in `adaptia-project`.

Technical stack, hosting, deployment and content architecture are not yet decided and must not be inferred from the awarded proposal.

Reference: Awarded Proposal, WP0 / M0.2 - Project website, M6.

Current draft implementation:

- Static HTML/CSS site intended for GitHub Pages.
- Public-only content derived from approved high-level project context.
- Self-contained copies of public branding assets under `assets/branding/`.
- No private repository dependency at build or runtime.

## Repository Visibility

This repository is intended to be public.

All committed content must therefore be treated as publicly accessible.

Internal project information remains in the private ADAPTIA repositories and must only be published here after explicit review for public dissemination.

## Security Boundary

The website must not contain or depend on:

- Clinical or participant-derived data.
- Secrets, credentials or tokens.
- Private consortium documentation.
- Private meeting records.
- Internal governance discussions.
- Confidential technical or security information.
- Private datasets.
- Material whose redistribution rights are unclear.
- Private repository content required at build or runtime.

## Canonical Sources

Project governance, Work Packages, decisions, project status, proposal baseline and internal coordination context remain canonical in `adaptia-project`.

This repository contains only the public dissemination representation of approved project information.

## Build Independence

The public website should be operationally self-contained. It should not require access to `adaptia-project`, `adaptia-research`, `adaptia-platform`, or the private superproject during GitHub Pages builds, at runtime, through Git submodules, or through private-repository fetches.

Derived public copies of approved assets are allowed where necessary.

## Branding Relationship

Canonical shared branding lives in `adaptia-project/branding/`.

This website may later contain web-optimised copies such as logos, favicons or public graphics, but those copies do not become the canonical branding source.
