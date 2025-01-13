# Validação de CPF com Azure Functions

Este projeto é uma **Azure Function** desenvolvida para validar números de CPF. Ele foi criado como parte do **Bootcamp AZ-204** da **DIO (Digital Innovation One)**, com o objetivo de aplicar conceitos de **Serverless Computing** e boas práticas no desenvolvimento em nuvem.

---

## 📋 Descrição do Projeto

A função `httpValidaCpf` é uma API HTTP que valida números de CPF enviados via requisição. Ela verifica se o número informado é válido com base nas regras oficiais de validação de CPF no Brasil.

---

## 🛠️ Tecnologias Utilizadas

- **Azure Functions**: Computação serverless.
- **C#**: Linguagem utilizada para implementar a lógica.
- **Visual Studio Code**: IDE para desenvolvimento.
- **Azure CLI**: Para deploy e gerenciamento de recursos.
- **.NET Core**: Framework utilizado na construção do projeto.

---

## 🚀 Funcionalidades

- **Validação de CPF**: Recebe um número de CPF via requisição HTTP e retorna:
  - **200 OK**: Se o CPF é válido.
  - **400 Bad Request**: Se o CPF é inválido ou a entrada não está no formato correto.

---

## 🔧 Como Executar o Projeto Localmente

### Pré-requisitos
- **Azure Functions Core Tools**: Para executar Azure Functions localmente.
- **.NET Core SDK**: Para compilar e executar o projeto.
- **Git**: Para clonar o repositório.
- **Azure CLI**: (Opcional) Para gerenciar a publicação na nuvem.

### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/HandsOn-ServlessValidaCPF.git
   cd HandsOn-ServlessValidaCPF/httpValidaCpf
2. Instale as dependências:
   ```bash
   dotnet restore
3. Execute a função localmente:
   ```bash
   func start
4. Teste a API em http://localhost:7071/api/httpValidaCpf

