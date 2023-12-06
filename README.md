# Puc Fit

O objetivo do Puc Fit é otimizar a gestão operacional, oferecendo uma plataforma integrada para automação de processos, como cadastro de clientes, alocação de clientes em turmas e cadastro de professor. Essa ferramenta visa melhorar a eficiência, reduzir erros e retrabalho, proporcionando uma experiência mais fluida tanto para os clientes quanto para a equipe administrativa. 

Ao centralizar e automatizar tarefas, o sistema contribui para uma administração mais eficaz, permitindo que a equipe dedique mais tempo a atividades de maior valor, como oferecer suporte personalizado aos clientes e aprimorar seus resultados de condicionamento físico.


##1. Introdução
Em um contexto de constantes inovações tecnológicas, o setor fitness se destaca tanto pelas oportunidades quanto pelos desafios que emergem destas transformações. Com a evolução do comportamento do consumidor e a crescente busca por saúde e bem-estar, as academias se tornaram espaços essenciais para muitos indivíduos, reforçando a necessidade de processos otimizados e sistemas de gestão eficientes (Censo Fitness, 2022).
Apesar desta crescente demanda, os dados do Censo Fitness (2022) indicam que uma parcela significativa destes estabelecimentos ainda não adotou sistemas digitais para a gestão e administração dos seus processos, sobretudo nos cadastros de clientes e elaboração de treinos personalizados. Tal lacuna pode representar uma barreira no atendimento às expectativas de um público cada vez mais digitalizado.

Problema: A ausência de sistemas digitais nas academias pode acarretar ineficiências operacionais, desde a recepção até a elaboração de treinos. Tais ineficiências podem comprometer a experiência do cliente e a eficácia das atividades dos profissionais envolvidos.
Motivação: A adoção de sistemas digitais nas academias não apenas atenderia a demanda de um público mais tecnológico, mas também proporcionaria uma gestão mais eficiente, otimizando o tempo dos colaboradores (recepcionistas e professores) e permitindo uma experiência mais personalizada para os clientes. Diante disso, surge a necessidade de desenvolver um sistema que integre os processos de gestão das academias, desde o cadastro de clientes até a entrega de treinos personalizados.

1.1. Objetivos geral e específicos
Este trabalho tem como objetivo principal desenvolver um sistema de automação destinado ao processo de cadastro de treinos personalizados e à gestão de clientes em uma academia, visando aprimorar a eficiência e a organização dessas atividades.
Objetivos Específicos:
Elaborar uma plataforma que permita o cadastro detalhado dos treinos personalizados..
Implementar um sistema de cadastro de clientes que facilite o armazenamento e acesso às informações relevantes.
1.2. Justificativas
A relevância deste projeto reside na necessidade de otimizar e modernizar os procedimentos manuais de cadastro de treinos e gestão de clientes em academias. A automação desses processos simplificará a rotina dos instrutores, possibilitando o direcionamento mais eficiente dos treinos de acordo com as necessidades individuais de cada cliente. Além disso, a centralização das informações dos clientes em um sistema digital contribuirá para a rápida recuperação de dados e melhor acompanhamento de seu progresso ao longo do tempo. Essa solução resultará em uma experiência mais satisfatória para os clientes, aumentando sua motivação e engajamento. 
2. Participantes do processo de negócio
Os participantes-chave do sistema incluem:
CLIENTES: aqueles que contrataram um plano na academia e usufruem dos seus serviços.
Acessam o treino personalizado na plataforma;
Informam se treinaram hoje.
RECEPCIONISTAS: responsáveis por verificar, registrar e modificar os planos e cadastros dos clientes.
Cadastram os clientes na plataforma;
Gerenciam os cliente na plataforma;
PROFESSORES: responsáveis por cadastrar treinos personalizados na plataforma.
Cadastram treinos personalizados.
3. Modelagem do processo de negócio
3.1. Análise da situação atual (AS-IS)
Cadastro de cliente
No processo manual atual de cadastro de clientes na academia e ginástica, os clientes em potencial precisam preencher formulários impressos com suas informações pessoais, como nome, endereço, número de telefone, data de nascimento, histórico médico e metas de condicionamento físico. Esses formulários são fornecidos na recepção da academia e devem ser preenchidos à mão demandando muito tempo e uma falta de acesso fácil aos dados dos clientes.
Automatizar o processo de cadastro de clientes não apenas aumentaria a eficiência operacional, mas também melhoraria a qualidade do atendimento ao cliente e reduziria erros e retrabalho. Isso permitiria que a equipe se concentrasse em atividades mais valiosas, como fornecer orientação personalizada aos clientes e melhorar seus resultados de condicionamento físico.



Alocação de clientes em turmas
 No atual cenário de alocação de clientes em turmas de academia e ginástica, o processo é predominantemente manual e propenso a ineficiências. A alocação de clientes em turmas específicas muitas vezes depende de listas impressas e planilhas físicas, o que torna o procedimento suscetível a erros e limita a visibilidade em tempo real da disponibilidade de cada turma. Os clientes, ao se inscreverem para aulas, preenchem formulários em papel na recepção, e a alocação é então realizada manualmente pela equipe, resultando em idas e vindas para acomodar solicitações ou corrigir possíveis conflitos. 

Automatizar o processo de alocação de clientes em turmas não apenas agilizaria a administração das inscrições, mas também proporcionaria uma visão instantânea da disponibilidade de cada turma, otimizando a distribuição de alunos. Isso não só aumentaria a eficiência operacional, mas também melhoraria a experiência do cliente, permitindo uma escolha mais flexível de horários e reduzindo a probabilidade de conflitos de agendamento.
‘
Cadastro de professor
No modelo As-Is de cadastro de professores em uma academia, o processo é majoritariamente manual e suscetível a ineficiências. Os professores interessados em integrar a equipe da academia precisam preencher formulários em papel, fornecendo detalhes como nome, endereço, contato, experiência profissional e habilidades específicas. Esses documentos, uma vez preenchidos, são submetidos à administração da academia, muitas vezes resultando em idas e vindas para correções ou esclarecimentos adicionais.

Esse método não só consome tempo considerável, mas também pode levar a erros de interpretação e retrabalho. Ao migrar para um modelo mais automatizado, seria possível agilizar o processo de cadastro, reduzir as redundâncias e proporcionar uma gestão mais eficaz das informações dos professores, resultando em benefícios tanto para a administração quanto para os próprios profissionais, que teriam uma experiência mais fluida e eficiente ao ingressarem na equipe da academia.

3.2.  Modelagem dos processos aprimorados (TO-BE) 
Cadastro de cliente
O cliente será cadastrado com todas as informações necessárias como nome completo, endereço, data de nascimento, número de telefone e endereço de e-mail. As informações fornecidas pelo cliente são registradas, criando um perfil para o novo cliente.


Alocação do cliente em turmas
Com base nas preferências do cliente e na disponibilidade de horários nas turmas escolhidas, o sistema de gerenciamento da academia aloca o cliente nas turmas correspondentes.

Cadastro de professor
O Professor será cadastrado com todas as informações necessárias como nome completo, endereço, data de nascimento, número de telefone e endereço de e-mail. As informações fornecidas pelo professor são registradas. 

4. Projeto da arquitetura de dados da solução proposta
4.1. Diagrama de Entidades e Relacionamentos (DER)

4.2. Impactos da implementação em um banco de dados NoSQL
Ao considerar a implementação da solução proposta usando um banco de dados NoSQL, diversos fatores e aspectos são relevantes para serem abordados.
Escala e Performance: A natureza distribuída de muitos bancos de dados NoSQL permite que a solução escale horizontalmente. Isso é especialmente útil para lidar com grandes volumes de dados e para garantir performance mesmo com o crescimento do número de clientes e treinos personalizados.
Flexibilidade de Estrutura: Sem a necessidade de um esquema fixo, a solução pode adaptar-se mais facilmente a mudanças nos requisitos de dados, permitindo, por exemplo, adicionar novos atributos ao cadastro de treinos ou clientes sem grandes alterações.
Disponibilidade: Alguns sistemas NoSQL, especialmente os baseados em sistemas distribuídos, têm alta disponibilidade, sendo ideais para aplicações que não podem ter tempo de inatividade.
Consistência: Muitos bancos NoSQL adotam um modelo eventualmente consistente, o que pode levar a situações onde os dados não são refletidos imediatamente em todas as partes do sistema.
Complexidade de Consulta: Bancos de dados NoSQL podem não suportar a ampla gama de operações de consulta que os bancos de dados relacionais tradicionais suportam. Isso pode tornar algumas operações mais complexas de serem implementadas.

4.3. Modelo relacional


5. Relatórios analíticos


Relatório "Alunos por Modalidade"
Objetivo: Este relatório visa fornecer uma visão clara da distribuição de alunos nas diferentes modalidades oferecidas, auxiliando na alocação de recursos e no planejamento estratégico.

Relatório "Total de Alunos"
Objetivo: Oferece uma visão geral da academia , essencial para entender o tamanho e a escala das operações da instituição.


Relatório "Professor por Modalidade"
Objetivo: Este relatório ajuda a entender a distribuição de professores pelas diversas modalidades, facilitando a gestão de recursos humanos e a coordenação acadêmica.
  
 5.1. Associação de comandos SQL com relatórios analíticos
Nome do Relatório Analítico
Comando SQL-DML (SELECT)
Alunos por Modalidade
SELECT
  modalidade.NomeModalidade AS modalidade,
  COUNT(*) AS quantidade_alunos
FROM
  aluno
  INNER JOIN turma ON aluno.id = turma.id_aluno
  INNER JOIN modalidade ON turma.id_modalidade = modalidade.id
GROUP BY
  modalidade.nome
Total de Alunos
SELECT COUNT(*) AS total_alunos
FROM aluno;
Professor por Modalidade
SELECT
  modalidade.nome AS modalidade,
  professor.nome AS professor
FROM
  modalidade
  INNER JOIN professor ON modalidade.instrutor_principal = professor.id;
Alunos por Professor
SQL
SELECT
  aluno.nome AS aluno,
  professor.nome AS professor
FROM
  aluno
  INNER JOIN turma ON aluno.id = turma.id_aluno
  INNER JOIN modalidade ON turma.id_modalidade = modalidade.id
  INNER JOIN professor ON modalidade.instrutor_principal = professor.id;


6. Indicadores de desempenho
Indicador
Objetivo
Descrição
Fórmula de cálculo
Fontes de dados
Perspectiva
Média de Alunos por Modalidade
Avaliar o envolvimento médio dos alunos em diferentes modalidades
Média do número de alunos matriculados em cada modalidade em relação ao total de modalidades oferecidas
Σ (Alunos por Modalidade) / Total de Modalidades
Tabela Alunos por Modalidade
Aprendizado e Crescimento
Taxa de Crescimento de Clientes Mensal
Avaliar o aumento mensal no número de clientes
Percentual de crescimento no número total de clientes em relação ao mês anterior
[(Clientes Atuais - Clientes do Mês Anterior) / Clientes do Mês Anterior] * 100
Gráfico total de alunos
Cliente e Processos Internos
Taxa de Crescimento de Alunos por Modalidade
Avaliar a popularidade das modalidades oferecidas 
Percentual de crescimento no número de alunos em uma modalidade em relação ao período anterior
[(Alunos Atuais - Alunos Anteriores) / Alunos Anteriores] * 100
Tabela alunos por Modalidade
Processos Internos
Taxa de Participação de Professores por Modalidade
Medir o engajamento dos professores em diferentes modalidades
Percentual de modalidades em que um professor está envolvido em relação ao total de modalidades
(Modalidades com Professor / Total de Modalidades) * 100
Tabela professor por modalidade
Professor e Processos Internos
Índice de Retenção de Alunos
Avaliar a capacidade de manter alunos matriculados
Percentual de alunos que permanecem matriculados em relação ao total de alunos matriculados
(Alunos Retidos / Total de Alunos) * 100
Gráfico total de alunos
Cliente


7. Conclusão
Apresentem aqui a conclusão do trabalho que deve conter uma síntese dos principais resultados obtidos com a melhoria dos processos, uma discussão das limitações da solução proposta e sugestões de novas linhas de estudo. 

REFERÊNCIAS
CENSO FITNESS. Relatório sobre o panorama do setor fitness no Brasil. 2022. Disponível em: https://censofitness.com.br/. Acesso em: 25 ago. 2023.
Como um projeto de software não requer revisão bibliográfica, a inclusão das referências não é obrigatória. No entanto, caso vocês desejem incluir referências relacionadas às tecnologias, padrões, ou metodologias empregadas no trabalho, relacione-as de acordo com a ABNT.
Verifiquem no link abaixo como devem ser as referências no padrão ABNT:
http://www.pucminas.br/imagedb/documento/DOC_DSC_NOME_ARQUI20160217102425.pdf

## Integrantes

* Eduardo Medeiros de Moraes
* Ana Corina Damas Batista
* André Santana
* Carlos Alberto Morais Junior
* João Pedro Lindenberg Pimenta
* João Ricardo Rezende Vaz de Mello

## Professor

* Juliana Amaral Baroni de Carvalho

