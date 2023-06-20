# Starlark Language Server Proposal

Do you wish that your editor/IDE provided fancy capabilities for [Starlark] (e.g., auto complete, go
to definition, hover information)? If so, read on and help us get to our funding goal to make this
project a reality.

| Quick Facts  |                                                                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| What         | Implement a language server for the [Starlark language].                                                                                                 |
| Why          | Fancy features like go to definition, hover information and auto complete in your favorite editor/IDE. (see [Language Server Protocol] for more details) |
| Who          | [Chuck Grindel]                                                                                                                                          |
| Language     | Implement the server using [Go].                                                                                                                         |
| License      | [Apache 2.0]                                                                                                                                             |
| GitHub Owner | <https://github.com/bazel-contrib>                                                                                                                       |
| Contribute   | Help us reach our funding goals by [contributing].                                                                                                       |

## 💻 What is a language server?

A language server is a command-line executable that implements the [Language Server Protocol] (LSP).
It interacts with a client in your editor/IDE to provide the smarts that every developer loves and
wishes that they had for [Starlark].

## 📝 The Plan

The plan consists of four phases:

1. Initial server implementation plus support for go to definition and find references.
1. Support hover information.
1. Support auto completion.
1. Support signature help.

Other features that are on the roadmap are support for

- linting
- formatting
- code lens (provide contextual information and actions)
- code folding
- rename variables/functions

### 💰 Funding Goals

To gauge the community's interest and to ensure that we have enough support before we get started,
we are setting this up like a Kickstarter project. Reaching a funding goal unlocks the phase,
green-lighting it for development.

| Phase                                                            | Estimate (Weeks) | Funding Goal |
| ---------------------------------------------------------------- | ---------------: | -----------: |
| Initial server implementation; go to definition, find references |                8 |      $60,000 |
| Support hover information                                        |                3 |      $16,000 |
| Support auto completion                                          |                3 |      $16,000 |
| Support signature help                                           |                3 |      $16,000 |

### 💵 Contribute / Sponsorship

### 🗓️ Timeline

## 🙋‍♀️ FAQ

## 🌎 Related Links

- [Starlark LSP issue](https://github.com/bazel-contrib/SIG-rules-authors/issues/52)

[Go]: https://go.dev/
[Chuck Grindel]: https://github.com/cgrindel
[Apache 2.0]: https://www.apache.org/licenses/LICENSE-2.0
[Language Server Protocol]: https://microsoft.github.io/language-server-protocol/
[Starlark language]: https://github.com/bazelbuild/starlark/blob/master/spec.md
[Starlark]: https://github.com/bazelbuild/starlark/blob/master/spec.md
[contributing]: https://opencollective.com/bazel-rules-authors-sig/projects/language-server#category-CONTRIBUTE
