# 🔢 Sorteador de Números

Aplicação web para sortear números aleatórios dentro de um intervalo definido pelo usuário, desenvolvida como exercício prático do curso de **Lógica de Programação** da [Alura](https://www.alura.com.br/).

## 📋 Sobre o projeto

O Sorteador de Números permite que o usuário informe a quantidade de números desejada e o intervalo (mínimo e máximo), exibindo os resultados na tela. Também conta com um botão de reiniciar para limpar os resultados e começar um novo sorteio.

> O HTML e o CSS foram fornecidos pela Alura como material de apoio. O foco do exercício foi o desenvolvimento da lógica em JavaScript.

## 🚀 Funcionalidades

- Definir a quantidade de números a sortear
- Definir o intervalo mínimo e máximo
- Exibir os números sorteados na tela
- Reiniciar o sorteio limpando os resultados

## 🛠️ Tecnologias utilizadas

- HTML
- CSS
- JavaScript

## 📁 Estrutura do projeto

```
sorteadorNumeros/
├── img/          # Imagens da aplicação
├── app.js        # Lógica em JavaScript
├── index.html    # Página principal
└── style.css     # Estilos da aplicação
```

## ▶️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/M13Guilherme/sorteadorNumeros.git
```

2. Abra o arquivo `index.html` no navegador.

> Dica: use a extensão **Live Server** do VS Code para facilitar o desenvolvimento.

## 🌐 Deploy

O projeto está disponível em: [sorteador-numeros-murex.vercel.app](https://sorteador-numeros-murex.vercel.app)

## 📚 Aprendizados

- Captura de valores de inputs com `document.getElementById`
- Geração de números aleatórios com `Math.random()` e `Math.floor()`
- Manipulação do DOM para exibir resultados dinamicamente
- Lógica de validação de entradas do usuário
