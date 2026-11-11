# Rise

Rise is an experimental Rust UI toolkit for building desktop applications with a DOM-like structure, CSS-like styling, and a custom render pipeline. It is best described as a toy toolkit and a learning project, but it is usable for small GUI experiments and prototypes.

## Highlights

- Rust-first desktop UI toolkit
- DOM-inspired component tree model
- CSS/JSS-inspired styling
- Layout powered by Yoga
- Windowing and event handling via glutin
- Rendering pipeline using WebRender-style primitives
- Example app included for quick experimentation

## Project status

This repository is an early-stage experimental project. The codebase is compact and focused on learning and experimentation rather than production-grade application development. It is a good reference for understanding how a simple Rust GUI toolkit can be structured.

## Architecture

The crate is organized around a few core modules:

- `src/app.rs` — application lifecycle, window configuration, event loop
- `src/render.rs` — render context and drawing logic
- `src/ui.rs` — UI composition and update flow
- `src/window.rs` — window abstraction
- `src/resources/` — resource handling
- `examples/simple.rs` — a minimal example app

## Getting started

### Prerequisites

- Rust toolchain (stable or nightly depending on your environment)
- Cargo
- Platform support consistent with the dependencies used by `glutin` and the rendering stack

### Build

```bash
cargo build
