# Stitch Your Pitch

Turn one resume and one job posting into a factual first draft.

Stitch Your Pitch is a public beta for Grok Bot. It helps you compare a job with your actual experience, tailor a resume and write a cover letter in your own voice. This repository contains the public setup guide, a fictional example and release notes.

**[Open the Grok Bot](https://x.ai/bot/Yaqu1CNc1OG_Ffi-vVWsY)** · **[Get started](https://stitchyourpitch.com/setup/)** · **[Try the beta](https://stitchyourpitch.com/beta/)**

## Start with a useful draft

1. Add your copy of the public Grok Bot template.
2. Paste a resume and one job posting. Contact details are unnecessary for a first review.
3. Ask for a requirement, evidence and gap table, followed by a tailored resume and cover letter.
4. Check every claim against your experience before using the drafts.

Try the [fictional first-run example](examples/fictional-first-run.md) before sharing career details. The [getting started guide](GETTING_STARTED.md) covers writing preferences and optional scoring.

## What is included

- Seven skills covering setup, tailoring, search and scoring review, document review, selected application assistance, email intake and reply tracking.
- Writing choices for tone, length, punctuation and phrases to avoid. Cover letters exclude "thrilled" and "passionate" by default, and you can change that list.
- Instructions to preserve dates, employers, reporting frequency and the exact scope of your work. Missing qualifications stay visible as gaps.
- Optional evidence-linked job-fit scoring through a separate MCP connection and your own sign-in.

Skills are instructions. They do not install connections, transfer the creator's access or grant permission to read mail or submit applications. Native application assistance requires approval of the exact job, destination, documents and answers.

## Public MCP scoring

The hosted public MCP exposes one tool: `score_job`. It evaluates supplied resume and job evidence. Scores are provisional heuristics, not employer ATS results, hiring predictions or guarantees.

The scoring service does not search job boards, generate documents, read mail or submit applications. Conversation and drafting take place in Grok. See the [connection guide](https://stitchyourpitch.com/setup/) for the current public endpoint and sign-in settings.

Scoring is free within beta limits. Grok Bot plan and usage limits still apply. No model API key is needed for the scoring connection.

## Current availability

| Item | Status |
| --- | --- |
| Grok Bot template | Published: 0.4.2-r3, platform version 14 |
| Setup and beta guides | Available on [stitchyourpitch.com](https://stitchyourpitch.com/) |
| Optional public scoring | Beta; separate connection and individual sign-in required |
| Public ChatGPT directory plugin | Not available yet |

Owner scoring and token renewal have been observed. Independent new-user setup and isolation checks remain open. This public repository is a documentation and discovery page; it does not contain the backend source or a self-hosting package.

See the [release notes](CHANGELOG.md) for the November 6, 2026 update. Existing copies of the Bot have not been verified as automatically receiving that update.

## Help test it

Use the [beta guide](https://stitchyourpitch.com/beta/) to test drafting or optional scoring setup. It includes an optional progress report with an anonymous tester code. Reporting is opt-in and records self-reported progress, not verified completion.

Send a fictional reproduction through the [support page](https://stitchyourpitch.com/support/). Include the step that failed and the visible error. Keep real resumes, mailbox contents, passwords and tokens out of public reports.

[Privacy and data handling](https://stitchyourpitch.com/privacy/) · [Support](https://stitchyourpitch.com/support/) · [RelativelySmart on X](https://x.com/DumbEinstein)
