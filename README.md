# filepath/shared

Shared repository for files that are intended to be available publicly, including assets and documents used on public-facing surfaces such as `iu.com.au` and `members.live` where appropriate.

## Purpose

Use this repo as a normal collaborative project for shared files:
- store publicly shareable assets and documents
- track changes with git
- collaborate through normal commits, diffs, branches, and merges
- keep a durable history of updates to shared materials

## What belongs here

Examples:
- images
- downloadable documents
- shared reference files that are safe to expose publicly
- other files intended for public or member-facing distribution

## What must not go here

Do **not** store:
- secrets
- API keys
- passwords
- private client data
- internal-only documents that should not be public
- anything that would be a problem if the repo owner or other collaborators could see it

Assume files in this repo are suitable for public or broadly shared use.

## Collaboration model

This repo is intended to be managed like a normal project:
- clone locally
- edit files in place
- review diffs
- commit logically
- push changes
- use branches/PRs when the change is non-trivial or review is useful

Direct commits to `main` are acceptable for small, low-risk changes when appropriate.

## File management guidance

- Use clear filenames.
- Prefer replacing files intentionally rather than creating confusing near-duplicates.
- Keep folder structure simple and obvious as the repo grows.
- If a file is used externally, avoid unnecessary renames because URLs or references may depend on the filename.

## Operational note

IQnode/OpenClaw can work with this repo locally using normal git workflows, including file edits, commits, tracking, and GitHub sync.
