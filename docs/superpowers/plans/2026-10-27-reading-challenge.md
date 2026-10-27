# Reading Challenge Integration Plan

**Goal:** Add the supplied 30-day reading challenge to Kalimati using the home card and return navigation approved by the user.

**Architecture:** Preserve the supplied standalone application in `reading-challenge.html`. Extend the existing JSON-encoded home template in `index.html` with a card matching the existing reading card. Keep application scripts and progress storage unchanged.

**Tech Stack:** Static HTML, CSS, JavaScript, JSON template.

- [x] Copy the UTF-8 document into `reading-challenge.html`, add Arabic document attributes and a return link outside its application container.
- [x] Duplicate the existing reading card with the challenge title, description, and relative page URL in the bundled template.
- [x] Validate template JSON, preservation of existing content and scripts, and both navigation destinations. JavaScript syntax checked with Node.js.
