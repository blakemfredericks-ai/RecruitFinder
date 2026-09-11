# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** RecruitFinder, a one-page rush-board demo where a chapter can filter and browse fictional prospective-member profiles.
- **Audience:** Fraternity chapters and rush chairs who want a quick, structured way to explore possible PNM fits during recruitment planning.
- **Requirements:** One working primary interaction: preset filters for hometown, sports, interests, and legacy status update the visible profile cards; selected filters and zero-result states are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. Use clearly labeled fictional/sample profiles only—no real names, contact information, private records, accounts, required external service, keys, runtime AI, or data collection. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A clean, friendly roommate-app-style browsing layout with an approachable card grid, compact filter controls, and profile detail cards that feel organized rather than like a spreadsheet.
- **Test:** I can apply and clear a filter, confirm that the matching cards and count change, check the no-results boundary, and point to my standing rule’s effect in the actual preview. After I approve and merge, the same registered Pages URL works.
