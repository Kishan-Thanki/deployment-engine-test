# Deployment Engine Test

A disposable test application used to verify the generic deployment engine.

## Purpose

This repository provides versioned application artifacts for testing:

- Artifact download
- SHA-256 verification
- Archive validation
- Release creation
- Atomic activation
- Current release tracking
- Previous release tracking
- Rollback
- Release retention and pruning
- Deployment locking
- Failure handling

## Application

The application itself is intentionally minimal and has no runtime dependencies.

The deployable payload is the `app/` directory.

## Releases

Each GitHub Release provides a versioned `.tar.gz` deployment artifact together with its SHA-256 checksum.

Example:

```text
test-app-1.0.0.tar.gz
test-app-1.0.0.tar.gz.sha256
