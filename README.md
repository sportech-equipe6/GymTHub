
# Projeto GymTHub: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: https://padlet.com/isacbaia2005/my-luminous-padlet-euc2c72lmjqc4qxe

## 1. Introdução

***1.1.  Nome do Grupo***

Gabriel Cecilio Menezes - RA2623404 <br />
Isadora Costa Baía - RA2614685 <br />
João Flávio Loureiro - RA2525828 <br />
Pedro Henrique Zanatta - RA2601443 <br />
Vitória Cardoso - RA2312174

***1.2.  Nome do Sistema***

GymTHub

***1.3.  Propósito do Sistema***

Facilitar o registro e acompanhamento de treinos e dieta. Ter todas as ferramentas relacionadas a "bem-estar" e vida saudável no mesmo local.

***1.2.  Público Alvo***

Estudantes universitários que frequentam academia e buscam um maior controle da sua rotina.

***1.3. Descrição dos usuários***

Estudantes e frequetadores de academia que buscam organizar melhor os seus treinos, alimentação e relacionados devido a rotina corrida e ocupada.

***Personas:***

[Persona 1](https://github.com/sportech-equipe6/GymTHub/blob/c4f4b2fdaaacf8691680ec7ba39bd8e30334d99b/Personas/Persona1.jpeg)
[Persona 2](https://github.com/sportech-equipe6/GymTHub/blob/c4f4b2fdaaacf8691680ec7ba39bd8e30334d99b/Personas/Persona2.jpeg)

***Análise da situação atual: antes da introdução de sua solução***

1. **O que as pessoas fazem?**  
   Tentam organizar treinos e dietas de forma manual ou utilizando múltiplos aplicativos, o que resulta em informações fragmentadas e desorganizadas.

2. **Quais os artefatos envolvidos?**  
   Blocos de notas, planilhas, aplicativos pagos com funcionalidades limitadas e materiais impressos.

3. **O que elas precisam saber?**  
   Que a falta de um sistema unificado e acessível dificulta o planejamento, o acompanhamento e a consistência na adoção de hábitos saudáveis.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

1. **O que as pessoas fazem?**  
   Utilizam o **GymTHub** para planejar, registrar e acompanhar treinos, dietas e metas de bem-estar em um único lugar.

2. **Quais os artefatos envolvidos?**  
   Aplicativo **GymTHub**, dispositivos móveis e integrações com wearables (como smartwatches).

3. **O que elas precisam saber?**  
   Que o **GymTHub** centraliza informações de treinos e dietas, facilita o planejamento e acompanhamento da rotina e incentiva hábitos saudáveis, de forma prática e acessível.

***Cenário: Antes***

Ana Carolina é uma estudante bem conectada as redes sociais o que leva uma facilidade em mexer com tecnologia. Ela geralmente utiliza o próprio bloco de notas já integrado no seu celular para organizar seus prórpios treinos. Devido a esse meio de organização, Ana esquece de consultar sua rotina e tem um certo desinteresse em ficar consultando o bloco de notas para revisar seus treinos e alterá-los. 

A inteface simples do bloco de notas faz com que Ana não consiga manter a atenção e o interesse por muito tempo, o que acaba em não construir um hábito de visitas no aplicativo e algumas das vezes acaba esquecendo de seu compromisso, assim perdendo a sua motivação.

***Cenário: Depois***

Ana agora podia planejar e acompanhar seus treinos de maneira mais visual.Com uma interface mais interativa visualmente, ela começou a se habituar com o aplicativo e passou a consulta-lo mais para atualizar sua rotina de treinos.Com essa facilidade ela se sentia mais engajada aos seus objetivos de uma forma mais gratificante. 

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

[Requisitos Funcionais](https://github.com/sportech-equipe6/GymTHub/blob/e500b27f0e644d49a3c9182ad6e5a8a76fea8ea7/Requisitos/Requisitos%20Funcionais.pdf)
|ID| Requisito Funcional | Prioridade | Depende de |
|--|--|--|--|
| RF01 | O software deve permitir que o usuário faça cadastro da sua conta. | Alta | 
| RF02 | O software não deve permitir que um usuário faça o seu cadastro caso as informações obrigatórias não tenham sido preenchidas. | Alta | RF01 | 
| RF03 | O sistema deve permitir que o usuário vincule um treino cadastrado a uma data e uma frequência específicas. | Média |
| RF04 | O software deve permitir que usuários interajam entre si por mensagem. | Baixa | RF01 | 
| RF05 | O software deve permitir que o usuário salve ou avalie o treino de outros usuários | Baixa | RF01, RF03
| RF06 | O software deve enviar ao usuário no final do treino um relatório com tempo total, tempo em cada exercício e carga em cada exercício. | Média | RF03 |
| RF07 | O software deve permitir que o usuário acesse uma área de configuração de conta para que as suas informações sejam alteradas. | Baixa | RF01 | 
| RF08 | O software deve permitir que o usuário altere os dados da sua própria tabela de treino. | Média | RF03 |
| RF09 | O software deverá permitir que o usuário defina metas específicas, como peso-alvo, ingestão diária de água ou calorias. | Média | RF01 |
| RF10 | O software deverá apresentar um painel de progresso que exiba estatísticas e gráficos atualizados sobre o desempenho do usuário em relação às metas estabelecidas. | Média | RF09 |

***2.2. Requisitos Não Funcionais***

[Requisitos Não Funcionais](https://github.com/sportech-equipe6/GymTHub/blob/e500b27f0e644d49a3c9182ad6e5a8a76fea8ea7/Requisitos/Requisitos%20Na%CC%83o-Funcionais.pdf)
|ID| Requisito Não-Funcional | Prioridade | 
|--|--|--|
| RNF01 | O sistema deve suportar 10.000 usuários concorrentemente. | Alta | 
| RNF02 | O sistema deve ser operacionalizado em iOS e Android. | Média | 
| RNF03 | O sistema deve proteger os dados do usuário de acordo com a LEI Nº 13.853, Lei Geral de Proteção de Dados. | Alta |
| RNF04 | O sistema deve interagir com os sistemas da Google Workspace e Microsoft Office.| Baixa |  
| RNF05 | O usuário deve conseguir atualizar as informações de cada treino em 4 cliques.| Média |
| RNF06 | O executável do sistema não deve ser superior 200Mbytes. | Baixa | 
| RNF07 | O sistema deve estar disponível 99.9% do tempo (uptime). | Alta | 
| RNF08 | Notificações devem ser enviadas em menos de 10 segundos de um evento programado. | Média | 
| RNF09 | O sistema não deve informar aos operadores nenhuma informação pessoal dos usuários. | Alta | 
| RNF10 | O usuário deve ser capaz de utilizar todas as funcionalidades da aplicação após um tutorial de 2 min. | Baixa | 

***2.3. Perguntas***

Perguntas para a entrevista: <br />
•⁠  ⁠Qual sua rotina na academia ? (Quantas vezes vai por semana) <br />
•⁠  ⁠⁠Na academia qual a rotina que ele faz ? (Pode ser de vários dias) <br />
•⁠  ⁠⁠Ele usa algum aplicativo que auxilia ele na academia ? <br />
•⁠  ⁠⁠Ele possui algum profissional que auxilia ? (Nutricionista, personal) <br />
•⁠  ⁠⁠Fora da academia ele faz alguma ação que ajuda ele nos ganhos ? (Uma dieta específica etc) <br />
•⁠  ⁠⁠De toda essa rotina (dentro e fora da academia) o que ele acha mais difícil de manter a longo prazo ?<br />

***2.4. Entrevista***

[Transcrição entrevista](Entrevista/Entrevista.md)
[Áudio entrevista](https://drive.google.com/file/d/1i8KlhvbOVmuHW5kWf2TbrBFYyNpf0B8m/view?usp=drive_link)

***2.5. Histórias do Usuário***

|ID| User Story  |
|--|--|
| US01 | Como usuário, quero criar uma conta preenchendo as informações obrigatórias, para acessar todas as funcionalidades do sistema. |
| US02 | Como usuário, quero receber uma mensagem de erro clara se eu não preencher todas as informações obrigatórias ao tentar criar minha conta, para saber o que falta corrigir. |
| US03 | Como usuário, quero acessar uma área de configuração de conta, para poder alterar minhas informações pessoais facilmente. |
| US04 | Como usuário, quero vincular um treino a uma data e frequência específicas, para organizar minha rotina de exercícios. |
| US05 | Como usuário, quero acessar um painel de progresso com estatísticas e gráficos atualizados, para visualizar meu desempenho em relação às metas estabelecidas. |
| US06 | Como usuário, quero salvar ou avaliar os treinos de outros usuários, para marcar treinos que gostei e ajudar a comunidade com meu feedback. |
| US07 | Como usuário, quero definir metas específicas como peso-alvo, ingestão diária de água ou calorias, para acompanhar meu progresso de forma personalizada. |
| US08 | Como usuário, quero criar um treino personalizado adicionando exercícios específicos, definindo séries, repetições, carga e tempo para cada um, para atender às minhas necessidades e objetivos de condicionamento físico. |

***2.6. Diagramas de Caso de Uso e Especificações***<br />
[Descrição do Caso de Uso](https://drive.google.com/file/d/17zF2bBpkwdJ5EHKUWMGrHt99T8eYRaQJ/view?usp=sharing)<br />
[Diagrama de Caso de Uso](./Diagramas)

***2.7. Diagramas de Atividades***<br />
[Diagrama de Atividade](./Diagramas)


***2.8. Diagrama de Classes***

[Diagrama de Classes](./Diagramas)

***2.9. Protótipos***

[Protótipo](https://ninjamock.com/s/N95N2Lx)

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
