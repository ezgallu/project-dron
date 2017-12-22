# project-dron

#git - help -> sve budemo u master stavljali
#neke komande su u word datoteci
git status
git add ime_koje_hocete_dodati 
#za sve je
#git add -A
git commit -m "napisati poruku"
git fetch
git rebase
git push -u origin master

#ak bude kolizije instalirajte koristite:
git mergetool
#ak nemate to podešeno upišite ove dvije komande
git config --global merge.tool p4merge
git config --global mergetool.p4merge.cmd 'p4merge.exe \"$BASE\" \"$LOCAL\" \"$REMOTE\" \"$MERGED\"'
