# Código de Ética

De 4326 questões a respeito da legislação Código de Ética retiradas do QConcursos, 3868 eram voltadas para provas de assistentes sociais.

Destas, 355 questões mencionam artigos de lei específicos.

![Quantidade de Questões p/ Assistentes Sociais](images/graphs/código_de_ética/is_social_work.png)


## Análise de Artigos Pedidos Explicitamente

Como algumas questões mencionam mais de um artigo de lei, há a menção de 375 artigos em meio a estas 355 questões. O gráfico a seguir ilustra os 15 artigos mais pedidos:

![15 artigos mais pedidos](images/graphs/código_de_ética/top_articles.png)

Gráfico completo:

![Todos os artigos mencionados](images/graphs/código_de_ética/all_articles.png)

## Análise dos demais dados

Se considerarmos todos os dados, não só os que mencionam artigos, teremos as seguintes palavras como as mais citadas:

![Wordcount](images/graphs/código_de_ética/wordcloud.png)
![Top-15 words](images/graphs/código_de_ética/top_words.png)

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
      <td>Outros</td>
      <td>[ética, ético, sociais, atribuições, regulamentação, assistentes, profissionais, direitos, serviços, constitui]</td>
      <td>1369</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0</td>
      <td>Ética e Democracia</td>
      <td>[ético, ética, autoritarismo, equidade, socialização, liberdade, sociais, sociedade, democracia, emancipação]</td>
      <td>222</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>Políticas Sociais Brasileiras</td>
      <td>[políticas, sociais, sociedade, política, político, brasil, brasileiro, brasileiros, brasileira, políticos]</td>
      <td>176</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2</td>
      <td>Sociedade e Conservadorismo</td>
      <td>[societário, sociais, ético, societários, ética, sociedade, políticas, social, política, conservadorismo]</td>
      <td>168</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>Profissão e Trabalho Social</td>
      <td>[profissão, ocupacionais, sociais, profissionais, sociedade, assistentes, competências, interdisciplinar, trabalho, social]</td>
      <td>119</td>
    </tr>
    <tr>
      <th>5</th>
      <td>4</td>
      <td>Supervisão de Estágio e Responsabilidade</td>
      <td>[supervisão, supervisionado, supervisores, supervisor, responsabilidade, assistente, profissionais, atribuição, pedagógico, profissional]</td>
      <td>109</td>
    </tr>
    <tr>
      <th>6</th>
      <td>5</td>
      <td>Sigilo Profissional</td>
      <td>[ética, protegerá, assistente, autoridade, admissível, interesses, profissional, constitui, multidisciplinar, afirmar]</td>
      <td>94</td>
    </tr>
    <tr>
      <th>7</th>
      <td>6</td>
      <td>Ética Institucional e Participação Social</td>
      <td>[ética, institucional, social, autoridade, institucionais, interesses, assistente, serviços, respeitando, participação]</td>
      <td>86</td>
    </tr>
    <tr>
      <th>8</th>
      <td>7</td>
      <td>Regulamentação Federativa e Assessoria</td>
      <td>[federativa, normativo, federal, constituem, regulamentação, assessoria, consultiva, atribuições, sociais, normatizar]</td>
      <td>81</td>
    </tr>
    <tr>
      <th>9</th>
      <td>8</td>
      <td>Assistência Social e Ética Profissional</td>
      <td>[assistente, atendimento, assistentes, situação, ética, serviço, atribuições, profissional, serviços, social]</td>
      <td>75</td>
    </tr>
    <tr>
      <th>10</th>
      <td>9</td>
      <td>Responsabilidades e Direitos dos Assistentes Sociais</td>
      <td>[ética, responsabilidade, responsabilidades, direitos, prerrogativas, atribuições, assistentes, institucionais, assistente, profissionais]</td>
      <td>73</td>
    </tr>
    <tr>
      <th>11</th>
      <td>10</td>
      <td>Regulamentação e Fiscalização das Instituições</td>
      <td>[regulamentação, instituições, federal, jurisdição, organizações, diretoria, legitimidade, assistentes, fiscalizando, membros]</td>
      <td>58</td>
    </tr>
    <tr>
      <th>12</th>
      <td>11</td>
      <td>Políticas Socioassistenciais em Saúde</td>
      <td>[socioassistenciais, políticas, reforma, sociais, saúde, descentralização, assessoria, alternativas, atendimento, ético]</td>
      <td>52</td>
    </tr>
    <tr>
      <th>13</th>
      <td>12</td>
      <td>Abordagens Éticas no Atendimento Social</td>
      <td>[atendimento, atendimentos, assistente, serviços, intervenção, éticas, informar, profissional, social, abordagens]</td>
      <td>52</td>
    </tr>
    <tr>
      <th>14</th>
      <td>13</td>
      <td>Regulamentação e Supervisão Privativas</td>
      <td>[privativas, regulamentação, regulamenta, supervisionar, privadas, profissão, atribuições, assessoria, disciplinas, administração]</td>
      <td>50</td>
    </tr>
    <tr>
      <th>15</th>
      <td>14</td>
      <td>Competência e Ética Profissional</td>
      <td>[ética, éticos, autoridade, assistente, justiça, atribuição, competente, depoimento, competência, profissional]</td>
      <td>48</td>
    </tr>
    <tr>
      <th>16</th>
      <td>15</td>
      <td>Infrações e Penalidades na Ética Profissional</td>
      <td>[penalidades, penalidade, punibilidade, infrações, infração, infratores, interdição, multa, ética, disciplinar]</td>
      <td>47</td>
    </tr>
    <tr>
      <th>17</th>
      <td>16</td>
      <td>Currículo e Políticas Acadêmicas</td>
      <td>[currículo, acadêmica, ensino, sociedade, interdisciplinaridade, educação, curriculares, curso, curricular, políticas]</td>
      <td>46</td>
    </tr>
    <tr>
      <th>18</th>
      <td>17</td>
      <td>Formação e Graduação em Serviço Social</td>
      <td>[profissão, profissionais, sociais, profissional, assistentes, social, atribuições, competente, ensino, graduação]</td>
      <td>43</td>
    </tr>
    <tr>
      <th>19</th>
      <td>18</td>
      <td>Moralidade e Ética na Sociedade</td>
      <td>[moralidade, moral, ético, ética, filosófico, morais, filosofia, consciência, racional, sociedade]</td>
      <td>42</td>
    </tr>
    <tr>
      <th>20</th>
      <td>19</td>
      <td>Intervenção e Pareceres dos Assistentes Sociais</td>
      <td>[assistentes, assistente, atribuição, intervenção, profissionais, serviço, competência, profissional, social, pareceres]</td>
      <td>41</td>
    </tr>
    <tr>
      <th>21</th>
      <td>20</td>
      <td>Princípios Éticos e Conservadorismo</td>
      <td>[éticos, ético, ética, equidade, conservadorismo, autocracia, idealista, doutrina, filosófica, princípios]</td>
      <td>38</td>
    </tr>
    <tr>
      <th>22</th>
      <td>21</td>
      <td>Discriminação e LGBTQIA+</td>
      <td>[discriminatórias, discriminação, sociais, transexualizador, estigmas, preconceito, social, identidades, identidade, profissionais]</td>
      <td>38</td>
    </tr>
    <tr>
      <th>23</th>
      <td>22</td>
      <td>Regulamentação e Legislação dos Assistentes Sociais</td>
      <td>[ética, ético, éticos, profissão, profissionais, regulamentação, profissional, responsabilidade, legislação, sociais]</td>
      <td>35</td>
    </tr>
    <tr>
      <th>24</th>
      <td>23</td>
      <td>Disciplinas e Práticas Acadêmicas</td>
      <td>[disciplinas, metodologica, formação, curriculares, prática, acadêmica, curricular, curso, sociedade, princípios]</td>
      <td>35</td>
    </tr>
    <tr>
      <th>25</th>
      <td>24</td>
      <td>Administração e Legislação em Serviço Social</td>
      <td>[profissão, sociais, legislação, administração, assistente, social, ensino, competente, privativa, serviço]</td>
      <td>32</td>
    </tr>
    <tr>
      <th>26</th>
      <td>25</td>
      <td>Capitalismo e Ética Profissional</td>
      <td>[éticas, ético, ética, moral, moralidade, profissão, morais, sociedade, profissionais, capitalista]</td>
      <td>31</td>
    </tr>
    <tr>
      <th>27</th>
      <td>26</td>
      <td>Penalidades e Disciplinas na Ética Profissional</td>
      <td>[penalizado, penalidades, penalidade, infrações, infração, advertências, advertência, disciplinares, disciplinar, multa]</td>
      <td>31</td>
    </tr>
    <tr>
      <th>28</th>
      <td>27</td>
      <td>Jornada de Trabalho dos Assistentes Sociais</td>
      <td>[horas, duração, empregador, salarial, salário, semanais, assistentes, trabalho, profissão, escritório]</td>
      <td>30</td>
    </tr>
    <tr>
      <th>29</th>
      <td>28</td>
      <td>Família</td>
      <td>[famílias, parental, familiares, família, genitor, afirmativas, sociais, pais, filhos, afirmativa]</td>
      <td>29</td>
    </tr>
    <tr>
      <th>30</th>
      <td>29</td>
      <td>Assessoria e Consultoria em Serviço Social</td>
      <td>[assessoria, assessor, profissionais, consultoria, atribuições, interdisciplinar, assistente, profissão, profissional, multidisciplinar]</td>
      <td>29</td>
    </tr>
    <tr>
      <th>31</th>
      <td>30</td>
      <td>Profissionalismo e Institucionalização</td>
      <td>[profissão, profissionais, profissional, institucionais, organizações, instituições, profissões, societários, sociedade, legitimam]</td>
      <td>25</td>
    </tr>
    <tr>
      <th>32</th>
      <td>31</td>
      <td>Disciplinas e Infrações na Ética Profissional</td>
      <td>[disciplinares, disciplinar, infração, infrações, ética, profissão, autoridade, profissional, instituição, assistente]</td>
      <td>24</td>
    </tr>
    <tr>
      <th>33</th>
      <td>32</td>
      <td>Pesquisa e Estudos em Serviço Social</td>
      <td>[empiricamente, socioeconômicos, qualitativos, pesquisa, sociais, investigação, investigativa, interventiva, estudos, pesquisador]</td>
      <td>23</td>
    </tr>
    <tr>
      <th>34</th>
      <td>33</td>
      <td>Educação e Pedagogia</td>
      <td>[educação, educacional, educacionais, pedagógica, ensino, sociais, pedagogia, social, escola, empobrecimento]</td>
      <td>22</td>
    </tr>
    <tr>
      <th>35</th>
      <td>34</td>
      <td>Código de Ética de 1993</td>
      <td>[ética, éticos, decreto, 1993, alterações, institui, direitos, social, aprovado, código]</td>
      <td>22</td>
    </tr>
    <tr>
      <th>36</th>
      <td>35</td>
      <td>Socialismo e Humanização do Serviço Social</td>
      <td>[sociais, societárias, societário, sociedade, social, humanização, ético, serviço, moral, socialismo]</td>
      <td>20</td>
    </tr>
    <tr>
      <th>37</th>
      <td>36</td>
      <td>Competências em Serviço Social</td>
      <td>[responsabilização, sociais, competências, competência, organizações, administração, social, serviços, políticas, atendimento]</td>
      <td>19</td>
    </tr>
    <tr>
      <th>38</th>
      <td>37</td>
      <td>Supervisão e Serviços Privados</td>
      <td>[privativas, privadas, sociais, serviços, sociedade, supervisão, social, pública, assessoria, supervisionar]</td>
      <td>19</td>
    </tr>
    <tr>
      <th>39</th>
      <td>38</td>
      <td>Confidencialidade e Segurança de Informações Técnicas</td>
      <td>[confidencial, divulgação, documentação, documentos, segurança, sigilosos, cfess, informações, salvaguarda, técnico]</td>
      <td>19</td>
    </tr>
    <tr>
      <th>40</th>
      <td>39</td>
      <td>Responsabilidades e Demissão</td>
      <td>[ética, responsabilidade, responsabilidades, exoneração, profissionais, profissão, assistente, profissional, demissão, emprego]</td>
      <td>19</td>
    </tr>
    <tr>
      <th>41</th>
      <td>40</td>
      <td>Ética Profissional Pública - Censura</td>
      <td>[responsabilidade, competentes, ética, profissão, pública, profissionais, inviolabilidade, censura, práticas, alternativas]</td>
      <td>18</td>
    </tr>
    <tr>
      <th>42</th>
      <td>41</td>
      <td>Desafios Sociais</td>
      <td>[assistentes, intervenção, imperativo, desafios, necessidades, sociais, propostas, assistente, profissão, demandas]</td>
      <td>17</td>
    </tr>
    <tr>
      <th>43</th>
      <td>42</td>
      <td>Ética na Intervenção</td>
      <td>[subordinados, ética, éticos, assistente, profissionais, atribuições, profissão, profissional, intervir, emprego]</td>
      <td>16</td>
    </tr>
    <tr>
      <th>44</th>
      <td>43</td>
      <td>Diversidade e Discriminação</td>
      <td>[discriminados, preconceito, ética, social, estigma, diversidade, respeito, socialmente, incentivando, atribuição]</td>
      <td>15</td>
    </tr>
    <tr>
      <th>45</th>
      <td>44</td>
      <td>Interprofissionalidade</td>
      <td>[responsabilidade, profissionais, assistente, interprofissionais, autoridade, interdisciplinar, éticos, interdisciplinares, organizações, profissional]</td>
      <td>15</td>
    </tr>
    <tr>
      <th>46</th>
      <td>45</td>
      <td>Socialização e Equidade</td>
      <td>[ética, ético, éticos, sociais, socialização, equidade, institucional, social, assessoria, princípios]</td>
      <td>14</td>
    </tr>
    <tr>
      <th>47</th>
      <td>46</td>
      <td>Fiscalização e Normas</td>
      <td>[fiscal, normativa, reguladores, federal, comissão, normas, fiscais, disciplinadora, compromissos, nacional]</td>
      <td>13</td>
    </tr>
    <tr>
      <th>48</th>
      <td>47</td>
      <td>Instituições</td>
      <td>[institucionalmente, institucionais, ética, instituições, organizações, sociais, sociedade, profissionais, interdisciplinares, constituem]</td>
      <td>13</td>
    </tr>
    <tr>
      <th>49</th>
      <td>48</td>
      <td>Ética e Moral</td>
      <td>[moral, ético, ética, morais, sociedade, ethos, sociais, capitalista, objetivações, objetivação]</td>
      <td>13</td>
    </tr>
    <tr>
      <th>50</th>
      <td>49</td>
      <td>Estudo Social</td>
      <td>[social, estudo, socioeconômicos, estudada, pesquisa, intervenção, avaliação, análise, crítica, afirmações]</td>
      <td>12</td>
    </tr>
    <tr>
      <th>51</th>
      <td>50</td>
      <td>Deveres</td>
      <td>[responsabilidade, competentes, profissionais, atendimento, profissão, assistente, ética, profissional, pública, legislação]</td>
      <td>12</td>
    </tr>
    <tr>
      <th>52</th>
      <td>51</td>
      <td>Supervisão e Fiscalização</td>
      <td>[sociais, sociedade, privativas, organizações, serviços, supervisionar, privadas, social, supervisão, socioeconômicos]</td>
      <td>12</td>
    </tr>
    <tr>
      <th>53</th>
      <td>52</td>
      <td>Normativas e CFESS</td>
      <td>[normativa, regulamentar, cfess, federal, institui, instaurado, medidas, 2002, política, denunciante]</td>
      <td>12</td>
    </tr>
    <tr>
      <th>54</th>
      <td>53</td>
      <td>Assessoria e Atribuições</td>
      <td>[sociais, privativas, assessoria, privadas, socioeconômicos, administração, pública, políticas, atribuições, privativa]</td>
      <td>11</td>
    </tr>
    <tr>
      <th>55</th>
      <td>54</td>
      <td>Direitos e Dignidade</td>
      <td>[afirmativas, afirmativa, correta, iguais, direitos, duas, direita, direito, dignidade, opinião]</td>
      <td>11</td>
    </tr>
    <tr>
      <th>56</th>
      <td>55</td>
      <td>Assessoria e Supervisão</td>
      <td>[sociais, assessoria, assessorados, assessora, atribuições, assistentes, privativas, privadas, supervisionar, profissionais]</td>
      <td>11</td>
    </tr>
    <tr>
      <th>57</th>
      <td>56</td>
      <td>Assessoria e Atendimento</td>
      <td>[assessoria, sociais, administração, organizações, políticas, assertivas, atendimento, social, associações, supervisionar]</td>
      <td>11</td>
    </tr>
    <tr>
      <th>58</th>
      <td>57</td>
      <td>Assessoria e Intervenção</td>
      <td>[sociais, políticas, organizações, assessoria, social, entidades, pública, organização, administração, intervenção]</td>
      <td>11</td>
    </tr>
    <tr>
      <th>59</th>
      <td>58</td>
      <td>Ética e Integridade Profissional</td>
      <td>[ética, integridade, administrativo, assistente, infração, regulamento, empregado, profissional, interesses, instituição]</td>
      <td>10</td>
    </tr>
    <tr>
      <th>60</th>
      <td>59</td>
      <td>Políticas e Organizações Sociais</td>
      <td>[políticas, administração, organizações, sociais, constitui, socioeconômicos, pública, organização, constituem, entidades]</td>
      <td>10</td>
    </tr>
    <tr>
      <th>61</th>
      <td>60</td>
      <td>Reforma e Pobreza</td>
      <td>[socioeducativas, reforma, pobreza, população, fatores, saúde, brasil, brasileira, social, alternativas]</td>
      <td>10</td>
    </tr>
    <tr>
      <th>62</th>
      <td>61</td>
      <td>Prerrogativas e Competências</td>
      <td>[prerrogativas, profissão, atribuições, profissionais, assessoria, regulamenta, profissional, competências, administração, atribuição]</td>
      <td>10</td>
    </tr>
  </tbody>
</table>

![Topic frequency](images/graphs/código_de_ética/topics.png)

Se observarmos os artigos pedidos em cada tópico, teremos os seguintes gráficos:

![Articles by Topic](images/graphs/código_de_ética/articles_by_topic.png)