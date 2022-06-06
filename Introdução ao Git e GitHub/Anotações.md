# Gerei chave pública
 - ### **Códigos que digitei no GitBash:**

 
 LIDIA@DESKTOP-A4CUV1E MINGW32 ~
 
 ssh-keygen -t rsa -b 4096 -C "leticialayla2018@gmail.com"

Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/LIDIA/.ssh/id_rsa):

Created directory '/c/Users/LIDIA/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:

Your identification has been saved in /c/Users/LIDIA/.ssh/id_rsa
Your public key has been saved in /c/Users/LIDIA/.ssh/id_rsa.pub

The key fingerprint is:
SHA256:KK9LREaHqiXt3FtASri66luBlFIrqAXNi187wbGVrHs leticialayla2018@gmail.com

The key's randomart image is:
+---[RSA 4096]----+
|.+. .o..         |
|oo=o+.+          |
|+Bo*o=           |
|BoBoB  .         |
|oO +o=. S        |
|o +.*oE          |
| . ..=.          |
|. ....           |
|+o. o.           |
+----[SHA256]-----+

LIDIA@DESKTOP-A4CUV1E MINGW32 ~
 cd /c/Users/LIDIA/.ssh/

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 ls
 id_rsa  id_rsa.pub

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 cat id_rsa.pub

ssh-rsa
AAAAB3NzaC1yc2EAAAADAQABAAACAQCs/4fLIq/+OyKd5Kq2dhxL0jsI9rRoOcBV6Q5CD+C6wNjH8pefCo11RzOcp5D/vMnuRtGnDQbNmy90tkGTqLk8zUI4t1T/xfSyFUfxiT3x9RkI+oLsGCsr3C8IX7Oh+zegzXh084VyTxPGaCue8PDqrqfRpAZ+tI7LqAt5U0yjPmipm/Vq3GEKRmL4jO34WdlXEWcDGuQ9tGqS2FR1W+JsZkSA5owh07L6YpehPbSgw6+dy6uGVdgFT7OgjGUdgjyg+t/5f5QrZrAHxyK3otuRcK8o7OUJPdxyLdHkNnTpTaoRmhPZzfEy65ia7+hJ6zZGpX6e+q19xqLl/SouI/DSd/jcUZ5d1YEev1RiNyS+ZsAXtuvaGxL0HBwy5UICgYSu8/rVjdrl1JvvXNjWXMKsKSSdxlaxzoUaR3m42AKz25cB16JgDwK+37SYP5I85xs+PBKebC6TbqWYuvEd5NNgeyO5tsR8+V4SMwu854pVVk3JTGn3aMCqGtmy3VQYp33XhSjUdgVakALpr7D2I809QsIr0l7ln78wUnFt5Iufh4QeDjDzOlJRfuHfAT7bPhFWf90q7XCE6GlCTYkbiz96PpEEmJc9oKPkkh2aJwjtvPe/O6CtFpDEDZiMJ9A1o0fZgkMiXTO6SxOKBYuYIH3cIVCGi1PvIXKmYSrr2ThHGQ== leticialayla2018@gmail.com

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 ls
id_rsa  id_rsa.pub

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 pwd
/c/Users/LIDIA/.ssh

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 eval (ssh-agent) -s
Agent pid 128
bash: -s: command not found

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 eval $(ssh-agent -s)
Agent pid 134

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 ls
id_rsa  id_rsa.pub

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh
 ssh-add id_rsa

Enter passphrase for id_rsa:
Identity added: id_rsa (leticialayla2018@gmail.com)

LIDIA@DESKTOP-A4CUV1E MINGW32 ~/.ssh


# Sistema não compatível
 - ### **Não sei se isso pode interferir em algo no futuro**
 
 [10:46, 06/06/2022]:

  Observação: Se você estiver usando um sistema legado que não é compatível com o algoritmo Ed25519, use:

   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
: ssh-keygen -t ed25519 -C "your_email@example.com"

# Fiz meu primeiro Token de segurança

Observação: coloquei para expirar até 60 dias
Data da criação 06/06/2022

# Fui clonar mas pediu minha senha:

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$ git clone git@github.com:unform/unform.git

Cloning into 'unform'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.

ED25519 key fingerprint is SHA256:

+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.

This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes

Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.

Enter passphrase for key '/c/Users/LIDIA/.ssh/id_rsa':

remote: Enumerating objects: 3600, done.
remote: Counting objects: 100% (154/154), done.
remote: Compressing objects: 100% (123/123), done.
remote: Total 3600 (delta 60), reused 97 (delta 25), pack-reused 3446
Receiving objects: 100% (3600/3600), 7.49 MiB | 7.51 MiB/s, done.
Resolving deltas: 100% (1877/1877), done.

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$ ls
hello.txt  unform/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$


# Git pasta oculta 


LIDIA@DESKTOP-A4CUV1E MINGW32 /c
$ ls
'$GetCurrent'/              PerfLogs/                     Workspace/
'$Recycle.Bin'/            'Program Files'/               Workstest/
'$WinREAgent'/             'Program Files (x86)'/         bootTel.dat
3DP/                       ProgramData/                  bootmgr
'Arquivos de Programas'@    Recovery/                     found.000/
BOOTNXT                   'System Volume Information'/   hiberfil.sys
'Documents and Settings'@   Users/                        pagefile.sys
DumpStack.log.tmp          Windows/                      swapfile.sys
MSOCache/                  Windows10Upgrade/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c
$ cd Workspace/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$ mkdir livro-receitas

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$ ls
hello.txt  livro-receitas/  unform/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace
$ cd livro-receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas
$ git init
Initialized empty Git repository in C:/Workspace/livro-receitas/.git/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ ls

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ ls -a
./  ../  .git/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$  cd .git/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas/.git (GIT_DIR!)
$ ls
HEAD  config  description  hooks/  info/  objects/  refs/

# Untracked 

1. Tinha criado um commit e nele não tinha a pasta receitas q criei, ou seja fiz uma modificação e o git não reconheceu. Ele diz que meu arquivo foi deletado mas na verdade ele só esta dentro de uma pasta não reconhecida.

2. No do professor ocorreu tudo tranquilo e direto, eu tive q fazer receitas/ primeiro pra dps fazer strogonoff, n sei se isso atrapalhou alguma coisa, mas no fim apareceu a msm, mensagem q apareceu no do professor. 

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add *

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git commit -m "commit inicial"
[master (root-commit) 33c93f8] commit inicial
1 file changed, 36 insertions(+)
create mode 100644 Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ ls
Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
nothing to commit, working tree clean

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ mkdir receitas

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ ls
Strogonoff  receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ mv Strogonoff ./receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ ls
receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ cd receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas/receitas (master)
$ ls
Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas/receitas (master)
$ cd ..

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
Changes not staged for commit:
(use "git add/rm <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
deleted:    Strogonoff

Untracked files:
(use "git add <file>..." to include in what will be committed)
receitas/

no changes added to commit (use "git add" and/or "git commit -a")

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add
Strogonoff  receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ gt status
bash: gt: command not found

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
Changes not staged for commit:
(use "git add/rm <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
deleted:    Strogonoff

Untracked files:
(use "git add <file>..." to include in what will be committed)
receitas/

no changes added to commit (use "git add" and/or "git commit -a")

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add/rm Strogonoff receitas/
git: 'add/rm' is not a git command. See 'git --help'.

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add/rm Strogonoff
git: 'add/rm' is not a git command. See 'git --help'.

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add receitas/

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   receitas/Strogonoff

Changes not staged for commit:
(use "git add/rm <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
deleted:    Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add Strogonoff/
fatal: pathspec 'Strogonoff/' did not match any files

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git add Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
renamed:    Strogonoff -> receitas/Strogonoff

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$

# Commitei mais uma vez

1. Aqui o arquivo foi commitado novamente.

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git commit -m "cria pasta receitas, move arquivo para receitas"
[master bcfa162] cria pasta receitas, move arquivo para receitas
1 file changed, 0 insertions(+), 0 deletions(-)
rename Strogonoff => receitas/Strogonoff (100%)

2. Aqui pode se perceber os status da branch, nada para ser commitado, ou seja nenhuma alteração não identificada, em untracked. Também nada para colocar em estado de stagin. 

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
nothing to commit, working tree clean

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$

# Push 

1. Como fazer o push, colocar no repositório do github, do repositório do meu terminal. 

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git remote add origin [https://github.com/LeticiaLayla/Livro-receitas.git](https://github.com/LeticiaLayla/Livro-receitas.git)

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git remote -v
origin  [https://github.com/LeticiaLayla/Livro-receitas.git](https://github.com/LeticiaLayla/Livro-receitas.git) (fetch)
origin  [https://github.com/LeticiaLayla/Livro-receitas.git](https://github.com/LeticiaLayla/Livro-receitas.git) (push)

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git status
On branch master
nothing to commit, working tree clean

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$ git push origin master
familia2015Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 3 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 1.11 KiB | 380.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To [https://github.com/LeticiaLayla/Livro-receitas.git](https://github.com/LeticiaLayla/Livro-receitas.git)

- [new branch] master -> master

LIDIA@DESKTOP-A4CUV1E MINGW32 /c/Workspace/livro-receitas (master)
$

2. Para reverter eh só usar Pull ao invés de push. 
Assim vou poder pegar oq foi alterado no Github pro meu terminal.
