# n8n LinkedIn Post Approval Workflow

A multi-agent n8n workflow that drafts LinkedIn posts, reviews them, and waits for human approval by email before logging the result.

> Part of my Gen AI course practice work (Week 4, Day 2).

## Tech stack

- n8n
- OpenAI
- Gmail
- Google Sheets

## Features

- Form trigger collects the post topic
- Writer agent drafts, reviewer agent improves
- Gmail send-and-wait approval step
- Approved posts are appended to a Google Sheet

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/n8n-linkedin-post-approval-workflow.git
   cd n8n-linkedin-post-approval-workflow
   ```
2. In n8n choose Import from File and select `workflows/linkedin-post-approval.json`, then connect your own credentials.

## License

MIT, see [LICENSE](LICENSE).
