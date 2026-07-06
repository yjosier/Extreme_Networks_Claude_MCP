# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project purpose

This repo documents/implements how to interconnect Extreme Networks' Fabric Engine architecture
with Claude through an MCP (Model Context Protocol) server, for network troubleshooting and
configuration purposes.

## Current state

The repository currently contains no source code — only `README.md` and `LICENSE` (GPLv3). The
`.gitignore` is a standard Python template, indicating the implementation will likely be Python-based,
but no project scaffolding (package structure, dependency manifest, tests, MCP server entrypoint) has
been created yet.

When implementing the MCP server in this repo, set up standard Python project tooling (dependency
manifest, entrypoint, tests) as part of that work, and update this file with the resulting build/lint/test
commands and architecture once real structure exists.
