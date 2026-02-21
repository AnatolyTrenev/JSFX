Installation (via ReaPack)

1. Open REAPER
2. Extensions → ReaPack → Import repositories
3. Paste this URL:

https://raw.githubusercontent.com/AnatolyTrenev/JSFX/master/index.xml

4. Synchronize packages
5. Install **Creamy Wide**

The plugin will appear in:
Effects / Trenev /

## Included plugins

- Creamy Wide
- WILDER

## Auto version/index update flow

1. Update the JSFX header fields in the changed plugin:
   - `version: x.y.z`
   - `changelog: ...`
2. Push to `master`.
3. GitHub Actions runs `reapack-index --commit` and updates `index.xml` automatically.
4. Updated `index.xml` is pushed back by workflow.

## License
GPL-3.0-only
