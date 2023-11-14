# Anotações sobre Spring Boot

![SpringLogo](https://miro.medium.com/v2/resize:fit:600/1*ljHUhFnaBissdRBe7DIo6g.png)

## Sumário:
- [O que é o Spring Boot?](#resumo)
- [Service](#service)
- [RestController](#restcontroller)
- [Repository](#repository)
- [Data](#data)



<a name="resumo"></a>
## O que é o Spring Boot?

:pushpin:	O Spring Boot é um framework Java que simplifica o desenvolvimento de aplicativos, oferecendo configuração automática e estrutura pré-definida. Ele é conhecido por sua facilidade de uso, construção de aplicativos autônomos e integração perfeita com o ecossistema Spring, tornando o desenvolvimento de aplicativos Java mais rápido e eficiente. 

Com o Spring Boot, os desenvolvedores podem se concentrar mais na lógica de negócios e menos na configuração, acelerando o desenvolvimento e facilitando a implantação de aplicativos prontos para produção

<a name="service"></a>
## @Service

A anotação @Service no Spring Boot é usada para marcar uma classe como um componente de serviço. Em outras palavras, ela é usada para indicar que a classe desempenha o papel de um serviço ou lógica de negócios no contexto de uma aplicação Spring. 



<a name="restcontroller"></a>
## @RestController 

A anotação @RestController no Spring Boot é usada para criar controladores que tratam solicitações HTTP RESTful e retornam respostas no formato desejado, como JSON ou XML. Os métodos em um controlador marcados com @RestController são mapeados para URLs específicas e tratam diferentes tipos de solicitações HTTP, como GET, POST, PUT, DELETE, etc.



<a name="repository"></a>
## @Repository 

A anotação @Repository no Spring é usada para marcar uma classe como um componente de repositório. Ela é usada principalmente em classes que acessam e gerenciam o acesso a um banco de dados ou a fontes de dados de armazenamento. 



<a name="data"></a>
## @Data 

A anotação @Data no Spring Boot, associada à biblioteca Lombok, ajuda a reduzir a quantidade de código que você precisa escrever. Quando você coloca @Data em uma classe, o Lombok automaticamente cria alguns métodos comuns, como getters, setters e constructors. Isso simplifica o código e torna a sua classe mais fácil de ler e manter, sem perder funcionalidades. 

