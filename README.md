# Projeto-base Flask para Desenvolvimento de Sistemas

Uma base didática para começar projetos em grupo usando Python, Flask, templates Jinja2 e SQLite. O projeto traz cadastro, acesso simples e um CRUD de `records` somente como referência.

> Este material é introdutório: a tela de acesso não mantém uma sessão do usuário. Em projetos reais, autenticação deve ser implementada com cuidado.

## Preparação

Crie o ambiente virtual:

```bash
python -m venv .venv
```

Ative no Linux/macOS:

```bash
source .venv/bin/activate
```

Ative no Windows:

```bash
.venv\Scripts\activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o projeto:

```bash
python app.py
```

Depois, acesse: <http://127.0.0.1:5000>

Na primeira execução, o arquivo `database.db` e as tabelas `users` e `records` serão criados automaticamente.

## Organização

```text
app.py              rotas e regras simples da aplicação
database.py          conexão e criação do banco SQLite
templates/           páginas HTML com Jinja2
static/css/          estilos da interface
```

## O que você deverá modificar

1. Alterar o nome do sistema.
2. Alterar a descrição da página inicial.
3. Identificar a entidade principal do projeto.
4. Substituir ou adaptar o CRUD de `records`.
5. Criar os campos necessários.
6. Alterar o banco de dados.
7. Criar novas rotas.
8. Criar novos templates.
9. Implementar as funcionalidades específicas do projeto.
10. Melhorar a interface conforme necessário.

Por exemplo: uma biblioteca pode adaptar `records` para `livros`; uma clínica, para `pacientes`; uma oficina, para `veiculos`; e um estoque, para `produtos`.

## Próximos passos

* Adicionar uma nova tabela.
* Relacionar duas tabelas.
* Criar filtros e campo de busca.
* Criar uma página de detalhes.
* Validar campos e mostrar mensagens de erro.
* Melhorar a interface.
* Adicionar funcionalidades específicas do projeto.
