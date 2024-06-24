Synchronal is an unincorporated cooperative group dedicated to developing and maintaining
open-source projects. We care deeply about testing and development workflow.

## Elixir

- [ecto_date_time_range](https://hexdocs.pm/ecto_date_time_range) - A library extending Ecto with field types to handle
  PostgreSQL column types encapsulating timestamp ranges. The types provided by this library can be paired with view
  components in order to facilitate editing ranges in forms.
- [ecto_email](https://hexdocs.pm/ecto_email/) - An Ecto.Type for email addresses, using the :email_validator library for validations.
- [ecto_temp](https://hexdocs.pm/ecto_temp) - An Ecto extension to support using PostgreSQL temporary tables with Ecto.
  This can be useful in situations where permanent tables may not be viable, such as when testing data migrations
  (where the schema at the time of test creation will differ over time), or to test modules that extend Ecto, but
  are not concernted with a specific schema.
- [elixir-gestalt](https://hexdocs.pm/gestalt) - A wrapper for Application.get_config and System.get_env
  that makes it easy to swap in process-specific overrides. Among other things, this allows tests to provide
  async-safe overrides.
- [exceed](https://hexdocs.pm/exceed) - A high-level stream-oriented library for generating Excel files, useful
  when generating spreadsheets from data sets large enough that they may exceed available memory—or the available
  memory that one wants to dedicate to building spreadsheets.
- [hex-publish-action](https://github.com/synchronal/hex-publish-action) - This action publishes an Elixir package
  to Hex.pm.
- [html_query](https://hexdocs.pm/html_query) - Helpers for finding and traversing HTML
  in Elixir. Typically used in tests for Phoenix/LiveView projects, paired with [pages](https://hexdocs.pm/pages).
- [markdown_formatter](https://hexdocs.pm/markdown_formatter/readme.html) - An Elixir formatter plugin for
  for Markdown.
- [medic](https://hexdocs.pm/medic) - Development workflow management. Help developers to
  rapidly set up a project on their workstations, and ship code that will pass CI. doctor/test/audit/shipit
  with alacrity.
- [moar](https://hexdocs.pm/moar) - A dependency-free library containing an assortment of useful functions.
- [pages](https://hexdocs.pm/pages) - A library for testing Phoenix user interfaces including seamlessly
  switching between LiveViews and controller-based views.
- [schema_assertions](https://hexdocs.pm/schema_assertions) - Test helpers for validating ecto schemas.
- [specter](https://github.com/synchronal/specter) - A wrapper for webrtc.rs as an Elixir NIF, using Rustler.
- [supra](https://hexdocs.pm/supra) - Common functions and macros for Ecto.
- [tablerone](https://github.com/synchronal/tablerone) - Renders Tabler Icons by downloading individual icons to the
  priv directory of the parent application during development, and loading them from files at runtime.
- [xml_query](https://github.com/synchronal/xml_query) - Some simple XML query functions. Delegates much of its work
  to :xmerl, but provides an API similar to HtmlQuery.

## Rust

- [dyd](https://github.com/synchronal/dyd) - Daily Diff. Opens diffs of changes across multiple git
  repositories, to rapidly review recent changes.
- [medic-rs](https://github.com/synchronal/medic-rs) - Medic. A rewrite of [elixir medic](https://hexdocs.pm/medic)
  in Rust, to facilitate the usage of the Medic workflow on projects written in languages other than Elixir.
- [retrogress](https://github.com/synchronal/retrogress) - A wrapper around indicatif, providing structs and traits
  that have a simple and limited API and that can be passed between modules and functions.
