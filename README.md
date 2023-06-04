<p align="center">
	<img src="https://vhs.charm.sh/vhs-1q9uo4hkLStOL4UHZFfQ4W.gif" alt="Made with VHS">
	<a href="https://vhs.charm.sh">
		<img src="https://stuff.charm.sh/vhs/badge.svg">
	</a>
	<br>
	<h1 align="center">timer</h1>
	<p align="center">A <code>sleep</code> with progress.</p>
</p>

---

Timer is a small CLI, similar to the `sleep` everyone already knows and love,
with a couple of extra features:

- a progress bar indicating the progression of said timer
- a timer showing how much time is left
- named timers

## Usage

```sh
timer <duration>
timer -n <name> <duration>
man timer
timer --help
```

It is possible to pass a time unit for `<duration>`.

Valid time units are "ns", "us" (or "µs"), "ms", "s", "m", "h".
If no unit is passed, it defaults to seconds ("s").

## Installation

0. Make sure [go](go.dev) is installed
1. Clone this repo
2. Run `go build -o timer`

(`go build -o timer.exe` for windows)
