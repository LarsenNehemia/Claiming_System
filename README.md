git add .
git commit -m "Updated all files with new content"

git add missed_file.txt
git commit --amend -m "Corrected commit message and added missed file"

chmod u+rw 'Claiming_System/.vs/Claiming_System/FileContentIndex/197dbd79-1204-407b-8e2c-abec99b38102.vsidx'

git add .
git commit -m "Fixed corrupted code issue"

rm -rf .git
git init
git add .
git commit -m "Reinitialize repository"

echo ".vs/" >> .gitignore
git rm -r --cached .vs

