# IP - API
Dado um IP válido, a aplicação irá consultar uma API e retornar a cidade de onde esse IP se origina. Possui também um histórico de buscas recentes.
Tecnologias utilizadas: Python, Django, HTML

Instruções de utilização:
1. Descompactar o arquivo do projeto
2. Na linha de comando do Windows mudar para a pasta raiz do projeto 'IPApi'
3. Digitar: env\scripts\activate
4. Digitar: cd IPApi para mudar o diretório
5. Digitar: python manage.py runserver para rodar o servidor
6. Em um navegador, acessar http://127.0.0.1:8000/
7. Você pode fazer uma nova consulta à API digitando um endereço IPV4 válido. Clicando em submit, se obtem o resultado, que é gravado em um banco de dados.
8. Você também pode acessar o histórico de consultas da API no botão logo mais abaixo.
