# 🏦 Banco do Pobre

Este projeto é um sistema bancário simples em **Python**, que permite o cadastro de clientes, criação e gerenciamento de contas bancárias, autenticação, depósitos, saques e visualização de extratos. Projeto desenvolvido para o curso de python da [Digital Innovation One (DIO)](https://www.dio.me/)

Os dados de clientes e contas são armazenados em arquivos **JSON**, garantindo persistência entre execuções.

---

## 🚀 Funcionalidades

- **Cadastro de clientes** (com CPF, nome, endereço e cidade).
- **Autenticação de clientes** via CPF.
- **Criação de contas bancárias** com número sequencial único.
- **Depósitos** em contas.
- **Saques**, com limite diário configurado (R$ 500,00).
- **Extrato** com histórico de transações (depósitos e saques), incluindo data e hora de acordo com o fuso horário da cidade do cliente.
- **Persistência de dados** em arquivos JSON (`clientes.json` e `contas.json`).

---

## 🛠️ Tecnologias utilizadas

- [Python 3](https://www.python.org/)
- [JSON](https://docs.python.org/3/library/json.html) para armazenamento de dados
- [Decimal](https://docs.python.org/3/library/decimal.html) para cálculos monetários
- [pytz](https://pypi.org/project/pytz/) para fuso horário

---

## 📂 Estrutura do Projeto

Banco_melhorado/
│── script.py # Código principal do sistema
│── clientes.json # Base de dados de clientes
│── contas.json # Base de dados de contas
│── README.md # Documentação do projeto


---

## ▶️ Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Castilhos02/Banco_melhorado.git
   cd Banco_melhorado

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

==========

🎯 Próximas Melhorias

Interface gráfica com Tkinter

Integração com API de CEP

Histórico de transações por período

Transferências entre contas

👨‍💻 Autor

Desenvolvido por Douglas Castilho como projeto do curso de Python da DIO.

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
