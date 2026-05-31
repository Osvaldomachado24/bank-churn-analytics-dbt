# 🏦 Bank Churn Analytics — Pipeline End-to-End com DBT

## 📋 Descrição
Projecto completo de análise de Churn Bancário utilizando 
o Modern Data Stack.

## 🛠️ Stack Tecnológico
- Python (Pandas, SQLAlchemy, getpass)
- PostgreSQL 15
- DBT (Data Build Tool) 1.12
- Power BI

## 🔄 Pipeline
CSV → Python (ETL) → PostgreSQL → DBT (6 modelos) → Power BI

## ⚙️ DBT — Modern Data Stack
6 modelos SQL criados automaticamente com 1 comando:
- vw_visao_geral
- vw_churn_perfil
- vw_churn_por_pais
- vw_churn_por_produto
- vw_analise_saldo
- vw_retencao_clientes

## 💡 Insights Principais
- Alemanha lidera com 32% de Churn
- 1 em cada 5 clientes abandona o banco (20,4%)
- Mulheres abandonam mais que os homens (25% vs 16%)
- Sénior (46-55) é o grupo de maior risco — 51% de Churn
- Clientes inactivos têm o dobro da probabilidade de abandonar

## 📊 Dashboard Power BI
5 KPIs + 6 visuais analíticos conectados directamente 
ao PostgreSQL via views DBT

## 👤 Autor
Osvaldo Machado | Analytics Engineer
github.com/Osvaldomachado24
