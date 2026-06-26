# GFT_AWS
Repositório para as atividades do GFT AWS

Primeiro laboratório contém as informaçoes a respeito das instâncias EC2 e S3.
EC2 é usado com EBS e RDS.
S3 é usado com Lambda.
O fluxo das instâncias está no arquivo Desafio_Instancias_AWS.drawio

Step Functions
É um construtor visual, no code, usado para criar fluxos de trabalho. Dentre suas possibilidades, existe o carregamento de modelos pré definidos.
No caso de uso desses modelos, vale ressaltar que os recursos serão criados automáticamente, por exemplo, um bucket S3 mapeado será criado no AWS.

Amazon CloudFormation
É um processo de criação de recursos via arquivo JSON e YAML.
A criação das Stacks pode ser feita usando um modelo existente, carregando um template via S3 URL ou ainda pelo upload de um template.
Para mais informações, é possível utilizar a documentação: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-console-create-stack.html

Tarefas automatizadas
É possível usar ferramentas de diferentes fornecedores para automatizar as atividades no AWS, algumas dessas ferramentas são o VsCode, Local Stack, NoSQL, Postman (e para desenho de arquitetura, drawio)
Local Stack: é um projeto OpenSource que simula localmente o ambiente AWS com seus recursos. É possível conectar com o NoSQL para consultas de banco de dados, e com linha de comando acessar, criar e configurar os recursos do ambiente. Essa ferramenta é muito útil para a execução de testes e simulações em ambiente neutro.
A configuração do Lambda é atualizado/criado subindo o arquivo (pode ser zip) na configuração do seu Lambda no Local Stack.
No laboratório foi explorado o método GET e POST, assim como o uso do Postman para consulta da AWS via API.
