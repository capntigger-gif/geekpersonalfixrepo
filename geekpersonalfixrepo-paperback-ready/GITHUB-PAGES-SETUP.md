# GitHub Pages setup

1. Push this repository to `https://github.com/capntigger-gif/geekpersonalfixrepo`.
2. On GitHub, open **Settings → Actions → General** and ensure Actions are allowed.
3. Push to `main` (the workflow will build automatically).
4. After the workflow finishes, open **Settings → Pages**.
5. Set **Source** to **Deploy from a branch**.
6. Set the branch to **gh-pages** and folder to **/(root)**.
7. The Paperback repository URL is:

   https://capntigger-gif.github.io/geekpersonalfixrepo/0.9/stable/

The first deployment creates `versioning.json` and the compiled bundles under `0.9/stable/`.
