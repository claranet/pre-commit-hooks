# Claranet's pre-commit hooks

This is a colleciton of [pre-commit](http://pre-commit.com) hooks made and used by Claranet


## Hooks

* [gitlab-ci-local](#gitlab-ci-local)

### [gitlab-ci-local](https://github.com/firecow/gitlab-ci-local)

```yaml
  - repo: https://github.com/claranet/pre-commit-hooks
    hooks:
      - id: gitlab-ci-local
        # optional custom config:
        args:
          - Lint  # Jobname's to execute
```
