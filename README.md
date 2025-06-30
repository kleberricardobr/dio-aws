# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 30/06/2025
Empresa: Abstergo Industries 
Responsável: Kleber Ricardo

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstrego Industries, realizado por Kleber Ricardo.
O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

1. AWS Lambda
Foco da ferramenta:
Execução de código sem necessidade de gerenciar servidores (computação serverless).

Descrição de caso de uso:
Automatizar tarefas internas, como o processamento de arquivos enviados para um bucket do S3. 
Por exemplo, ao receber uma planilha de vendas, o Lambda pode ser acionado automaticamente para processar os dados, atualizar um banco de dados e enviar um relatório por e-mail. Isso reduz intervenção manual e aumenta a eficiência operacional.

2. Amazon S3 (Simple Storage Service)
Foco da ferramenta:
Armazenamento de objetos altamente escalável, durável e seguro.

Descrição de caso de uso:
Armazenamento centralizado de documentos, relatórios financeiros, backups de sistemas e arquivos de mídia (como vídeos e imagens institucionais). 
Pode-se organizar os arquivos em buckets por departamento e aplicar políticas de acesso específicas, facilitando a organização e a segurança da informação.

3. Amazon SQS (Simple Queue Service)
Foco da ferramenta:
Comunicação assíncrona entre sistemas via filas de mensagens.

Descrição de caso de uso:
Em uma empresa com vários sistemas interconectados (ex: sistema de vendas, estoque e faturamento), o SQS pode ser usado para garantir que as mensagens fluam de forma confiável entre os sistemas. 
Por exemplo, quando um pedido é realizado, ele é colocado em uma fila e processado por serviços responsáveis pela reserva de estoque e emissão de nota, mesmo que esses serviços estejam temporariamente indisponíveis.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado benefícios como automação de processos repetitivos, redução de custos operacionais, melhoria na comunicação entre sistemas, aumento da escalabilidade e segurança no armazenamento de dados,
o que aumentarão a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Anexos em /anexos
