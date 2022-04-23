# senai-versoes-colaboracoes
Práticas em versionamentos

# Segue a lista dos principais comandos utilizados para gerenciar o versionamento dos códigos no ambiente Git

Git é um sistema de controle de versão distribuído open source que facilita ações com o GitHub

A etapa inicial a se ter em conta no ambiente Git, incia com a instalação do próprio Git, através do link <https://gitforwindows.org/>.

Na sequência, a configuração da ferramenta faz-se necessária, cujo comandos são:

$ git config --global user.name "[nome]" 
# Que configura o nome que você quer ligado as suas transações de
commit

$ git config --global user.email "[endereco-de-email]"
# Configura o email que você quer ligado as suas transações de commit

## CRIAÇÃO DE REPOSITÓRIOS
# Criação um novo repositório local com um nome específico
$ git init [nome-do-projeto]

# Baixa um projeto e seu histórico de versão inteiro
$ git clone [url]

## Revisão edições e criação de uma transação de commit:

# Lista todos os arquivos novos ou modificados para serem commitados
$ git status

$ git diff
# Mostra diferenças no arquivo que não foram realizadas

$ git add [arquivo]
# Faz o snapshot de um arquivo na preparação para versionamento

$ git diff --staged
# Mostra a diferença entre arquivos selecionados e a suas últimas
versões

$ git reset [arquivo]
# Deseleciona o arquivo, mas preserva seu conteúdo

$ git commit -m "[mensagem descritiva]"
# Grava o snapshot permanentemente do arquivo no histórico de versão


$ git branch
# Lista todos os branches locais no repositório atual

$ git branch [nome-do-branch]
# Cria um novo branch

$ git checkout [nome-do-branch]
$ Muda para o branch específico e atualiza o diretório de trabalho

$ git merge [branch]
# Combina o histórico do branch específico com o branch atual

$ git branch -d [nome-do-branch]
# Exclui o branch específico


$ git log
# Lista o histórico de versões para o branch atual

$ git log --follow [arquivo]
# Lista o histórico de versões para um arquivo, incluindo mudanças de nome

$ git diff [primerio-branch]...[segundo-branch]
# Mostra a diferença de conteúdo entre dois branches

$ git show [commit]
# Retorna mudanças de metadata e conteúdo para o commit especificado


OBS.: É importante frisar que a lista não pára por aqui, no entanto, essa lista limita-se à oque consegui assimilar no conteúdo apresentado pelo professor.




