# OpenCode Toolkit

Focused plugins for [OpenCode](https://opencode.ai). See what each session costs, let text-only agents understand pasted images, and annotate replies and documents without leaving the terminal.

| Plugin | What it does | Install | Source |
|---|---|---|---|
| **opencode-metrics** | Sidebar metrics for each session: tokens, speed, time to first token, cache, and timing. | `opencode plugin add opencode-metrics@latest` | [nxxxsooo/opencode-metrics](https://github.com/nxxxsooo/opencode-metrics) |
| **opencode-multimodal-looker** | Sends pasted images to a cheap vision model, so a text-only main agent works from its text output. | Add the npm package to `opencode.json`; see the repo README. | [nxxxsooo/opencode-multimodal-looker](https://github.com/nxxxsooo/opencode-multimodal-looker) |
| **opencode-plannotator-tui** | Annotates the latest reply or a document in the terminal, then sends your confirmed feedback back to the session. | `opencode plugin add opencode-plannotator-tui@latest` | [nxxxsooo/opencode-plannotator-tui](https://github.com/nxxxsooo/opencode-plannotator-tui) |

Each plugin lives in its own repository, with its own release history and npm package. Read the plugin's README for requirements and configuration.

After installing or updating a plugin, restart the OpenCode client to load the new code.

## Related

- [another](https://github.com/nxxxsooo/another): move a session to another coding agent and keep the conversation.

## Notes

These are community plugins. They are not affiliated with or endorsed by OpenCode.

## License

Each plugin is licensed separately. See its repository for details.
