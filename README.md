# 🎮 Adivinhe - Jogo de Adivinhação de Palavras

Um jogo interativo de adivinhação de palavras desenvolvido com React e TypeScript. Teste suas habilidades tentando descobrir a palavra secreta com base em dicas!

## 🔗 Deploy

🚀 **[Acesse o projeto em produção aqui](#)** _(https://adivinhe-dev.netlify.app/)_

---

## 📋 Sobre o Projeto

**Adivinhe** é um jogo de palavras onde o jogador precisa descobrir uma palavra secreta com base em uma dica fornecida. A cada tentativa, você digita uma letra e o jogo indica se ela está presente na palavra. O desafio é descobrir a palavra completa antes de esgotar todas as tentativas disponíveis!

### ✨ Funcionalidades

- 🎯 Sistema de pontuação baseado em acertos
- 💡 Dicas para ajudar na descoberta da palavra
- 🔄 Reiniciar jogo a qualquer momento
- ✅ Validação de letras já utilizadas
- 📊 Contador de tentativas restantes
- 🎨 Interface moderna e responsiva
- ⚡ Feedback visual para letras corretas e incorretas

---

## 🛠️ Tecnologias Utilizadas

<div align="center">

![React](https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Modules-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

### Principais Dependências

- **React** - Biblioteca para construção de interfaces
- **TypeScript** - Superset JavaScript com tipagem estática
- **Vite** - Build tool e dev server ultrarrápido
- **CSS Modules** - Estilização com escopo local

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### Instalação

1. Clone o repositório
```bash
git clone https://github.com/EvelynnBR/adivinhe
```

2. Acesse a pasta do projeto
```bash
cd adivinhe
```

3. Instale as dependências
```bash
npm install
```

4. Execute o projeto em modo de desenvolvimento
```bash
npm run dev
```

5. Abra seu navegador e acesse `http://localhost:5173`

### Scripts Disponíveis

```bash
npm run dev      # Inicia o servidor de desenvolvimento
npm run build    # Gera a build de produção
npm run preview  # Visualiza a build de produção localmente
```

---

## 🎮 Como Jogar

1. **Leia a dica** fornecida no topo da tela
2. **Digite uma letra** no campo de palpite
3. **Clique em "Confirmar"** para verificar se a letra está na palavra
4. **Acompanhe suas tentativas** - você tem um número limitado de chances
5. **Descubra a palavra** antes que as tentativas acabem!

### Regras

- ✅ Cada letra correta revela sua posição na palavra
- ❌ Letras incorretas contam como tentativa
- 🔁 Não é possível usar a mesma letra duas vezes
- 🎯 O número de tentativas é baseado no tamanho da palavra + 5 tentativas extras

---

## 📁 Estrutura do Projeto

```
adivinhe/
├── src/
│   ├── components/      # Componentes reutilizáveis
│   │   ├── Header/
│   │   ├── Tip/
│   │   ├── Letter/
│   │   ├── Input/
│   │   ├── Button/
│   │   └── LettersUsed/
│   ├── utils/          # Utilitários e dados
│   │   └── words.ts    # Banco de palavras e dicas
│   ├── App.tsx         # Componente principal
│   └── main.tsx        # Ponto de entrada
├── public/             # Arquivos estáticos
└── package.json        # Dependências e scripts
```

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido com ❤️ por **Evelyn Bezerra**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evelynbrdev/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EvelynnBR)

---

<div align="center">
  <p>⭐ Se este projeto te ajudou, considere dar uma estrela!</p>
</div>
