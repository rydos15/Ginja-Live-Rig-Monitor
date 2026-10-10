# Data Handling

This describes the reviewed application, not a certification of a future binary.

Ginja reads local system/process metrics and device information. Preferences, routing rules, the event timeline and session reports are stored locally. Logs/reports can reveal app/device names, errors and paths. Review them before sharing. No remote analytics service was identified in the reviewed application modules; verify the final build before promising identical behavior.

OBS connects to the configured WebSocket endpoint. Its password is held in memory for the current run in the reviewed code. MIDI rules can send messages to selected output ports. Optional network ping contacts the chosen host. Hardware links open configured third-party applications or websites.

Optional Discord profile connection uses local RPC and can fetch a public avatar from Discord's CDN. Public Rich Presence is a separate setting. Review persisted/migrated settings after updates. Discord applies its own terms and policies.

The documentation repository does not operate a Ginja account backend. GitHub processes visits, profiles and issue submissions under its own policies.
