# GitHub Copilot Community SDKs

Community-maintained SDKs for building extensions and integrations with GitHub Copilot through the [Copilot CLI](https://github.com/features/copilot/cli).

> ⚠️ **Disclaimer**: These are unofficial, community-maintained SDKs. They are not officially supported by GitHub and may break due to changes in the Copilot CLI or APIs.

## What is GitHub Copilot CLI?

[GitHub Copilot CLI][copilot-cli] is an agent-powered terminal companion that reads, writes, and runs code where you work. It enables developers to code faster and smarter directly from the command line.

![GitHub Copilot CLI running in a terminal window](https://images.ctfassets.net/8aevphvgewt8/5oSoYr8RQkN6yYWqSObKGQ/f08bda1d8589ab89d9adf55a732beb13/HeaderImage.webp?w=1248&fm=webp&q=90)

### Key Capabilities

- **Get started in any codebase instantly** — Ask Copilot CLI to explore project structure, install dependencies, and explain how everything works through simple conversation.
- **Leverage GitHub context** — Bring context from your issues and pull requests directly to your environment, eliminating context switching.
- **Extend with MCP servers** — Extend Copilot CLI's capabilities through custom [MCP servers][mcp-registry].
- **Build, edit, debug, and refactor code locally** — Copilot CLI edits files, runs commands, and helps you iterate fast without leaving your terminal.

Copilot CLI is included with Copilot Pro, Pro+, Business, and Enterprise plans.

## What is the GitHub Copilot SDK?

The [Copilot SDK][copilot-sdk] provides language-specific libraries for programmatic access to the GitHub Copilot CLI, enabling developers to build custom tools and integrations.

### Key Features

- **Multi-turn conversations** — Maintain session history for context-aware interactions.
- **Tool execution** — Define custom tools that the model can invoke during conversations.
- **Full lifecycle control** — Manage client and session lifecycles programmatically.

## About

This organization hosts community-driven SDKs that enable developers to build tools and integrations with GitHub Copilot. These SDKs are created and maintained by the community to fill gaps in official tooling and provide language-specific implementations.

## Community SDKs (Hosted)

The following community SDKs are hosted within this organization:

| Language | Repository                          | Maintainer        |
| -------- | ----------------------------------- | ----------------- |
| Java     | [copilot-sdk-java][sdk-java]        | [@brunoborges][1] |
| Rust     | [copilot-sdk-rust][sdk-rust]        | [@0xeb][2]        |
| Clojure  | [copilot-sdk-clojure][sdk-clojure]  | [@krukow][3]  |

## Community SDKs (External)

The following community SDKs are maintained outside this organization:

| Language | Repository                          | Maintainer    |
| -------- | ----------------------------------- | ------------- |
| C++      | [copilot-sdk-cpp][sdk-cpp]          | [@0xeb][2]    |

## Official SDKs

For officially supported SDKs, see the [GitHub Copilot SDK][official-sdk] maintained by GitHub.

Currently, the officially supported languages by GitHub are:

| Language  | Repository                            |
| --------- | ------------------------------------- |
| .NET / C# | [copilot-sdk/dotnet][official-dotnet] |
| Python    | [copilot-sdk/python][official-python] |
| Go        | [copilot-sdk/go][official-go]         |
| Node.js   | [copilot-sdk/node][official-node]     |

## Contributing

Contributions are welcome! If you'd like to add a new SDK or improve existing ones, please open a pull request.

## License

See individual SDK directories for their respective licenses.

<!-- Copilot CLI and SDK References -->
[copilot-cli]: https://github.com/features/copilot/cli
[copilot-sdk]: https://github.blog/changelog/2026-01-14-copilot-sdk-in-technical-preview/
[mcp-registry]: https://github.com/mcp

<!-- Community SDK References -->
[sdk-java]: https://github.com/copilot-community-sdk/copilot-sdk-java
[sdk-cpp]: https://github.com/0xeb/copilot-sdk-cpp
[sdk-rust]: https://github.com/copilot-community-sdk/copilot-sdk-rust
[sdk-clojure]: https://github.com/copilot-community-sdk/copilot-sdk-clojure

<!-- Maintainer References -->
[1]: https://github.com/brunoborges
[2]: https://github.com/0xeb
[3]: https://github.com/krukow

<!-- Official SDK References -->
[official-sdk]: https://github.com/github/copilot-sdk
[official-dotnet]: https://github.com/github/copilot-sdk/tree/main/dotnet
[official-python]: https://github.com/github/copilot-sdk/tree/main/python
[official-go]: https://github.com/github/copilot-sdk/tree/main/go
[official-node]: https://github.com/github/copilot-sdk/tree/main/nodejs
