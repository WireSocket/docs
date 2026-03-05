# WireSocket Documentation

This repository contains the source code for the official WireSocket documentation, powered by [Mintlify](https://mintlify.com).

## Project Overview

WireSocket is a globally distributed Yjs sync infrastructure. This documentation is divided into three primary sections:

1.  **[Dashboard](/dashboard/overview)**: Management of tenants, apps, plans, and JWT authentication.
2.  **[Data Plane](/data-plane/dataplane)**: Real-time synchronization, document discovery, regional nodes, and editor setup.
3.  **[API Reference](/api-reference/introduction)**: Detailed endpoint documentation for Discovery, Usage, and WebSocket sync.

---

## Development

To preview changes locally, you'll need the [Mintlify CLI](https://www.npmjs.com/package/mint).

### Installation

```bash
npm i -g mint
```

### Local Preview

Run the following command at the root of the repository:

```bash
mint dev
```

Your local preview will be available at `http://localhost:3000`.

## Publishing

Changes pushed to the `main` branch are automatically deployed via the Mintlify GitHub App.

## Maintenance

- **`docs.json`**: Controls the sidebar navigation and global theme configuration.
- **`dashboard/`**: Documentation for Dashboard account and resource management.
- **`data-plane/`**: Documentation for the sync engine and regional architecture.
- **`api-reference/`**: Endpoint specifications.

### AI-assisted writing

To use Mintlify's documentation skills with your AI coding tool:

```bash
npx skills add https://mintlify.com/docs
```

---

_For technical support, contact the WireSocket team or visit [wiresocket.com](https://wiresocket.com)._
