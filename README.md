# Dockerfile Linter

## How to use?

```yaml
- name: Docker lint check
  uses: jwr0/dockerfile-linter-action@master
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    DOCKERFILE: build/ansible-runner/Dockerfile
```
