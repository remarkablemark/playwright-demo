# playwright-demo

🎭 [Playwright](https://playwright.dev/) demo.

## Prerequisites

- [Node.js](https://nodejs.org/)

## Install

Clone the repository:

```sh
git clone https://github.com/remarkablemark/playwright-demo.git
cd playwright-demo
```

Install the dependencies:

```sh
npm install
```

## Run

Run the end-to-end tests:

```sh
npx playwright test
```

Start the interactive UI mode:

```sh
npx playwright test --ui
```

Run the tests only on Desktop Chrome:

```sh
npx playwright test --project=chromium
```

Run the tests in a specific file:

```sh
npx playwright test example
```

Run the tests in debug mode:

```sh
npx playwright test --debug
```

Auto generate tests with Codegen:

```sh
npx playwright codegen
```

Show HTML test reports:

```sh
npx playwright show-report
```

We suggest that you begin by typing:

```sh
npx playwright test
```

And check out the following files:

- `./tests/example.spec.ts` - Example end-to-end test
- `./tests-examples/demo-todo-app.spec.ts` - Demo Todo App end-to-end tests
- `./playwright.config.ts` - Playwright Test configuration

Visit https://playwright.dev/docs/intro for more information. ✨

Happy hacking! 🎭
