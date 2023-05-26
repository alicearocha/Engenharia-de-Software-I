# Engenharia-de-Software-I
Atividades da matéria de Engenharia de Software I curso ADS FATEC São José dos Campos

17/02 ATIVIDADE 1:
I. O que é enganharia de software?
qual a relação com programação?
exemplo prático

Texto: "We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play.   On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth."

- comentário: Na engenharia de software, identifica-se a necessidade de desenvolver um software que envelheça bem e que atenda não apenas às necessidades atuais de uma organização, mas também aos seus requisitos futuros. Escolher corretamente não só a linguagem que melhor se encaixa, mas também os requisitos funcionais e não funcionais, sabendo que muitas decisões são difíceis e que às vezes é preciso abrir mão de uma funcionalidade para ganhar outra.

23.02 CONTINUAÇÃO ATIVIDADE 1:
Texto: "Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming  is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming."

- comentário: Apesar da programação ser parte integrante da Engenharia de Software, fica claro a partir da experiencia trazida pelos autores que a Engenharia de Software está longe de ser apenas programação. É levar em consideração o contexto amplo de ciclo de vida do software, sua usabilidade, escoloha de tecnologia, manutenção, é fazer a tomada de decisões que irá ditar a funcionalidade e longividade do software em questão. Tornar a programação e o software funcional através do tempo.


ATIVIDADE 2 - II. O QUE SÃO OS REQUISITOS? 

Os requisitos do software são as necessidades do CLIENTE. 
São divididos em requisitos funcionais e não funcionais: 
Requisitos funcionais são a necessidade do cliente, normalmente são apresentados em verbos. Exemplo: lançar notas no sistema, salvar as informações etc. 
Requisitos não funcionais é o que o sistema não precisa para funcionar, mas que pode ser adicionados. Normalmente são apresentados como adjetivos do sistema. Exemplo: rapidez, acessibilidade etc. 

 Se os requisitos funcionais especificam o que um sistema deve fazer, os requisitos não funcionais descrevem como ele o fará. Por exemplo, o novo aplicativo nos fornecerá a lista final de todos os usuários conectados. Isso faz parte dos requisitos funcionais. Se o requisito disser que o sistema funcionaria apenas em um sistema Windows e Linux, isso faria parte dos requisitos não funcionais. 

 II.2 Requisitos não funcionais: Além disso, os requisitos não funcionais podem ser categorizados em 3 tipos: requisitos de produto final, organizacional e externo. Contudo, também há outras categorias, como:
de eficiência;
de confiabilidade;
de portabilidade;
de entrega;
de implementação;
de padrões;
de interoperabilidade;
éticos;
legais;
de integração.

Requisitos de Produto Final
Os requisitos de produto final são aqueles que estão relacionados ao comportamento do software, como:
tempo de resposta;
velocidade de execução;
latência;
conexão;
portabilidade;
consistência;
mobilidade;
confiabilidade;
segurança;
taxa de erros.

Requisitos Organizacionais
Os requisitos organizacionais são aqueles que estão relacionados aos padrões da organização. Ou seja, o software deve ser desenvolvido de acordo com as políticas e definições da empresa para garantir que o produto final gerado esteja em conformidade com as normas empresariais. Alguns exemplos:
infraestrutura;
sistema operacional compatível;
conexão;
criptografia usada pela empresa;
linguagem de programação requisitada pela empresa (caso já existam outros programas que a utilizam).

Requisitos Externos
Os requisitos externos são aqueles que estão relacionados a qualquer tipo de agente externo ao software. Ou seja, qualquer aspecto não relacionado diretamente com o produto, mas que pode impactar no seu funcionamento deve ser definido. Entre os principais, estão:
localização geográfica em que será usado;
legislação;
sistemas;
política de proteção de dados.


ATIVIDADE 3 - TRADE OFFS:

Em engenharia de software e no desenvolvimento de sistemas computacionais, o termo "trade-off" refere-se a decisões ou escolhas que precisam ser feitas ao projetar, implementar ou gerenciar um sistema. Um trade-off envolve a consideração e a negociação de benefícios e compromissos entre diferentes aspectos do sistema, como funcionalidade, desempenho, usabilidade, segurança, custo, tempo de desenvolvimento e manutenção, entre outros.
Ao criar sistemas computacionais, os trade-offs podem ocorrer em várias áreas, como:
Funcionalidade versus Desempenho: Adicionar mais recursos e funcionalidades a um sistema pode afetar o desempenho, pois pode exigir mais recursos computacionais. É necessário encontrar um equilíbrio entre as funcionalidades desejadas e a velocidade ou eficiência do sistema.
Usabilidade versus Segurança: Medidas de segurança rigorosas podem afetar a usabilidade do sistema. Por exemplo, solicitar autenticação em várias etapas pode aumentar a segurança, mas também pode aumentar a complexidade e a frustração do usuário. É preciso considerar cuidadosamente a experiência do usuário em relação aos requisitos de segurança.
Flexibilidade versus Complexidade: Oferecer um sistema altamente flexível pode aumentar a complexidade de sua implementação. Adicionar muitas opções de configuração e personalização pode tornar o sistema difícil de entender e manter. É necessário encontrar um equilíbrio entre a flexibilidade desejada e a complexidade resultante.
Tempo de Desenvolvimento versus Qualidade: O desenvolvimento rápido pode levar a compromissos na qualidade do software. Pressões para cumprir prazos apertados podem resultar em código mal estruturado, falta de testes adequados e maior probabilidade de erros. É necessário avaliar cuidadosamente a relação entre o tempo de desenvolvimento e a qualidade do produto final.
Custo versus Recursos: Alocar mais recursos, como hardware de alto desempenho ou equipe especializada, pode aumentar os custos do projeto. É importante encontrar um equilíbrio entre os recursos disponíveis e o orçamento atribuído.
Manutenção versus Inovação: À medida que um sistema evolui, a manutenção contínua se torna necessária para corrigir defeitos, atualizar recursos e garantir a estabilidade. No entanto, investir muito tempo e recursos na manutenção pode limitar a capacidade de inovar e introduzir novas funcionalidades. É necessário encontrar um equilíbrio entre manutenção e inovação.
É importante reconhecer que os trade-offs são inevitáveis e que a melhor solução depende dos requisitos e das restrições específicas de cada projeto. Os trade-offs devem ser avaliados e gerenciados de forma cuidadosa para alcançar um equilíbrio adequado entre as diferentes características e metas do sistema.

TRADE-OFFS NA API:
- Escolha da priorização de entregas. Explicação: tivemos que escolher entre entregar toda a parte de cadastramento e armazenamento dos dados dos alunos e funcionalidade das entregas das atividades e depois a parte de edição dos dados dos alunos e das atividades, ou escolher entre ter a parte do cadastramento e armazenamentos dos dados dos alunos junto a parte de edição desses dados e só depois a funcionalidade das entregas. Escolhemos a primeira opção por estar mais alinhada com as requisições do cliente. 
- Tivemos que ponderar entre usar o código cru para a interface gráfica ou o uso do Swing. Explicação: Escolhemos usar o Swing pela dificuldade que o grupo teve com o uso da linguagem + tempo de criação disponível para o projeto + ponderando sobre a vida útil que o projeto teria.


ATIVIDADE 4 - DIAGRAMA DE CLASSES UML

<br>
<img src = "https://github.com/alicearocha/Engenharia-de-Software-I/blob/main/img/Diagrama%20UML%20Sorveteria%20-%20Classe%20UML.png" alt="Diagrama de Classe Sorveteria"/>
