![Logo](https://cdn.addtowallet.io/img/addtowallet-sdk-logo-2.png)

**Full documentation:** [https://addtowallet.github.io/sdk/](https://addtowallet.github.io/sdk/)

**TypeScript client for the AddToWallet API**

`@addtowallet/sdk` is a library for communicating with the AddToWallet platform from Node.js and TypeScript:

- **Full API coverage:** Campaigns, passes, templates, scanners, workflows, webhooks, and more.
- **Runtime validation:** Zod schemas for every response type with optional strict parsing.
- **Flexible auth:** API keys or OAuth providers wired through a shared `Client`.

## Documentation

| Topic               | Link                                                                       |
| ------------------- | -------------------------------------------------------------------------- |
| Getting started     | [Introduction](https://addtowallet.github.io/sdk/)                         |
| Installation        | [Installation](https://addtowallet.github.io/sdk/installing)               |
| Setup               | [Setup](https://addtowallet.github.io/sdk/setup)                           |
| API usage           | [Usage](https://addtowallet.github.io/sdk/usage/)                          |
| Response validation | [Runtime validation](https://addtowallet.github.io/sdk/runtime-validation) |

Canonical docs live in [`docs/`](./docs/). Edit those pages directly, then run `pnpm docs:build:nav` to refresh the VitePress sidebar.

## Development

```bash
pnpm install
pnpm test
pnpm docs:serve    # VitePress dev server with nav watcher
pnpm docs:build    # production docs build
```

## License

MIT
