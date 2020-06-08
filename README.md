# Dockerfile Linter

## How to use?

```yaml
- name: Docker lint check
  uses: uditgaurav/docker-linter@v1
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    DOCKERFILE: build/ansible-runner/Dockerfile
```
