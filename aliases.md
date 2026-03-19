# some aliases

```sh
# My aliases
alias la='ls -a'
alias gatus='git status'
alias gush='git push'
alias gull='git pull'
gg() {
  git pull && git push && echo "perfecto!"
}
gomit() {
  git add .
  git commit -m "$*"
}

# Prompt
PS1="🌈 %F{cyan}%n%f:%F{magenta}%t%f %1~ %# "
```