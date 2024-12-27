git init
git add .
git commit -m "Desplegando mi portafolio"
gh repo create Portafolio-Cloudfare --private --source=.
git branch -m master main
git push -u origin main


pnpm astro build

