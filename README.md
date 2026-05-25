# Regressão Ridge — IAA005 Estatística Aplicada II

**Universidade Federal do Paraná — SEPT**  
Especialização em Inteligência Artificial Aplicada  

---

## 📌 Objetivo

Modelar o **salário-hora feminino** (variável `lwage`) usando Regressão Ridge,
uma técnica de regressão regularizada que evita overfitting controlando 
o peso das variáveis explicativas.

---

## 📊 Base de Dados

- **Arquivo:** `trabalhosalarios.RData`
- **Observações:** 2.574 mulheres
- **Variável dependente:** `lwage` (log do salário-hora)
- **Variáveis explicativas:** 15 variáveis sobre a esposa e o marido

---

## 🔢 Resultados

| Métrica | Valor |
|---|---|
| Lambda ótimo | 0,02316 |
| RMSE | 0,44128 |
| R² | 0,28525 |
| Predição (US$/hora) | US$ 7,99 |
| IC 95% | US$ 6,12 a US$ 10,18 |

---

## 🚀 Como executar

1. Instale o R e o RStudio
2. Instale o pacote: `install.packages("glmnet")`
3. Coloque o arquivo `trabalhosalarios.RData` na mesma pasta
4. Execute o script `ridge.R`

---

## 📁 Arquivos

- `ridge.R` — código completo com todos os passos comentados
- `README.md` — documentação do projeto
