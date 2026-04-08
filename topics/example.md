# Example Context File

Place your context files here to give OpenReels more direction when generating videos.

## How to use

Create a markdown (or plain text) file in this folder describing what you want, then reference it with the `--context` flag:

```bash
pnpm start "the apollo 13 disaster" --context topics/my-apollo-brief.md
```

## What to include

- **Angle / thesis**: What specific perspective should the video take?
- **Key points**: Must-include facts, quotes, or data points.
- **Tone**: Serious, humorous, dramatic, educational, etc.
- **Target audience**: Who is this for?
- **Call to action**: What should viewers do after watching?
- **Things to avoid**: Topics, claims, or imagery you don't want.

## Example

```markdown
# Apollo 13 — The Human Side

Focus on the emotional experience of the astronauts and mission control,
not the technical details. Highlight the moment Jim Lovell saw the oxygen
venting and knew they were in trouble.

Tone: Tense, then hopeful. End on the triumphant splashdown.

Must include:
- "Houston, we've had a problem" (use the correct quote, not the movie version)
- The CO2 scrubber improvisation
- The 4-minute blackout during reentry

Avoid: Conspiracy theories, movie dramatizations presented as fact.
```
