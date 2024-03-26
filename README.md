<h1>Prova técnica Teste de API</h1>

<h2>Instruções</h2>
 
- A aplicação deve executar;
- Realize um fork do projeto;
- Adicione @helton-maia, <colcar o usu do Chuvs>, <colocar o uso do Odione> como membro do seu fork. Você pode fazer isto em https://gitlab.com/'your-user'/tech-test-train/settings/members;
- Quando você começar, faça um commit vazio com a mensagem "Iniciando o teste de tecnologia" e quando terminar, faça o commit com uma mensagem "Finalizado o teste de tecnologia";
- Commit após cada ciclo de refatoração pelo menos;
- Não use branches;
- Tente concluir o projeto em até 4 horas;
- Você deve prover evidências suficientes de que sua solução está completa indicando, no mínimo, que ela funciona utilizando os dados de teste contidos na planilha excel denro da pasta "/massa-de-dados";
- Inclua na pasta "/documentos/" o arquivo instruçoes-executar-projeto.md, para disponibilizar as instruções para execusão do seu projeto.

<h2>Problema a ser resolvido</h2>

A Elo a partir de 2024, será uma das patrocinadoras oficiais das Olimpíadas. O time de Marketing e Campanhas da Elo, em parceira com seus Bancos parceiros, vão lançar, em Abril 2024, para seus clientes, a campanha/promoção "Arquibancada Elo nas Olimpíadas". A campanha consiste em sortear, de Abril/24 a Jun/24, 1 cliente por semana para assistirem os jogos olímpicos. Cada ganhador, terá o direito de levar um acompanhante de sua escolha. Os portadores que se cadastraram na campanha com seus cartões de crédito ou débito da bandeira Elo, poderão ganhar seus números da sorte efetuando compras no valor mínimo de R$ 150,00.

<h2>Regras de Negócios</h2>

- Uma campanha deve ser cadastrada no periodo estimado acima;
- O cliente precisa efetuar um cadastro para campanha; 
- O cliente poderá cadastrar todos os seus cartões da Bandeira Elo;
- A cada compra que o cliente fizer no valor mínimo de R$ 150,00, ele ganha 1 número da sorte;
- Caso o valor da compra seja maior ou menor, o sistema deverá gardar para que a próxima compra seja somada a esse valor até chegar no valor de R$ 150,00 e disponibilizar o número da sorte;
- Os bilhetes sorteados deverão possuir uma identificação a ser retornada na lista de números da sorte co cliente. 

<h2>O que você deve entregar considerar como entrega?</h2>

Para entrega do exercício, considere os seguintes serviços:

- Cadastrar Campanha;
- Cadastrar cliente na campanha (não se preocupe com login, senha. Use apenas os dados do cliente contidos na planilha); 
- Simular a transação do cartão e gerar números da sorte;
- Efetuar os sorteios.

*<h4>Você deverá, obrigatoriamente, utiliar as seguintes tecnologias</h4>*

- Java 11 em diante;
- Framework Spring (Boot, Security, etc.);
- Banco de Dados a seu critério (Sugiro: MySql ou SQL);
- Faça o teste unitário na classe que vai transacionar e gerar o número da sorte via JUNIT (Será um diferencial se entregar mais classes com testes).

<h2>Como você será avaliado</h2>

***<h4>Etapa 1</h4>***

Iremos avaliar seu projeto considerado as seguintes premissas:

- A aplicação deve executar sem erros;
- Seus conhecimentos sobre O.O., Arquitetura de Software, uso das boas práticas de desenvolvimento (SOLID, uso de algum design partner);
- Seus conhecimentos sobre design de API utilizando as boas práticas de construção api rest (Ref. Open API, uris, métodos de chamadas, tipos de retorno);
- Seus conhecimentos sobre Modelagem de Dados e conectividade com outros microserviços;
- Seus conhecimentos sobre testes unitários;
- Seus conhecimentos de uso do GitHub;
- Software funcionando e atendendo as regras acima.

***<h4>Etapa 2</h4>***

- Se necessário, faremos essa etapa de avaliação que será mais uma entrevista técnica com você para falarmos sobre seu projeto entregue;

***<h3>Boa sorte!</h3>***
