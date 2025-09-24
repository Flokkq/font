## font

- add private font repo as a git submodule

```bash
git submodule add https://github.com/schnis/repo.git
```

- commit and push

## workflow

- mirror behaviour of [template workflow](.github/workflows/build.yaml)
- add `FONT_REPO_PAT` as a secret to the workflow runner
 - needs `repo:read` permissions on the private lfs repo

![PAT permissions](assets/pat.png)
