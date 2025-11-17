# 🍰 Confeitaria Lumiere - Sistema de Controle de Estoque

Sistema desenvolvido para gerenciar o estoque de produtos da Confeitaria Lumiere, com cadastro, listagem, movimentação e análise de dados.

---

## ✨ Funcionalidades

1. **Cadastro de Produtos**  
   - Inserção de nome, preço, quantidade, categoria (MP, PP, EMB, INS) e unidade (KG, L, UN, CX).  

2. **Listagem de Produtos**  
   - Exibição em **tabela organizada** (`tabulate`).  
   - Produtos com **estoque baixo** (<5 unidades) destacados com ⚠.  

3. **Busca de Produtos**  
   - Pesquisa por **nome**, mostrando informações completas do produto.  

4. **Exclusão de Produtos**  
   - Remoção de produtos por **ID**, com confirmação de sucesso.  

5. **Movimentação de Estoque**  
   - Entradas (adicionar) e saídas (remover) de produtos.  
   - Movimentações registradas automaticamente com **data e hora**.  

6. **Giro de Estoque**  
   - Calcula `giro de estoque = total de saídas / estoque atual`.  
   - Resultados baseado total de saídas, estoque atual e última movimentação registrada.  

7. **Custo de Manutenção do Estoque**  
   - Calcula custo médio de manutenção com percentual configurável (default: 8%).
     (Percentual baseado em pesquisas sobre estoques reais) 

8. **Tempo Médio de Reposição**  
   - Mostra dias entre a primeira e última saída de cada produto.  

9. **Dashboard Gráfico**  
   - **Gráfico de linha:** entradas e saídas ao longo do tempo.  
   - **Gráfico de barra:** estoque atual por produto.  
   - (`Matplotlib`).  

---

## 🛠 Linguagem e Bibliotecas Utilizadas

- **Python 3.13**  
- **SQLite** (banco de dados local e leve)  
- **Matplotlib** (visualização gráfica)  
- **Tabulate** (tabelas organizadas no terminal)  

---

## 💡 Como executar:


