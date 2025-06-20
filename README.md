# 🛳️ Análise de Dados - Titanic

## 🔗 Fonte do Dataset

- [Titanic - Machine Learning from Disaster | Kaggle](https://www.kaggle.com/c/titanic/data)  
- Alternativa (arquivo CSV direto):  
  - [titanic.csv - GitHub (Data Science Dojo)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 📄 Descrição do Dataset

O dataset **Titanic** é um dos mais famosos no universo de dados, amplamente utilizado para ensinar ciência de dados, estatística e machine learning.

Ele contém informações sobre os passageiros do navio **RMS Titanic**, que naufragou em 1912. O objetivo é analisar os dados para entender os perfis dos passageiros, padrões de sobrevivência e fatores que impactaram as chances de sobreviver.

### ✅ As colunas do dataset são:

| Coluna        | Descrição                                                               |
|----------------|------------------------------------------------------------------------|
| **PassengerId** | Identificador único de cada passageiro.                              |
| **Survived**    | Sobrevivência (0 = Não sobreviveu, 1 = Sobreviveu).                  |
| **Pclass**      | Classe da passagem (1 = Primeira, 2 = Segunda, 3 = Terceira).        |
| **Name**        | Nome completo do passageiro.                                         |
| **Sex**         | Sexo do passageiro (male, female).                                  |
| **Age**         | Idade em anos.                                                       |
| **SibSp**       | Número de irmãos/cônjuges a bordo.                                  |
| **Parch**       | Número de pais/filhos a bordo.                                      |
| **Ticket**      | Número do bilhete.                                                   |
| **Fare**        | Tarifa paga pela passagem.                                           |
| **Cabin**       | Número da cabine.                                                    |
| **Embarked**    | Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton). |

---

## 🎯 Objetivo da Análise

Realizar uma análise exploratória e descritiva dos dados para responder questões de negócio e entender padrões relacionados aos perfis dos passageiros e suas chances de sobrevivência.

---

## 📌 Demandas para Resolver com Pandas

1. **Qual a proporção geral de sobreviventes no dataset?**  
2. **Quantos passageiros há em cada classe (`Pclass`)?**  
3. **Qual a média, mediana e desvio padrão da idade dos passageiros?**  
4. **Quantos passageiros têm idade desconhecida (`missing`)?**  
5. **Qual a taxa de sobrevivência por gênero (`Sex`)?**  
6. **Qual a taxa de sobrevivência por classe (`Pclass`)?**  
7. **Qual o ticket médio pago (`Fare`) por classe?**  
8. **Existe alguma correlação entre idade e sobrevivência?**  
9. **Qual a média de familiares a bordo (`SibSp + Parch`) por passageiro?**  
10. **Quantos passageiros embarcaram em cada porto (`Embarked`)?**  
11. **Qual o perfil médio dos passageiros que sobreviveram?**  
12. **Quantos passageiros viajaram sozinhos (sem familiares)?**  
13. **Qual a taxa de sobrevivência entre passageiros que viajaram sozinhos vs. com familiares?**  
14. **Quais os 5 nomes mais comuns entre os passageiros?**  
15. **Qual a distribuição das tarifas (`Fare`) pagas (ex.: quartis)?**  
16. **Quantos passageiros tinham cabine registrada vs. sem cabine?**  
17. **Qual o número de sobreviventes por faixa etária (ex.: crianças, adultos, idosos)?**  
18. **Como a taxa de sobrevivência varia de acordo com o porto de embarque (`Embarked`)?**  
19. **Qual o percentual de passageiros que eram mulheres em cada classe?**  
20. **Qual o percentual de passageiros em cada classe que tinham mais de 1 familiar a bordo?**  

---
