# Formulario eletronico de consulta ao Quadro Geral MPPE

## Como executar

1. Instale as dependencias:

```powershell
pip install -r requirements.txt
```

2. Rode o app:

```powershell
streamlit run app_consulta_mppe.py
```

## O que o app faz

- Carrega as planilhas oficiais do MPPE:
  - 1a Entrancia
  - 2a Entrancia
  - 3a Entrancia
  - 2a Instancia
- Permite escolher a base (quadro) e depois o criterio: `Circunscricao`, `Municipio`, `Atuacao` ou `Atribuicao`.
- Exibe tabela filtrada com os campos:
  - `Circunscricao`
  - `Municipio`
  - `Cargo`
  - `Atribuicao`
  - `Atuacao`
  - `Promotor de Justica`
