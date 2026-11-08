# mcp-registry-daily

Daily changelogs and periodic snapshots of the [official Model Context Protocol registry](https://github.com/modelcontextprotocol/registry).

## Files (`data/`)

- **Delta files** (`YYYY-MM-DD.json`, most days): servers **added or updated** since the previous baseline, fetched via the registry's `updated_since` parameter. Fields: `counts.new`, `counts.updated`, `new[]` and `updated[]` (compact: name/title/version/prev_version).
- **Full snapshots** (weekly, Sundays): every name@version entry in the registry at fetch time. Baselines so far: `2026-11-04.json` (211,818 records) and `2026-11-08.json` (229,431 records, 59,541 distinct servers).
- `2026-11-03` has no file (the registry API has no historical endpoint; the gap is documented, not backfilled).
- `2026-11-02.json` was the initial seed snapshot (16,880 repository-level records from MCPNav's early sync).

## Source & disclaimer

Data comes from the public upstream registry above. This project is unofficial and not affiliated with the Model Context Protocol team. For a browsable directory of MCP servers with install commands, see [MCPNav](https://mcpnav.net).
