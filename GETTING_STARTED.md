# Getting started

Start with Grok Bot and pasted text. The scoring connection is optional.

## 1. Add the template

Open [Stitch Your Pitch in Grok Bot](https://x.ai/bot/Yaqu1CNc1OG_Ffi-vVWsY), review the template and add your copy. Use your own Grok account. The template includes seven skills; connections and permissions are separate.

For a first beta report, use the Grok Bot desktop app and record your operating system and app version. Other clients have separate setup and compatibility checks.

## 2. Try a fictional draft

Copy the prompt in [fictional-first-run.md](examples/fictional-first-run.md). It requests an evidence table, a short resume section and a cover letter without calling tools.

Check the resume and letter separately. Preserve weekly reporting as weekly reporting, tracking as tracking, and overall experience separately from time at a particular employer. A qualification missing from the source remains a gap.

## 3. Set your writing preferences

Tell Stitch the tone and length you want, whether to avoid em dashes and contractions, and any phrases to exclude. For example:

> Use a plain professional tone and a short cover letter. Avoid em dashes and contractions. Keep the default excluded phrases and add "results-driven". Keep factual review notes outside the final draft.

The default cover-letter exclusions are "thrilled" and "passionate". You can add, remove or replace phrases, use an empty list (`[]`) for one request, or reset to the defaults. Exact names and source quotations keep their wording, with any conflict flagged outside the letter.

Preference changes do not authorize new facts or actions. Do not assume preferences are saved across conversations unless an available save action is explicitly requested and confirmed.

## 4. Add scoring when you need it

Follow the [live connection guide](https://stitchyourpitch.com/setup/) for the current settings. Add the public scoring MCP in your own Grok account and complete the normal sign-in flow. No client secret or model API key is required.

After connection, ask Grok to discover `score_job` and run one score on the supplied fictional resume and posting. Ask for the actual returned score, uncertainty, component breakdown and request ID. A connected badge alone does not confirm a successful score.

Scores are provisional heuristics, not employer ATS results, hiring predictions or guarantees. The beta admits up to 30 scores per minute and 100 per UTC day per user, subject to a shared limit and availability. Grok plan and usage limits are separate.

If scoring is unavailable, continue with the evidence table and drafting. Keep the visible error and request ID. A timeout or unknown result is not permission for an automatic retry.

## 5. Report your experience

The [beta guide](https://stitchyourpitch.com/beta/) separates writing feedback from connection testing. Its optional progress reporting accepts an anonymous tester code and does not require a name or resume.

For a problem report, include the last successful step, the next attempted step, the visible error and the approximate time with time zone. Use fictional text to reproduce inaccurate wording. Never share passwords, authorization codes, tokens or personal documents in a public report.

[Back to the project page](README.md) · [Support](https://stitchyourpitch.com/support/) · [Privacy](https://stitchyourpitch.com/privacy/)
