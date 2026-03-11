# @demo/shared-utils

Shared utilities, validators, and React hooks consumed by downstream applications via the **Component Sync** GitHub App.

## Modules

| Category | Export | Description |
|----------|--------|-------------|
| Formatters | `formatCurrency`, `parseCurrency` | Locale-aware currency formatting |
| Formatters | `formatDate`, `timeAgo` | Date formatting and relative time |
| Formatters | `formatCompact`, `formatPercentage` | Number abbreviation and percentages |
| Validators | `isEmail`, `isUrl`, `minLength`, `maxLength` | String validation helpers |
| Validators | `validateField`, `required` | Composable form validation rules |
| Hooks | `useDebounce` | Debounced value hook |
| Hooks | `useLocalStorage` | Persistent localStorage hook |

## Usage

These utilities are automatically synced into consuming repos (e.g. `demo-repo-c`) by the [Component Sync App](https://github.com/GitHubDemoPlayground/GitHubApp).
Pushing to `main` triggers an automatic sync PR in downstream repos.
