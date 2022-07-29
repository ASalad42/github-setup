# testing ssh setup 




https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

mkdir .filename
cd .name 
use pwd command to check what file are working in 



$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


$ eval "$(ssh-agent -s)"
> Agent pid 59566


$ ssh-add ~/.ssh/id_ed25519
