# Journey publish prep notes for agent-census

## What I validated
- Journey account exists for `joule`
- Email `ghostshell.host@gmail.com` is verified
- API key works and has `kits:write`
- No kits currently published under this account

## Publish fit assessment
The workflow fits Journey if framed as a portable agent workflow rather than an OpenClaw-only skill.

## Recommended publish positioning
- Outcome-first title
- Optional public submission
- Local memory first, public registry second
- Cross-harness adaptability notes

## Risks to fix before publishing
- Current OpenClaw skill language is too platform-specific
- Current implementation references `MEMORY.md` directly; this should be described as an adaptation point, not a universal assumption
- Current brand wording should avoid sounding like pure promotion for ghostshell.host
- Need to ensure examples contain no personal email addresses or private tokens

## Suggested package contents
- `kit.md`
- `scripts/census`
- optional concise examples later if needed

## Recommended next validation
- Review `scripts/census` for any hardcoded assumptions that should become placeholders or notes
- Confirm whether Journey expects `failures` or `failuresOvercome` naming strictly in publish bundle JSON versus `kit.md` frontmatter
- Build final publish bundle JSON after content review
