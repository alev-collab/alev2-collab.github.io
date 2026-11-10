Alec - AI Operations portfolio

Structure
  index.html                   Home: hero, results, request-flow animation, case study cards, method
  supplement-brand/index.html  Case study: supplement brand (29,900+ AI-resolved)
  sportswear-brand/index.html  Case study: sportswear brand (216 estimated hours saved)
  clothing-brand/index.html    Case study: clothing brand (94.5% AI resolution)
  assets/site.css              Unused right now: no page links it (all pages use inline styles)

Add a new case study
  1. Copy the clothing-brand/ folder, rename it (e.g. new-brand/), and edit its index.html.
  2. In index.html, copy one <a class="project-card reveal" ...> card in the "Work" section,
     point its href to "new-brand/", and update the tag, title, description, and stat tags.
  3. Update the matching metric card in "Selected results" if the new case adds a number.

Motion
  Scroll reveals, counters, the request-flow diagram, and the live routing feed are in
  index.html. All of them respect prefers-reduced-motion, so visitors who turn that setting
  on see the final state with no movement.
