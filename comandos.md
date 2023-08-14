# Descrição dos Comandos

```
git status
```
 - Permite inspecionar quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git

 ```
 git add <filename ou .>
 ```
 - Adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, git add não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar git commit.

 ```
 git restore --staged <filename ou .>
 ```
 - Faz o mesmo que o reset , ele apenas vai fazer com que o HEAD aponte para o último commit, ou seja vai remover o arquivo com mudanças da área de stage.

 ```
 git branch <branchname>
 ```
 - Permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo.

 ```
 git checkout <branchname>
 ```
- Permite navegar entre ramificações criadas pelo git branch . A verificação de uma ramificação atualiza os arquivos no diretório atual para que fique igual à versão armazenada nessa ramificação e diz ao Git para gravar todos os novos commits nessa ramificação.

```
git checkout -b <branchname>
```
- Permite navegar entre ramificações criadas pelo git branch . A verificação de uma ramificação atualiza os arquivos no diretório atual para que fique igual à versão armazenada nessa ramificação e diz ao Git para gravar todos os novos commits nessa ramificação. Cria a branck e muda ela.

```
git commit -m "<description"
```
- Pode ser utilizado de múltiplas formas para comitar as alterações para o repositório, porém todo commit necessita de uma mensagem para logar, já que esta o identificará. Para isso basta utilizar o comando git commit -m "mensagem de exemplo". A mensagem pode ser qualquer string válida.

```
git push
```
- É usado para enviar o conteúdo do repositório local para um repositório remoto. O comando push transfere commits do repositório local a um repositório remoto.

```
git branch -D <branchname>
```
- É a ferramenta de administração de ramificações de uso geral. Permite criar ambientes de desenvolvimento isolados em um único repositório.

```
git fetch
```
- É um comando básico usado para baixar conteúdos de um repositório remoto. O git fetch é usado em conjunto com git remote , git branch , git checkout e git reset para atualizar um repositório local ao estado de um remoto.

```
git pull
```
-  É usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.

  ```
  code .
  ```
-  É usado para abrir o repositório no VS Code
-  Caminho: cd Documents >> git clone (link do repositório criado no github) >> cd Documents >> cd (nome do repositório criado) >> code .
