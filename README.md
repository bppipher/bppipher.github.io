# [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv)
https://gohugo.io/

https://hugoblox.com/

# Netflify Status - Do not use due to pricing issues
[![Netlify Status](https://api.netlify.com/api/v1/badges/c0ae9fd0-b72f-4805-9f23-3b21058ba5d7/deploy-status)](https://app.netlify.com/sites/bpipher/deploys)

# Set up
Steps are more specifically tailored to windows, and is likely easier on linux

Clone theme repository (theme-academic-cv from hugoblox).  Github Desktop can even be used.

Install Git, Go and Hugo (using winget).  Can be ran from VS Code Powershell Terminal (not Windows Powershell).

Use 'hugo' to set up and 'hugo server -D' to serve locally with draft posts.

Pull ./.github/workflows/import-notebooks.yml from another repo and create ./notebooks/ directory. Allows ipynb conversions.

Needs a .gitignore to be created.

/Public/ folder is generated site