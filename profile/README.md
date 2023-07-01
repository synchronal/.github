Synchronal is an unincorporated cooperative group dedicated to developing and maintaining
open-source projects, typically using Elixir and Rust. We care deeply about testing and
development workflow.

## Elixir

- [html_query](https://hexdocs.pm/html_query) - Helpers for finding and traversing HTML
  in Elixir. Typically used in tests for Phoenix/LiveView projects, paired with [pages](https://hexdocs.pm/pages).
- [markdown_formatter](https://hexdocs.pm/markdown_formatter/readme.html) - An Elixir formatter plugin for
  for Markdown.
- [medic](https://hexdocs.pm/medic) - Development workflow management. Help developers to
  rapidly set up a project on their workstations, and ship code that will pass CI. doctor/test/audit/shipit
  with alacrity.
- [pages](https://hexdocs.pm/pages) - A functional [page object pattern](https://martinfowler.com/bliki/PageObject.html)
  providing adapters for writing Phoenix/LiveView tests.
- [schema_assertions](https://hexdocs.pm/schema_assertions) - Test helpers for validating ecto schemas.
- [seed](https://github.com/synchronal/seed) - Opinionated boilerplate for starting Phoenix/LiveView projects.

## Development workflow

- [dyd](https://github.com/synchronal/dyd) - Daily Diff. Opens diffs of changes across multiple git
  repositories, to rapidly review recent changes.
- [medic-rs](https://github.com/synchronal/medic-rs) - Medic. A rewrite of [elixir medic](https://hexdocs.pm/medic)
  in Rust, to facilitate the usage of the Medic workflow on projects written in languages other than Elixir.
