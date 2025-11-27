### Trabalho Final da Disciplina DATA COLLECTION E STORAGE

#### Aluno: Maria Luiza - 10742925
####        Paulo Vasconcelos - 10742919

#### Base de dados escolhida: 
### Game Recommendations on Steam
##### A dataset of games, users and reviews for building recommendation systems

Tema Escolhido: Construção de um Data Lakehouse Transacional
Data Base Escolhido: Steam Game Recommendations
Objetivo: Criar um pipeline de dados que simule a ingestão e o processamento de dados transacionais, aplicando as técnicas de pré-processamento e os formatos Open Data para garantir ACIDidade (Atomicidade, Consistência, Isolamento, Durabilidade).

#### Requisitos Mínimos:

* Coleta/Aquisição: Simular a ingestão de dados de uma fonte de logs ou transações em tempo real (pode ser um dataset CSV/JSON grande) na camada Raw (Bruta).
* Pré-processamento: Aplicar pelo menos 3 transformações de qualidade (ex: limpeza de nulos, casting de tipos, desduplicação). Mover para a camada Curated (Tratada).
* Persistência: Utilizar um dos Formatos Open Data (Delta Lake, Apache Iceberg ou Apache Hudi) para armazenar a tabela final.
* Recurso Avançado (Obrigatório): Demonstrar uma operação de UPSERT (Update ou Insert) ou DELETE na tabela final.

Entrega: Apresentar o código (preferencialmente em Python/PySpark) e um diagrama da arquitetura (simples) explicando as decisões.
