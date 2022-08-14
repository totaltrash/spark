# Spark

Spark is a generic tool for building well documented and powerful DSLs that come with useful tooling out of the box. DSLs are declared using simple structs, and every DSL has the ability to be extended by the end user. Spark powers all of the DSLs in Ash Framework.

What you get for your DSL when you implement it with Spark:

- Extensibility. Anyone can write extensions for your DSL.
- Autocomplete and in-line documentation: An elixir_sense plugin that "Just Works" for any DSL implemented with Spark.
- Tools to generate documentation for your DSL automatically.
- Tools to create rich library documentation. [AshHq](https://ash-hq.com)'s documentation is all derived from `Spark.DocIndex`.

## Dependency

```elixir
def deps do
  [
    {:spark, "~> 0.1.2"}
  ]
end
```