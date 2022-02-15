create repo
add collabolators
**bonus** lock main branch
create new branch
make some changes
commit changes
push to remote branch
create PR
1- approve PR
2- pull from main
make more changes
3- revert to previous change (keeping history) " git revert fcd3e72 "
commit revert
4- reset to previous commit (removing history) " git reset 1b05420 --hard "
5- reset to HEAD "git reset HEAD --hard"
6- show first 5 commits " git log --oneline -5 "
7- display graph commit " git log --graph "

9- get diff between last comment and first comment " git diff 4b825dc642cb6eb9a060e54bf8d69288fbee4904 HEAD "
4b825dc642cb6eb9a060e54bf8d69288fbee4904 is the id of the "empty tree" in Git and it's always available in every repository.