# actions-audit-cage

A GitHub Action template built with Node.js 24.

## Features

- Built with Node.js 24
- TypeScript support
- ESLint and Prettier for code quality
- Jest for testing
- Automated CI/CD with GitHub Actions

## Development

### Prerequisites

- Node.js 24.x or later
- npm

### Setup

```bash
npm install
```

### Build

```bash
npm run build
```

### Test

```bash
npm test
```

### Lint

```bash
npm run lint
```

### Format

```bash
npm run format
```

## Usage

```yaml
- uses: loilo-inc/actions-audit-cage@v1
  with:
    who-to-greet: 'World'
```

## Inputs

- `who-to-greet` - **Required** Who to greet (default: 'World')

## Outputs

- `time` - The time we greeted you

## License

MIT