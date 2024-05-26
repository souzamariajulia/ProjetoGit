<<>> Aqui irei colocar os passos e comandos para utilização do Git e GitHub <<>>


# Guia Básico para Usar Git e GitHub com Git Bash

## Configuração Inicial

1. **Instalar o Git Bash**
- Baixe e instale o Git Bash no site oficial: [Git Bash](https://gitforwindows.org/).

2. **Abrir Git Bash na Pasta do Projeto**
- Navegue até a pasta do seu projeto.
- Clique com o botão direito do mouse, selecione "Mostrar Mais Opções" e depois "Open Git Bash Here".

3. **Verificar Instalação**
- No Git Bash, digite `git --version`.
- Se a instalação estiver correta, a versão do Git instalada será exibida.

---------------------------------------------------------------------------------------------------------------------------------------
## **Comandos Básicos de Git e GitHub**

### Inicialização do Repositório

1. **Iniciar um Repositório**
   ```bash
   git init
   ```
   - Inicializa um repositório Git vazio na pasta atual.

### Adicionar e Comitar Arquivos

2. **Adicionar Arquivos**
   - Adicionar um arquivo específico:
     ```bash
     git add <nome-do-arquivo>
     ```
   - Adicionar todos os arquivos:
     ```bash
     git add .
     ```
   - Esses comandos movem os arquivos para a área de stage (preparados para serem comitados).

3. **Comitar Arquivos**
   ```bash
   git commit -m "mensagem do commit"
   ```
   - Comita os arquivos que estão na área de stage com uma mensagem descritiva.

### Conectar ao GitHub

4. **Configurar Repositório Remoto**
   - No GitHub, crie um novo repositório e copie o link HTTPS do repositório.
   - No Git Bash, adicione o repositório remoto:
     ```bash
     git remote add origin <link-do-repositório>
     ```

5. **Remover Repositório Remoto Existente (se necessário)**
   - Se já houver um repositório remoto configurado e você precisar removê-lo:
     ```bash
     git remote remove origin
     ```
   - Adicione o novo repositório remoto novamente com o comando anterior.

---------------------------------------------------------------------------------------------------------------------------------------
### Enviar Alterações para o GitHub **resumão para gravar na memória**

6. **Enviar Alterações**
   ```bash
   git push origin main
   ```
   - Envia os commits locais para o repositório remoto no GitHub.

## Versionamento Contínuo

1. **Verificar Modificações**
   ```bash
   git status
   ```

2. **Adicionar Alterações**
   ```bash
   git add .
   ```

3. **Verificar Status Novamente**
   ```bash
   git status
   ```

4. **Comitar Alterações**
   ```bash
   git commit -m "mensagem do commit"
   ```

5. **Enviar Alterações para o GitHub**
   ```bash
   git push origin main
   ```
---------------------------------------------------------------------------------------------------------------------------------------
## Criar e Mudar de Branch

1. **Criar uma Nova Branch**
   ```bash
   git checkout -b "nome-da-branch"
   ```

2. **Alterar Arquivos na Nova Branch**
   - Realize as modificações necessárias.

3. **Voltar para a Branch Principal**
   ```bash
   git checkout main
   ```

Seguindo esses passos, você poderá gerenciar o versionamento de seu código com eficiência usando Git e GitHub através do Git Bash.