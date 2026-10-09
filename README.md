# 🛒 Lista de Compras — React Native e Expo

## 📖 Sobre o Projeto

Este projeto consiste no desenvolvimento de um aplicativo de **Lista de Compras**, utilizando React Native, Expo e TypeScript.

A aplicação permite que o usuário adicione produtos à lista, informe a quantidade desejada, visualize os itens cadastrados e remova produtos quando necessário.

O objetivo da atividade é praticar conceitos fundamentais do desenvolvimento de aplicativos, trabalhando com componentes, estados, listas e interação com o usuário.

## 🎯 Objetivo

Desenvolver uma aplicação funcional de lista de compras, aplicando os conceitos de componentes e manipulação de dados no React Native.

## ⚙️ Funcionalidades

* 🛒 Exibir uma lista de produtos.
* ✏️ Informar o nome do produto.
* 🔢 Definir a quantidade desejada.
* ➕ Adicionar novos itens à lista.
* ❌ Remover produtos cadastrados.
* ⚠️ Validar o preenchimento do nome do produto.
* 🔄 Atualizar automaticamente a quantidade de itens exibidos.
* 🧺 Exibir uma mensagem quando a lista estiver vazia.

## 🧠 Conceitos Aplicados

### TextInput

Utilizado para permitir que o usuário digite o nome e a quantidade dos produtos.

### Button

Utilizado para executar a ação de adicionar um produto à lista.

### Arrays

Utilizados para armazenar e organizar os itens de compra, permitindo adicionar e remover elementos.

### FlatList

Componente do React Native utilizado para renderizar a lista de produtos de forma organizada.

### useState

Hook utilizado para controlar os estados da aplicação, como os dados digitados no formulário e os itens cadastrados.

### Componentes

A aplicação é dividida em componentes para facilitar a organização, a manutenção e a reutilização do código.

### TypeScript

Utilizado para definir os tipos de dados dos produtos e das propriedades dos componentes, ajudando a identificar erros durante o desenvolvimento.

## 📁 Estrutura do Projeto

```text
lista-de-compras/
├── components/
│   ├── Cabecalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── index.tsx
├── types.ts
├── app.json
├── package.json
├── tsconfig.json
└── babel.config.js
```

## 🧩 Descrição dos Componentes

* **Cabecalho.tsx:** apresenta o título e o subtítulo do aplicativo.
* **FormularioItem.tsx:** contém os campos para informar o produto e a quantidade, além do botão para adicionar itens.
* **ItemCompra.tsx:** apresenta os dados de cada produto e o botão para removê-lo.
* **ListaCompras.tsx:** utiliza o `FlatList` para exibir os produtos cadastrados.
* **App.tsx:** controla os dados da lista e as funções para adicionar e remover produtos.
* **types.ts:** define a estrutura dos dados de cada item de compra.

## 🛠️ Tecnologias e Ferramentas

* React Native
* Expo
* TypeScript
* JavaScript
* Visual Studio Code
* Node.js
* Expo Web

## ▶️ Como Executar o Projeto

### 1. Criar o projeto

Com o Node.js instalado, execute no terminal:

```bash
npx create-expo-app@latest lista-de-compras --template blank-typescript
```

### 2. Acessar a pasta

```bash
cd lista-de-compras
```

### 3. Instalar as dependências para a versão web

```bash
npx expo install react-dom react-native-web
```

### 4. Iniciar a aplicação

```bash
npx expo start --web
```

Após executar o comando, o aplicativo será iniciado no navegador.

## 🧪 Testes Realizados

Para verificar o funcionamento da aplicação, podem ser realizados os seguintes testes:

* Adicionar um produto informando nome e quantidade.
* Verificar se o novo produto aparece na lista.
* Tentar adicionar um produto sem informar o nome.
* Adicionar um produto sem informar a quantidade e verificar a quantidade padrão.
* Remover um produto utilizando o botão correspondente.
* Remover todos os produtos e verificar a mensagem de lista vazia.
* Conferir se o contador de itens é atualizado corretamente.

## 📚 Aprendizado

O desenvolvimento deste projeto permite compreender como criar interfaces interativas com React Native, manipular arrays, controlar estados com `useState` e exibir dados utilizando `FlatList`.

A atividade também contribui para o aprendizado da organização de componentes, da validação de formulários e da utilização do Expo para executar aplicações no navegador.

## 📦 Entrega do Projeto

Conforme as orientações da atividade, a entrega deve conter:

* Captura de tela da aplicação em funcionamento.
* Projeto compactado em arquivo ZIP.
* Pasta `node_modules` removida do arquivo ZIP.

## 👨‍💻 Autor

**Arthur Ribeiro**

**Curso:** Técnico em Desenvolvimento de Sistemas
