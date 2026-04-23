# Submission Guide

This repo is a **template** for your build-session project submission. Your team's final submission is a GitHub repo created from this template — code, designs, prompts, sample outputs, screenshots, and any links the NGO needs to pick up your work after the session.

The goal: someone who wasn't at the session (an NGO stakeholder, a judge, a future collaborator) should be able to open your repo and within 2 minutes understand **what you built, for whom, and how to use it**.

---

## 1. Before you start

1. **Create a new repo from this template.** On GitHub, click *Use this template* → *Create a new repository*. Name it something like `indogether-<your-idea>` or `atypical-advantage-<your-idea>`.
2. **Add all teammates as collaborators** so everyone can commit under their own name.
3. **Read your NGO's brief carefully** — it's in [`Briefs/`](Briefs/). Keep the brief file in the repo; your README should link to it.
4. **Pick a primary tech/stack early** (Figma? Flutter? a prompt pack? a Notion export?) and agree on where each teammate will commit their work.

---

## 2. Fill in the README

The [`README.md`](README.md) is your project's front page. It is what gets read first — more than the code, more than the Drive. Fill in every placeholder in `< >` or `[...]` and delete the sections that don't apply to your project.

A good README answers:

- [ ] **What** did you build? (one line + a screenshot at the top)
- [ ] **For whom?** (which NGO, which users)
- [ ] **What problem** does it solve? (in your own words, not copy-paste)
- [ ] **How do you use it?** (run code / open Figma / use the prompt pack)
- [ ] **Where is everything?** (repo folders + Drive / Figma / video links)
- [ ] **Who's on the team?** (names + emails + what each person did)

---

## 3. Pick a repo shape based on your project type

The template intentionally ships with only `assets/` and `Briefs/`. Add the folders below **only if you're using them** — an empty folder with no content is noise. Delete the row from the README table if you don't create it.

### 🎨 Design / prototype project (most Atypical Advantage submissions)

```
design/
  home-screen.png
  lesson-player.png
  chapter-map.pdf
  figma-link.md        # shareable Figma URL + notes on navigating the file
assets/
  demo.gif             # short screen-recording of the prototype
  cover.png            # hero image for the README
docs/
  design-decisions.md  # why you chose specific flows, accessibility notes
```

**Must-haves:**
- A public / view-access Figma link in the README
- PNG exports of key screens committed to `design/` (in case Figma access changes)
- A short GIF or video of the prototype being used
- Notes on how you honoured the brief's non-negotiables (no audio, no sign language, WCAG AA contrast, large tap targets, 2-minute lesson cap)

### 🤖 AI / content system project (most INDOGETHER submissions)

```
prompts/
  social-post.md       # one file per use case, with {{variables}} marked
  donor-outreach.md
  one-pager.md
examples/
  inputs/              # real raw material you used as input
  outputs/             # the generated content, ready to use
docs/
  how-to-use.md        # step-by-step for non-technical NGO staff
  1-pager-indogether.pdf
```

**Must-haves:**
- A plain-English "how to use this after the session" guide for the NGO
- Real sample outputs built from the NGO's actual material (not placeholder text)
- Prompts structured so a non-technical user can copy-paste and replace variables

### 💻 Code / app project (either NGO)

```
src/                   # your source code
assets/
  screenshots/
  demo.gif
docs/
  architecture.md
```

**Must-haves:**
- Clear `Run instructions` block in the README (clone → install → run)
- A `.env.example` file if you use env vars — never commit actual keys
- Screenshots and/or a short demo video

---

## 4. Commit hygiene

- **Small, meaningful commits.** "Fix" and "update" tell the reader nothing. Write `Add home screen mockup` or `Add donor-outreach prompt v1`.
- **Real names in commits.** Don't commit as "root" or an anonymous GitHub identity — the NGO should be able to see who did what.
- **Don't commit large raw files.** Big video files, RAW photos, giant PSDs → put them on the shared Drive and link. Keep git fast.
- **Never commit secrets.** No API keys, `.env` files, or credentials. Use `.env.example` with placeholder values.
- **Commit the NGO's brief PDF** — it's already in [`Briefs/`](Briefs/). Leave it.

---

## 5. External resources

Some things live better outside git. Link them from the README:

- **Google Drive folder** — working files, presentations, large media, raw research
- **Figma file** — make sure the share link allows view access for anyone with the URL
- **Demo video** — YouTube unlisted, Loom, or a Drive link
- **Deck / presentation** — export a PDF and commit it to `docs/`; keep the editable version on Drive

> Drive links rot. Treat them as working space, not the archive. The repo is the archive.

---

## 6. Submission checklist

Before you hand off, walk through this:

- [ ] README has no placeholder text left (`<...>`, `[insert]`, `Person 1 Name`, etc.)
- [ ] At least one screenshot or demo asset is visible in the README
- [ ] Google Drive / Figma / video links all open in an incognito window
- [ ] Every teammate appears in the team table with their actual email
- [ ] The brief PDF is still in [`Briefs/`](Briefs/)
- [ ] The repo is public (or shared with the NGO contact)
- [ ] The license file ([`LICENSE`](LICENSE)) is present — or replaced if your team prefers a different one
- [ ] No secrets or personal data in the history (`git log -p` sanity check)

---

## Questions during the session?

Ask the organizers or post in the session channel. Happy building.
