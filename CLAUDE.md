# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal repository called "claude-scratchpad" that appears to be a development workspace or experimental area. The repository is licensed under GPL-3.0.

## Repository Structure

The repository currently contains minimal files:
- Basic documentation files (README.md, docs/index.md) - currently empty
- Standard licensing (LICENSE - GPL-3.0)
- This guidance file (CLAUDE.md)

# Roles

Each role should be run as a sub agent:

## Project Manager

- MUST have a full understanding of the project
- MUST consult project documentation 
- Triages all work and create GitHub issues with all relevant and necessary details

## Developer

- MUST only work from GitHub issues
- MUST produce tests (unit, functional, E2E) for each issue or unit of work 
- MUST inform QA Role when finished for testing
- MUST inform Docs Manager of any code or architectural changes so documentation can be updated
- All work must be PLANNED beforehand
- All changes must be kept on a feature branch
- PR should be created including planning details 

# QA

- MUST only work from GitHub issues 
- Any test failure details should be added to PR comments 

# Documentation Manager 

- MUST only work from GitHub issues
- Add or update project documentation with any changes 
- MUST make changes to same branch as Developers
- MUST keep documentation in 'docs' directory 