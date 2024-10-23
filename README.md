# Workshop Git, GitHub, GitLab
[GitHub]()
[GitLab]()
---

 > Git
 > GitHub
 > GitLab

 - Git: Versiyon Kontrol Sistemi
 - GitHub: **Git** Repository

## Git Config
```sh
git -v
git --version

git --help

git config --global user.name
git config --global user.name "myaseminsungur"
git config --global user.email
git config --global user.email "mysmn@windowslive.com"
git config --global core.editor "notepad++"
git config --global -l
git config core.autocrlf true
```
---


## Git Sıklıkla Kullanılan Komutlar
```sh
clear
git status
git log
```
---


## Git Remote
```sh

git init
git add .
git add dosyaAdi dosyaAdi2
git commit -m "initial commit"
git remote add origin GitHubURL
git remote
git branch -M main
git push -u origin origin
```
---


## Git Commit
```sh
git add .
git commit -m "mesaj adı"
git push

NOT: Eğer önceden ilgili dosya "git add" ile eklenmişse 
git commit -a -m "commit adı" 
```
---


## Git Hakkında
```sh
Git Nedir?
- Global Information Tracked kısaltmasıdır
- VCS Version Control System
- Repository: GitHub, GitLab, vs. 
- En önemli özelliği: Dağıtık olması. Aynı anda birden fazla kişiyle çalışabiliriz.
- Ücretsiz
- Açık kaynak kodludur. 
- Git yazarı Linux çekirdeğini yazan Linus Torvalds tarafından 2005 yılında yazılıyor.
- Eski kodlarımıza erişim sağlayabiliyoruz. 
- Dosya değişikliğini önceki sürümlere geçerek sağlayabiliyoruz.
```
---




## Git Clone
```sh
git clone https://github.com/myaseminsungur/Workshop_Git_GitHub_GitLab.git
```
---


## Git Alias
```sh
git log --decorate --oneline --graph --all
git config --global alias.graph "log --decorate --oneline --graph --all"
git graph
```
---


## Git Remote
```sh
git remote 
git remote set-url yeniRemoteAdi URLYazıyoruz
```
---


## Git Diff
```sh
git log
git diff commitID1 commitID2
 git diff ba57baf c9dd820
```
---


## .gitignore
```sh
# Bu dosyayı takip etme
secret.txt

# React, Angular vs.
node_modules

```
---

## Git Stash
```sh
git add .
git stash
git stash save "stash kendi ismi"
git stash list

git stash apply stash:{0}
git stash drop stash:{0}

git stash pop
```
---

## Git Tag
```sh
git add .
git tag v1.0.0 - isimlendirme
git show v1.0.0 - bana bu versiyonda ne varsa göster
git checkout v1.0.0 - istediğim versiyona geçiş sağlayabilme
git checkout main - yukarıdaki işlemlerden sonra main branch'a dönmek istediğimde bunu kullanırım
git push origin v1.0.0 - bu tag'i gönderme
git tag --delete v1.0.0 - versiyonu silme
```
---

## Git Pull/Fetch
```sh
git pull: Uzak repodaki bütün dosyaları hemen local projemize ekler.
NOT: Genelde conflict yeriz.

git fetch: Uzak repodaki bütün dosyaları hemen local projemize EKLEMEZ.
Biz kontrol ettikten sonra istersek local projemize ekleriz.
NOT: Conflict yememek için kullanmak gerekir.

git fetch
git branch -a
git checkout remote/origin/main
git checout main
git merge origin/main
```
---

## Git Branch
```sh

NOT: Branch yapmadan önce add, commit ve push yapalım.
git branch -M main

git branch
git branch -all
git branch -a

# Senaryo 1
git branch frontend
git checkout frontend
cat >> frontend.txt
git add .
git commit -m "frontend"
cat >> frontend2.txt
git add .
git commit -m "frontend2"
git push origin frontend
git switch main
git merge frontend
git add .
git commit -m "frontend main"
git push

git branch -D frontend

# Senaryo 2
git checkout -b backend
cat >> backend.txt
git add .
git commit -m "backend"
git push origin backend
git switch main
git merge backend
```
---

## Git Merge
```sh

```
---

## Git Conflict
```sh
git reset HEAD~1
git add .
git commit -m "Çakışma Sonrası"
git push --force

```
---

## Git
```sh

```
---


