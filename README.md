# SurrealDemo

SurrealDemo implements a demonstration of using deno to connect to a surreal database and perform CRUD operations.

## Setup

1. Install Deno

```bash
curl -fsSL https://deno.land/x/install/install.sh | sh
```

2. Install Surreal CLI

```bash
deno install -A surreal
```

3. Install Deno

```bash
deno install -A ts-node
```

## Usage

```bash
deno run --allow-env --allow-net src/index.ts
```

## Notes

- The database is created in the `src/db/db_operations.ts` file.
- The queries are created in the `src/db/schema_queries.ts` file.

## License

MIT License. Please see the [LICENSE file](LICENSE) for more details.
