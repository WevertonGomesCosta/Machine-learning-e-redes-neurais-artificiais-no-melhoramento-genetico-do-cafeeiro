# Machine Learning e Redes Neurais no Melhoramento Genético do Cafeeiro

Bem-vindo! Este repositório reúne código, dados e relatórios associados ao estudo de seleção genômica ampla (GWS) em Coffea arabica, empregando métodos de machine learning e redes neurais artificiais para seleção de genótipos e detecção de SNPs informativos.

![Pipeline de Análise](images/analysis_pipeline.png)

## Publicação Associada

Este trabalho faz parte do Projeto de Pesquisa:  

- Processo: BPD-00922-22  
- Chamada: Edital 017/2022 – Programa de Apoio à Fixação de Jovens Doutores  
- Período: 01/04/2023 a 28/02/2025  

## Sobre o LICAE
Este projeto foi desenvolvido no âmbito das pesquisas do [Laboratório de Inteligência Computacional e Aprendizado Estatístico (LICAE)](https://www.licae.ufv.br/) da Universidade Federal de Viçosa (UFV), especializado em aplicações avançadas de inteligência computacional em problemas genômicos complexos.

## Recursos Disponíveis

1. **Código de Análise**: Scripts R/Python para pré-processamento, modelagem e avaliação.  
2. **Dados**: Genótipos reais (195 indivíduos, 21 211 SNPs) e simulados (1 000 indivíduos, 4 010 SNPs).  
3. **Notebooks**: Exemplos interativos de EDA, GWS e GWAS.  
4. **Visualizações**: Gráficos de acurácia (R²), RMSE e ranking de genótipos.  

![Arquitetura do Modelo](images/model_architecture.png)

## Como Utilizar
1. Clone o repositório: `git clone https://github.com/wevertongomescosta/Genomic-prediction-through-machine-learning-and-neural-networks-for-traits-with-epistasis.git`
2. Instale as dependências: `renv::restore()`
3. Execute o pipeline principal: `Rscript scripts/main_analysis.R`

## Contribuição
Contribuições são bem-vindas mediante:
- Abertura de issues para discussão de melhorias
- Submissão de pull requests para correções críticas
- Sugestões de extensões metodológicas

## Licença
Este trabalho está licenciado sob [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Para uso comercial ou modificações significativas, por favor contate os autores.

## Contato
**Coordenador**  
Moyses Nascimento  
Professor Adjunto - Departamento de Estatística - UFV
moysesnascim@ufv.br

**Bolsista**  
Weverton Gomes da Costa  
Pós-Doutorando - Departamento de Estatística - UFV  
weverton.costa@ufv.br


**Laboratório LICAE**:  
licae@ufv.br | [https://www.licae.ufv.br/](https://www.licae.ufv.br/)

---

# Machine Learning and Neural Networks in Coffee Genetic Breeding

Welcome! This repository gathers code, data, and reports associated with the Genome Wide Selection (GWS) study in *Coffea arabica*, employing machine learning and artificial neural network methods for genotype selection and informative SNP detection.

![Analysis Pipeline](images/analysis_pipeline.png)

## Associated Project

This work is part of the Research Project:

- Process: BPD-00922-22  
- Call: Notice 017/2022 – Program to Support the Retention of Young Postdocs in Brazil  
- Period: April 1, 2023 to February 28, 2025  

## About LICAE

This project was developed within the research activities of the [Computational Intelligence and Statistical Learning Laboratory (LICAE)](https://www.licae.ufv.br/) at the Federal University of Viçosa (UFV), specialized in advanced computational intelligence applications to complex genomic problems.

## Available Resources

1. **Analysis Code**: R and Python scripts for preprocessing, modeling, and evaluation.  
2. **Data**: Real genotypes (195 individuals, 21,211 SNPs) and simulated (1,000 individuals, 4,010 SNPs).  
3. **Notebooks**: Interactive examples of EDA, GWS, and GWAS.  
4. **Visualizations**: Plots of accuracy (R²), RMSE, and genotype rankings.  

![Model Architecture](images/model_architecture.png)

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/wevertongomescosta/coffee-gws.git
   ```
2. Install dependencies:  
   ```bash
   renv::restore()
   ```
3. Run the main pipeline:  
   ```bash
   Rscript scripts/main_analysis.R
   ```

## Contribution

Contributions are welcome via:  
- Opening issues for improvement discussions  
- Submitting pull requests for critical fixes  
- Suggestions for methodological extensions  

## License

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). For commercial use or significant modifications, please contact the authors.

## Contact

**Project Coordinator**  
Moyses Nascimento  
Associate Professor, Department of Statistics, UFV  
moysesnascim@ufv.br  

**Research Fellow**  
Weverton Gomes da Costa  
Post-Doctoral Researcher, Department of Statistics, UFV  
weverton.costa@ufv.br  

**LICAE Laboratory**  
licae@ufv.br | https://www.licae.ufv.br/