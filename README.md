# ong-gam
Website criado para a ONG GAM – Grupo de Artistas de Maricá, com o objetivo de divulgar suas atividades culturais e sociais, apresentar sua história, projetos e facilitar o contato com a comunidade. O projeto inclui páginas institucionais, galeria, formulário de contato e áreas estruturadas de forma simples e funcional.

**Acesse o site:**  
https://beatrizm.pythonanywhere.com/

---

## Tecnologias Utilizadas

- **Python 3**
- **Django**
- **HTML5**
- **CSS3**
- **JavaScript**
- **Bootstrap**
- **SQLite**
- **PythonAnywhere (Deploy)**

---

## ⚙️ Como Rodar o Projeto Localmente

### Clone o repositório
```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
cd SEU-REPOSITORIO
```

### Crie e ative o ambiente virtual
```bash
python -m venv venv
```

Linux/Mac:
```bash
source venv/bin/activate
```

Windows:
```bash
venv\Scripts\activate
```

### Instale as dependências
```bash
pip install -r requirements.txt
```

### Execute as migrações
```bash
python manage.py migrate
```

### Inicie o servidor
```bash
python manage.py runserver
```

Agora acesse:  
http://127.0.0.1:8000/

---

## Deploy no PythonAnywhere

O deploy foi realizado utilizando:

- Ambiente virtual configurado
- App Django integrada ao WSGI
- Arquivos estáticos configurados em **/static/**
- Banco SQLite hospedado no próprio serviço

---

Static files configurados em /static/

Banco SQLite
