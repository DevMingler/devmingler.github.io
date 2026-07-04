Revive the DevMingler GitHub Pages website.

Repo: DevMingler/devmingler.github.io
Live site: https://devmingler.github.io/

Goal:
Review the existing codebase and revive the site into a modern, lightweight landing page for the DevMingler developer community. Keep the site simple, fast, readable, and easy to maintain.

Important context:
DevMingler started as a developer community page in 2023. The community has now been revived in 2026. The Discord server has grown again, from about 9 members on 11 June 2026 to 41 members on 04 July 2026. The site should feel alive, current, welcoming, and project-focused.

DevMingler is now:
- a cozy build club for developers, tinkerers, learners, and AI-tool explorers
- a place to share repos, small wins, questions, bugs, and experiments
- a community with Discord channels, builders energy, and project-specific spaces
- home to small open-source experiments, especially Footprints

Please review the existing code first.
Before making changes:
1. Inspect the current file structure.
2. Identify the current HTML, CSS, assets, and copy.
3. Preserve anything useful from the existing site.
4. Improve outdated or overly generic copy where needed.
5. Keep the spirit of the original DevMingler message: developers unite, learn together, build together, and support each other.

Visual direction:
Use the new DevMingler banner design as the main visual inspiration.

The banner image should be added to the site as a hero/banner image or used as a visual reference for the overall design.

Expected banner asset path:
`./images/devmingler-banner.png`

If the asset does not exist yet, add a placeholder reference and document where the image should be placed.

Design language:
- soft blue gradient
- navy accents
- clean white text
- rounded shapes
- subtle cloud-like forms
- faint connection lines or node patterns
- small developer motifs such as code brackets, stars, laptop icons, group/community icons, or simple geometric accents
- friendly, modern, minimal vector-inspired style
- professional but warm
- not corporate
- not noisy
- not overdesigned

Avoid:
- heavy animations
- badge clutter
- giant walls of text
- generic startup copy
- excessive JavaScript
- complicated frameworks unless the repo already uses one
- visual clutter
- pretending DevMingler is a massive organization

Content requirements:
Create a revived one-page landing site with these sections:

1. Hero
- Use the banner image or a banner-inspired hero layout.
- Main heading: DevMingler
- Tagline: A cozy build club for developers
- Short intro copy explaining the community.
- Primary CTA: Join the Discord
- Secondary CTA: View Projects

If there is no Discord invite link in the existing code, use a clear placeholder:
<!-- TODO: Add Discord invite link -->

2. What is DevMingler?
Use brief, warm copy. Suggested direction:
DevMingler is a small developer community for people who want to build, learn, experiment, and stay gently in motion. Bring a repo, a half-built idea, a question, a tiny win, or a suspicious bug.

3. What we do
Use short cards or bullets:
- Build small open-source projects
- Share repos, bugs, questions, and ideas
- Experiment with AI-assisted development
- Celebrate tiny wins and progress
- Help each other keep going

4. Featured project: Footprints
Add a highlighted section for Footprints.

Suggested copy:
Footprints is an open-source experiment for exploring ChatGPT export data and turning conversation history into useful reflection. It helps people notice what they have been building, asking, learning, repeating, and becoming.

Include links to:
- https://github.com/DevMingler/footprints-codex-skill
- https://github.com/DevMingler/footprints-custom-gpt
- https://github.com/DevMingler/footprints-bts

5. Community experiments
Add a compact project list or card grid linking to:
- https://github.com/DevMingler/logo-matcher-game
- https://github.com/DevMingler/logo-pairs-game
- https://github.com/DevMingler/codewars-leaderboard
- https://github.com/DevMingler/rainbow-finder
- https://github.com/DevMingler/youtube-shorts-saver

Keep descriptions short.

6. Join in
Add a friendly invitation section.

Suggested copy:
No grand entrance required. Lurking is allowed. Gentle chaos is encouraged. Come share what you are building, or ask the tiny question.

Include:
- Discord CTA with placeholder if needed
- GitHub organization link: https://github.com/DevMingler
- Contact email: dev.mingler@gmail.com

Technical requirements:
1. Keep the site static and GitHub Pages friendly.
2. Do not add unnecessary dependencies.
3. Use semantic HTML.
4. Ensure responsive design for desktop and mobile.
5. Ensure good contrast and readable font sizes.
6. Add alt text for images.
7. Keep CSS organized and easy to maintain.
8. If there is existing CSS, improve it rather than replacing everything blindly.
9. If there are unused files or stale assets, identify them and clean them up only if safe.
10. Test locally if possible or explain how to preview the site.

Suggested implementation:
- Update index.html.
- Update or create a main stylesheet if needed.
- Add or reference images/devmingler-banner.png.
- Use CSS variables for colors.
- Use card sections with rounded corners and soft borders.
- Add subtle background accents using CSS gradients or pseudo-elements.
- Keep everything lightweight.

Suggested color palette:
- deep navy: #0b1f3a
- rich blue: #0f4c81
- bright sky blue: #4bb3fd
- pale blue: #dff4ff
- white: #ffffff
- soft background: #f5fbff

Suggested tone:
Warm, brief, practical, lightly playful.

Example lines that can be used or adapted:
- “Bring a repo, a half-built idea, a question, a bug, or a tiny win.”
- “We are not here to be perfect. We are here to keep building.”
- “A small community for developers who want to build gently and share early.”
- “No grand entrance required. Lurking is allowed. Gentle chaos is encouraged.”

Deliverables:
1. Updated website files.
2. A brief summary of what changed.
3. Any TODOs left behind, especially for missing links or missing banner asset.
4. Ensure the final result is polished enough to commit and deploy through GitHub Pages.