Remove Branches Locally
git branch -d dev
git branch -d test

Remove Branches Remotely
git push origin --delete dev
git push origin --delete test

----- to list tags -------
git tag
git show-ref --tags

------ Delete tag locally and remotely ------
Delete the Tag Locally ----> git tag -d v1.7
Delete the Tag Remotely -----> git push origin --delete v1.7
-------------------------------------------------------


