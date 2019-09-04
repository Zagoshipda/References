How to Git & Github
==========


 <br/><br/>


### references
- [Git - Book](https://git-scm.com/book/en/v2)
- [Resources to learn Git](http://try.github.io/)
- [Learn Git- Git tutorials, workflows and commands | Atlassian Git Tutorial](https://www.atlassian.com/git)
- [Git & GitHub Crash Course For Beginners - YouTube](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
- [생활코딩 - 지옥에서 온 Git(Git from the HELL)](https://www.youtube.com/playlist?list=PLuHgQVnccGMA8iwZwrGyNXCGy2LAAsTXk)
- [A successful Git branching model » nvie.com](https://nvie.com/posts/a-successful-git-branching-model/)
- [[GitHub] Git 브랜치의 종류 및 사용법 (5가지) - Heee's Development Blog](https://gmlwjd9405.github.io/2018/05/11/types-of-git-branch.html)
- [초보자를 위한 Git & GitHub](https://www.slideshare.net/jayjin0427/git-github-145104268?fbclid=IwAR0czFuOQALN6gybwm2CnKmf7nBApFeT07-Y-AUZ5In3prcW7_bTzUYZlC8)
- [SE 스타트업 엔지니어링 - 깃(Git)과 함께 개발하기](https://tech.10000lab.xyz/git/using-git-as-you-work.html)
- [Tower - The most powerful Git client for Mac and Windows](https://www.git-tower.com/windows)


 <br/><br/>


### Git 
- [Git - Reset Demystified](https://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified) (The Three Trees - HEAD, Index, Working Directory(tree)/ git reset --soft, --mixed, --hard/ squashing commits/ checkout vs reset --hard) 
- [GIT4 - Reset & Revert 4.1. reset --soft vs --mixed vs --hard](https://www.youtube.com/watch?v=DZSZowycr2o&list=PLuHgQVnccGMAvTJlPGzizAkyqXfZ9IyY8&index=6)
- [KLDP - diff 보는 법](https://kldp.org/node/103533)
- [Outsider's Dev Story - git diff 에서 변경된 부분을 더 명확하게 보는 방법](https://blog.outsider.ne.kr/1011) 
- [git add -p 와 git commit -v 의 사용 :: Outsider's Dev Story](https://blog.outsider.ne.kr/1247)
- [[Git] git add 취소하기, git commit 취소하기, git push 취소하기 - Heee's Development Blog](https://gmlwjd9405.github.io/2018/05/25/git-add-cancle.html)
- [Stack Overflow - LF will be replaced by CRLF in git - What is that and is it important?](https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important)
- [Stack Overflow - Git refusing to merge unrelated histories on rebase](https://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories-on-rebase/37938036#37938036)
- [git의 merge와 rebase 비교하기](https://blog.outsider.ne.kr/666)
- [What is the difference between `git merge` and `git merge --no-ff`? - Stack Overflow](https://stackoverflow.com/questions/9069061/what-is-the-difference-between-git-merge-and-git-merge-no-ff)  <br/><br/>
- [Git rebase를 이용한 커밋 수정 (Interactive Rebase) « Guppy's 난중(개발)일기](https://wckhg89.github.io/archivers/rebase)
- [Git - Rewriting History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History#_git_amend) (git rebase -i HEAD~n/ git commit --amend)
- [stackoverflow - Git rebase interactive drop vs deleting the commit line](https://stackoverflow.com/questions/35846154/git-rebase-interactive-drop-vs-deleting-the-commit-line)
- [[초보용] Git 되돌리기( Reset, Revert ) | devpools blog](http://www.devpools.kr/2017/02/05/%EC%B4%88%EB%B3%B4%EC%9A%A9-git-%EB%90%98%EB%8F%8C%EB%A6%AC%EA%B8%B0-reset-revert/)
- [[Git] 명령어(5) - reset, revert :: victolee](https://victorydntmd.tistory.com/79)
- [What's the difference between 'git merge' and 'git rebase'? - Stack Overflow](https://stackoverflow.com/questions/16666089/whats-the-difference-between-git-merge-and-git-rebase/16666418#16666418)
- [[Git] git stash 명령어 사용하기 - Heee's Development Blog](https://gmlwjd9405.github.io/2018/05/18/git-stash.html)
- [git stash 사용하기 :: Outsider's Dev Story](https://blog.outsider.ne.kr/788) (stash 내용 보기 : git stash show stash@{n})
- [stash - 생활코딩](https://opentutorials.org/course/2708/15332)
- [git rebase -i 사용하기](https://jupiny.com/2018/05/07/git-rebase-i-option/)
- [git amend | Atlassian Git Tutorial](https://ko.atlassian.com/git/tutorials/rewriting-history)  <br/><br/>
- [How to use Git Revert - Stack Overflow](https://stackoverflow.com/questions/19032296/how-to-use-git-revert)
- [Git Revert | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/undoing-changes/git-revert)
- [Git: Revert to a Previous Commit](https://stackabuse.com/git-revert-to-a-previous-commit/)
- [Git - Rebasing](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)
- [Git - Advanced Merging](https://git-scm.com/book/en/v2/Git-Tools-Advanced-Merging#_reverse_commit)
- [git rebase | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
- [Git Tip: Rebase Your Stash | Heliom](http://heliom.ca/blog/posts/git-tip-rebase-your-stash) (git stash / git reset HEAD~1)
- [[Git기초] 브랜치 강제로 옮기기](https://cornswrold.tistory.com/251) (branch를 특정 commit에 직접적으로 재지정하기 : git branch -f (branch) (commit ref / branch) ex. git branch -f master HEAD~3)
- [[Git기초] Git에서 작업 되돌리기](https://cornswrold.tistory.com/252) (git reset vs git revert : local branch의 경우 reset을 사용할 수 있지만, "history를 고쳐쓴다"는 점 때문에 다른 사람과 협업하는 remote branch에는 쓸 수 없음. 변경사항을 되돌리고 이 되돌린 내용을 다른 사람들과 공유하기 위해서는 git revert를 사용해야 함)
- [What's the difference between "git fetch" and "git pull"?](https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull)  <br/><br/>
- [git stash - Saving Changes | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/saving-changes/git-stash) (git stash / git stash pop stash@{n} / git stash list / git stash drop stash@{n})
- [git 도구 - stashing 과 cleaning · 초보몽키의 개발공부로그](https://wayhome25.github.io/git/2017/05/16/git-07-stashing-cleaning/) (git stash drop stash@{n})
- [git cherry-pick: 다른 브랜치의 일부 커밋만 반영하고 싶을 때 : TOAST Meetup](https://meetup.toast.com/posts/45)
- [git 명령어 : git cherry-pick :: 삐멜 소프트웨어 엔지니어](https://imasoftwareengineer.tistory.com/7) (git cherry-pick \<ref1\> \<ref2\> \<ref3\> ... )
- [Git push/fetch 내부 동작 정리 | 기록하기](https://hongsii.github.io/2018/11/08/git-push-fetch/)
- [Git - git-reflog Documentation](https://git-scm.com/docs/git-reflog)
- [[git] REFLOG - REBASE 취소하기](https://americanopeople.tistory.com/206)
- [shaking blog :: [GIT] reset 한거 취소하는 방법](https://88240.tistory.com/284) (git reflog / git reset --hard HEAD@{n})
- [#git reflog - HEAD 변경 이력을 볼 수 있다. 커밋은 어디 안 간다.](http://ohyecloudy.com/pnotes/archives/1994/)
- [Git을 잘 써보자- 12. git 복구 - git reflog | Suwoni-Codelab](https://suwoni-codelab.com/git/2018/04/07/Git-reflog/)  <br/><br/>


 <br/><br/>
  

### Github
- [SJ 아카이브 [깃허브 친해지기 2탄] 깃허브에 폴더별로 commit 다르게 설정해서 업로드하기](https://sojungarchive0414.blogspot.com/2018/03/2-commit.html)
- [Github를 이용하는 전체 흐름 이해하기 #1](https://blog.outsider.ne.kr/865)
- [안경잡이 개발자 :: 아톰(Atom) 개발 환경과 깃허브(GitHub) 연동하는 방법](https://ndb796.tistory.com/51)
- [아톰(atom) 에디터 깃(git) 연동 :: 깃(git) 편하게 사용하자 !!](http://blog.naver.com/PostView.nhn?blogId=wlgh325&logNo=221443819508&categoryNo=46&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=search) 
- [Github Tutorial : What is Pull Request?](https://www.youtube.com/watch?v=e3bjQX9jIBk)
- [git 초보를 위한 풀리퀘스트(pull request) 방법 · 초보몽키의 개발공부로그](https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/)
- [github - git - remote add origin vs remote set-url origin - Stack Overflow](https://stackoverflow.com/questions/42830557/git-remote-add-origin-vs-remote-set-url-origin/42830632)
- [Git Branch - 릴리즈 플래닝 - 회사에서 하고 있는 걸 정리해본다.](https://thdev.tech/android/git/2018/01/21/Git-Branch/)
- [요기요 Android 개발 Git Branch와 Release Planning -- RGP Tech Blog](https://rgpkorea.github.io/posts/ygy-android-release-planning/)
- [Solved: Clone private repo - GitHub Community Forum](https://github.community/t5/How-to-use-Git-and-GitHub/Clone-private-repo/td-p/12616) (git clone https://(github ID):(github PWD)@github.com/(github ID)/(repository name).git) <br/><br/>
- [git - What do you do with your branch after a pull request on GitHub? - Stack Overflow](https://stackoverflow.com/questions/7904038/what-do-you-do-with-your-branch-after-a-pull-request-on-github)
- [Git Pull | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/syncing/git-pull) (git pull vs git pull --rebase)
- [Difference between git pull and git pull --rebase - Stack Overflow](https://stackoverflow.com/questions/18930527/difference-between-git-pull-and-git-pull-rebase)
- [github - Git Desktop error " ! [remote rejected] master -> master (permission denied)" - Stack Overflow](https://stackoverflow.com/questions/51976794/git-desktop-error-remote-rejected-master-master-permission-denied)
- [Innovative Thinking IT :: git push, pull (fatal: refusing to merge unrelated histories) 에러](https://jobc.tistory.com/177)
- [How do I delete a Git branch locally and remotely? - Stack Overflow](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely) (git push <remote_name> --delete <branch_name>)
- [git - I deleted a branch in remote, how do I synchronize in local? - Stack Overflow](https://stackoverflow.com/questions/46156118/i-deleted-a-branch-in-remote-how-do-i-synchronize-in-local) (git remote prune origin)
- [Message 'src refspec master does not match any' when pushing commits in Git - Stack Overflow](https://stackoverflow.com/questions/4181861/message-src-refspec-master-does-not-match-any-when-pushing-commits-in-git) (git show-ref)
- [Differences between git remote update and fetch? - Stack Overflow](https://stackoverflow.com/questions/1856499/differences-between-git-remote-update-and-fetch) (특정 remote만 fetch하기 : git fetch <remote> <remote branch>, update는 branch 단위로는 안되고 remote 단위로만 가능한 듯)
- [Remote Git branches not visible - Stack Overflow](https://stackoverflow.com/questions/41406903/remote-git-branches-not-visible) (git branch -r / git branch -a / ___git remote show \<remote\>___ : remote repo의 branch 상태를 local repo와 비교해서 각각 확인할 수 있음) <br/><br/>
- [Can git permanently ignore a remote branch? - Stack Overflow](https://stackoverflow.com/questions/16842426/can-git-permanently-ignore-a-remote-branch) (remote branch를 log에서 삭제하고 싶다면 ***local directory에서 git이 저장하고 있는 reference 자체를 삭제***하는 방법이 가능 : rm .git/refs/remotes/\<remote\>/\<branch\>)
- [Git Workflow | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/comparing-workflows) (<Centralized/ Feature Branch/ Gitflow/ Forking> Workflow)
- [Git, 가장 쉽게 사용하기 - (2) commit, branch 전략 잘 짜는 법 : 네이버 블로그](http://blog.naver.com/PostView.nhn?blogId=tmondev&logNo=220763012361&redirect=Dlog)
- [How do I delete a Git branch locally and remotely? - Stack Overflow](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely) (___git push --delete <remote_name> <branch_name>___)


