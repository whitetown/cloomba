# Maintainer setup

Most of this repo's behaviour comes from committed files, but a few things are **GitHub repository
settings**, not files. Work through this checklist once after pushing and making the repo public.

> The repo uses a single contact address, `support@cloomba.com` — confirm it's live before going
> public. All repo URLs assume `whitetown/cloomba` — update them everywhere if the slug changes.

## 1. Visibility & features

- [ ] Make the repository **public**.
- [ ] **Settings → General → Features:** turn **off** Wikis and Projects.
- [ ] Turn **on** Issues and Discussions.

## 2. Discussions

- [ ] Enable Discussions, then create categories whose **slugs match** the template files:
  - **Ideas** → slug `ideas` (matches `.github/DISCUSSION_TEMPLATE/ideas.yml`)
  - **Q&A** → slug `q-a` (matches `.github/DISCUSSION_TEMPLATE/q-a.yml`), format **Question / Answer**
- [ ] (Optional) Pin a "Start here / Welcome" discussion.

## 3. Security

- [ ] **Settings → Security → Advanced Security:** enable **Private vulnerability reporting**.
      (This powers the "Report a vulnerability" link used in `SECURITY.md` and the issue-template
      contact link.)

## 4. Labels

- [ ] After the first push to `main`, check **Actions** → the **Sync labels** workflow ran.
      If not, trigger it manually via **Run workflow** (`workflow_dispatch`).
- [ ] Confirm the label list matches `.github/labels.yml`. The sync uses `prune: true`, so GitHub's
      default labels not in the file are removed automatically.

## 5. Nice-to-haves

- [ ] Add a short repo description + the `cloomba.com` website link.
- [ ] Set up a few **saved replies** for common triage responses (needs-info, duplicate, thanks).
- [ ] Confirm the issue chooser looks right: **New issue** shows only **Bug** and **Feature**, blank
      issues are disabled, and the three contact links (security / discussions / email) appear.
