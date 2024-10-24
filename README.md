# Projeto Proteja Seu Amanhã: Aprendizado de Máquina para Seguros

## Visão Geral
Utilizar aprendizado de máquina para resolver várias tarefas relacionadas à análise de clientes e previsões de seguros, para companhia de seguros **Proteja Seu Amanhã**. Este projeto aborda quatro tarefas principais que visam melhorar a eficiência da empresa e a experiência do cliente.

## Objetivos
1. **Encontrar Clientes Semelhantes**: Identificar clientes com perfis semelhantes a um cliente específico para auxiliar os agentes de marketing.
2. **Predição de Pagamentos de Seguro**: Criar um modelo para prever se um novo cliente provavelmente receberá um pagamento de seguro, comparando com um modelo dummy.
3. **Predição do Número de Pagamentos**: Usar um modelo de regressão linear para prever quantos pagamentos de seguro um novo cliente provavelmente receberá.
4. **Mascaramento de Dados Pessoais**: Desenvolver um algoritmo de ofuscação de dados que proteja informações pessoais, garantindo que a qualidade do modelo de predição não seja comprometida.

## Descrição dos Dados
O conjunto de dados é armazenado no arquivo `insurance_us.csv` e contém as seguintes características:
- **Sexo**: Gênero do segurado.
- **Idade**: Idade do segurado.
- **Salário**: Renda do segurado.
- **Número de Familiares**: Quantidade de familiares do segurado.

**Alvo**:
- **Número de Pagamentos de Seguro**: Total de pagamentos recebidos por um segurado nos últimos cinco anos.

## Ferramentas e Bibliotecas Utilizadas
- **Python**: Linguagem principal utilizada para a análise.
- **Pandas**: Manipulação e análise de dados.
- **Scikit-learn**: Modelagem preditiva e machine learning.
- **NumPy**: Computação numérica.
- **Seaborn**: Visualização de dados, gráficos informativos e atraentes.

## Instruções do Projeto
1. **Carregamento dos Dados**:
   - Importação do conjunto de dados a partir do arquivo `insurance_us.csv`.
2. **Verificação da Qualidade dos Dados**:
   - Análise dos dados para garantir que não há valores ausentes ou extremos.
   - Aplicação de limpeza e pré-processamento conforme necessário.
3. **Tarefa 1 - Encontrar Clientes Semelhantes**:
   - Implementação de algoritmos de similaridade para identificar clientes com perfis semelhantes.
4. **Tarefa 2 - Predição de Pagamentos de Seguro**:
   - Desenvolvimento de um modelo preditivo para estimar a probabilidade de um novo cliente receber um pagamento de seguro.
   - Comparação do desempenho do modelo com um modelo dummy.
5. **Tarefa 3 - Predição do Número de Pagamentos**:
   - Construção de um modelo de regressão linear para prever quantos pagamentos um novo cliente provavelmente receberá.
6. **Tarefa 4 - Mascaramento de Dados Pessoais**:
   - Desenvolvimento de um algoritmo de ofuscação de dados para proteger informações pessoais.
   - Avaliação da eficácia da ofuscação em preservar a qualidade das predições do modelo.
7. **Análise dos Resultados**:
   - Análise das métricas de desempenho e comparação entre os dados originais e ofuscados.
   - Verificação da integridade dos valores previstos.
8. **Conclusões e Aprendizados**:
   - Reflexão sobre as descobertas e habilidades adquiridas durante o projeto.

## Conclusão
Os resultados demonstram que a ofuscação dos dados não compromete a precisão do modelo. As métricas de desempenho e o REQM para os dados originais e ofuscados são idênticos, evidenciando que a técnica de ofuscação preserva as propriedades relevantes para a regressão linear. Além disso, os valores previstos para ambas as versões dos dados são iguais, confirmando que a transformação não afeta as previsões. Essa abordagem de ofuscação se mostra eficaz, permitindo a proteção da privacidade sem sacrificar a qualidade da análise preditiva.

## Aprendizados
Este projeto proporcionou o desenvolvimento das seguintes habilidades:

- **Análise de Dados**: Aprendi a manipular e preparar conjuntos de dados para análise preditiva.
- **Modelagem Preditiva**: Aprofundei meus conhecimentos em técnicas de aprendizado de máquina, especialmente em regressão linear.
- **Ofuscação de Dados**: Explorei técnicas de mascaramento de dados, compreendendo a importância da privacidade na análise de dados.
- **Avaliação de Modelos**: Entendi como calcular e interpretar métricas de desempenho, como o REQM, para avaliar a eficácia dos modelos.
- **Resolução de Problemas**: Desenvolvi habilidades na identificação e solução de problemas relacionados a dados, como valores ausentes e extremos.
- **Documentação**: Melhorei minha capacidade de documentar processos e resultados, tornando o projeto mais acessível e compreensível para outros.

Esses aprendizados são valiosos para minha formação na área de ciência de dados, álgebra linear e são aplicáveis a futuras iniciativas.

## Como Executar o Projeto

- Clone o repositório.
- Navegue até o diretório do projeto.
- Abra o projeto no seu IDE favorito.
- Instale as dependências.
- Execute o script principal.

## Contato

Luciano Pinto
[LinkedIn](https://www.linkedin.com/in/lucianolcp/)  
Email: dslucianopinto@gmail.com
