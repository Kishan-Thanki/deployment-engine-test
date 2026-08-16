# Test Application

This is a minimal application artifact used to test the generic deployment engine.

## Application

- Name: `test-app`
- Purpose: Deployment engine functional testing
- Runtime: None
- Dependencies: None

## Verification

The deployed version is recorded in `version.txt`.

The deployment engine test verifies that the expected artifact is:

1. Downloaded successfully.
2. SHA-256 verified.
3. Validated as a safe `.tar.gz` archive.
4. Extracted into a release directory.
5. Activated through the `current` symlink.
6. Available for rollback.
