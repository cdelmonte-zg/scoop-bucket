# scoop-bucket

Scoop bucket for tools by [Christian Del Monte](https://github.com/cdelmonte-zg).

## Available manifests

- **delta-explain** — Make Delta pruning visible: CLI for partition pruning and data skipping in Delta Lake. ([repo](https://github.com/cdelmonte-zg/delta-explain))

## Usage

```powershell
scoop bucket add cdelmonte-zg https://github.com/cdelmonte-zg/scoop-bucket
scoop install delta-explain
```

## Updates

Manifests are kept up to date automatically by the [`Excavator`](.github/workflows/excavator.yml) workflow, which runs `scoop checkver -u` against `bucket/` every three hours. When a new upstream release is detected, the manifest's `version`, `url`, and `hash` fields are refreshed and committed.

You can also trigger an update on demand from the Actions tab via `workflow_dispatch`.

## License

Each manifest's license matches the upstream tool. The bucket itself is MIT.
