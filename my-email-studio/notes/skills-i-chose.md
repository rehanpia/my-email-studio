# Skills I chose

Researched on the web, not with `npx skills find`. Install counts and star counts change often, so re-run the four searches in Claude Code and compare before trusting these numbers.

## Use these

1. **anthropics/knowledge-work-plugins (the marketing plugin)** for writing campaigns.
   Published by Anthropic itself. The repository has tens of thousands of GitHub stars (sources I saw ranged from about 16k to 25k depending on the date). The marketing plugin covers campaign planning, content drafting and brand voice checks, which is exactly what this studio needs.

2. **resend/resend-skills** for sending email.
   Published by Resend, the company that runs the email service, so the advice matches the real product. The repository has roughly 105 to 159 stars depending on the date. Its main `resend` skill has about 12.8K installs, and the collection has about 33.5K installs in total. The skills warn about real problems such as duplicate sends and webhook checks.

## Avoid these

1. **aradotso/marketing-skills (email-marketing-bible-skill)**.
   About 839 installs but only 6 GitHub stars. Few people have looked at the code behind the install number, and the publisher is not a name I recognise.

2. **techwavedev/agi-agent-kit (resend skill)**.
   Only 1 install and 3 stars. A tiny, unknown copy of a skill that Resend already publishes officially, so there is no reason to prefer it.

## How I decided

1. **Who publishes it?** Prefer the company that makes the product (Anthropic, Resend) over an unknown account.
2. **Do the stars match the installs?** Many installs with very few stars is a warning sign, because install counts can be inflated. Also check when it was last updated.
3. **What does it do, and what does the security audit say?** Read the `SKILL.md` before installing. A skill that can send emails or run scripts deserves extra care. One listing showed a HIGH risk audit flag on the official `resend-cli` skill, so even trusted publishers need a read-through.
