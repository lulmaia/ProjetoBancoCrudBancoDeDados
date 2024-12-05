# 🎓 Alunos que participaram do projeto
- **Victor Batista Passos**
- **Luís Gustavo Maia Cavalcanti Santos**

---

# 🎶 Sistema de Gerenciamento de Álbuns

Este é um projeto backend desenvolvido em **Node.js** utilizando **Express**, com um sistema CRUD para gerenciar álbuns musicais. O projeto permite criar, listar, atualizar e excluir álbuns, além de realizar buscas personalizadas.

---

## 🛠 Funcionalidades

- **🎵 Criar Álbuns**: Adicione novos álbuns ao banco de dados.
- **📜 Listar Álbuns**: Visualize todos os álbuns disponíveis.
- **✏️ Atualizar Álbuns**: Atualize as informações de um álbum existente.
- **🗑️ Excluir Álbuns**: Remova álbuns do banco de dados.
- **🔍 Busca Personalizada**: Filtre álbuns com base em critérios como título, artista ou gênero.

---

## 🚀 Como executar o projeto

### Pré-requisitos

- **Node.js** (v16 ou superior)
- **MySQL** configurado com uma tabela `albums` com as seguintes colunas:

  | Coluna        | Tipo          | Detalhes                       |
  |---------------|---------------|--------------------------------|
  | `id`          | INT           | AUTO_INCREMENT, PRIMARY KEY   |
  | `title`       | VARCHAR       |                               |
  | `artist`      | VARCHAR       |                               |
  | `genre`       | VARCHAR       |                               |
  | `release_date`| DATE          |                               |
  | `rating`      | FLOAT         |                               |

---

### Passos para rodar:

1. **Clone o repositório**:
   git clone https://github.com/lulmaia/ProjetoBancoCrudBancoDeDados
   cd seu-repositorio
   
Instale as dependências:
npm install

Inicie o servidor:
npm start
O servidor estará disponível em: http://localhost:3000

📄 Rotas da API
- Álbuns
Método	Endpoint	Descrição:
- POST	/albums	Cria um novo álbum.
- GET	/albums	Lista todos os álbuns.
- PUT	/albums/:id	Atualiza um álbum por ID.
- DELETE	/albums/:id	Exclui um álbum por ID.
- Busca Personalizada


🗂 Estrutura do Projeto
.
- ├── controllers/
- │   └── albumController.js    # Controladores CRUD
- ├── routes/
- │   └── albumRoutes.js        # Rotas da API
- ├── server.js                 # Configuração principal do servidor
- └── package.json              # Configurações e dependências

🖥 Tecnologias Utilizadas:
- Node.js
- Express
- MySQL
