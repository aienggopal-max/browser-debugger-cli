# bdg - Browser Debugger CLI

`bdg` opens a persistent Chromium session that developers and coding agents can control from the terminal. Use it to interact with a page, inspect the DOM and styles, read console and network activity, and send raw Chrome DevTools Protocol commands.

## Quick start

Requires Node.js 22.12+ and a Chromium-based browser such as Chrome, Chromium, or Microsoft Edge. Use macOS, Linux, or WSL on Windows.

```bash
npm install -g browser-debugger-cli
bdg https://example.com
bdg dom inspect 'h1'
bdg network list --preset errors
bdg console
bdg stop
```

Use `bdg --help --json` for machine-readable command help, `bdg install-skill` to install the agent skill, or `bdg attach` to connect to a browser you already have open.

## Documentation

- [CLI reference](docs/CLI_REFERENCE.md)
- [Changelog](CHANGELOG.md)

## Repository owner

`aienggopal-max` owns and maintains this GitHub repository.

## License

See the [MIT License](LICENSE).
