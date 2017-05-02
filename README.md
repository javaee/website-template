# website-template

The gh-pages branch contains all the initial assets for a simple website.

Clone your project repo
Make sure the master branch contains 
- CONTRIBUTING.md (see here)
- LICENSE.md (see here for the standard GF GPVv2/CDDL/CPE)
Create an orphan branch that will host your site
  git checkout --orphan gh-pages
You might want to delete uneccsary files (but do keep CONTRIBUTING.MD and LICENSE.md in both branches!)
  git rm --cached -r stuff_to_delete
Add and push the initial assets
  git add *
  git commit
  git push --set-upstream origin gh-pages  
You can now test your web site (check the setting tabs to check the site build status and URL).


   


