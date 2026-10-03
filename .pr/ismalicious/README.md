# IOC Triage validation evidence

This branch stores review evidence for the separate template PR branch `add-ismalicious-ioc-triage`. The template PR itself changes only the native JSON starter project.

The screenshot is from the actual published Langflow 1.12.4 Studio after the JSON was imported through its authenticated local API. Native CUA commands operated a dedicated Chrome window and its standard Capture screenshot command. No synthetic render or paid model was used. The screenshot demonstrates import and the native node wiring; it is not evidence of an end-to-end LLM response. Model provider and managed MCP credentials are deliberately not embedded in the export.

Graph.from_payload accepted four computational vertices and three edges. The native backend imported five UI nodes and three edges (the Note is not a computational vertex). Native MCP discovery reached the tools in the published npm0.6.0; npx discovery worked but an invocation hit the native 60-second session timeout on this host. Node 24.21.0 launching dist/index.js directly from the actual published npm tarball completed two native component builds. Both hit the synthetic HTTP fixture with the expected X-API-KEY header and exact content, preserving allow and block. This isolates the difference to the launcher path; it does not establish host load as the cause. The template Note now recommends a pinned local install, with npx as an alternative. This screenshot predates that setup wording clarification, but the nodes and wiring are unchanged. Full paid-model Agent and Cloud runs were not performed.

No live IsMalicious credentials, customer content or user email interface is in the screenshot or exported JSON. Prepared with AI assistance.
