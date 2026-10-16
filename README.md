# weird-readme-generator
> Paste a folder structure. Get a README that either roasts your project or says as little as possible.

**[Try it live](https://0sint0.github.io/weird-readme-generator/)**

## What it does

- Takes a folder structure (output from `tree`, an indented list, or plain file paths)
- Writes a README in **Funny** or **Minimal** mode
- Annotates your tree with jokes, and spots things like `.env`, `node_modules` and `final_v2` files
- Guesses install and run commands from the files it finds
- Lets you copy or download the result as `README.md`

Everything runs in your browser. Nothing is uploaded, and there are no dependencies.

## Run it locally

Download `index.html` and open it in a browser. That's it.

## Example

Input:

```
haunted-toaster/
├── src/
│   ├── main.py
│   └── toast_final_v2.py
├── tests/
└── Dockerfile
```

Funny mode output:

```
haunted-toaster/
├── src/                   # where the magic happens (and the bugs)
│   ├── main.py            # start here
│   └── toast_final_v2.py  # naming convention: panic
├── tests/                 # aspirational
└── Dockerfile             # works on my machine, now in a box
```

## Contributing

Ideas welcome: new tones (pirate, corporate, overly dramatic), more detected project types, better jokes. Open an issue or a pull request.

## License

MIT
