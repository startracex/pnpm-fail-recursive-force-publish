## force publish pkg-a

```sh
cd pkg-a
pnpm publish -f
pnpm publish -f
```

## force publish pkg-b

```sh
cd pkg-b
pnpm publish -f
pnpm publish -f
```

## recursive force publish

```sh
# npm error You cannot publish over the previously published versions: 1.0.0.
pnpm -r publish -f 
```