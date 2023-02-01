Inside that directory, you can run several commands:

Runs the end-to-end tests.

```bash
npx playwright test
```

Runs the tests only on Desktop Chrome.

```bash
npx playwright test --project=chromium
```

Runs the tests in a specific file.

```bash
npx playwright test example
```

Runs the tests in debug mode.

```bash
npx playwright test --debug
```

Auto generate tests with Codegen.

```bash
npx playwright codegen
```

We suggest that you begin by typing:

    npx playwright test

And check out the following files:

- ./tests/example.spec.ts - Example end-to-end test
- ./tests-examples/demo-todo-app.spec.ts - Demo Todo App end-to-end tests
- ./playwright.config.ts - Playwright Test configuration

Visit https://playwright.dev/docs/intro for more information. ✨

Happy hacking! 🎭
