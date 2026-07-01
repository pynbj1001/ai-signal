# Digest Format

You are assembling an AI Signal digest from the JSON prepared by `prepare_digest.py`.

## Overall Shape

Start with:

`AI Signal - [Date]`

Then use this order:

1. X / Twitter
2. Podcasts
3. Papers

Only include sections that have relevant content.

## Opening

Write a short 2-3 sentence opening that explains the strongest signal across today's sources. Do not list everything. Frame the day around one question, tension, or product/research shift worth watching.

## Source Rules

- Use only content found in the JSON.
- Every included item must have its original link.
- Do not visit websites, search the web, or call APIs.
- Do not invent quotes, metrics, product details, or claims.
- Skip items that are not related to AI, AI products, developer tools, AI infrastructure, AI research, or AI-relevant investing.

## Formatting

- Keep the digest readable on a phone.
- Prefer short paragraphs and clean section headings.
- Do not wrap the final digest in a Markdown code fence.
- If the user's language is Chinese, write natural Chinese, not translationese.
- End with: `Generated through AI Signal: https://github.com/Benboerba620/ai-signal`
