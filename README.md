# NotaXpert 📄

Extrator de dados de NF-e em lote com exportação para Excel.

## Estrutura do projeto

```
notaxpert/
├── app.py               ← Servidor Flask
├── requirements.txt     ← Dependências Python
├── Procfile             ← Configuração para Railway/Render
├── README.md
└── templates/
    └── index.html       ← Interface web
```

## Como publicar no Railway (gratuito)

1. Crie uma conta em https://railway.app (entre com o GitHub)
2. Crie um repositório no GitHub e faça upload de todos esses arquivos
3. No Railway: **New Project → Deploy from GitHub repo**
4. Selecione o repositório → o deploy é automático
5. Vá em **Settings → Networking → Generate Domain** para obter seu link público

## Como rodar localmente

```bash
pip install -r requirements.txt
python app.py
# Acesse: http://localhost:5000
```
