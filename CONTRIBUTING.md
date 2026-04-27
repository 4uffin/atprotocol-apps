# Contributing to the AT Protocol App Directory

To maintain the quality and organization of this directory, please follow these guidelines when submitting new applications or updates.

## Submission Standards
1. **Alphabetical Order:**
   - Ensure the category is placed alphabetically within the main list.
   - Ensure the application is placed alphabetically within its specific category.
3. **Link Attributes:** All hyperlinks MUST include:
   - `target="_blank"` (Open in new tab)
   - `rel="noopener"` (Security best practice)
   - `title="Visit [App Name]"` (Tooltip accessibility)
4. **Descriptions:** Descriptions should be brief, professional, and accurate. Avoid marketing "fluff."

## Technical Checklist
Before submitting a Pull Request, verify the following structure:
```
<section class="app">
  <details>
    <summary>
      <a href="URL" target="_blank" rel="noopener" title="Visit AppName">AppName (Type)</a>
    </summary>
    <p>Description of the service.</p>
  </details>
</section>
```

## Category Definitions
If an app does not fit an existing category, propose a new one in your PR description. Current categories include:
- Blogging & Longform
- Communities & Forums
- Developer & Infrastructure Tools
- Lifestyle & Events
- Music & Audio
- Social Bookmarking & Curation
- Social Clients (Microblogging)
- Video & Photo Platforms
