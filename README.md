# React TypeScript Testing-Library Interview

## Installation

Install Yarn:

```bash
https://yarnpkg.com/lang/en/docs/install/
```

Clone and install Yarn dependencies:

```bash
$ git clone git@github.com:taj-averylane/react-typescript-testinglibrary-interview.git
$ cd react-typescript-testinglibrary-interview
$ yarn
```

## Running Tests

See `package.json`

## Tasks

### Task 1

Complete the tests with `testing-library` inside `Home.test.tsx`, `About.test.tsx`, and `LayoutContainer.test.tsx`.

For `Home`, you should be able to show that you can verify Home rendered correctly

For `LayoutContainer`, you should be able to render the layout container, followed by navigating to the About page.

For `About`, you should be able to click the increment button and verify the count.

Run `yarn test` to test.

### Task 2

Inside of `reducers/sample.ts`, you will see `type SampleAction = unknown`.

Fix this type to be specific to the actions available. Please make the type as accurate as possible.

Run `yarn typecheck` to test.

### Submitting

Push your code to some git repository that is public. For example, you can use GitHub or Gitlab.
