# SQL - LeetCode Easy

Repositório com resolução de atividades de SQL do LeetCode.

### Atividade 1 - LeetCode 1757: Recyclable and Low Fat Products

**O que a atividade pediu:**  
Achar o id dos produtos que são low fat E recicláveis ao mesmo tempo.

**Código SQL:**
```sql
SELECT product_id
FROM Products
WHERE low_fats = 'Y' AND recyclable = 'Y'
