# AGENTS.md — Rules for working on this site

This repo is Yiru (Louisa) Xu's personal website, served by GitHub Pages at
`https://yirulouisaxu-arch.github.io`. Every AI agent or assistant that edits it follows these rules.

## 1. Never publish

These must never appear in any committed file, page, metadata, or commit message:

- **Phone number** (it is on the CV, but it stays off the site).
- Home or mailing address, date of birth, or any government ID / visa / immigration details.
- Salary, compensation, or salary expectations.
- Grades or GPA, unless Louisa explicitly adds them.
- Confidential employer or client information: client names, deal details, internal numbers,
  or anything beyond what is already written on the public CV.
- Names or contact details of references, managers, or colleagues.
- Passwords, API keys, tokens, or any `.env` contents.
- Private source files: the CV PDF (`Yiru_Louisa_Xu_Resume.pdf`), `Cover Letter_Template.docx`,
  and other drafts in this folder. Add them to `.gitignore` before the first commit.
- Anything invented. Every claim on the site must come from the CV or from Louisa directly.
  No made-up metrics, titles, dates, testimonials, or skills.

## 2. Ask Louisa first

Stop and ask before you:

- **Push, commit, or deploy anything to GitHub** (including creating the repo or enabling Pages).
- Add a downloadable CV/PDF, a photo, or any new personal detail to the site.
- Change her email address shown on the site or add a new contact channel.
- Add analytics, tracking, cookies, contact forms, or any third-party script.
- Delete, rename, or overwrite an existing file.
- Rewrite or "improve" CV wording beyond light formatting (changing the meaning of a bullet,
  adding numbers, or reordering CV sections).
- Install dependencies or add a build step / framework.

## 3. Content rules

- Keep the CV's section order: **Education → Professional Experience → Skills & Interests**.
- Keep CV wording verbatim except for typographic fixes (dashes, capitalization of section titles).
- Public links allowed: LinkedIn `https://www.linkedin.com/in/yiru-louisa-xu/`,
  GitHub `https://github.com/yirulouisaxu-arch`, and email `yx3005@columbia.edu`.
- When the CV changes, update the site to match and tell Louisa what changed.

## 4. Style

- **Vibe:** professional and casual. Confident, warm, plain language. No buzzword filler, no emoji.
- **Color:** sage green `#B7CCB0` as the signature accent, with deep forest green `#2C4434` for
  headings and buttons, `#6F8F67` as the mid sage, and white / very light sage `#F6F9F4` backgrounds.
  Keep text contrast at WCAG AA or better.
- **Type:** one sans-serif family (Inter, with system fallbacks). Generous whitespace.
- **Navigation:** streamlined. One sticky top bar with anchor links to each section, plus the
  section tiles near the top. No dropdowns, no more than five nav items.
- **Layout:** tiles/cards for jobs and skills; mobile-first; no horizontal scrolling at 360px width.
- **Tech:** plain HTML + CSS in `index.html`, minimal vanilla JS only where it helps. No frameworks,
  no build tools. External assets only from Google Fonts.
- **Accessibility:** semantic HTML (`header`, `nav`, `main`, `section`), alt text on any image,
  visible focus states, respects `prefers-reduced-motion`.
