# Add the original n8n workflows

The screenshots document two workflows. Their importable JSON exports have not been added to this repository yet.

## Export from n8n

1. Open the support-email workflow.
2. Open the workflow menu in the canvas header and choose **Download**.
3. Repeat for the knowledge-base ingestion workflow.

n8n downloads each workflow as JSON. The same menu provides **Import from File** for importing a workflow. See the [official export/import instructions](https://docs.n8n.io/workflows/export-import/).

## Prepare files for this public repository

Review each export before sharing it. Remove private pinned/test data, hardcoded secrets, and identifying resource values. n8n notes that exported workflows contain credential names and IDs, and HTTP Request nodes can retain authentication headers. Replace private configuration with descriptive placeholders while preserving the workflow structure.

Save the reviewed exports here as:

```text
workflows/
├── support-email-workflow.json
├── knowledge-base-ingestion.json
└── README.md
```

Reconnect credentials and configure private resource values inside the destination n8n instance. Record the n8n version, selected model IDs, sheet headers, and required configuration alongside the exports so another person can reproduce the setup.

Once reviewed exports are committed, update the **Current release** paragraph in the main README to describe what is actually available.

[Back to the project README](../README.md)
