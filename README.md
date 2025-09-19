# 📋 Tarefas Simples — Projeto React Native com Expo Router

Este é um app básico feito com **React Native + Expo**, criado para praticar os conceitos de:

- **Estado Local (`useState`)**
- **Estado Global com Context API (tema claro/escuro)**
- **Navegação entre telas (Tabs + Stack)**
- **Listas com `FlatList`**
- **Formulário com validação**
- **Passagem de dados entre telas**
- **Feedback visual: `ActivityIndicator`, `Alert`**
- **Acessibilidade básica**

---

## 📱 O que o app faz

- **Home (Tarefas)**
  - Campo para digitar o nome da tarefa
  - Botão para **adicionar tarefa**
  - Se o campo estiver vazio, mostra um **alerta**
  - Lista com tarefas (FlatList)
    - **Favoritar**
    - **Remover**
    - **Ver detalhes**

- **Tela de Detalhe**
  - Mostra o ID, título e se a tarefa está favoritada
  - Botão para **voltar**

- **Config/Sobre**
  - Botão para **trocar o tema** (claro/escuro)
  - Texto explicando o app

---

## ✅ Requisitos da atividade (todos cumpridos)

- [x] Múltiplas telas: Home, Detalhe, Config/Sobre  
- [x] Navegação com **Tabs** e **Stack**  
- [x] Uso de **`useState`** para campos, listas e loading  
- [x] Atualização de estado (adicionar, remover, favoritar, mudar tema)  
- [x] Lista com **FlatList**  
- [x] Validação simples (campo obrigatório com `Alert`)  
- [x] Passagem de dados entre telas (`params`)  
- [x] Uso de `ActivityIndicator` (carregando)  
- [x] Layout com Flexbox  
- [x] Acessibilidade básica (`accessibilityLabel` em botões)

---

## 🛠️ Como rodar o projeto localmente

### Pré-requisitos:
- Ter o **Node.js** instalado
- Ter o app **Expo Go** no celular
- Ter o **Git** instalado (opcional)

### Passos:

```bash
# 1. Instalar dependências
npm install

# 2. Instalar bibliotecas de navegação
npm install expo-router @expo/vector-icons
npx expo install react-native-screens react-native-safe-area-context

# 3. Rodar o projeto
npm run start
