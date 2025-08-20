
# my-github
## 💻 Tech Stack

**Front-End:**  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Back-End:**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Ferramentas:**  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Git Bash](https://img.shields.io/badge/Git--Bash-353535?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS--Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)


#                |

# 📌 Comandos importantes do Git

| Comando                     | Descrição                               |
|-----------------------------|-----------------------------------------|
| 🆕 `git init`               | Inicializa um repositório vazio         |
| 📥 `git clone <url>`        | Clona repositório remoto                |
| 🔎 `git status`             | Mostra estado da árvore de trabalho     |
| ➕ `git add <arq>`          | Adiciona mudanças ao stage              |
| 💾 `git commit -m "msg"`    | Registra snapshot das alterações        |
| 🚀 `git push`               | Envia commits ao GitHub                 |
| 🔄 `git pull`               | Sincroniza e integra mudanças remotas   |
| 🌿 `git branch`             | Lista ou cria branches                  |
| 🔀 `git merge`              | Mescla branches                         |
| 📜 `git log --oneline --graph` | Exibe histórico de commits compacto |

# 🔄 Guia de Pull Request (PR)

Um **Pull Request (PR)** é um pedido para que alterações feitas em uma **branch** sejam revisadas e integradas na branch principal (`main` ou `master`).  
Ele é essencial em projetos colaborativos, pois permite que o código seja **revisado, discutido e aprovado** antes do merge.

---

## ⚙️ Fluxo de um Pull Request

1. 🌱 **Criar uma nova branch**
   ```bash
   git checkout -b feature/nova-funcionalidade


✏️ Fazer alterações no código e salvar mudanças:
git add .
git commit -m "feat: adiciona nova funcionalidade X"

🚀 Enviar a branch para o repositório remoto

git push origin feature/nova-funcionalidade

🔃 Abrir o Pull Request no GitHub

Vá até o repositório no GitHub.

Clique em Compare & Pull Request.

Selecione a branch base (main) e a sua branch (feature/...).

Escreva um título claro e uma descrição explicando as mudanças.

👀 Revisão

Outros colaboradores revisam, comentam e sugerem melhorias.

Você pode ajustar o código se necessário.

✅ Merge

Quando aprovado, o PR é integrado à branch principal.

A branch pode ser apagada após o merge.

✅ Boas Práticas em Pull Requests

🔹 Commits pequenos e organizados → facilitam a revisão.

🔹 Título e descrição claros → explique o que mudou e por quê.

🔹 Referencie issues → se resolver um problema, use Closes #123.

🔹 Revise seu código antes de abrir o PR.

🔹 Teste suas mudanças → evite quebrar funcionalidades já existentes.