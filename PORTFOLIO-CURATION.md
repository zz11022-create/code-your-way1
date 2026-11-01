# Portfolio curation — November 1, 2026

The active entry point is `index.html`, which redirects to `Queena_profile/`.
The original navigation, visual system, Play, and Explore are retained.

## Selected homepage work

| Project | Evidence it contributes | Available experience |
| --- | --- | --- |
| Career Mixtape | Product research, information architecture, human–AI roles | Public prototype; fictional example stories; AI connection pending |
| Feline Oracle | Multimodal interaction and a complete coded interaction sequence | Local, credential-free portfolio demo with clearly labeled preset readings; optional camera/voice |
| Material Loop | Complex B2B workflows, procurement timing, traceability | Existing prototype; select Back to Home on the initial 404 screen |
| Boundary | Embodied interaction, sensor input, real-time visual feedback | Original installation documentation; no browser simulation is claimed |

## Supporting collection

INFORITANCE, Emotional Gut, Lifeview Foods, and Bluebeard–Fluid are presented as
creative and speculative projects, with original portfolio spreads and separate
introductions. Paws & Progress and Soleluxe remain accessible in the archive.
Kindred Pathways, Aether, and Rehousing are moved out of the selected homepage
collection. Existing source assets are retained.

This is a choice about the strongest evidence for the intended role, not a claim
that the archived projects have no value. Small code exercises remain outside
the selected collection.

## Content principles

- Explain the human problem, interaction model, and actual artifact.
- Describe AI as implemented, proposed, or disabled, as appropriate.
- Do not turn prototype statistics, sample reviews, or heuristic scores into
  evidence of adoption, conversion, carbon savings, or model performance.
- Do not claim clinical benefits, scientific validation, or completed user
  testing without supporting evidence.
- Name design focus without inventing team ownership or a sole-author role.
- Give each link an accurate label: prototype, preset demo, source, or documentation.

## Sources reviewed

- Relevant ChatGPT conversations, including “生成平台原型”, “design research”,
  “职业方向建议”, “AtoZ3.0”, and “canvasForCoders”. These are a scoped review,
  not an assertion that every historical conversation was read.
- Career Mixtape's public interface and the local Design Research outcome boards.
  The boards label themselves as design reconstructions with illustrative content.
- Public GitHub repositories under `zz11022-create`, including project source in
  `100days_of_making` and the available local GitHub checkouts.
- The 24-page NYU application portfolio on LaCie (project pages 3–24),
  earlier project texts, the Feline Oracle proposal, and its complete local source.
- Material Loop's initial route, its Back to Home interaction, and resulting homepage.
- Soleluxe's own hosted prototype rather than the previous collaborator-hosted link.

The application portfolio's résumé/contact page and unrelated application,
immigration, health, and financial records are not included in the website assets.

## Maintaining the site

Edit project descriptions and archive entries in `Queena_profile/projects/build.py`,
then run `python3 Queena_profile/projects/build.py`. The generated HTML is committed
so the site works on GitHub Pages without a build step. Homepage cards are edited
directly in `Queena_profile/index.html`. Shared additions are in `projects.css`.

The portfolio Feline Oracle copy is intentionally separate from the source on
LaCie. It contains no service credential or live generative API call. Its original
gesture, manual, card selection, and voice/text interactions are retained.

## Verification

- Checked local paths and fragment targets across 11 pages.
- Checked both inline JavaScript programs with `node --check`.
- Completed Feline Oracle's camera-free question → manual shuffle → draw →
  preset interpretation flow in the browser.
- Inspected the homepage on the available mobile browser viewport.
- Verified Career Mixtape public browsing, Material Loop's working in-app route,
  and Soleluxe's own prototype entry.

External prototype availability and service cold starts remain outside this static
portfolio's control. Camera/voice permissions and real sensor performance were
not exercised in browser verification.
