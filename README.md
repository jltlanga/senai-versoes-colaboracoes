# senai-versoes-colaboracoes
Práticas em versionamentos

Segue a lista dos principais comandos utilizados para gerenciar o versionamento dos códigos no ambiente Git

Git é um sistema de controle de versão distribuído open source que facilita ações com o GitHub

A etapa inicial a se ter em conta no ambiente Git, incia com a instalação do próprio Git, através do link <https://gitforwindows.org/>.

Na sequência, a configuração da ferramenta faz-se necessária, cujo comandos são:

$ git config --global user.name "[nome]" 
Que configura o nome que você quer ligado as suas transações de
commit

$ git config --global user.email "[endereco-de-email]"
Configura o email que você quer ligado as suas transações de commit

CRIAÇÃO DE REPOSITÓRIOS
Criação um novo repositório local com um nome específico
$ git init [nome-do-projeto]

Baixa um projeto e seu histórico de versão inteiro
$ git clone [url]

Revisão edições e criação de uma transação de commit:

Lista todos os arquivos novos ou modificados para serem commitados
$ git status

$ git diff
Mostra diferenças no arquivo que não foram realizadas

$ git add [arquivo]
Faz o snapshot de um arquivo na preparação para versionamento



