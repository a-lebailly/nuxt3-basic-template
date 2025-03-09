# 🚀 Nuxt 3 Starter Template

This is a **basic** Nuxt 3 starter template that includes essential developer tools and configurations. It is designed to be minimal yet functional, providing a solid foundation for further customization and development.

## ✨ Features

- **Nuxt 3**: Modern Vue framework with powerful capabilities.
- **Nuxt UI Module**: Provides UI components for faster development.
- **ESLint (via Nuxt ESLint Module)**: Ensures code quality and consistency.
- **Husky**: Enables Git hooks for better workflow automation.
- **Lint-staged**: Runs linters on staged files before committing.
- **Commitlint**: Enforces conventional commit messages.
- **Better Commits**: Enhances commit message writing experience.

## 📦 Installation

Clone the repository:

```sh
git clone https://github.com/a-lebailly/nuxt3-basic-template
cd nuxt3-basic-template
```

Make sure you have **pnpm** installed (or use another package manager) before running:

```sh
pnpm install
```

## 🔧 Available Scripts

- `pnpm dev` - Start the development server
- `pnpm build` - Build the project for production
- `pnpm generate` - Generate static site
- `pnpm preview` - Preview the built application
- `pnpm lint` - Run ESLint
- `pnpm lint:fix` - Fix linting issues
- `pnpm commitlint` - Check commit messages against conventional rules
- `pnpm lint-staged` - Run lint-staged manually on staged files without committing
- `pnpm better-commits` - TUI to create commits
- `pnpm prepare` - Setup Husky Git hooks
- `pnpm postinstall` - Run Nuxt prepare after installation

## 🔗 Git Hooks

- **Pre-commit hook**: Runs ESLint on staged files via lint-staged.
- **Commit message hook**: Enforces commit message style via Commitlint.

## 🎨 ESLint Configuration

Basic ESLint rules are defined, with stylistic rules enabled. The `no-console` rule is enforced.

## 📝 Commit Convention

This project follows conventional commits with predefined types and scopes:

### Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `refactor`: Code restructuring without functionality changes
- `perf`: Performance improvements
- `test`: Adding or modifying tests
- `build`: Changes to the build system
- `ci`: Changes to CI/CD configuration
- `chore`: Maintenance tasks

### Scopes

- `app`
- `shared`
- `server`
- `tools`

## ⚠️ Notes

This template is intentionally kept **basic**. It provides just the minimum configurations to start development efficiently with a clean and structured setup. You can extend it as needed for your project.

## 📜 License

[MIT License](./LICENSE)

