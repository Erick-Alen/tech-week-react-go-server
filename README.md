```bash
docker compose up
```

- Database migrator
- Goose
- Tern **(which will be used here)**
Using tern to generate migrations

```bash
go install github.com/jackc/tern/v2@latest
```

`/internal folder`

everycode into internal folder is internal to its package, to keep its binary code separaed from the rest of the project.

`/cmd (command)`
