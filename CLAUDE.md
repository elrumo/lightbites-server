# LightBites Server (release repository): instructions for agents

This repository only hosts the public downloads, the install script (`install.sh`) and the release notes of LightBites
Server. The source and the issue tracker are in [`elrumo/lightcraft`](https://github.com/elrumo/lightcraft)
(`apps/lightcraft-server`): code changes belong there.

## HelpBites
- **Not sure how to do something in HelpBites? Look it up before guessing.** This covers anything the user asks you to do
  in HelpBites (the board, comments and attachments, feedback, the changelog, email, errors, pricing, settings, anything).
  Read the live OpenAPI spec first (`https://helpbites.app/_docs/openapi.json`; the browsable reference is
  `https://helpbites.app/_docs/scalar`): it lists every route with its parameters and what it does. Then go through
  **all** the tools the HelpBites MCP connector offers (its tool list, or `tools/list` on `https://helpbites.app/mcp`),
  not only the board ones, and any HelpBites skill your client lists: a tool for the job often exists under a name you
  would not have guessed. Prefer a connector tool; call the admin API directly only when no tool covers it or the
  connector is down. Don't work from memory of this file or of an earlier session: HelpBites gains routes and tools
  often, and the spec and the tool list are always current.
- The LightBites app's tasks live on the HelpBites project's Planning board (project `tb4A2EAxRx`). For cards, comments,
  screenshots and moving work between columns, follow the `lightcraft` repo's `CLAUDE.md` → *HelpBites planning follows
  the work*.
