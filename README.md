# termbox.c3l

[Termbox2](https://github.com/termbox/termbox2) bindings for the [C3](https://c3-lang.org) language.

## Installation

From your project's `lib/` folder, clone the repository:

```sh
cd lib/
git clone https://github.com/guiBrisson/termbox.c3l
```

Then add it to your `project.json`:

```json
"dependency-search-paths": ["lib/"]
"dependencies": ["termbox"],
```

## Compressed version

If you prefer a packed `.c3l` file, run the included script after cloning:

```sh
cd lib/termbox.c3l
./compress.sh
```
