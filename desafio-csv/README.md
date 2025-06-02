# 🧾 Desafio — Agente para Notas Fiscais

Este notebook permite realizar **perguntas em linguagem natural** sobre arquivos CSV contendo 100 notas fiscais públicas (cabeçalho e itens) do mês de janeiro de 2024.

---

## 🚀 Como usar

1. Crie um arquivo `.env` com sua chave da Groq (veja o exemplo em `.env.example`);
2. Rode o notebook em:
   - Google Colab (recomendado) — já instala tudo automaticamente;
   - VSCode ou Jupyter local — use `pip install -r requirements.txt` antes de executar;
3. Monte seu Google Drive para acessar os arquivos CSV;
4. Ajuste os caminhos dos arquivos:
```python
cabecalho_path = '/content/drive/MyDrive/SUA_PASTA/202401_NFs_Cabecalho.csv'
itens_path = '/content/drive/MyDrive/SUA_PASTA/202401_NFs_Itens.csv'
```
5. No final do notebook, digite suas perguntas como:

```
- Qual fornecedor recebeu o maior valor?
- Qual item teve maior volume entregue?
- Quais datas de emissão aparecem mais?
```

Digite `sair` para encerrar a interação.

---

## 📄 Arquivos

- `agente_nota_fiscal.ipynb` — notebook com a solução
- `.env.example` — exemplo de configuração com chave da API
- `requirements.txt` — pacotes necessários para execução
