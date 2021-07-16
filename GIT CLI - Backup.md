# GIT CLI - Backup

> local repository ----(push)----> remote repository
>
> remote repository ----(clone)----> local repository 2
>
> local repository 2 ----(push)----> remote repository
>
> remote repository ----(pull)----> local repository 

작업 이동성 극대화



## 원격저장소 (Git hosting)

- [GitHub](https://github.com/)	유료 private repository
- [GitLab.com](GitLab.com)	unlimited project / collaborator



## 연결

```
git remote add [원격저장소이름] [HTTPS]
git remote
git remote -v : 상세 출력
```



## git push

```
git push
git push --set-upstream origin master : 앞으로 origin으로 push 한다
```



## git clone

```
git clone [HTTPS]
```



## git pull

```
git pull : 이미 주소는 저장되어 있음
```



## 오픈소스

- [Git](https://git-scm.com/) > [source code](https://github.com/git/git) 
  - git으로 버전 관리 되어 github 사이트를 통해 공유/협업



1. 압축된 파일 다운
2. git으로 clone (주소 copy)

```
git clone [HTTPS]
```



