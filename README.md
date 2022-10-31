Repository to see what I learned about Git && Github.


//create new repo
echo "# github-basic" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/thanhbl-hust/github-basic.git
git push -u origin main

//push an existing repo
git remote add origin https://github.com/thanhbl-hust/github-basic.git
git branch -M main
git push -u origin main