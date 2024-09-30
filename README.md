# To autotest and back

## 🚀 Review

"To autotest and back" - This is my pet-project, in which I get acquainted with practices and approaches in auto-tests using TypeScript and the Playwright framework. The project is organized according to the Page Object Model principle, which helps improve testing skills.

## 🛠️ Functions

- Practicing skills with the Playwright framework.
- Writing tests in TypeScript.
- Organizing code using the Page Object Model pattern.
- Integration with ESLint to maintain code quality

## 📦 Install

To install and run my project, make sure you have Node.js and Git installed! Then follow these steps:

1. **Clone the repository:**

```bash
git clone [https://github.com/rybignat/TestPopierdolilo.git]
```

2. Installing dependencies:

```bash
npm install
npx playwright install --with-deps
```

3. **Check functionality:**

Run tests to make sure everything works:

```bash
npm run test
```

## 🚀 Use

The following commands are available in this project:

- `npm run tests`: Run all tests using Playwright.
- `npm run lint`: Code inspection using ESLint.
- `npm run lint fix`: Automatically fix errors found by ESLint.

##    Testing

The project uses Playwright to write and run tests. To run the tests, use the `npm run test` command.

Project structure:

```plaintext
.github/
└── workflows/
    └── playwright.yml

node_modules/

pageObjects/

test-results/

tests/
├──checkBox.scec.ts
└──textBox.spec.ts

Utills/
├──Components/
|   └──navigationBar.ts
├──cusomReporter.ts
├──functions.ts
└──types.ts

.eslintignore
.eslintrc.js
.gitignore
package-lock.json
package.json
playwright.config.ts
tsconfig.json
README.md
```

Main files and folders:

- **Utills/Components**: Contains application components.
- **pageObjects/**: Contains the described application pages.
- **pageObjects/main.page.js**: An example of a page organized according to the Page Object Model.
- **Utills/**: Utility functions, such as `functions.js` or `customReporter.js`.
- **tests/**: Contains *spec* files - that is, test scripts / suites.
- **.github/workflows/playwright.yml**: CI configuration to run tests automatically.