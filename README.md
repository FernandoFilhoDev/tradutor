# 🌍 Tradutor

Mini projeto de tradutor de textos feito com **HTML, CSS e JavaScript puro**, que usa a API gratuita [MyMemory](https://mymemory.translated.net/) para traduzir entre 5 idiomas.

## ✨ Funcionalidades

- Tradução entre **Português, Inglês, Espanhol, Italiano e Japonês**
- Escolha do idioma de origem e de destino
- Duas caixas de texto lado a lado: entrada e tradução
- Opções de idioma geradas dinamicamente com JavaScript
- Layout centralizado e responsivo, com Flexbox

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox)
- JavaScript (manipulação do DOM e Fetch API)
- [API MyMemory](https://mymemory.translated.net/doc/spec.php)

## 📁 Estrutura do projeto

```
tradutor/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 Como executar

1. Clone o repositório:

```bash
   git clone https://github.com/seu-usuario/tradutor.git
```

2. Entre na pasta do projeto:

```bash
   cd tradutor
```

3. Abra o arquivo `index.html` no navegador.
4. Escolha os idiomas, digite o texto e clique em **TRADUZIR**.

Não é necessário instalar nada nem configurar chave de API.

## 📸 Preview

![Preview do projeto](preview.png)

## ⚠️ Limitações

A versão gratuita da API MyMemory aceita cerca de 500 caracteres por requisição e tem um limite diário de uso.

## 📚 O que aprendi

- Criar elementos dinamicamente com `insertAdjacentHTML`
- Consumir uma API com `fetch` e tratar a resposta em JSON
- Montar layouts com Flexbox
- Enviar texto com segurança na URL usando `encodeURIComponent`

## 🔮 Próximas melhorias

- [ ] Botão para inverter os idiomas
- [ ] Botão para copiar a tradução
- [ ] Mais idiomas
- [ ] Contador de caracteres

## 👤 Autor

Feito por **Fernando**

[GitHub](https://github.com/seu-usuario)
