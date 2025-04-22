# 🤖 Node-RED Telegram Bot - IBM Cloud Integration

Este projeto é um bot criado com **Node-RED** e integrado ao **Telegram**, hospedado na **IBM Cloud**. Ele permite interações automatizadas com usuários via Telegram, utilizando fluxos visuais e integrações inteligentes.

---

## 📦 Tecnologias Utilizadas

- [Node-RED](https://nodered.org/) - Plataforma de programação visual baseada em fluxos
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [IBM Cloud](https://www.ibm.com/cloud) - Hospedagem e orquestração do bot
- [Node.js](https://nodejs.org/) - Ambiente de execução JavaScript
- [node-red-contrib-telegrambot](https://flows.nodered.org/node/node-red-contrib-telegrambot) - Plugin Node-RED para Telegram

---

## 🚀 Como Funciona

1. O bot foi criado no **BotFather** do Telegram e sua `API Token` foi conectada ao Node-RED.
2. Fluxos personalizados foram criados para interpretar mensagens e executar ações automatizadas.
3. O Node-RED foi implantado no IBM Cloud, permitindo disponibilidade contínua do bot.
4. O bot pode responder a comandos como `/start`, textos específicos, botões interativos e muito mais.

---

## ⚙️ Como Executar Localmente

> Requisitos:
> - Node.js instalado
> - Docker (opcional)
> - Conta no Telegram
> - API Token do BotFather

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
2. Instale o Node-RED e o plugin do Telegram
bash
Copy
Edit
npm install -g node-red
npm install node-red-contrib-telegrambot
3. Execute o Node-RED
bash
Copy
Edit
node-red
Acesse http://localhost:1880 e importe os fluxos disponíveis em flows.json.

4. Configure o Bot
No nó telegram receiver e telegram sender, insira a API Token do seu bot Telegram.

☁️ Hospedagem no IBM Cloud
Para hospedar na IBM Cloud:

Crie uma instância Node-RED usando o serviço "Node-RED Starter" na IBM Cloud.

Importe seus fluxos na interface da IBM.

Configure variáveis de ambiente com sua API Token.

📁 Estrutura do Projeto
bash
Copy
Edit
.
├── flows.json           # Fluxo exportado do Node-RED
├── README.md            # Este documento
└── .env.example         # Exemplo de configuração do bot
💡 Exemplos de Comandos

Comando	Função
/start	Inicia o bot e envia mensagem de boas-vindas
/ajuda	Mostra lista de comandos disponíveis
/info	Mostra informações úteis sobre o bot
🤝 Contribuições
Contribuições são bem-vindas! Sinta-se livre para abrir issues ou enviar pull requests com melhorias.

📄 Licença
Este projeto está licenciado sob a MIT License.

✨ Autor
Desenvolvido por Seu Nome 🚀

php
Copy
Edit

Se quiser que eu substitua `"Seu Nome"` e `"seu-usuario"` com seu nome real e usuário do GitHub, só avisar!







