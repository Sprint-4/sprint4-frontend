
# 🏥 Frontend – Sprint 4  
**Projeto:** Challenge Hospital das Clínicas  
**Curso:** Análise e Desenvolvimento de Sistemas – FIAP  
**Equipe:** BDB Team  

link do video - https://youtu.be/kQmOOXfxa30

link do repositorio - https://github.com/Sprint-4/sprint4-frontend.git

---

## 👥 Integrantes
- **Pedro Henrique Luiz Alves Duarte** – RM563405  
- **Guilherme Macedo Martins** – RM562396  
 
---

## 🚀 Sobre o Projeto
O **Frontend da Sprint 4** faz parte do desafio integrador da FIAP com o **Hospital das Clínicas**, onde o objetivo é desenvolver uma aplicação web intuitiva e funcional para apoiar o sistema hospitalar.  

A solução tem foco em **acessibilidade digital**, **usabilidade** e **integração com o backend em Java + Oracle**, criado também pela equipe BDB.

---

## 💻 Tecnologias Utilizadas
- **HTML5**  
- **CSS3 (Tailwind CSS)**  
- **JavaScript (ES6+)**  
- **Node.js & npm**  
- **React / Vite** *(dependendo do setup do grupo)*  
- **Axios (para integração com API Java)**  

---

## 🧠 Principais Funcionalidades
- 📋 **Cadastro de Pacientes**  
- 🩺 **Listagem de Consultas e Prontuários**  
- 🧑‍⚕️ **Gestão de Médicos e Especialidades**  
- 📞 **Atendimento via Teleconsulta (simulação)**  
- ⚙️ **Integração completa com API REST do Backend**

---

## 🔗 Integração com Backend
- **API Java (Quarkus)** hospedada no Render  
- **Banco de Dados:** Oracle  
- Comunicação via **endpoints RESTful**  
- Testes realizados com **Swagger UI**

Este projeto é uma aplicação web **SPA (Single Page Application)** completa, desenvolvida como parte do **Challenge de Front-End da FIAP (Sprint 4)**.  
O objetivo principal é consumir **100% uma API RESTful de Java (Quarkus)**, fornecendo uma **interface administrativa completa** para gerenciar 6 entidades do sistema:

> Médicos, Pacientes, Consultas, Convênios, Endereços e Especialidades.

O projeto implementa um **CRUD (Create, Read, Update, Delete)** completo para cada uma dessas entidades, com:
- Tratamento de erros (como `429 Too Many Requests` e `503 Service Unavailable`)
- Validação de formulários
- Carregamento de dados assíncrono (fetch + retry)
- Feedback visual para ações do usuário

---

## 🚀 Informações para Manipular o Sistema

Esta seção contém todos os detalhes técnicos para entender, instalar e executar o projeto.

### ✨ Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

- **React** → Biblioteca para construção de interfaces de usuário.
- **Vite** → Ferramenta de build moderna e ultrarrápida para desenvolvimento front-end.
- **TypeScript** → Superset do JavaScript que adiciona tipagem estática, aumentando a robustez do código.
- **Tailwind CSS** → Framework de CSS utility-first para criar designs customizados rapidamente.
- **React Router DOM** → Gerenciamento de rotas (SPA).
- **React Hook Form** → Validação e gerenciamento de estado dos formulários de CRUD.


### 🖼️ Imagens e Ícones

O projeto utiliza imagens locais para exibir as fotos dos integrantes (na rota `/integrantes`).  
As imagens estão em:

```
src/assets/img/
```

E são importadas diretamente nos componentes React, garantindo que o **Vite** as processe corretamente durante o build.

---

### 📁 Estrutura de Pastas do Projeto

A estrutura segue o padrão **Vite + React**, com foco na componentização de CRUDs e rotas:

```
challenge-front/
├── src/
│   ├── assets/
│   │   └── img/                     # Imagens (fotos dos integrantes)
│   ├── componentes/                 # Componentes reutilizáveis (Header, Menu, Footer)
│   │   ├── Cabecalho/
│   │   ├── Menu/
│   │   └── Rodape/
│   ├── rotas/                       # Componentes de Página (SPA)
│   │   ├── AdminGeral/              # Página única com os 6 CRUDs
│   │   │   ├── index.tsx
│   │   │   ├── CrudMedico.tsx
│   │   │   ├── CrudPaciente.tsx
│   │   │   ├── CrudConsulta.tsx
│   │   │   ├── CrudConvenio.tsx
│   │   │   ├── CrudEndereco.tsx
│   │   │   └── CrudEspecialidade.tsx
│   │   ├── contato/
│   │   ├── error/
│   │   ├── faq/
│   │   ├── home/
│   │   ├── integrantes/
│   │   ├── marcarConsulta/
│   │   └── tutorial/
│   ├── utils/                       # Funções auxiliares (api.ts com fetchWithRetry)
│   │   └── api.ts
│   ├── App.tsx                      # Componente principal (layout geral)
│   ├── index.css                    # CSS global (importa Tailwind)
│   └── main.tsx                     # Ponto de entrada (React Router)
├── .gitignore
├── index.html                       # Arquivo HTML principal
├── package.json                     # Dependências e scripts
├── README.md                        # Documentação do projeto
└── vite.config.ts                   # Configurações do Vite (Proxy da API)
>>>>>>> develop
```

O código-fonte completo do projeto, incluindo todo o histórico de commits e o Gitflow, está disponível no GitHub:
=======
## ⚙️ Como Executar o Projeto

### 🔧 Pré-requisitos
- Node.js e npm instalados  
- Git configurado  

### ▶️ Passos
```bash
# Clonar o repositório
git clone https://github.com/Sprint-4/sprint4-frontend.git

# Entrar na pasta
cd Frontend-sprint4

# Instalar dependências
npm install

# Rodar o projeto
npm run dev
```

---

## 📸 Protótipos e Telas
*(Adicione aqui prints das principais telas do sistema ou link para o Figma)*

---

## 🧩 Contribuição
Sinta-se à vontade para contribuir com melhorias, ajustes ou sugestões!  
Basta criar uma branch, fazer suas alterações e abrir um pull request. 💡  

---

## 📜 Licença
Projeto acadêmico desenvolvido para fins educacionais – FIAP © 2025  
Todos os direitos reservados à equipe **BDB**.  



---

### 🎥 Vídeo de Apresentação no YouTube

O vídeo demonstra o sistema completo — incluindo a responsividade, a navegação entre as páginas e o funcionamento da área administrativa com os 6 CRUDs integrados à API Java em tempo real.



---

> 📘 Desenvolvido com dedicação para o Challenge da FIAP — Sprint 4 – 2025.
>>>>>>> develop
