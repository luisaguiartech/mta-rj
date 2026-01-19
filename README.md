# mta-rj
# MTA-RJ - Mapa do Tratamento Autismo RJ

App gratuito que ajuda mães de crianças autistas a encontrarem clínicas e hospitais no Rio de Janeiro — mesmo sem internet.

## 🎯 Objetivo

O **MTA-RJ** foi desenvolvido para facilitar o acesso a unidades de saúde especializadas em autismo e tratamento infantil no Rio de Janeiro. Ideal para mães que precisam de apoio, orientação e localização rápida — inclusive em áreas com pouca ou nenhuma internet.

## 🌐 Demonstração

👉 [Acesse o App](https://luisaguiartech.github.io/mta-rj)

## ✨ Funcionalidades

- **Mapa interativo** com unidades de saúde do Rio de Janeiro.
- **Geolocalização** para encontrar locais próximos.
- **Funcionamento offline-first**: dados carregados previamente continuam disponíveis sem internet.
- **Assistente virtual integrado** (chatbot) para tirar dúvidas e guiar o usuário.
- **PWA (Progressive Web App)**: pode ser instalado como um app no celular.
- **Design responsivo**: funciona em celulares, tablets e desktops.

## 🛠️ Tecnologias Utilizadas

- **HTML5, CSS3, JavaScript**
- **Leaflet.js** – para mapas interativos
- **Service Worker** – para funcionamento offline
- **Universal Chatbot** – componente leve e reutilizável
- **GitHub Pages** – hospedagem gratuita

## 📁 Estrutura do Projeto


## 🚀 Como Usar

1. Acesse o link: [https://luisaguiartech.github.io/mta-rj](https://luisaguiartech.github.io/mta-rj)
2. Permita a localização para encontrar unidades próximas.
3. Clique no botão 💬 para conversar com o assistente virtual.
4. Clique em "Adicionar à Tela Inicial" para instalar como PWA.

## 🧠 Dados das Unidades de Saúde

Os dados são carregados de `data/unidades.json`, com:
- Nome da unidade
- Endereço
- Especialidades
- Telefone
- Localização (latitude e longitude)

> Dados atualizados com base no [CNES – Cadastro Nacional de Estabelecimentos de Saúde](https://cnes.datasus.gov.br/).

## 🤖 Universal Chatbot

Componente reutilizável de assistente virtual integrado ao app. Responde perguntas comuns e guia o usuário pelas funcionalidades.
