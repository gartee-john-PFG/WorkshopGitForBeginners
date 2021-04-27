# WorkshopGitForBeginners
### Git Documentation
* git --help
* [git documentation)[https://git-scm.com/docs]
* (an excellent tutorial...gitimmersion.com)[https://gitimmersion.com]
### Git aliases. 
Some shortcuts I've provided
```
[alias]
	lg = log --oneline --graph --decorate --all
	fa = fetch --all
	co = checkout
	ci = commit
	c = commit
	cm = commit -m 
	st = status
	br = branch
	hist = log --pretty=format:'%C(green bold)%h %C(yellow)%ad %C(white bold)| %C(green)%s%C(auto)%d %C(cyan bold)[%an]' --graph --date=short --all
  	r = remote -v
	type = cat-file -t
  	dump = cat-file -p
	go = git checkout
```