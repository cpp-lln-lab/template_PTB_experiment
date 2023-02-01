[![](https://img.shields.io/badge/Octave-CI-blue?logo=Octave&logoColor=white)](https://github.com/cpp-lln-lab/template_PTB_experiment/actions)
![](https://github.com/Remi-gau/template_matlab_analysis/workflows/CI/badge.svg)
[![codecov](https://codecov.io/gh/Remi-gau/template_matlab_analysis/branch/master/graph/badge.svg)](https://codecov.io/gh/cpp-lln-lab/template_PTB_experiment)

# Template repository for psycthoolbox experiment

## Content

```bash
├── .git
├── .github  # where you put anything github related
│   └── workflows # where you define your github actions
│       └── moxunit.yml # a yaml file that defines a github action
├── lib # external libraries (mathworks website or other github repositories)
│   └── README.md
├── src # where you put your code
│   ├── README.md
│   └── miss_hit.cfg
├── tests # where you put your unit tests
|   ├── README.md
|   └── miss_hit.cfg
├── LICENSE
├── README.md
├── requirements.txt # python packages used: to install `pip install -r requirements.txt`
├── miss_hit.cfg # configuration file for the matlab miss hit linter
└── initEnv.m # a .m file to set up your project (adds the right folder to the path)
```

## How to install and use this template

By using the
[template PTB experiment repository](https://github.com/cpp-lln-lab/template_PTB_experiment):
you can create a new repository on your github account with all the basic
folders, files and submodules already set up. You only have to then clone the
repository and you are good to go.

## How to install and run

Install

```
git clone --recurse-submodules https://github.com/your_github_account/the_name_of_your_new_experiment.git
```

Set parameters in `setParameters.m`

Run

```
mainScript
```
