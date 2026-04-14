# Agent Instructions

When creating a new Docker stack in this project:

1. Create a `compose.yaml` file for the service.
2. Create a `README.md` file in the same folder.
3. In `README.md`, document environment variables in two sections:
   - **Required environment variables**
   - **Optional environment variables** (include defaults when available)
4. Any persistent volume path must use this base pattern:
   - `/mnt/user/appdata/<stack-name>`

This is the standard format to keep each stack easy to use and consistent.
