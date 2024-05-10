# Account-Kit

**A development kit for building and testing smart account modules.**

Account-Kit allows you to:

- **Easily build smart account modules** with interfaces for:
  - Validators
  - Executors
  - Hooks
- **Unit test** your modules using a dedicated helper library
- **Integration test** your modules using different modular ERC-4337 accounts and a helper library that abstracts away the complexity

In-depth documentation is available at [docs.rhinestone.wtf](https://docs.rhinestone.wtf/account-kit/).

> The Account-Kit is in active development and is subject to breaking changes. If you spot a bug, please take out an issue and we will fix it as soon as we can.

## Installation

```bash
pnpm install
```

### Using git submodules

```bash
forge install digiv3rse/account-kit
```

### Using a package manager

```bash
pnpm install @rhinestone/account-kit
```

## Updating

To update the Account-Kit, run:

```bash
forge update digiv3rse/account-kit
```

or

```bash
pnpm update @digiv3rse/account-kit
```

## Usage

To learn more about using Account-Kit, visit the [account-kit section](https://docs.rhinestone.wtf/account-kit) of the docs. To get a better understanding of Modules generally, visit the [modules section](https://docs.rhinestone.wtf/overview/modules) and for hands-on tutorials on the entire lifecycle of modules, visit the [tutorials section](https://docs.rhinestone.wtf/account-kit/build-multi-owner-validator).

## Features

- [ ] ERC-4337 integration tests
  - [x] On-chain integration test (EntryPoint -> Account)
  - [ ] Off-chain integration test (Bundler simulation and spec validation)
- [ ] Unit testing library
- [x] Different Module types
  - [x] Validators
  - [x] Executors
  - [x] Hooks
  - [x] Fallbacks
- [x] Different Modular Accounts
  - [x] ERC-7579
  - [x] Safe
  - [x] Biconomy
  - [x] Kernel
- [x] Deployment helper using Module Registry
- [x] Gas calculation helper

## Examples

For module examples, check out our [account-kit examples](./examples) and for module inspiration see our [module idea list](https://rhinestone.notion.site/Module-ideas-for-product-inspo-338100a2c99540f490472b8aa839da11). For general examples, check out the [awesome modular accounts repo](https://github.com/digiv3rse/awesome-modular-accounts).

## Contributing

For feature or change requests, feel free to open a PR, start a discussion or get in touch with us.

For guidance on how to create PRs, see the [CONTRIBUTING](./CONTRIBUTING.md) guide.

### Using this repo

To install dependencies, run:

```bash
pnpm install
```

To build the project, run:

```bash
pnpm build
```

To run tests, run:

```bash
pnpm test -r
```

## Credits

- [Safe{Core} Protocol](https://github.com/safe-global/safe-core-protocol/): ExecutorManager.sol is heavily insprired by Safe's SafeProtocolManager but is compatible across all supported accounts

## Authors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://twitter.com/digiv3rse/"><img src="https://pbs.twimg.com/profile_images/1639062011387715590/bNmZ5Gpf_400x400.jpg" width="100px;" alt=""/><br /><sub><b>zeroknots</b></sub></a><br /><a href="https://github.com/digiv3rse/registry/commits?author=zeroknots" title="Code">💻</a></td>
    
  </tr>
</table>
