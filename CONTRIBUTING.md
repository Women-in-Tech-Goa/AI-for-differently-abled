# Submission Guide

This repo is a template. Your team's submission is a GitHub repo created from it, filled in with your project.

Goal: anyone opening your repo should understand **what you built, for whom, and how to use it** in under 2 minutes.

## Quick start

1. On GitHub, click **Use this template** and create a new repo.
2. Add all teammates as collaborators so commits show real names.
3. Read your NGO's brief in [`Briefs/`](Briefs/).
4. Fill in [`README.md`](README.md). Replace every `<...>` and `[...]` placeholder. Delete sections you don't use.

## Pick a repo shape

Only create the folders you'll actually use.

**Design / prototype project**
```
design/       exported screens (PNG/PDF) + Figma link
assets/       cover image, demo GIF
docs/         design decisions, accessibility notes
```

**AI / content system project**
```
prompts/      one file per use case, with {{variables}}
examples/     inputs (raw material) and outputs (generated content)
docs/         "how to use this" guide for non-technical staff
```

**Code / app project**
```
src/          source code
assets/       screenshots, demo GIF
docs/         setup notes
```

## Rules

* Never commit secrets (`.env`, API keys). Use `.env.example` with placeholders.
* Large raw files (video, RAW photos) go on Drive; link them from the README.
* Keep the brief PDF in [`Briefs/`](Briefs/). Don't delete it.
* Write meaningful commit messages (not "fix" or "update").

## Before you submit

* [ ] No placeholder text left in the README
* [ ] At least one screenshot or demo visible in the README
* [ ] Every teammate listed with name, role, email
* [ ] All external links (Drive, Figma, video) open for anyone with the link
* [ ] Repo is public or shared with the NGO contact
* [ ] No secrets in git history
