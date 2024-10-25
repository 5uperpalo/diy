# Documentation/Website

Documentation is created using github pages and mkdocs, [see](https://www.mkdocs.org/user-guide/deploying-your-docs/)

```bash
# to build locally
cd docs
pip install -r requirements.txt
mkdocs build
# to push to github pages
mkdocs gh-deploy
# if you want to run webserver locally
mkdocs serve
```