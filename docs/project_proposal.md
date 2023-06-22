# Starlark Language Server Proposal

Do you wish that your editor/IDE provided fancy capabilities for [Starlark] (e.g., auto complete, go
to definition, hover information)? If so, read on and help us get to our funding goal to make this
project a reality.

| Quick Facts  |                                                                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| What         | Implement a language server for [Starlark].                                                                                                              |
| Why          | Fancy features like go to definition, hover information and auto complete in your favorite editor/IDE. (see [Language Server Protocol] for more details) |
| Who          | [Chuck Grindel]                                                                                                                                          |
| When         | As soon as we meet our funding goals.                                                                                                                    |
| Language     | Implement the server using [Go].                                                                                                                         |
| License      | [Apache 2.0]                                                                                                                                             |
| GitHub Owner | <https://github.com/bazel-contrib>                                                                                                                       |
| Contribute   | Help us reach our funding goals by [contributing].                                                                                                       |

## 💻 What is a language server?

A language server is a command-line executable that implements the [Language Server Protocol] (LSP).
It interacts with a client in your editor/IDE to provide the smarts that every developer loves and
wishes that they had for [Starlark].

## 📝 The Plan

[The plan] consists of four phases:

1. Initial server implementation plus support for go to definition and find references.
1. Support hover information.
1. Support auto completion.
1. Support signature help.

Once we meet our initial funding goals, other features that are on the roadmap are support
for

- linting
- formatting
- code lens (provide contextual information and actions)
- code folding
- rename variables/functions

### 💰 Funding Goals

To gauge the community's interest and to ensure that we have enough support before we get started,
we are setting this up like a Kickstarter project. Reaching a funding goal unlocks the phase,
green-lighting it for development.

| Phase                                                                     | Estimate (Weeks) | Funding Goal |
| ------------------------------------------------------------------------- | ---------------: | -----------: |
| Phase 1: Initial server implementation; go to definition, find references |               11 |      $64,000 |
| Phase 2: Support hover information                                        |                3 |      $16,000 |
| Phase 3: Support auto completion                                          |                3 |      $16,000 |
| Phase 4: Support signature help                                           |                3 |      $16,000 |
| Grand Total                                                               |               20 |     $111,000 |

For more details on the plan and the estimates, please see the [planning Google sheet].

### 💵 Contribute / Sponsorship

We need your help! We can't get this project started without you. If you wish that your editor/IDE
provided magic for [Starlark] like other first-class languages, please head over to the [contribution
page] and sponsor this project.

### 🗓️ Timeline

We are [collecting funds now]. The deadline for meeting the goal for the first phase of the project
is August 1, 2023. If we hit our goal by August 1, 2023, implementation will start August 7, 2023.

## 🙋‍♀️ FAQ

### Is this being run through Kickstarter?

No. The financial management for this project is hosted by the [Starlark Language Server project]
under the [Bazel Rules Authors SIG Open Collective].

### Can I see the budget? Can I see how the money is being spent?

Yes. All of the financial activity for the project can be viewed on the [Starlark Language Server
project] page.

### What kind of oversight is in place?

The engineers that work on the project submit invoices for the work performed on the project.
The invoices are reviewed and approved by [the administrators for the Bazel Rules Authors SIG Open
Collective].

### What happens if I donate money, but the first funding goal is not met?

You have two options. The first option is that we can refund the money that you donated.
Alternatively, you can choose to donate the money to the [Bazel Rules Authors SIG Open Collective].

### Once implemented, are there any additional fees to use the Starlark language server?

No. The code will be available on GitHub under the [Apache 2.0] license. However, we would greatly
appreciate recurring sponsorship to incent the maintenance and upkeep of the project.

## 🌎 Related Links

- [Contribution page]
- [Starlark LSP issue]
- [Open Collective Projects documentation]

[Apache 2.0]: https://www.apache.org/licenses/LICENSE-2.0
[Bazel Rules Authors SIG Open Collective]: https://opencollective.com/bazel-rules-authors-sig
[Chuck Grindel]: https://github.com/cgrindel
[Go]: https://go.dev/
[Language Server Protocol]: https://microsoft.github.io/language-server-protocol/
[Open Collective Projects documentation]: https://docs.opencollective.com/help/collectives/projects
[The plan]: https://docs.google.com/spreadsheets/d/1IJCaemCIii3V0ClV8MzrZ1Vxx3KQcOt2Eg69Jj7oQYQ/edit?usp=sharing
[planning Google sheet]: https://docs.google.com/spreadsheets/d/1IJCaemCIii3V0ClV8MzrZ1Vxx3KQcOt2Eg69Jj7oQYQ/edit?usp=sharing
[Starlark LSP issue]: https://github.com/bazel-contrib/SIG-rules-authors/issues/52
[Starlark Language Server project]: https://opencollective.com/bazel-rules-authors-sig/projects/starlark-language-server
[Starlark]: https://github.com/bazelbuild/starlark/blob/master/spec.md
[collecting funds now]: https://opencollective.com/bazel-rules-authors-sig/projects/starlark-language-server#category-CONTRIBUTE
[contributing]: https://opencollective.com/bazel-rules-authors-sig/projects/starlark-language-server#category-CONTRIBUTE
[contribution page]: https://opencollective.com/bazel-rules-authors-sig/projects/starlark-language-server#category-CONTRIBUTE
[the administrators for the Bazel Rules Authors SIG Open Collective]: https://opencollective.com/bazel-rules-authors-sig#category-ABOUT
