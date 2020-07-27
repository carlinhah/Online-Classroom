# Online-Classroom

Utilizando o dataset  E-Learning Student Reactions disponível no Kaggle, queremos classificar o comportamento dos alunos com tendo como base as "reações online" durante uma disciplina.  Trabalharemos com os atributos abaixo que dispõem de pontuação concernente as "Habilidades do Século 21", em uma escala de 0 a 10 em cada Habilidade, e o "Tempo Online" dos alunos.

**timeonline** - Tempo total que o aluno passou online durante a disciplina;<br/>
**sk1_classroom** - Habilidades de pensamento crítico e capacidade de resolução de problemas;<br/> 
**sk2_classroom** - Habilidades de criatividade e inovação;<br/>
**sk3_classroom**- Habilidades auto-aprendizado ;<br/>
**sk4_classroom** - Habilidades de colaboração e auto-direção;<br/>
**sk5_classroom** - Responsabilidade social e cultural;<br/>

Utilizando os algorítmo machine learning queremos  dentro de nossa análise identificar a correlação entre as variáveis para responder algumas perguntas como :

O tempo online (timeonline) aluno tem influência sobre sua pontuação nas habilidades descritas nas SKs?<br/>
A aprovação do aluno (Approved) foi baseada no seu tempo online?<br/>
As habilidades (SKs) tiveram influência sobre a aprovação (Approved) ?<br/>

Como descrito anteriormente para realização desse experimento utilizamos os algoritmos foram sugeridos sob a supervisão do professor Dr. Rafael listados abaixo para predizer ou classificar os seguintes problemas: 

**Sugestão 1:** Predizer o valor TEMPO baseado nas skills (KNN);<br/>
**Sugestão 2:** Classificar nível do aluno (Básico, interm., Avançado) utilizando as avaliações (Decision Tree ou Random Forest);<br/>
**Sugestão 3:** Predizer o valor de aprovação (binário) considerando os tipos de reações (Regressão linear).<br/>
