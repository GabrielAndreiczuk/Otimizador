# Otimizador de Produção e Venda

Este projeto implementa um otimizador comercial com foco na **maximização do lucro diário** da operação comercial, determinando a **quantidade ideal de produção e venda** 
de produtos, considerando **restrições logísticas, operacionais e de mercado**.

## 📌 Objetivo

Definir, para o dia atual, quais produtos devem ser produzidos e vendidos, **maximizando o lucro**, com base em dados atualizados e restrições comerciais específicas.

## ⚙️ Tecnologias Utilizadas
<div>
  <img align="center" alt="C#" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">
  <img align="center" alt="C#" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg">
  <img align="center" alt="C#" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original-wordmark.svg">
  <img align="center" alt="C#" height="50" width="50" src="https://raw.githubusercontent.com/or-tools/logo/078ccc065ee367659b43c5e5e8f22ac3cbaf400a/logo.svg">
  </div>


## 📊 Funcionamento

1. **Leitura de dados**: produtos e parâmetros são carregados de arquivos `.csv`.
2. **Criação das variáveis de decisão**: produção e venda por produto.
3. **Função objetivo**: maximização do lucro (preço - custo).
4. **Restrições**: produção mínima/máxima, venda mínima/máxima, entre outras.
5. **Resolução com OR-Tools**: uso de solver para encontrar a melhor combinação.
6. **Geração de gráfico**: visualização da produção e venda por produto.         

## 🧠 Sobre o Projeto

Este projeto foi desenvolvido como **meu primeiro estudo prático com a linguagem Python**, com o objetivo de aplicar conceitos de otimização linear com a biblioteca OR-Tools, manipulação de dados com Pandas e visualização com Matplotlib/Seaborn.

Além de consolidar conhecimentos técnicos, este projeto também foi uma oportunidade de explorar **modelagem de problemas reais com foco em tomada de decisão baseada em dados**.


## 📍 Autor

[Gabriel Andreiczuk](https://www.github.com/GabrielAndreiczuk)<br><br>
<a href="https://www.linkedin.com/in/gabriel-andreiczuk/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href = "mailto:gabriel.andreiczuk@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

