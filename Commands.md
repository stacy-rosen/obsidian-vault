# Obsidian CLI Commands

Managed by Stacy (OpenClaw).

## Quick Reference

```bash
# Search notes (fuzzy)
obsidian-cli search "query"

# Search inside notes
obsidian-cli search-content "query"

# Create note
obsidian-cli create "Folder/Note" --content "# Title"

# Move/rename (updates wikilinks)
obsidian-cli move "old/path" "new/path"

# Delete
obsidian-cli delete "path/note"

# Set default vault
obsidian-cli set-default "VaultName"
```

## Vault Location
- Path: `~/Documents/Obsidian/Workspace`
- Config: `~/Library/Application Support/obsidian/obsidian.json`

## Open in Obsidian
Just open the app - it auto-loads the vault.
