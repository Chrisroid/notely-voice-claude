# Notely Voice

Search and read your existing Notely Voice Pro library from Claude: voice notes, full audio transcripts, AI-generated summaries, action items, and folders.

## What it does

- **Library overview** – total notes, starred notes, folder breakdown and recent activity
- **Recent notes** – your latest recordings with titles, dates, folders and summaries
- **Search** – find notes by topic, with snippet previews
- **Open a note** – full transcript, summary, key takeaways and action items
- **Folders** – list your folders with note counts

The plugin is read-only. It does not record audio, transcribe new uploads, edit or delete notes, share notes, or process payments.

## Example prompts

- "Give me an overview of my voice notes and library."
- "What are my most recent voice notes?"
- "Search my voice notes for project launch discussions."
- "Open the transcript and action items for my last meeting."
- "List all my voice note folders."

## Setup

1. Install the plugin.
2. When prompted, connect your Notely Voice account. Sign-in uses OAuth on notelyvoice.ai; you never paste a password or token into Claude.
3. Ask: "Give me an overview of my voice notes."

You need a Notely Voice Pro account.

## What the plugin contains and connects to

- One skill (`get-started`) that tells Claude how to use the Notely Voice tools safely.
- One remote MCP server: `https://mcp.notelyvoice.ai/mcp`, operated by Notely Voice Pro.

Your search queries and note requests are sent to that server, and the notes it returns are shown to Claude to answer you. The plugin runs no local code, installs no packages, contains no credentials, and sends data nowhere else.

## Privacy and support

- Privacy policy: https://notelyvoice.ai/privacy
- Terms of service: https://notelyvoice.ai/terms
- Support: support@notelyvoice.ai

To disconnect, remove the Notely Voice connection in Claude's connector settings, and revoke access from your Notely Voice account if you want existing authorization removed.
