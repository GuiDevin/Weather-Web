# 🌤️ Weather Web

Aplicação web para consulta de previsão do tempo em tempo real, com busca por nome de cidade usando a API do OpenWeatherMap.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenWeather](https://img.shields.io/badge/OpenWeatherMap-API-orange?style=for-the-badge)

## 🔗 Demo

👉 [Acesse o projeto no GitHub Pages](https://guidevin.github.io/Weather-Web)

## ✨ Funcionalidades

- 🔍 Busca de clima por nome de cidade
- 🌡️ Temperatura atual com ícone dinâmico de condição climática
- 🔺 Temperatura máxima e mínima do dia
- 💧 Umidade do ar
- 💨 Velocidade do vento
- 📍 Exibição do nome e país da cidade encontrada
- ⚠️ Alerta para cidades não encontradas

## 🛠️ Tecnologias

- **HTML5** — estrutura da página
- **CSS3** — estilização e layout
- **JavaScript** — lógica e consumo de API
- **[OpenWeatherMap API](https://openweathermap.org/api)** — dados meteorológicos em tempo real
- **[Font Awesome 6](https://fontawesome.com/)** — ícones de temperatura, vento e humidade

## 📁 Estrutura do projeto

```
📦 Weather-Web
 ┣ 📂 src
 ┃ ┣ 📂 styles
 ┃ ┃ └── 📄 styles.css
 ┃ └── 📂 javascript
 ┃     └── 📄 script.js
 ┣ 📄 index.html
 └── 📄 README.md
```

## 🚀 Como executar localmente

```bash
# Clone o repositório
git clone https://github.com/GuiDevin/Weather-Web.git

# Acesse a pasta do projeto
cd Weather-Web
```

Abra o arquivo `index.html` no navegador, ou use a extensão **Live Server** no VS Code.

> ⚠️ **Importante:** você precisa de uma chave de API gratuita do [OpenWeatherMap](https://openweathermap.org/api). Insira-a no arquivo `src/javascript/script.js`.

## 🔑 Como obter a chave de API

1. Acesse [openweathermap.org](https://openweathermap.org/) e crie uma conta gratuita
2. Vá em **My API Keys** e copie sua chave
3. No arquivo `src/javascript/script.js`, substitua o valor da variável pela sua chave:
```js
const apiKey = "SUA_CHAVE_AQUI";
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

Feito por [GuiDevin](https://github.com/GuiDevin) 🚀
