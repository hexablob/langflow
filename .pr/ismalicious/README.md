# IOC Triage validation evidence

This branch stores review evidence for the separate template PR branch `add-ismalicious-ioc-triage`. The template PR itself changes only the native JSON starter project.

The screenshot is from the actual published Langflow 1.12.4 Studio after the JSON was imported through its authenticated local API. Native CUA commands operated a dedicated Chrome window and its standard Capture screenshot command. No synthetic render or paid model was used. The screenshot demonstrates import and the native node wiring; it is not evidence of an end-to-end LLM response. Model provider and managed MCP credentials are deliberately not embedded in the export.

Graph.from_payload accepted four computational vertices and three edges. The native backend imported five UI nodes and three edges (the Note is not a computational vertex). Native MCP discovery reached the tools in the published npm0.6.0; the first stdio invocation attempt hit the native60s session timeout under host load. Final isolated tool-call results are recorded in the publication receipt.

No live IsMalicious credentials, customer content or user email interface is in the screenshot or exported JSON. Prepared with AI assistance.
