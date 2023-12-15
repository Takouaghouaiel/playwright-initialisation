 pnpm exec playwright test
    ``Runs the end-to-end tests.``

  pnpm exec playwright test --ui
   `` Starts the interactive UI mode.``

  pnpm exec playwright test --project=chromium
    ``Runs the tests only on Desktop Chrome.``

  pnpm exec playwright test example
    ``Runs the tests in a specific file.``

  pnpm exec playwright test --debug
  pnpm exec playwright codegen
    ``Auto generate tests with Codegen.``

``We suggest that you begin by typing:``

    pnpm exec playwright test

-----------------------------------------------------------

``ui mood:``
npx playwright test --ui
``codegn recorder``
npx playwright codegen demo.playwright.dev/todomvc