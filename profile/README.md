# aDDM-Toolbox

This organization provides toolboxes to fit the attentional drift diffusion model described in [Krajbich, Carmel and Rangel (2010)](https://www.nature.com/articles/nn.2635) using the algorithm described in [Tavares, Perona, Rangel (2017)](https://www.frontiersin.org/articles/10.3389/fnins.2017.00468/full)in various programming languages.

The project is developed and maintained by the [Rangel Neuroeconomics](https://www.rnl.caltech.edu/index.html) Lab at [Caltech](https://www.caltech.edu/).

## Contribution guidelines

To contribute to any of the toolboxes please go to the repo for the toolbox you'd like to make a contribution and fork it. Below is an example of how to contribute to `aDDM-Julia` toolbox.

**On Github**

1. Fork `aDDM-Toolbox/addm-Julia`

<img width="1657" alt="Screenshot 2023-09-11 at 3 44 57 PM" src="https://github.com/aDDM-Toolbox/.github/assets/8344019/5e56f0ef-d12b-40e6-9f00-4b1535c050a3">

**On your machine**

2. Clone your fork to local disk

- HTTPS
```
git clone https://github.com/<YOUR_USERNAME>/aDDM-Julia.git
```

- SSH  
```
git clone git@github.com:<YOUR_USERNAME>/aDDM-Julia.git
```

3. Navigate into your cloned repo

```
cd aDDM-Julia
```

4. Add upstream to your cloned repo. This way you can pull changes from the organization and send PRs back.

- HTTPS
```
git remote add upstream https://github.com/aDDM-Toolbox/aDDM-Julia.git
```

- SSH
```
git remote add upstream git+ssh://git@github.com:aDDM-Toolbox/aDDM-Julia.git
```

Check your remotes are set up correctly

```
git remote -v
```

should return

- HTTP
```
origin  https://github.com/<YOUR_USERNAME>/aDDM-Julia.git (fetch)
origin  https://github.com/<YOUR_USERNAME>/aDDM-Julia.git (push)
upstream        https://github.com/aDDM-Toolbox/aDDM-Julia.git (fetch)
upstream        https://github.com/aDDM-Toolbox/aDDM-Julia.git (push)
```

- SSH
```
origin  git+ssh://git@github.com:<YOUR_USERNAME>/aDDM-Julia.git (fetch)
origin  git+ssh://git@github.com:<YOUR_USERNAME>/aDDM-Julia.git (push)
upstream        git+ssh://git@github.com:aDDM-Toolbox/aDDM-Julia.git (fetch)
upstream        git+ssh://git@github.com:aDDM-Toolbox/aDDM-Julia.git (push)
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
