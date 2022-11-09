# Resposta ao relatório

## Sumário

0. Contexto desse relatório
1. Argumento de diferença dos modelos das urnas
1. Argumento da diferença de software entre as urnas

## 0. Contexto do relatório

Recebi o arquivo "RELATÓRIO PRELIMINAR DE ANÁLISE DAS URNAS ELETRÔNICAS USADAS NA ELEIÇÃO PRESIDENCIAL DO BRASIL NO PRIMEIRO TURNO – 02 DE OUTUBRO DE 2022" - o arquivo depois foi apresentado em uma live no twitch e Gettr.

O "relatório" que recebi é na verdade uma apresentação de 70 slides, dividido em dois argumentos. Que ocorreu na eleição de 2022: diferença entre modelos de urnas auditadas e não-auditadas e diferença de software dentro das urnas.

### Coisas que não vou responder nesse documento

* Porque o site do TSE saiu do ar depois da live;
* Se existem diferenças de resultados entre modelos de urnas;
* Se o TSE está sendo justo com seus críticos;
* Se houve fraude na eleição de 2022;
* Qualquer coisa relacionada a outras eleições;


Esse documento só existe para explicar a fragilidade das premissas dos argumentos apresentados. **Quem tem que provar algo com premissas fortes é quem está acusando a eleição de fraude**.

## 1. Diferença entre modelos das urnas eletrônicas

O primeiro argumento é baseado na seguinte hipótese:

> Hipótese: Os modelos de urna podem determinar votos para o candidato 13 ou 22? Ou seja, há interferência das urnas nas votações?

Os autores escolhem para comparação os resultados da urna modelo 2020 (UE2020) comparando com os resultados das urnas de modelos anteriores (UE2015, UE2013, UE2011, UE2010 e UE2009).

Essa escolha foi justificada pela afirmação que 

> As urnas de modelo anterior a 2020 não têm qualquer documentação de auditoria recente, e relatórios anteriores referem não serem passíveis de auditoria. Não há documentação comprobatória acerca dos modelos 2009/2010/2011/2013/2015.

Existe aqui na minha opinião um erro conceitual, a rotina mais importante realizada antes das eleições são os *testes* das urnas, uma *auditoria* seria uma rotina relevante após a eleição.

Então a pergunta relevante para a hipótese proposta é: "Qual dos modelos de urnas foi melhor testada para essa eleição?". 

O TSE para 2022 realizou testes em dois modelos de urnas. O Teste Público de Segurança (TPS), **que é a rotina mais completa de testes realizada pelo TSE** foi realizada com o modelo 2015 das urnas, como pode ser verificado no [edital publicado pelo TSE](https://www.justicaeleitoral.jus.br/tps/arquivos/TPS-edital.pdf).

Além disso, após pressão de setores da academia e dos militares, foi realizado um teste [nas urnas modelo 2020](https://www.tse.jus.br/comunicacao/noticias/2022/Agosto/universidades-validam-nova-urna-e-codigos-fonte-dos-sistemas-eleitorais-357621). Esse teste foi menor que o TPS realizado no modelo 2015, realizado por uma equipe - ao invés de 109 investigadores como o teste público.

Então a base de comparação, UE2020 *vs.* modelos anteriores, é baseada ou em uma mentira, ou em um erro conceitual.

Se o objetivo era comparar urnas com maior garantia de funcionamento fidedigno, a comparação deveria ser entre as urnas UE2015 e os outros modelos.

## 2. Diferença entre códigos-fontes

O segundo argumento proposto no final dos slides é que houveram códigos diferentes dentro de um mesmo modelo de urna.

Essa afirmação é baseada em uma diferença apontada em uma linha de log gravada durante a configuração da urna pelo TSE.

Vale indicar que essa afirmação **é mais importante e baseada em uma evidência mais forte que a anterior**. Aqui cabe a cobrança para que o TSE demonstre que essa afirmação é falsa.

O problema da evidência usada para embasar esse argumento é que os logs que indicaram alguma diferença são logs realizados durante uma interação usuário-máquina. Esse tipo de log pode ser influenciado por comportamento diferente de usuários diferentes.

A afirmação que o relatório faz que "nada explica a diferença entre os logs" é uma conclusão errada, o mesmo software operado de modo diferente pelo usuário vai gerar logs diferentes. Resta ao TSE demonstrar como isso acontece para que seja encerrada essa questão.


## Conclusão

O relatório simplesmente aponta duas *curiosidades* sobre a eleição brasileira, e levanta suspeitas sobre a eleição baseado nisso. Ele não contém nenhuma informação que seja uma evidência forte os suficiente de fraude ou mal funcionamento.

O único ponto relevante (sobre os logs) pode ser encerrado com uma demonstração simples do TSE ou de outros que contenham acesso a urna.

## Propaganda

Acha que esse tipo de análise vale de alguma coisa? Me manda um trocado lá no [github sponsors](https://github.com/sponsors/projeto7c0)

## Atualizações

Estou deixando esse texto no github para que as pessoas possam ler eventuais alterações que forem incluídas. 

* O usuário [Johnson Aquino](https://twitter.com/aquino_johnson/status/1589203772357873664) sugeriu melhorias para o texto que não estava claro.