Aqui está uma lista com os comandos Git mais usados:  

### 📥 **Baixar e inicializar repositório**  
- `git clone <URL>` → Clona um repositório remoto.  
- `git init` → Inicializa um novo repositório Git na pasta atual.  

### 📂 **Trabalhando com arquivos**  
- `git status` → Mostra o status dos arquivos modificados.  
- `git add <arquivo>` → Adiciona um arquivo para o próximo commit.  
- `git add .` → Adiciona **todos** os arquivos modificados.  
- `git reset <arquivo>` → Remove um arquivo da área de staging.  
- `git reset --hard` → Descarta todas as mudanças **não commitadas**.  

### ✅ **Commit e histórico**  
- `git commit -m "mensagem"` → Cria um commit com uma mensagem descritiva.  
- `git log` → Exibe o histórico de commits.  
- `git log --oneline` → Exibe o histórico de forma resumida.  
- `git show <commit>` → Mostra detalhes de um commit específico.  

### 🔄 **Branches (ramificações)**  
- `git branch` → Lista as branches disponíveis.  
- `git branch <nome>` → Cria uma nova branch.  
- `git checkout <branch>` → Troca para outra branch.  
- `git checkout -b <nome>` → Cria e muda para uma nova branch.  
- `git merge <branch>` → Mescla uma branch na atual.  
- `git branch -d <branch>` → Deleta uma branch local.  

### 🔃 **Atualizando e enviando mudanças**  
- `git pull` → Baixa as atualizações do repositório remoto.  
- `git push` → Envia as alterações para o repositório remoto.  
- `git push -u origin <branch>` → Sobe a branch para o repositório remoto e a define como padrão.  

### 🚨 **Revertendo mudanças**  
- `git checkout -- <arquivo>` → Restaura um arquivo ao último commit.  
- `git revert <commit>` → Cria um commit que desfaz um commit específico.  
- `git reset --soft <commit>` → Volta para um commit sem apagar mudanças.  
- `git reset --hard <commit>` → Volta para um commit apagando todas as mudanças posteriores.  

### 📦 **Trabalhando com repositórios remotos**  
- `git remote -v` → Lista os repositórios remotos configurados.  
- `git remote add origin <URL>` → Adiciona um repositório remoto.  
- `git remote remove <nome>` → Remove um repositório remoto.  

Se precisar de mais detalhes sobre algum comando, só perguntar! 🚀