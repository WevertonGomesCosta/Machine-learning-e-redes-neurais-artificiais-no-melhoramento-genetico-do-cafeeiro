# Machine Learning e Redes Neurais Artificiais no Melhoramento Genético do Cafeeiro

Bem-vindo ao projeto de Genomic Wide Selection em Coffea arabica!  
Esta iniciativa da Universidade Federal de Viçosa aplica técnicas de machine learning e redes neurais para aprimorar a seleção de genótipos de café e identificar marcadores SNP informativos.

---

## About the Project

O objetivo principal é comparar a performance preditiva de métodos não paramétricos (MARS, Random Forest, Bagging, Boosting), redes neurais (RBF) e G-BLUP na seleção genômica ampla (GWS) de C. arabica. Utilizamos:

- **Dados reais**: 195 genótipos, 21 211 SNPs, características de bicho mineiro, cercosporiose e produtividade (fenotipagem 2014–2016, Estação Experimental UFV).  
- **Dados simulados**: população F₂ de 1 000 indivíduos, 4 010 SNPs, 12 características simuladas com variação de QTL (8–480) e herdabilidade (0,5/0,8).  
- **Métricas**: acurácia preditiva (R²) e erro (RMSE), validados via 5-fold cross-validation.

Além disso, realizamos análise de associação genômica (GWAS) para identificar SNPs informativos e potenciais variantes causais.

---

## Project Structure

1. [Exploratory Data Analysis (EDA)](https://wevertongomescosta.github.io/coffee-gws/eda.html)  
   Pacotes como DataExplorer e metan são usados para entender estrutura, ausências e padrões dos dados brutos.  

2. [Genomic Wide Selection (GWS)](https://wevertongomescosta.github.io/coffee-gws/gws.html)  
   Pré-processamento do marcador SNP e aplicação de modelos:  
   - [**MARS**](https://wevertongomescosta.github.io/coffee-gws/gws_mars.html)  
   - [**G-BLUP**](https://wevertongomescosta.github.io/coffee-gws/gws_gblup.html)  
   - [**Random Forest**](https://wevertongomescosta.github.io/coffee-gws/gws_rf.html)  
   - [**Bagging (BA)**](https://wevertongomescosta.github.io/coffee-gws/gws_bagging.html)  
   - [**Boosting (BO)**](https://wevertongomescosta.github.io/coffee-gws/gws_boosting.html)  
   - [**Rede de Base Radial (RBF)**](https://wevertongomescosta.github.io/coffee-gws/gws_rbf.html)  

3. [Seleção de Genótipos](https://wevertongomescosta.github.io/coffee-gws/selection.html)  
   Uso de GEBVs e BLUPs para ranquear e escolher os melhores genótipos de café para melhoramento.
   
4. [Identificação de SNPs Informativos (GWAS)](https://wevertongomescosta.github.io/coffee-gws/gwas.html)  
   Análise de associação genoma-fenótipo para detectar variantes estatisticamente associadas aos fenótipos de interesse.  

---

## Study Highlights

- Processo: BPD-00922-22  
- Chamada: Edital 017/2022 – Programa de Apoio à Fixação de Jovens Doutores  
- Período: 01/04/2023 a 28/02/2025  

**Pesquisador Coordenador**  
Moyses Nascimento – moysesnascim@ufv.br 

**Bolsista**  
Weverton Gomes da Costa – weverton.costa@ufv.br

---

## Manuscrito e Acesso

Em breve disponibilizaremos o preprint com todos os resultados completos. Fique atento à seção “Publications” no site.

---

## Contato

Dúvidas, sugestões ou colaborações? Abra uma issue ou envie e-mail para os pesquisadores do projeto.
