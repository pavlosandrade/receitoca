# 🍳 Receitoca

> O **Receitoca** é um aplicativo de receitas que permite ao usuário salvar, organizar e acessar suas receitas favoritas em qualquer dispositivo.  
> O sistema conta com autenticação, categorias personalizadas e uma experiência fluida tanto no mobile quanto no backend administrativo.  

---

## 📖 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)  
- [Funcionalidades](#-funcionalidades)  
- [Arquitetura](#-arquitetura)  
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)  
- [Instalação](#-instalação)  
- [Como Usar](#-como-usar)  
- [Estrutura de Pastas](#-estrutura-de-pastas)  
- [Próximos Passos](#-próximos-passos)  
- [Contribuição](#-contribuição)  
- [Licença](#-licença)  

---

## 📌 Sobre o Projeto
O **Receitoca** foi criado para resolver um problema comum: como organizar e acessar receitas de forma prática e acessível em qualquer dispositivo.  

Com ele, os usuários podem:  
- Criar uma conta segura  
- Organizar receitas em categorias como **Doces**, **Salgados**, **Massas**, etc.  
- Acessar suas receitas salvas em qualquer dispositivo (graças ao backend em C#)  
- Ter uma experiência moderna e intuitiva no app mobile  

---

## ✨ Funcionalidades
- ✅ Cadastro e login de usuários com autenticação JWT  
- ✅ CRUD completo de receitas  
- ✅ Criação de categorias personalizadas  
- ✅ Upload e galeria de imagens para cada receita  
- ✅ Visualização responsiva das receitas  
- ✅ Dashboard para gerenciar receitas (backend)  

---

## 🏗 Arquitetura
A arquitetura do projeto segue o padrão **frontend + backend + banco de dados**:  

- **Frontend (mobile):** React Native  
- **Backend (API):** C# com .NET 8  
- **Banco de Dados:** SQL Server (pode ser adaptado para PostgreSQL/SQLite)  
- **Autenticação:** JWT  
- **Comunicação:** REST (JSON)  

Fluxo:  
1. O usuário acessa o app no celular (React Native).  
2. As requisições são enviadas ao backend em C#.  
3. O backend consulta o banco de dados e retorna os dados via API.  
4. O usuário vê suas receitas e categorias no aplicativo.  

---

## 🛠 Tecnologias Utilizadas

### **Frontend**
- [React Native](https://reactnative.dev/)  
- [Expo](https://expo.dev/) *(opcional)*  
- [Axios](https://axios-http.com/) (requisições HTTP)  
- [React Navigation](https://reactnavigation.org/)  

### **Backend**
- [C# .NET 8](https://dotnet.microsoft.com/)  
- [ASP.NET Web API](https://learn.microsoft.com/aspnet/core/)  
- [Entity Framework Core](https://learn.microsoft.com/ef/)  

### **Banco de Dados**
- SQL Server  

### **Outros**
- Git/GitHub para versionamento  
- Docker *(opcional para deploy)*  

---

## ⚙️ Instalação

### 🔹 Pré-requisitos
- Node.js >= 18  
- .NET SDK >= 8.0  
- Banco de dados SQL Server instalado  
- Git  

### 🔹 Passo a passo

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/receitoca.git
cd receitoca
