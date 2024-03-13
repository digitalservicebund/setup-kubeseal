# Setup Kubeseal

## How to use

Add this step to your pipeline:

```yaml
      - name: Install kubeseal
        uses: digitalservicebund/setup-kubeseal@LATEST_HASH
```

Optional input: `version` (default: 0.18.0)

## Updating this action

After merging a dependabot PR or pushing changes, you need to [cut a new release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
