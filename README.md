# bash-event-logger

Lightweight Bash logging: `__event_control()` for messages, verbosity, tolerance, TTY stderr, syslog, and optional file logs.

**Version:** 1.0.0 · **License:** [MIT](LICENSE)

## Quick start

Source the library in your script:

```bash
source /path/to/bash-event-logger.sh

__event_control "Starting backup" 7
__event_control "Disk full" 2
```

## Documentation

Full reference (levels, `TOLERANCE`, `VERBOSITY`, `LOG_FILE`, logger setup): **[bash-event-logger.md](bash-event-logger.md)**
