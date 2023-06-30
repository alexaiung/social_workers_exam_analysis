# Estatuto da Pessoa com Deficiência

De 1543 questões a respeito da legislação Estatuto da Pessoa com Deficiência retiradas do QConcursos, 150 eram voltadas para provas de assistentes sociais.

Destas, 30 questões mencionam artigos de lei específicos.

![Quantidade de Questões p/ Assistentes Sociais](images/graphs/estatuto_da_pessoa_com_deficiência/is_social_work.png)


## Análise de Artigos Pedidos Explicitamente

Como algumas questões mencionam mais de um artigo de lei, há a menção de 30 artigos em meio a estas 30 questões. O gráfico a seguir ilustra os 15 artigos mais pedidos:

![15 artigos mais pedidos](images/graphs/estatuto_da_pessoa_com_deficiência/top_articles.png)

Gráfico completo:

![Todos os artigos mencionados](images/graphs/estatuto_da_pessoa_com_deficiência/all_articles.png)

## Análise dos demais dados

Se considerarmos todos os dados, não só os que mencionam artigos, teremos as seguintes palavras como as mais citadas:

![Wordcount](images/graphs/estatuto_da_pessoa_com_deficiência/wordcloud.png)
![Top-15 words](images/graphs/estatuto_da_pessoa_com_deficiência/top_words.png)

### Análise de tópicos

Com o uso da tecnologia de Processamento de Linguagem Natural (Bertopic), foi gerado um modelo de tópicos a respeito de nosso conjunto completo de questões. Estes tópicos organizam quais os principais grupos de questão associados à lei em questão.

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Topic</th>
      <th>topic_title</th>
      <th>Representation</th>
      <th>Count</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>-1</td>
      <td>Educação infantil e sociabilidade na escola</td>
      <td>[socioassistenciais, socioeducacionais, pedagógico, ensino, educação, sociabilidade, sociedade, escola, infantil, estudar]</td>
      <td>12</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0</td>
      <td>Inclusão e direitos à saúde</td>
      <td>[deficiência, inclusão, igualdade, saúde, acessibilidade, direitos, alternativas, restrição, pessoa, afirmativas]</td>
      <td>113</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>Cidadania e Igualdade</td>
      <td>[deficiência, liberdades, inclusão, direitos, acessibilidade, cidadania, estatuto, brasil, brasileira, igualdade]</td>
      <td>25</td>
    </tr>
  </tbody>
</table>

![Topic frequency](images/graphs/estatuto_da_pessoa_com_deficiência/topics.png)

Se observarmos os artigos pedidos em cada tópico, teremos os seguintes gráficos:

![Articles by Topic](images/graphs/estatuto_da_pessoa_com_deficiência/articles_by_topic.png)