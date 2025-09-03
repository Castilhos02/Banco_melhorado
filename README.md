# 🏦 Banco do Pobre

Um projeto que simula operações bancárias básicas, desenvolvido em **Python** como parte do curso da [Digital Innovation One (DIO)](https://www.dio.me/). Este sistema explora conceitos fundamentais de programação, como estruturas de dados, funções, loops e manipulação de arquivos.

---

## 📌 Funcionalidades

- 💰 **Depósito**
- 💸 **Saque** (com limite diário de R$ 500 e máximo de 3 saques por dia)
- 📄 **Extrato** (exibe todas as movimentações e saldo atual)
- 👤 **Cadastro de usuários**
- 🏢 **Criação de contas correntes** (vinculadas a usuários)
- 💾 **Persistência de dados** (em arquivo JSON)

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- JSON para armazenamento de dados
- Biblioteca `datetime` para registro de transações

---

## 📦 Estrutura do Projeto

banco_do_pobre/ │ ├── main.py # Programa principal ├── dados.json # Arquivo de armazenamento (gerado automaticamente) ├── README.md # Este arquivo └── requirements.txt # Dependências (se necessário)


---

## 🚀 Como Executar

Clone este repositório:

```bash
git clone https://github.com/seu-usuario/banco-do-pobre.git

🧠 Conceitos Aplicados
✅ Estruturas de controle (if, while, for)

✅ Funções e modularização

✅ Listas e dicionários

✅ Manipulação de arquivos (JSON)

✅ Validação de inputs do usuário

✅ Formatação de strings e números

📝 Exemplo de Uso

=============== MENU ===============
[1] Depositar
[2] Sacar
[3] Extrato
[4] Criar Usuário
[5] Criar Conta
[6] Listar Contas
[7] Sair
====================================
====================================
🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para:

Reportar bugs

Sugerir novas funcionalidades

Fazer pull requests

📄 Licença
Este projeto é parte do curso da DIO e está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

👨‍💻 Autor
Desenvolvido por Douglas Castilho como projeto do curso de Python da DIO.

🎯 Próximas Melhorias
Interface gráfica com Tkinter

Integração com API de CEP

Histórico de transações por período

Transferências entre contas

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
