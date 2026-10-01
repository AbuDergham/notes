# Caddy quick reference

```caddyfile
example.duckdns.org {
  reverse_proxy localhost:3000
}
```

- Auto HTTPS via Lets Encrypt.
- `caddy reload` to apply changes.
