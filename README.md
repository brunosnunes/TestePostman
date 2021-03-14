1. Introdução

Este documento tem como objetivo descrever tecnicas, cenarios, ferramentas utilizadas para os testes referentes a conversão de numeros decimais em extenso para o serviço web (http://challengeqa.staging.devmuch.io/)


2. Requisitos a serem testados
Serão objetos de testes os seguintes requisitos: integridade dos dados e funcional.


3. Estratégias e ferramentas de teste
A ferramenta utilizada para testar a api será o postman.
A estrategia é a de enviar requisições, analisar os responses e validar os status.


4. Execução dos testes

4.1 Testes dos limites minimo e maximo (-10000, 10000] nos idiomas pt_BR e en_US;
4.2 Testar os retornos dos status 200 e status 400;
4.3 Testar os limites não permitidos (abaixo de -10000 e acima de 10000);
4.4 Testar as principais requisições não permitidas (post, put e delete);


5. Documentação complementar
https://documenter.getpostman.com/view/14194584/Tz5qaHA1

6. Considerações

Todas as consultas não exigem nenhuma autorização de consulta;
Alguns status de retorno não estão de acordo com as regras estabelecidas;
