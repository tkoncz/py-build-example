# py-build-example

## How to use this project locally

You'll need [uv](https://docs.astral.sh/uv/) as a project manager.

With `uv`, you can create a virtual environment simply with `uv venv`.
You can active this venv simply by running `source .venv/bin/activate`.

You can also use the `uv run` command to run pythoin scripts, for example:
```sh
uv run main.py
```

However, this project relies on a python library from a private repository.

`uv` relies on `git` to resolve authentication.
The recommended way to do this is using [GCM](https://docs.github.com/en/get-started/git-basics/caching-your-github-credentials-in-git#git-credential-manager).

For more details, please refer to the materials below:  

- https://docs.astral.sh/uv/configuration/authentication/  
- https://doc.rust-lang.org/cargo/appendix/git-authentication.html#https-authentication  
- https://git-scm.com/docs/git-credential-store  
- https://docs.github.com/en/get-started/git-basics/caching-your-github-credentials-in-git  
