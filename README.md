# mcp-registry-daily

Daily snapshots of the [official Model Context Protocol registry](https://github.com/modelcontextprotocol/registry).

## Files

- `data/YYYY-MM-DD.json` — one snapshot per day: `total_entries`, source, upstream link and a `generated_at` timestamp. Entries are repository-level records (`owner/repo` keys) synced by MCPNav.
- `data/2026-11-02.json` is the initial snapshot (first synced on 2026-11-02, committed at repo root and moved into `data/` the next day). Daily diffs (new/changed servers) start from the second snapshot.

## Source & disclaimer

Data comes from the public upstream registry above. This project is unofficial and not affiliated with the Model Context Protocol team. For a browsable directory of MCP servers with install commands, see [MCPNav](https://mcpnav.net).
