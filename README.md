# JavaScript Exercises

A collection of small browser-based JavaScript exercises. The current repository contains a **timer example** in `Temporizador/`.

## Run the timer

There is no package manifest or build step. Serve the repository root with a static HTTP server; for example, with Python 3:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open **http://127.0.0.1:8000/Temporizador/**.

## Source

Start with [Temporizador/index.html](Temporizador/index.html). The directory name is retained from the original exercise.

## Development

Keep new exercises in separate directories with an `index.html` entry point. Document any required external scripts alongside the exercise.

The current repository does not contain automated tests. Check the timer controls and browser console manually after changes. Externally loaded resources require a working connection and have not been revalidated during this documentation update.
