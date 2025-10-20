# dashfetch
A tiny, resilient system summary utility for terminals. Configurable via `~/.config/dashfetch/config` or CLI flags.

## Flags
--align=labels|values, --no-logo, --no-color, --gap=N, --hide-services

## Config
Create `~/.config/dashfetch/config` and set:
ALIGN="values"
GAP=4
FACT_ORDER=( "Host" "OS" "Kernel" "Uptime" "CPU" "Memory" "Disk (/)" "Local IP" )
