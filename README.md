**Servindo Páginas com Spring MVC**

Neste exercício, explorei a diferença fundamental entre as anotações @RestController e @Controller.

Enquanto o @RestController devolve apenas o texto bruto para o navegador, o @Controller trabalha em 
conjunto com o motor de templates (Thymeleaf). Ao usar o método GET e retornar apenas a String "painel", 
o Spring não imprime a palavra na tela; em vez disso, ele realiza uma busca na pasta de recursos e renderiza 
o arquivo painel.html completo. Isso demonstra como o protocolo HTTP pode ser usado para entregar interfaces 
inteiras ao usuário.

Usei as dependências: Spring Web Web, Spring Boot DevTools e Thymeleaf.
