
🌱 Keep Green - Daily GitHub Contributions

This repository aims to keep the GitHub contributions graph active by performing a daily automated commit using GitHub Actions.

---

🛠️ Functionality

- Automates a daily commit to a file named `verde.txt`.
- Ensures your GitHub contributions graph stays green.
- Execution is scheduled using a GitHub Actions cron job.

---

🚀 How It Works

The workflow `verde-diario.yml`, located in `.github/workflows/`, performs the following steps:

1. Clones the repository.
2. Updates the `verde.txt` file with the current date.
3. Commits and pushes with an automatic message.

---

📅 Execution Schedule

- Runs every day at 12:00 PM UTC (09:00 AM in Brazil UTC-3).
- Can also be triggered manually via GitHub (`workflow_dispatch`).

---

📂 Repository Structure

keep-green/
├── .github/
│   └── workflows/
│       └── verde-diario.yml
├── verde.txt
└── README.md

---

💡 Notes

- The repository should be **public** for commits to appear directly on your GitHub contribution graph.
- For private repositories, enable the setting:  
  `Settings > Profile > Include private contributions on my profile`.

---

🧪 Execution Example

Ping: 2025-06-30 12:00:00  
Ping: 2025-07-01 12:00:00

---

🧾 License

This project is licensed under the MIT License.





🌱 Keep Green - GitHub Verde Diário

Este repositório tem como objetivo manter o gráfico de contribuições do GitHub sempre ativo, com um commit automatizado diário via GitHub Actions.

---

🛠️ Funcionalidade

- Automatiza um commit todos os dias em um arquivo chamado `verde.txt`.
- Garante que o gráfico de contribuições diárias do GitHub continue "verde".
- Execução feita via agendamento (cron job) pelo GitHub Actions.

---

🚀 Como funciona

O workflow `verde-diario.yml`, localizado na pasta `.github/workflows/`, realiza os seguintes passos:

1. Clona o repositório.
2. Atualiza o arquivo `verde.txt` com a data atual.
3. Faz commit e push com a mensagem de atualização automática.

---

📅 Frequência de execução

- Executado diariamente às 09h da manhã (UTC-3), horário de Brasília.
- Pode ser acionado manualmente pelo GitHub (`workflow_dispatch`).

---

📂 Estrutura do repositório

keep-green/
├── .github/
│   └── workflows/
│       └── verde-diario.yml
├── verde.txt
└── README.md

---

💡 Observações

- O repositório deve ser **público** para que os commits sejam visíveis diretamente no gráfico de contribuições do perfil.
- Para repositórios privados, ative a opção:  
  `Settings > Profile > Include private contributions on my profile`.

---

🧪 Exemplo de execução

Ping: 2025-06-30 12:00:00
Ping: 2025-07-01 12:00:00

---

🧾 Licença

Este projeto é disponibilizado sob os termos da Licença MIT.
