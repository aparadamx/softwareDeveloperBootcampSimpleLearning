# softwareDeveloperBootcampSimpleLearning

################create a new repository on the command line###############

echo "# softwareDeveloperBootcampSimpleLearning" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/aparadamx/softwareDeveloperBootcampSimpleLearning.git
git push -u origin main

###############push an existing repository from the command line##########

git remote add origin https://github.com/aparadamx/softwareDeveloperBootcampSimpleLearning.git
git branch -M main
git push -u origin main


#############kill process angular usng 4200 process
sudo kill $(sudo lsof -t -i:4200)

#alias
alias gst="git status"
alias glt="git log --oneline --decorate --graph --all"
alias glta="git log --graph --pretty="\'"%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset"\'" --all"

code () { VSCODE_CWD="$PWD" open -n -b "com.microsoft.VSCode" --args $* ;}
