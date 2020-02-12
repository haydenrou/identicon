# Identicon

**By taking a random string, this will generate an identicon of 5 by 5 pixels.**

## Installation

Assuming you have Elixir installed, enter the directory and run ```iex -S mix```
Within the console, run the following to generate an image in the current directory.
```
Identicon.main("my_string")
```

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

