# Metex

A simple weather app in Elixir. A concurrent program in Elixir. It uses mutliple processes to perform computations concurrently.

## Getting started

- Add Openweather credentials to `lib > metex.ex`
- run `iex -S mix`
- Call `Metex.Worker.temperature_of "<NAME OF CITY>"`