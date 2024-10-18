# Workshop Git, GitHub, GitLab
[GitHub]()
[GitLab]()
---

 > Git
 > GitHub
 > GitLab

 - Git: Versiyon Kontrol Sistemi
 - GitHub: **Git** Repository


## Git Version
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


## Git
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

## Git
```sh

```
---

## Git
```sh

```
---

## Git
```sh

```
---

## Git
```sh

```
---

## Git
```sh

```
---

## Git
```sh

```
---


