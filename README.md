# 🎄 Natal Mágico AI

O **Natal Mágico AI** é uma aplicação web progressiva (PWA) que utiliza inteligência artificial para transformar fotos em cenas de Natal, integrando rostos em bolas de natal de vidro hiper-realistas.

## 🚀 Funcionalidades

* **Geração de Imagens com IA**: Utiliza o modelo Gemini para criar imagens festivas.
* **Prompt de Alta Fidelidade**: Inclui configurações projetadas para preservação facial absoluta e detalhes em 8K.
* **Experiência PWA**: Pode ser instalado e exibido como um aplicativo independente (standalone).
* **Privacidade e Segurança**: A chave da API é armazenada localmente no navegador do usuário.
* **Suporte Offline**: Utiliza Service Workers para cache de ativos essenciais como Tailwind CSS e o próprio HTML.

## 🛠️ Tecnologias Utilizadas

* **Frontend**: HTML5, Tailwind CSS e JavaScript Vanilla.
* **IA**: API do Google Gemini (modelo `gemini-2.5-flash-image-preview`).
* **PWA**: Web App Manifest e Service Workers.

## ⚙️ Como Configurar

1.  **Obtenha uma Chave de API**:
    * Gere sua chave no [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  **Configuração no App**:
    * Abra a aplicação, clique no ícone de engrenagem e salve sua chave.
3.  **Uso**:
    * Faça upload de até 3 fotos (JPG/PNG).
    * Clique em "Criar Magia" para gerar sua imagem personalizada.

## 📂 Estrutura do Repositório

* `index.html`: Interface do usuário e lógica de integração com a IA.
* `manifest.json`: Manifesto para instalação como PWA.
* `sw.js`: Service Worker para estratégias de cache.
* `README.md`: Documentação do projeto.
