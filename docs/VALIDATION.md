# Validation And Known Limits

## Documentation Review

The visual guide was compared with the available application modules and actual interface/tutorial captures. Its PDF pages were rendered for layout inspection. Local documentation links and PDF page boundaries were checked. These checks validate documentation packaging; they do not establish runtime reliability or installer compatibility.

## Runtime Acceptance Checklist

Record the application/build version, Windows version, drivers, devices and relevant application versions with every test. The following checklist is a test plan, not a completed test report.

| Workflow | Acceptance Evidence |
| --- | --- |
| First Launch | Artwork and dashboard load on a second PC without Python installed |
| MIDI Input | Known controller channel, CC and value match the monitor |
| Routing | One known trigger produces the intended ordered outputs; repeats behave as configured |
| Notes | NOTE ON is paired with NOTE OFF and failure recovery is checked |
| OBS | Connection, scene state and supported recording actions match OBS |
| Popouts | Resize, arrange, close and restore behave predictably |
| Profiles | Saved appearance and layout restore without silently changing routing |
| Diagnostics | Events and reports capture a reproducible test and redact safely |
| Audio Discovery | Device information is available in the packaged runtime |
| Gaming | Optional provider captures valid frames; missing/stale readings remain unavailable |
| Disconnects | Device/app disconnection and reconnection do not leave misleading state |

## Known Product Boundaries

- Audio device discovery is not audio mixing or signal-path verification.
- Ableton process monitoring is not complete session or plug-in control.
- Current routing is CC-triggered; OBS start/stop streaming is not a supported routing action.
- FPS capture needs an external provider and compatible game/driver behavior.
- Discord profile connection does not expose private notification feeds or Online/Invisible status.
- Future integrations are not delivered merely because they appear in roadmap imagery.
- The new private build has not been built and tested here on a second PC.

Add measured results only after running the tests. Publish the tested environment and limitations alongside any future downloadable build.

[Report A Problem](../SUPPORT.md) · [Release Checklist](RELEASE-CHECKLIST.md)
