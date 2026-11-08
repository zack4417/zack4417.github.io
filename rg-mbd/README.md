# Project website: Recovery-Guided Model-Based Diffusion

Academic project page using the same Bulma / Nerfies-style layout as
[OACP](https://zack4417.github.io/oacp-website/).

**Live page:** https://zack4417.github.io/rg-mbd/

Published from this folder into
[`zack4417/zack4417.github.io`](https://github.com/zack4417/zack4417.github.io)
under `/rg-mbd/`.

## Preview locally

```bash
cd website
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Update the live site

```bash
rsync -a --delete ./ /tmp/zack4417.github.io/rg-mbd/
# then commit + push master on zack4417.github.io
```
