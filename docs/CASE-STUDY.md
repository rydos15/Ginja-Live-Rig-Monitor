# From A Real Rig Problem To A Working Suite

<p align="center"><img src="assets/studio-composite.png" alt="Creator's studio with illustrative screen replacements" width="100%"></p>

## The Problem

A live rig spans controllers, audio devices, production software, streaming software and the computer running them. Each exposes different information. Switching between those interfaces makes it harder to understand a symptom while performing.

## The Solution

Ginja places focused observations in one dashboard and detachable popouts. An explicit MIDI control-change trigger can also run an ordered sequence of supported MIDI and OBS actions. The creator reports using the suite in their own studio and live-performance workflow.

## The Work Behind The Product

| Area | Concrete Work | Evidence |
| --- | --- | --- |
| Product Thinking | Turned a fragmented rig workflow into focused monitoring and control tasks | Dashboard, workspace modes and popouts |
| Hardware Workflows | Expanded the MC6 Pro with a custom 3D-printed setup using two Omniports and sixteen additional physical buttons, with resistor-ladder detection and programmable Morningstar assignments | Custom hardware section in the manual |
| Application Integration | Combined MIDI messages, OBS state, process metrics and optional providers | Feature captures and configuration tutorials |
| Interaction Design | Added detachable views, sizing, appearance settings and saved profiles | Popout and settings chapters |
| Troubleshooting | Exposed events, process readings and local session reports | Diagnostic workflow and report instructions |
| Product Delivery | Documented setup, boundaries, support, privacy and planned work | This showcase repository |

## The Design Decisions

**Keep monitoring and control distinct.** A detected process or MIDI message is an observation. A routing rule explicitly names its trigger and outputs. This prevents the presentation from implying that an available reading proves an entire workflow is healthy.

**Put feedback beside the task.** Popouts let the user keep relevant readings near Ableton or OBS rather than repeatedly returning to a large dashboard.

**Make behavior reproducible.** Device, channel, CC and value conditions define a sequence. Events and session reports help document what happened during a test.

**Extend through explicit adapters.** The routing pattern can support other compatible MIDI workflows. Push 3 extensions, deeper Ableton workflows, Synesthesia, Stream Deck and controller input remain roadmap items.

## Results And Evidence

The portfolio demonstrates an implemented application, documented workflows and creator-reported practical use. It does not claim independently measured reliability, commercial deployments, customer counts or benchmark improvements. Captures contain recorded/example values; studio screen replacements and illustrative OBS activity are identified.

## A Short Explanation

“I built Ginja to solve a problem in my own rig: important status and control functions were spread across several devices and applications. It combines a dashboard, detachable monitors, diagnostics and explicit MIDI-triggered action sequences. The project connects hardware workflow design with software integration, and I’m developing it toward broader, clearly defined integrations.”

Describe personal ownership accurately, including any AI-assisted development or design when asked. Explain the decisions, source behavior and tests you can substantiate.

[Visual Manual](Ginja_Visual_User_Manual.pdf) · [Architecture](ARCHITECTURE.md) · [Validation](VALIDATION.md)
