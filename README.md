# Setting up a Repository

### Generate a key
ssh-keygen -t rsa -b 4096 -C "antosmichael07@gmail.com"

### Get the public key
  Linux: cat ~/.ssh/id_rsa.pub <br>
Windows: C:/users/user/.shh/id_rsa.pub

### Deleting the key from a computer
  Linux: rm -rf ~/.shh/* <br>
Windows: del C:/users/user/.shh/*

### Working with git
  Linux: touch README.md <br>
Windows: ? <br>
git init <br>
git branch -M main <br>
git remote add origin git@github.com:antosmichael07/test1.git <br>
git config --local user.email "you@example.com" <br>
git config --local user.name "name" <br>
git add . <br>
git commit -m "first commit" <br>
git push -u origin main
