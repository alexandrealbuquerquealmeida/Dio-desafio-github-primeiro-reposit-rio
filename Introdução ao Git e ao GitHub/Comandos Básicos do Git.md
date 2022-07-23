# 1. SETUP

### 1.1. Criando definições do usuário

     a) git config --global user.email "[xxxxx@xxx.com]"
    
     b) git config --global user.name "[xxx]"

#### 1.2. Verificando definições de usuário já criadas

     a) git config user.name
    
     b) git config --list

## 2. PROJETOS NOVOS |Clonagem

    a) git init
    
    b) git clone <repositório> <meu/diretório> 
       Para clonar um diretório num pasta específica
    
    c) git clone <repositório> 
       Para clonar na pst atual

# 3. SERVIDOR REMOTO

    a) git remote add nome_do_remote ssh://usuário@caminho_e_nome_completo_do_repositório.git
    
    b) git remote -v 
    
    c) git push web master

# 4. GERENCIAMENTO

    a) git status
    
    b) git log
    
    c) git log -p 
       Exibe o diff de cada arquivo
    
    d) git shortlog
    
    e) git diff 
       Alterações -arq- ainda ñ adic em stage area
    
    f) git diff --staged 

# 5. COMMITS

    a) git add -a 
       Add todos os arquivos na pst
    
    b) git add -u 
       Add apenas as mudanças
    
    c) git add. 
       Add todos os arquivos da árvore
    
    d) git commit -m "[mensagem]"
       Gera v estável c/ comentários
    
    e) git commit -a -m "[mensagem]"
       Gera versão estável e dispensa git add c/ comentário
    
    f) git rm --cached pasta_ou_arquivo -v
       Remove arquivos já monitorados pelo git



## 6. BRANCHS

    a) git branch
       Ver lista de branchs
    
    b) git branch -v
       Ver o último commit em cada branch
    
    c) git checkout -b nome_branch_novo
       Cria novo branch e muda para ele ao mesmo tempo
    
    d) git checkout master
       Trás mudança do branch X para o master
    
    e) git merge nome_do_branch_novo
       "Merge" das alterações no branch master
    
    f) git branch -d nome_branch_deletar
       Exclui branchs 
