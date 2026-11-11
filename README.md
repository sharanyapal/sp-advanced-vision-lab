<div align="center">

# Vision / Motion

**Computer vision experiments with inspectable behavior.**

`HTML · CSS · JavaScript` · Educational implementation · Source available

[Concept](#concept) • [Run](#run) • [Source tour](#source-tour) • [Caveats](#caveats)

</div>

---

## Concept

Privacy-first on-device motion detector and image capture via getUserMedia and pixel differencing.

## Run

```bash
python -m http.server 8000
```
Visit **http://localhost:8000/**.

## Source tour

| In this repository | Role |
|:--|:--|
| [`README.md`](./README.md) | Technical context |
| [`app.js`](./app.js) | Application logic |
| [`index.html`](./index.html) | Web interface |
| [`styles.css`](./styles.css) | Styling and layout |

## Caveats

Treat this as a reproducible educational project. Simulation outputs depend on the project assumptions; use synthetic inputs, inspect edge cases and review the source before applying any approach to a production system.

<details>
<summary>Original documentation and implementation notes</summary>

# Vision / Motion

Privacy-first on-device motion detector and image capture via getUserMedia and pixel differencing.

Run locally with a static server: `python -m http.server 8000` from the Advanced Labs root and open `http://localhost:8000/apps/vision-lab/`.

No credential or secret is embedded. See app.js for implementation and edge cases.

</details>

---

<sub>Code and commentary in the [Sharanya Pal project index](https://github.com/sharanyapal?tab=repositories).</sub>
