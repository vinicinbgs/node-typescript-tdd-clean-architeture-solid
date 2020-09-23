git config --local --edit

[alias]

s = !git status -s
c = !git add --all && git commit -m
l = !git log -pretty=format:'%C(blue)%h %C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
