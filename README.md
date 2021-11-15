# Push Docker image
Pushes a Docker image.

## Inputs

### `image-name`

**Required** Name of the docker image.

### `gh-container-push-token`

**Required** Token for pushing to the private github registry.

## Example usage

```
uses: interdiscount/github-actions-push-docker-image@main
with:
    image-name: microspot-frontend
    gh-container-push-token: ${{ secrets.GH_CONTAINER_PUSH_TOKEN }}
```
