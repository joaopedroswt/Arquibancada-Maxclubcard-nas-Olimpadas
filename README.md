<h1>Prova técnica Teste de API</h1>

<h2>Instruções</h2>
 
  - Realize um fork do projeto
  - Adicione @pottencial (Pottencial Seguradora) como membro do seu fork. Você pode fazer isto em https://gitlab.com/`your-user`/tech-test-train/settings/members;
  - Quando você começar, faça um commit vazio com a mensagem *"Iniciando o teste de tecnologia"* e quando terminar, faça o commit com uma mensagem *"Finalizado o teste de tecnologia"*;
  - Commit após cada ciclo de refatoração pelo menos;
  - Não use branches;
  - Tente não gastar mais de 6 horas para concluir o teste técnico;
  - Explique para nós, de forma detalhada, a solução dada no arquivo, /documentos/solucao-dada.txt
  - **Não obrigatório**: se tiver o desenho da solução, diagrama de sequencia, diagrama de relacionamento das tabelas, etc., compartilhe também no diretório /arquivos/ o print de cada diagrama feito.

*<h4>Informações para uso</h4>*

- Use o serviço https:://...... para fazer algumas validações de regras de negócio. Ao passar o número do cartão e CPF do portador, o serviço irá fazer as validaçoes de titularidade do cartão, se é cartão bandeira Elo, etc. e retornará se o portador é elegível ou não a campanha;
- Utilize a planilha excel denro da pasta /massa-de-dados/ para utiliar as informaçÕes para simular seu projeto;
- Inclua no arquivo, /documentos/instruçoes-executar-projeto.txt, para disponibilizar as instruções para execusão do seu projeto.

<h2>Problema a ser resolvido</h2>

A Elo a partir de 2024, será uma das patrocinadoras oficiais das Olimpíadas. O time de Marketing e Campanhas da Elo, em parceira com seus Bancos parceiros, vão lançar, em Abril 2024, para seus clientes, a campanha/promoção ***"Arquibancada Elo nas Olimpíadas"***. 

A campanha consiste em sortear, de Abril/24 a Jun/24, 5 portadores do cartão da Bandeira por mês para assistirem os jogos olímpicos. Cada ganhador, terá o direito de levar um acompanhante de sua escolha.

Os portadores que se cadastraram na campanha com seus cartões de crédito ou débito da bandeira, poderão ganhar seus números da sorte efetuando compras no valor mínimo de R$ 150,00.

*<h4>Restrição</h4>*

Os colaboradores da Bandeira Elo não estão elegíveis a participarem da campanha. 

Para que a campanha seja lançada, o time de Marketing e Campanhas necessita que o time de tecnologia desenvolva o backend para se comunicar com o site e fazer o gerenciamento da campanha. Sua equipe será responsável por executar esse projeto.

<h2>Regras de Negócios</h2>

Durante a reunião de refinamento, foi apresentado, pelo time de Marketing e Campanhas à sua equipe, as seguintes regras de negócio:

*<h4>Portadores:</h4>*

- Só poderá participar da camapnha, portadores que cadastrarem seus cartões de crédito ou débito da Bandeira Elo;
- O portador poderá cadastrar quantos cartões ele tiver em sua titularidade;
- Os cartões adicionais, ou seja, cartÕes crédito ou débito de có-titulares, só poderão ser cadastrados pelo mesmo. O titular não é elegível a cadastrá-los;
- Não é elegível a participar da camapanha os colaboradores da Bandeira Elo. Seja ele titular ou có-titular dos cartões de crédito ou débito.

*<h4>Geração do número da sorte</h4>*

- A cada compra no valor mínimo de R$ 150,00 que, o portador participante da campanha, fizer com seus cartões cadastrados, ganha 1 número da sorte. Caso o valor da compra seja maior, o sistema deverá gardar a diferença para que a próxima compra seja somada a esse valor para que um novo número da sorte seja disponibilizado ao chegar no valor mínimo.

O valor das compras a ser considerado é a soma de todas as compras feitas em todos os cartões cadastrados na campanha.

*<h4>Sorteio</h4>*
  
- Todo dia 27 de cada mês, até a vigência da campanha, sorteará 5 números da sorte;
- O sorteado só poderá ser premiado uma única vez enquanto a campanha estiver vigente;
- Os bilhetes sorteados deverão possuir uma identificação a ser retornada na lista de números da sorte. 

<h2>O que você deve entregar para solucionar o problema</h2>

Para resolver o problema, sua equipe deve disponibilizar api's que permitirá:

- CRUD de potadores para para participar campanha
- CRUD para os cartões de crédito e débito dos portadores;
- Gerar números da sorte;
- Efetuar sorteios;

***"Se atentem as regras de negócio acima"***

*<h4>Você deverá, obrigatoriamente, utiliar as seguintes tecnologias</h4>*

- Java 11 em diante;
- Framework Sprint (Boot, Security, etc.);
- Banco de Dados a seu critério (Sugiro: MySql ou SQL);
- Sua aplicação deverá rodar em um container (Docker);
- JUNIT para testes unitários (mínimo de covarage aceitável será de 95% em todo o projeto);

<h2>Como você será avaliado</h2>

***<h4>Etapa 1 - Eliminatória</h4>***

Iremos avaliar seu projeto considerado as seguintes premissas:

- A aplicação deve executar sem erros;
- Seus conhecimentos sobre O.O., Arquitetura de Software, uso das boas práticas de desenvolvimento (SOLID, uso de algum design partner);
- Seus conhecimentos sobre design de API utilizando as boas práticas de construção api rest (Ref. Open API, uris, métodos de chamadas, tipos de retorno);
- Seus conhecimentos sobre Modelagem de Dados e conectividade com outros microserviços.
- Seus conhecimentos sobre testes unitários;
- Seus conhecimentos de uso do GitHub;
- Software funcionando e atendendo as regras acima;

***<h4>Etapa 2 - Eliminatória</h4>***

- Se necessário, faremos essa etapa de avaliação que será mais uma entrevista técnica com você para falarmos sobre seu projeto entregue;

***<h3>E lembrem-se, "Menos é Mais". Boa sorte!</h3>***
