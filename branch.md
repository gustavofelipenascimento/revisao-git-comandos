# Branchs

São ramificados do projeto, o qual permite vários desenvolvedores, trabalharem em diferentes funcionalidades, sem bugar a versão estável.

## Principais Branchs

Branch main -> Que é a branch principal, ou seja, a branch estável da aplicação, Versão que é disponibilizado aos Clientes.

## Outras Branchs

Para cada nova funcionalidade ou correção de bugs é criada uma nova branch.

## Padrões para criar nome de branchs

!IMPORTANTE! Nomes de branchs não tem acento nem "Ç".

Para correção de bugs: fix_identificação_do_bug
Exemplo fix_botão_de_login, fix_cor_do_cabecalho

Para novas funcionalidades:

feat_identificação_da_novo_funcionalidade
Exemplo: feat_integracao_com_google, feat_nova_tela_de_contato

Para atualizar documentaão: doc_identificacao_da_alteração
Exemplo: doc_adicionada_nova_Image

Para criação/alteração de tarefas que não interfere no código:
chore_identificacao_da_modificacao
Exemplo: Chore_atualizacao_a_versao_dobanco

## Comandos para trabalhar com branchs
### Criação de novas branchs
git checkout -b nome_da_nova_branch
Exemplo: git checkout -b fix_botao_da_tela_login
Obs: O ideal é sempre criar as branchs a partir da main.

### Listar as branchs existentes

git branch list

### Trocar de branch 

git switch nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tela_login
Exemplo 02: git switch main

### Excluir uma branch

git branch -D nome_da_branch_que_deseja_excluir
Exemplo: git branch -D fix_botao_da_tela_login