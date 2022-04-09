# Mastodon ARM64 Docker Image

__[NOTE: The official repositories now support arm64 images, so their use is recommended.](https://hub.docker.com/r/tootsuite/mastodon/tags)__

Generating [Mastodon](https://github.com/mastodon/mastodon) ARM64 Docker Image fot Github Actions.

## GitHub Container Registry Public URL

[ghcr.io/potproject/mastodon-arm64](https://ghcr.io/potproject/mastodon-arm64)

### Docker Pull Command

```
# Using v3.4.1
docker pull ghcr.io/potproject/mastodon-arm64:v3.4.1
```

## Development

### Setting Secrets
| Parameter | Description | Permissions |
| -- | -- | -- |
| `GHCR_TOKEN` | [Personal access tokens](https://github.com/settings/tokens) | `repo`, `delete:packages`, `write:packages` |

## Licence
AGPL 3.0
