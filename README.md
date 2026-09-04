# claude-plugins

The catalog of my Claude Code plugins. Each plugin lives in its own repo; this
one only lists them, so a single marketplace name covers all of them and adding
the next plugin does not mean adding another marketplace.

```bash
claude plugin marketplace add tckerr/claude-plugins
claude plugin install workstreams@tckerr
```

## Plugins

- **workstreams** ([herdr-orchestration](https://github.com/tckerr/herdr-orchestration)) —
  run several Claude sessions on one repo at once, each in its own git worktree.
  An orchestrator provisions and tears down streams; an implementer works in each.

## Adding a plugin

Add an entry to `plugins` in `.claude-plugin/marketplace.json` pointing at its
repo. The marketplace name stays `tckerr`, so everything installs as
`<plugin>@tckerr`.
