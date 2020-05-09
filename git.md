
# Clone

git clone url

ex) git clone https://github.com/daejinseok/Note


# push
git add .
git commit -m "bra bra..."
git push


# unix
git config --global alias.acp '!f() { git add -A && git commit -m "$@" && git push; }; f'

# in powershell 
git config --global alias.acp '!f() { git add -A && git commit -m \"$1\" && git push; }; f'