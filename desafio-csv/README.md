# 🧾 Desafio — Agente para Notas Fiscais

Este notebook permite realizar consultas em linguagem natural sobre arquivos CSV contendo 100 notas fiscais públicas.

---

## 🚀 Como usar

1. Crie um arquivo `.env` na raiz do desafio com a chave da API Groq (exemplo em `.env.example`);
2. Instale os pacotes com `pip install -r requirements.txt`;
3. Execute o notebook `agente_nota_fiscal.ipynb` em ambiente como Google Colab, Jupyter ou VSCode;
4. Use a última célula interativa para digitar perguntas como:

```
"Qual fornecedor recebeu o maior valor?"
"Qual item teve maior volume entregue?"
"Quais datas de emissão aparecem mais?"
```

Digite `sair` para encerrar a interação.

---

## 📄 Arquivos

- `agente_nota_fiscal.ipynb` — Notebook com a solução
- `.env.example` — Exemplo de arquivo de variáveis de ambiente
- `requirements.txt` — Pacotes necessários para execução
