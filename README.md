# Awesome PDM [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
> A curated list of awesome PDM plugins and resources

## Plugins

- [pdm-download](https://github.com/pdm-project/pdm-download) - A PDM plugin to download all packages in a lockfile for offline use
- [pdm-packer](https://github.com/frostming/pdm-packer) - A PDM plugin that packs your packages into a zipapp
- [pdm-version](https://github.com/abersheeran/pdm-version) - Make `pdm version` like `poetry version`
- [pdm-bump](https://github.com/carstencodes/pdm-bump) - A PDM plugin that behaves like [bump2version](https://github.com/c4urself/bump2version) relying on PEP440 compliant versions
- [pdm-shell](https://github.com/abersheeran/pdm-shell) - Use `pdm shell` set PATH and PYTHONPATH in the current shell
- [pdm-django](https://github.com/neutron-sync/pdm-django/) - `pdm manage` and `pdm django-admin` shortcuts for Django commands
- [pdm-autoexport](https://github.com/frostming/pdm-autoexport) - A PDM plugin to sync the exported files with the project file
- [pdm-vscode](https://github.com/frostming/pdm-vscode) - A PDM plugin that autogenerates workspace vscode settings for you
- [pdm-multirun](https://github.com/pawamoy/pdm-multirun) - A PDM plugin to run a command on multiple Python versions
- [pdm-conda](https://github.com/macro128/pdm-conda) - A PDM plugin to install project dependencies with [Conda](https://docs.conda.io/projects/conda/en/latest/index.html)
- [pdm-plugin-torch](https://github.com/EmbarkStudios/pdm-plugin-torch) - A utility tool for selecting torch backend and version
- [pdm-dotenv](https://github.com/znd4/pdm-dotenv) - A PDM plugin that loads `.env` files
- [sync-pre-commit-fork](https://github.com/GabDug/sync-pre-commit-lock) - A PDM plugin to ease your life with `pre-commit` (automatic install, sync)
- [pdm-pip-index-url](https://github.com/theredfoxlee/pdm-pip-index-url) - A PDM plugin that automatically converts `PIP_*INDEX_URL` to `PDM_PYPI_*` envs
- [pdm-build-locked](https://github.com/sigma67/pdm-build-locked) - A PDM plugin to add locked packages as additional optional dependency groups to the distribution metadata on build
- [pdm-readiness](https://github.com/andriykohut/pdm-readiness) - A PDM plugin to check if your project dependencies support specified Python version
- [pdm-dockerize](https://github.com/noirbizarre/pdm-dockerize) - A PDM plugin to help generating docker images from PDM projects

## Eco-system

- [copier-pdm](https://github.com/pdm-project/copier-pdm) - A Copier template for PDM projects
- [copier-pdm](https://github.com/pawamoy/copier-pdm) - Another Copier template for Python projects managed by PDM
- [setup-pdm](https://github.com/pdm-project/setup-pdm) - A GitHub Action that installs pdm properly for all Python versions
- [pdm-ci](https://github.com/Seven45/pdm-ci) - A docker image for usage in multistage builds or gitlab-ci
- [tox-pdm](https://github.com/pdm-project/tox-pdm) - A plugin for tox that utilizes PDM as the package manager and installer
- [VSCode PDM Task Provider](https://marketplace.visualstudio.com/items?itemName=knowsuchagency.pdm-task-provider) - VSCode Task provider for PDM
- [Mina](https://github.com/GreyElaina/Mina) - a monorepo-like implementation, which act as a hacking agent of `pdm-pep517`
- [sync_with_pdm](https://github.com/floatingpurr/sync_with_pdm) - a `pre-commit` hook to keep PDM-managed packages and pre-commit hooks in sync
- [update-deps-action](https://github.com/marketplace/actions/pdm-update-dependencies) - A GitHub Action to update the pdm lockfile

## Articles

- [PDM: A smarter way to manage Python packages](https://www.infoworld.com/article/3654196/pdm-a-smarter-way-to-manage-python-packages.html) - Info World - 2022/03
- [A Review: Pipenv vs. Poetry vs. PDM](https://frostming.com/2021/03-26/pm-review-2021/) - Frost Ming - 2021/03
- [You don't really need a virtualenv](https://frostming.com/2021/01-22/introducing-pdm/) - Frost Ming - 2021/01
- [PDM - 一款新的 Python 包管理器](https://frostming.com/2020/02-28/pdm-introduction/) (Chinese) - Frost Ming - 2020/02

## Videos

- [How To Use PDM...](https://youtu.be/qOIWNSTYfcc) - Ian Wootten - 2022/03

## Gists

- [Automatic dependency updates with PDM](https://gist.github.com/carstencodes/bdf6c1664f49f387b6994a02965e787c) - Carsten Igel (@carstencodes) - 2022/02

## Slides & Talks

- [基于 PEP 582 的包管理器](https://slides.fming.dev/pep582/) (Chinese) - Frost Ming - 2020/05
