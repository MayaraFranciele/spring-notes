# Anotações sobre Spring Boot

![SpringLogo](https://miro.medium.com/v2/resize:fit:600/1*ljHUhFnaBissdRBe7DIo6g.png)

## Sumário:
- [O que é o Spring Boot?](#resumo)
- [Service](#service)
- [RestController](#restcontroller)
- [Repository](#repository)
- [Data](#data)
- [NoArgsConstructor](#noargsconstructor)




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



<a name="noargsconstructor"></a>
## @NoArgsConstructor

A anotação @NoArgsConstructor no Spring Boot, usando a biblioteca Lombok, simplifica a criação de construtores sem parâmetros em suas classes. Ao aplicar @NoArgsConstructor a uma classe, o Lombok automaticamente gera um construtor que não requer nenhum argumento. Isso é útil, por exemplo, ao criar instâncias da classe sem fornecer explicitamente valores para os atributos.

Essa anotação elimina a necessidade de você escrever manualmente um construtor sem parâmetros, economizando tempo e tornando o código mais conciso. Assim como com outras anotações do Lombok, é necessário garantir que a dependência do Lombok esteja corretamente configurada no seu projeto para que a anotação funcione conforme esperado.






