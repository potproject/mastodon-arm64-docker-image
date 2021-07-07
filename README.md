# mastodon-arm64-docker-image

Generating [Mastodon](https://github.com/tootsuite/mastodon) ARM64 Docker Image fot Github Actions.

## Setting Secrets
| Parameter | Description | Permissions |
| -- | -- | -- |
| `GHCR_TOKEN` | [Personal access tokens](https://github.com/settings/tokens) | `repo`, `delete:packages`, `write:packages` |

## GitHub Container Registry Public URL

[ghcr.io/potproject/mastodon-arm64](ghcr.io/potproject/mastodon-arm64)

### Docker Pull Command

```
# Using v3.4.1
docker pull ghcr.io/potproject/mastodon-arm64:v3.4.1
```

## Licence
AGPL 3.0
