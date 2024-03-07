# POC of git submodule


## Refs:
- Main repo: https://github.com/quocthanh2694/submodule-poc (current)
- App1 repo: https://github.com/quocthanh2694/poc-submodule-app1
- App2 repo: https://github.com/quocthanh2694/poc-submodule-app2

## Setup submodule
- (Optional) Remove all submodules: `git submodule deinit -f --all` ([Remove submodule cached](https://stackoverflow.com/questions/20929336/git-submodule-add-a-git-directory-is-found-locally-issue))
- Setup app1:  
`git submodule add https://github.com/quocthanh2694/poc-submodule-app1.git apps/app1`
- Setup app2:  
`git submodule add https://github.com/quocthanh2694/poc-submodule-app2.git apps/app2` 
- Then inside `apps` folder we will have
```
apps/
    app1
    app2
```
- Add git ignore for both `app1` & `app2`
