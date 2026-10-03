Published Langflow 1.12.4 imported the native JSON (HTTP201, 5 UI nodes and 3 edges). Native computational graph: 4 vertices and 3 edges. Actual core MCP Tools discovery reached npm0.6.0 tools.

Native test script completed successfully with the published tarball dist/index.js launched by Node24.21.0, synthetic fixture-key:fixture-secret, prewarm0 and a loopback HTTP API:
- Native registration HTTP200
- Native flow943bed8e-0c98-4358-9dab-33a559f9459d
- build e9d1afc9-927b-49ad-acbb-eb1d65ddb0b7 preserved allow
- build e31eae30-1237-4168-af86-a86c571aa3cf preserved block
- Both fixture requests had the expected X-API-KEY header and exact content, /gate/scan, one request each.

The earlier npx path discovered tools but tool-call connection attempts exceeded the native60-second session initialization. No timeout was raised or security check disabled. Direct published dist passed. This does not prove host load was the cause or that npx fails on other deployments. Native SDK/fixture tests do not test real detector accuracy, an actual paid language model or Cloud deployment.
