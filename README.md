# true-neutral-cookiecutter

A minimalist cookiecutter for research and data science projects

Run via `cookiecutter gh:Jordan-Morris20/pnp-data-science-cookiecutter`

# Folder structure

```
repo_name/
├── 01_development/         <- This is where you do your work
│   ├── data/               <- These are the paths to data assets
│   │   └── config.ini
│   ├── scripts/            <- These are custom modules in development
│   │   └── __init__.py     <- This is the file that makes the directory a package
│   └── tests/              <- These are the tests for the custom modules
├── 02_deployment/          <- This is where you deploy your work
│   ├── apps/               <- These are the deployed driver .py files
│   ├── scripts/            <- These are the deployed modules
│   │   └── __init__.py
│   └── data/
│       └── config.ini
├── docs/                   <- This is where informative markdown and notebook files are
├── results/                <- Where you put results, including checkpoints, hdf5 files, pickle files, as well as figures and tables.
└── setup.py                <- This enables you to install the modules created for this project
```

### To recreate this structure

[online tool](https://tree.nathanfriend.io/?s=(%27options!(%27fancy!true~fullPath!false~trailingSlash!true~rootDot!false)~6(%276%27repo_name-01_develop843test502_deploy8apps34-doc5result5setup9%27)~version!%271%27)*%20%20-%5Cn*37script5**__init__94data7*config.ini5s%2F-6source!7-*8ment79.py7%019876543-*)

```
repo_name
  01_development
    data
      config.ini
    scripts/
      __init__.py
    tests/
  02_deployment
    apps
    scripts/
      __init__.py
    data
      config.ini
  docs/
  results/
  setup.py
```