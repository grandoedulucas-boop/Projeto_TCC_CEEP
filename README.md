[README.md](https://github.com/user-attachments/files/28406268/README.md)
# ShildTech — Sistema de Agendamento de Suporte Técnico

Sistema web desenvolvido como Trabalho de Conclusão de Curso (TCC) no **CEEP**, com foco em agendamento de atendimentos para reparo de aparelhos eletrônicos.

---

## 💡 Sobre o Projeto

A **ShildTech** é uma plataforma que permite aos clientes agendar horários de atendimento nos Centros de Serviço, eliminando filas e tornando o processo mais prático. O sistema oferece cadastro de clientes e equipamentos, além de uma interface de gerenciamento interno.

---

## 🖥️ Demonstração

**Página inicial**
- Apresentação dos serviços oferecidos
- Canais de contato (WhatsApp, telefone, online)
- Navegação para login e cadastro

**Funcionalidades**
- Cadastro e login de clientes
- Cadastro de equipamentos vinculados ao cliente
- Painel de gerenciamento com listagem, edição e exclusão de registros (CRUD)

---

## 🛠️ Tecnologias Utilizadas

- **PHP** — lógica do servidor e processamento de formulários
- **MySQL / MariaDB** — banco de dados relacional
- **HTML & CSS** — estrutura e estilização das páginas
- **Font Awesome** — ícones da interface

---

## 🗄️ Banco de Dados

O banco `shildtech` possui 3 tabelas:

| Tabela | Descrição |
|--------|-----------|
| `pessoa` | Dados dos clientes (nome, contato, endereço, acesso) |
| `equipamentos` | Aparelhos cadastrados vinculados a um cliente |
| `tipo_pessoa` | Tipo de perfil do usuário (ex: admin, cliente) |

---

## 🚀 Como Executar

### Pré-requisitos
- PHP 8.x
- MySQL / MariaDB
- Servidor local: [XAMPP](https://www.apachefriends.org/) ou [WAMP](https://www.wampserver.com/)

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/grandoedulucas-boop/Projeto_TCC_CEEP.git
```

1. Importe o arquivo `shildtech/BD/shildtech.sql` no phpMyAdmin
2. Coloque a pasta `shildtech` dentro de `htdocs` (XAMPP) ou `www` (WAMP)
3. Acesse `http://localhost/shildtech/codigos/index.php` no navegador

---

## 👥 Autores

Desenvolvido por **Eduardo Grando** e **Gabryel Olavo** — Turma CEEP · 2024
