#how I got started with github
sudo apt-get install git
mkdir ghtest
cd ghtest
touch README.md
git init
git add README.md 
git commit -m "first commit"
git remote add origin https://github.com/kevin137/notebook.git
git push -u origin master
cd ..
mkdir ght2
cd ght2/
git clone https://github.com/kevin137/notebook.git
