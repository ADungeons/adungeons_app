# ADungeons App <img src="https://github.com/ADungeons/landingpage/blob/main/assets/images/logo_solid_bg.png" width="160" align="left">

O ADungeons App é uma aplicação que une RPG de mesa tradicional à Realidade Aumentada (AR), projetando miniaturas, monstros e armadilhas diretamente na mesa de jogo com uso de dispositivos móveis e QR Codes. O objetivo é democratizar o acesso a experiências imersivas, reduzindo o custo de entrada para mestres e jogadores.
<br>

> 🎲 "Transforme sua mesa em um campo de batalha épico com ADungeons e seu celular."

## 🔗 Acesse a Página

> **[ADungeons - Elevando o RPG ao próximo nível](https://adungeons.github.io/landingpage/)**

---

## 🚀 Tecnologias

- Unity com AR Foundation
- C# para lógica de aplicação
- GLTFast para modelos 3D
- Leitura de QR Code via plugin Unity
- Backend com Node.js + TypeScript
- Banco de Dados PostgreSQL
- Docker (para contêineres)

## 🎯 Funcionalidades Principais

- Visualização de personagens e inimigos via AR
- Campo de visão limitado por personagem (Jogador)
- Visão total e controle de elementos (Mestre)
- Sessões sincronizadas entre múltiplos dispositivos
- Leitura de QR Codes para posicionamento no mapa
- Transmissão da visão do mestre para espectadores

## 📦 Estrutura do Projeto

- `/app`: Aplicação Unity
- `/backend`: API de autenticação e gerenciamento de sessões
- `/assets`: Modelos 2D/3D e ilustrações
- `/docs`: Documentação técnica e artefatos do projeto

## 🛠️ Como rodar o projeto

```bash
# Clone este repositório
git clone https://github.com/ADungeons/adungeons_app.git
cd adungeons

# Instruções específicas do backend
cd backend
npm install
npm run dev

# Abrir a pasta /app no Unity (versão recomendada: 2023.3+ com suporte a AR Foundation)
