# Run-log Sanitization Prompt

Edit the following research Agent run log into a public-safe Markdown document.

Requirements:

1. Remove local file paths and machine-specific information.
2. Remove raw code blocks and command-line details.
3. Remove unpublished data files and private dataset names.
4. Generalize sensitive numerical values if they are not needed for public demonstration.
5. Keep the high-level workflow, decisions, troubleshooting process, and final outcomes.
6. Preserve the structure of the log so that readers can understand what the Agent accomplished.
7. Do not invent results or add unsupported claims.

The final document should demonstrate the Agent-assisted workflow without exposing confidential research details.
