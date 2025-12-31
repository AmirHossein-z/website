# My Website

## run the dev server

```bash
hugo server -D
```

## build the project

```bash
hugo
npx -y pagefind --site public
cd public;
liara deploy --platform=static
```

## liara ref for deployment
[link](https://docs.liara.ir/paas/static/related-apps/hugo/)

## to get updated project

```bash
git pull
git submodule update --init --recursive
```

## Acknowledgements

[typo](https://github.com/tomfran/typo)

[Hugo](https://gohugo.io/)
