# aDDM-Toolbox

This toolbox fits the attentional drift diffusion model described in [Krajbich, Armel and Rangel (2010)](https://www.nature.com/articles/nn.2635) using the algorithm described in [Tavares, Perona, Rangel (2017)](https://www.frontiersin.org/articles/10.3389/fnins.2017.00468/full) in various programming languages. 

The project is developed and maintained by the [Rangel Neuroeconomics Lab](https://www.rnl.caltech.edu/index.html) at [Caltech](https://www.caltech.edu/).

## Documentation

The toolboxes are offered in multiple languages (Julia, C++ and CUDA). You can find usage examples and tutorials for the toolbox version you're interested in at https://addm-toolbox.github.io/.

## Contribution guidelines

To contribute to any of the toolboxes please go to the repo for the toolbox you'd like to make a contribution and fork it. Below is an example of how to contribute to the `ADDM.jl` toolbox.

**On Github**

1. Fork `aDDM-Toolbox/ADDM.jl`

<img width="1378" alt="Screenshot 2023-09-11 at 6 05 36 PM" src="https://github.com/aDDM-Toolbox/.github/assets/8344019/66292bf5-3910-4451-9b0a-73b0964e4e8b">

**On your machine**

2. Clone your fork to local disk

- HTTPS
```
git clone https://github.com/<YOUR_USERNAME>/ADDM.jl.git
```

- SSH  
```
git clone git@github.com:<YOUR_USERNAME>/ADDM.jl.git
```

3. Navigate into your cloned repo

```
cd ADDM.jl
```

4. Add upstream to your cloned repo. This way you can pull changes from the organization and send PRs back.

- HTTPS
```
git remote add upstream https://github.com/aDDM-Toolbox/ADDM.jl.git
```

- SSH
```
git remote add upstream git@github.com:aDDM-Toolbox/ADDM.jl.git
```

Check your remotes are set up correctly

```
git remote -v
```

should return

- HTTP
```
origin  https://github.com/<YOUR_USERNAME>/ADDM.jl.git (fetch)
origin  https://github.com/<YOUR_USERNAME>/ADDM.jl.git (push)
upstream        https://github.com/aDDM-Toolbox/ADDM.jl.git (fetch)
upstream        https://github.com/aDDM-Toolbox/ADDM.jl.git (push)
```

- SSH
```
origin  git@github.com:<YOUR_USERNAME>/ADDM.jl.git (fetch)
origin  git@github.com:<YOUR_USERNAME>/ADDM.jl.git (push)
upstream        git@github.com:aDDM-Toolbox/ADDM.jl.git (fetch)
upstream        git@github.com:aDDM-Toolbox/ADDM.jl.git (push)
```


5. Create a branch to add your contribution. When possible, make your branch name descriptive of the functionality you're planning to add to it.

```  
git checkout -b <YOUR_BRANCH_NAME>
```

6. Add and commit your changes on your new branch

```
git add <MODIFIED_FILE_NAME>
git commit -m "<YOUR_COMMIT_MESSAGE>"
```

7. Make sure your version of the repo is synced with the upstream

```
git fetch upstream
git rebase upstream/main
```

8. Push your changes to *your* remote repo

```
git push -u origin <YOUR_BRANCH_NAME>
```

**On Github**

9. Go to your repo on Github and send a PR to the organization
