# Métodos para Comparação e Compressão de Dados Genômicos  
### FAPEMIG – Demanda Universal (APQ-01217-22)

Projeto financiado pela FAPEMIG com foco no desenvolvimento de algoritmos e estruturas de dados compactas para o processamento eficiente de grandes volumes de dados genômicos.

---

## 🎯 Objetivos

Investigar e desenvolver métodos eficientes, em tempo e memória, para problemas fundamentais em Bioinformática:

- Comparação de genomas por meio de grafos de Bruijn coloridos sucintos  
- Identificação de *Left-Bounded Shortest Unique Substrings (LSUS)*  
- Compressão de dados genômicos armazenados em arquivos FASTQ  

As soluções propostas são fundamentadas na **Transformada de Burrows–Wheeler (BWT)** e em **estruturas de dados compactas**, com ênfase em baixo uso de RAM e/ou uso de memória externa.

---

## 📚 Resultados Científicos

O projeto originou publicações em periódicos e conferências internacionais, incluindo:

- Veronica Guerrini, Felipe A. Louza, Giovanna Rosone: Lossy Compressor Preserving Variant Calling through Extended BWT. BIOINFORMATICS 2022: 38-48
- Lucas P. Ramos, Felipe A. Louza, Guilherme P. Telles: Genome Comparison on Succinct Colored de Bruijn Graphs. SPIRE 2022: 165-177
- Veronica Guerrini, Felipe A. Louza, Giovanna Rosone: Parallel Lossy Compression for Large FASTQ Files. BIOSTEC (Selected Papers) 2022: 97-120
- Lucas P. Ramos, Felipe A. Louza, Guilherme P. Telles: Comparative genomics with succinct colored de Bruijn graphs. Acta Informatica 62(1): 1 (2025)
- Larissa L. M. Aguiar, Felipe A. Louza: Faster computation of left-bounded shortest unique substrings. Algorithms Mol. Biol. 20(1): 11 (2025)

---

## 🔬 Reprodutibilidade

Este repositório contém as implementações desenvolvidas no projeto, permitindo a reprodução dos experimentos descritos nas publicações associadas.

Cada subdiretório inclui instruções de compilação e execução.

---

## 💻 Requisitos

- Compilador C/C++ compatível com C++17 (ou superior)  
- Ambiente Linux  
- Dependências específicas indicadas em cada subprojeto  

---

## 🏛 Financiamento

- **FAPEMIG – Fundação de Amparo à Pesquisa do Estado de Minas Gerais**
- Edital 001/2022 – Demanda Universal
- Processo APQ-01217-22
