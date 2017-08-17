### 1. Criar pasta no PC para o seu FORK

    mkdir NOME_DA_PASTA
    
### 2. Entre na pasta que foi criada

   cd NOME_DA_PASTA

### 3. Clone o seu fork para a pasta

    git clone https://github.com/SEU-USUARIO/PROJETO-FORKADO.git

### 4. Entrar na pasta do projeto forkado

    cd PROJETO-FORKADO
    
### 5. Adicionar o projeto oringal como remote e verifica as diferenças entre os arquivos: 

    git remote add upstream https://github.com/DESENVOLVEDOR-ORIGINAL/PROJETO-ORIGINAL.git
    
### 5. Verifica as diferenças entre os projetos (original e forkado): 

    git fetch upstream

### 5. Atualiza o projeto forkado com as modificações do projeto original:

    git pull upstream master
    
### 6. Enviar arquivos atualizados para o seu fork no GitHub:

    git push
