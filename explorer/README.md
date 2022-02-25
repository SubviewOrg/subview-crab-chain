# Subview

This is a tool for inspecting and analyzing the POA Network blockchain.


## Machine Requirements

* Erlang/OTP 21+
* Elixir 1.9+
* Postgres 10.3


## Required Accounts

* Github for code storage


## Setup Instructions

### Development

To get Subview up and running locally:

  * Install dependencies with `$ mix do deps.get, local.rebar, deps.compile, compile`
  * Create and migrate your database with `$ mix ecto.create && mix ecto.migrate`
  * Run IEx (Interactive Elixir) to access the index and explore: `$ iex -S mix`

### Testing

  * Format the Elixir code: `$ mix format`
  * Lint the Elixir code: `$ mix credo --strict`
  * Run the dialyzer: `mix dialyzer --halt-exit-status`
  * Check the Elixir code for vulnerabilities: `$ mix sobelow --config`
