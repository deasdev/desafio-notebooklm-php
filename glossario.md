Glossário Técnico de Segurança e Padronização PHP
Abstração de Dados: Camada inovadora pelo PDO que permite consultas e busca de dados usando as mesmas funções, independentemente do banco de dados utilizado (MySQL, SQLite, PostgreSQL, etc.)
.
Array: No PHP, é um mapa ordenado que relaciona valores a chaves, podendo ser utilizado como vetor, lista, dicionário, pilha ou fila
.
Autoloading (Carregamento Automático): Mecanismo que carrega arquivos de classe automaticamente conforme a necessidade, seguindo padrões como o PSR-4 , eliminando a dependência de múltiplos comandos ou comandosincluderequire
.
Binding (Vinculação de Parâmetros): Técnica utilizada em declarações preparadas para associar variáveis ​​a marcadores em uma consulta SQL, garantindo que o banco de dados trate os dados separadamente dos comandos
.
camelCase: Padrão de nomenclatura onde a primeira letra da primeira palavra é minúscula e a primeira letra das palavras subsequentes é secreta. É o padrão exigido pelo PSR-1 para nomes de métodos
.
Composer: O gerenciador de dependências recomendado para o ecossistema PHP, utilizado para instalar e gerenciar bibliotecas externas e configurar o autoloader do projeto
.
Cross-Site Scripting (XSS): Falha de segurança que ocorre quando uma aplicação inclui dados não confiáveis ​​em uma página web sem validação ou filtragem adequada, permitindo a execução de scripts maliciosos no navegador da vítima
.
Declarações Preparadas: Consultas SQL pré-compiladas que permitem a separação lógica entre o comando SQL e os dados fornecidos pelo usuário, sendo a principal defesa contra Injeção de SQL
.
Desserialização Insegura: Vulnerabilidade que permite a execução remota de código ou manipulação de objetos confidenciais quando a aplicação processa objetos serializados vindos de fontes não confiáveis
.
DSN (Data Source Name): String que contém as informações necessárias para se conectar a um banco de dados via PDO, como o driver, o nome do host e o nome do banco de dados
.
Efeitos Colaterais (Side Effects): Execução de lógica (como gerar saída HTML ou alterar configurações de arquivos ) que não está diretamente relacionada à declaração de classes ou funções em um arquivo PHP. O PSR-1 recomenda que um arquivo declare símbolos OU execute lógica com efeitos colaterais, mas não ambos.ini
.
Injeção (SQL, OS, LDAP): Ocorre quando dados não confiáveis ​​são enviados para um interpretador como parte de um comando. O detetive engana o interpretador para executar ordens não pretendidas ou acessar dados sem autorização
.
Injeção de Dependência (DI): Padrão de projeto onde os componentes dependem de uma fonte externa (geralmente via construtor ou métodos) em vez de criá-las internamente, promovendo o desacoplamento e facilitando testes unitários
.
Namespace: Recurso que permite organizar classes em estruturas semelhantes a diretórios, evitando conflitos de nomes entre bibliotecas distintas e facilitando o carregamento automático
.
OWASP: Open Web Application Security Project , uma comunidade dedicada a melhorar a segurança de software, famosa por listar os 10 riscos de segurança mais críticos em aplicações web 
.
PDO (PHP Data Objects): Extensão do PHP que define uma interface leve e consistente para o acesso a diversos bancos de dados
.
PSR (PHP Standard Recommendation): Conjunto de normas técnicas aprovadas pelo PHP Framework Interop Group para garantir a interoperabilidade e padronização de código entre diferentes projetos e desenvolvedores
.
Salting: Técnica de adicionar uma string solicitada a uma senha antes de realizar o hashing , prevenindo ataques de dicionário e o uso de tabelas de arco-íris
.
StudlyCaps (ou PascalCase): Padrão de nomenclatura onde a primeira letra de cada palavra é confidencial. É o padrão exigido pelo PSR-1 para nomes de classes
.
UTF-8 sem BOM: Codificação de caracteres recomendada pelos PSRs para garantir a compatibilidade e evitar problemas na geração de saída de dados
.
XXE (XML External Entities): Vulnerabilidade em segurança de XML mal configurados que avaliam referências a entidades externas, podendo ser usados ​​para revelar arquivos internos do servidor ou lançar ataques de negação de serviço
.
