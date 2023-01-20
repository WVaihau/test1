# Test 1

p1

p2

When push on dev

1 Create and push staging branch : git checkout -b staging && git push --set-upstream origin staging

2 Run the test

3 Merge main with staging uppon success :

- git checkout main
- git merge staging
- git push

4 Cleaning

Delete staging branch

- git push origin --delete staging && git branch -d staging
