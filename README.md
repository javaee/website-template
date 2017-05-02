# website-template

The gh-pages branch of this repo contains all the initial assets for a simple website.

* Clone your project repo

**Make sure the master branch of your project contains both CONTRIBUTING.md** (see [here](https://github.com/javaee/website-template/blob/gh-pages/CONTRIBUTING.md)) and **LICENSE.md** (see [here](https://github.com/javaee/website-template/blob/gh-pages/LICENSE.md) for the standard GF GPVv2/CDDL/CPE).

* Create an orphan branch that will host your site

```bash
git checkout --orphan gh-pages
```

* You might want to delete unnecessary files (but do **keep CONTRIBUTING.MD and LICENSE.md in both branches!**)

```bash
git rm --cached -r stuff_to_delete
```

* Add and push the initial assets
```bash
git add *
git commit
git push --set-upstream origin gh-pages  
```

* Configure your website, edit README.md (the main page) and _config.yml which contains project specific values (project name, repo URL...)

* Test your site (check the setting tabs to check the site build status and URL).
