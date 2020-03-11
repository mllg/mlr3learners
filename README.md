# mlr3learners
Meta package with most mlr3learners as submodules

Checkout:
```bash
git clone --recursive git@github.com:mllg/mlr3learners.git
```

Update all submodules:
```bash
git submodule update --remote --merge
```

Commit in all submodules:

```bash
git submodule foreach 'git commit -a -m "<msg>"'
```

Push in all submodules
```bash
git push --recurse-submodules=on-demand
```
