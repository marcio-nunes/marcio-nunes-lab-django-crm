# CRM

Projeto criado como exercício da plataforma de ensino open education Digital Innovation One. Trata-se de um projeto básico para elaboração de um CRUD de Cliente utilizando Python, Django e Bootstrap com autenticação.

### Instalar as dependências

```CMD
pip install -r requirements.txt
```

### Criar as tabelas

```CMD
python manage.py migrate
```

### Criar usuário admin

```CMD
python manage.py createsuperuser
```

### Levantar a aplicação

```CMD
python manage.py runserver
```

### Configuração de variáveis

Criar arquivo .env na raíz do projeto com as variáveis do arquivo de exemplo em contrib/env_sample. Não esquecer de configurar as variáveis no servidor.
