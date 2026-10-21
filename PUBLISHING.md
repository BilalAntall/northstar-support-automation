# Publish Northstar Support Automation on GitHub

## Repository details

Use these settings:

- **Name:** `northstar-support-automation`
- **Visibility:** Public
- **Description:** AI-assisted customer support automation with n8n, Gmail, Google Gemini, Pinecone RAG, and Google Sheets.
- **Suggested topics:** `n8n`, `workflow-automation`, `customer-support`, `gmail`, `google-gemini`, `pinecone`, `rag`, `google-sheets`

The repository package includes the README, two workflow screenshots, a demo transcription, and export instructions. The supplied Gmail screenshot stays outside this package because it displays a personal email address and profile photo.

## Upload using the GitHub website

1. Sign in to GitHub and open [Create a new repository](https://github.com/new).
2. Enter the details above. Leave the automatic README, .gitignore, and license options unselected; this package already provides the first two. Click **Create repository**.
3. Use **uploading an existing file** on the empty repository page, or **Add file → Upload files** on a repository that already has files.
4. Drag the **contents** of the prepared `northstar-support-automation` folder into the upload area. Preserve the `docs` and `workflows` folders. Do not upload the outer project folder, the `.git` directory, the ZIP archive itself, or the original screenshots beside the prepared folder.
5. Confirm that `README.md` will be at the repository root and the two PNGs will be under `docs/images/`.
6. Enter a commit message such as `Document Northstar support automation`, then complete GitHub's commit flow.
7. Open the repository and check that the README, both images, Mermaid diagram, and relative links render correctly.

If using the ZIP, extract it first and upload its contents. A ZIP committed as a single file will not display its README as the repository's homepage.

These steps follow GitHub's documentation for [creating a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository) and [uploading files](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## Add the automation files

Follow [workflows/README.md](workflows/README.md) to export and review the two original workflows. Add the reviewed JSON files through the same upload process, keeping them in the `workflows/` directory.

The project can be published as a portfolio walkthrough now. Adding the actual workflows, the n8n version, the configured model IDs, the sheet schema, and shareable policy content makes it more useful to someone who wants to reproduce it.

## Improve the repository page

In the repository's **About** settings, add the description and topics above. Choose a license later if you want to grant reuse permissions; none has been selected in this package.

[Back to the project README](README.md)
