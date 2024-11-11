
   Middleware é um tipo de software utilizado para agrupar as outras camadas de um software entre a aplicação final e o fornecimento de dados. Utilizando-se para realizar os trabalhos 
  de comunicação com as informações e muitas vezes de fontes diferentes, ele pode agir como uma camada que pode funcionar de uma forma bem distinta do restante da aplicação. Então quando
  falamos sobre uma aplicação de uma Arquitetura de Middleware tem em mente que pode se existir difenças de protocolos, plataformas, arquiteturas, ambientes e até sistemas operacionais.
  Portanto não é algo que se pertence a aplicação e pode ser desencaixada se necessário.

                        REQUISIÇÃO ----->  MIDDLEWARE  -----> MIDDLEWARE -----> RESPOSTA
                                              NEXT              NEXT

  Nesse diagrama temos um fluxo de comunição a partir da requisição, até a resposta passando por dois middleware, isso mostra que neste modelo de arquitetura pode ter várias camadas no meio
para que o fluxo da informação siga seu curso dentro da aplicação. São muitos tipos de softwares e modelos de arquiteturas, portanto o middleware não é algo concreto, ele simplistemnte 
complementa a arquitetura de acordo com as tecnologias empregadas no software. Nessa sentido os desenvolvedores podem criar aplicações com mais facilidade e eficiencia, pois esse tipo de 
software tem o papel de conectar aplicações, dados e usuários. Para ambiente Multicloud e Containers, o uso de middleware torna o desenvolvimento e a execulção de aplicações em escala algo
super economico. Assim ele é capaz de ofereçer suporte para Ambientes de Aplicação que funcionam de maneira estável e consistente em uma plataforma Altamente Distribuída, é a aplicação 
prática. O objetivo é facilitar o desenvolvimento das aplicações tipicamente distribuídas, assim como facilitar a integração de sistemas legados ou desenvolvidos de uma forma não integrada.

Um exemplo de middleware usando Express.js para Node.js

                        function minhaAplicacao(req, res, next) {
                          res.write("Olá mundo");
                          next();
                          }
                          
                        export default minhaAplicacao;
                           
    
