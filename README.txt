To do Installation:
https://git-scm.com/download/win     (choose 64 bit - just click next to everything)

Make a github:
https://github.com/ 
just use whatever email and do the bare minimum

To setup the repository:
1. go to the folder that has valheim in it
2. right click "open git bash here"
3. in the cmd enter > git init
----- side note: all commands you can copy as you normally would but when you paste into the terminal do not ctrl+v, just click your middle mouse button
----- also leave off the > in the commands, thats just to show your are in terminal
4. in the cmd enter > git config --global user.email "whatever your email is in these quotes"
5. in the cmd enter > git config --global user.name "whatever your name is in these quotes"
6. in the cmd enter > git remote add valheim_world "https://github.com/helikelley/valheim_git"
7. I will probably need to verify you on my github, but after this we should be able to just run the following commands to update the server

---------------------------------------------------------------------------------

BEFORE YOU PLAY
git pull

BEFORE YOU LOGOFF
git commit -am "some text"
git push

