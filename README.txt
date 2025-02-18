


branch https://github.com/amr080/st/new/main


cmds
git init
git remote add origin https://github.com/X-Financial-Technologies/xft-1.git
git checkout -b 20250215-prod
git add assets cs fs ic mkt p prb sai sec shr sp usr wp
git commit -m "upload"
git push -u origin 20250215-prod
Remove-Item -Recurse -Force .git
