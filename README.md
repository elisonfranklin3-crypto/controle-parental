git init
echo "<!doctype html><html><body><h1>Olá</h1></body></html>" > index.html
git add index.html
git commit -m "site inicial"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_REPO.git
git push -u origin main
