## Guia de Estudos para o Exame AWS Certified Cloud Practitioner (CLF-C02)

**Resumo:**

**Compreenda o Exame:**

* **Formato:**
    * 65 questões de múltipla escolha ou múltipla resposta
    * Duração de 90 minutos
    * Aprovação com 70% de acertos
* **Conteúdo:**
    * 35% Conceitos básicos da AWS
    * 25% Segurança e conformidade
    * 25% Faturamento e gerenciamento de custos
    * 15% Rede e entrega de conteúdo

**Recursos de Estudo:**

**Oficiais da AWS:**

* **Guia do Exame AWS Certified Cloud Practitioner (CLF-C02):** [https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf](https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
* **AWS Cloud Quest: Cloud Practitioner:** [URL inválido removido]

**Exteriores:**

* **Simulado CLF-C02 em Português:** [https://simuladoclf.s3.amazonaws.com/portugues.html](https://simuladoclf.s3.amazonaws.com/portugues.html)
* **Curso AWS Practitioner em Português na Udemy:** [https://www.udemy.com/course/aws-practitioner-em-portugues/?couponCode=JUST4U02223](https://www.udemy.com/course/aws-practitioner-em-portugues/?couponCode=JUST4U02223)
* **Udemy:** [https://www.udemy.com/course/aws-practitioner-em-portugues/?couponCode=JUST4U02223](https://www.udemy.com/course/aws-practitioner-em-portugues/?couponCode=JUST4U02223)


**Regiões:**

* **Definição:** Agrupamentos geográficos de datacenters da AWS, localizados em diferentes partes do mundo. Cada região oferece uma variedade de serviços AWS e possui infraestrutura independente, incluindo energia, rede e refrigeração.
* **Objetivo:** Fornecer redundância e baixa latência para seus aplicativos e dados, aproximando-os dos seus usuários finais.
* 
**Zonas de Disponibilidade (AZs):**

* **Definição:** Subdivisões de uma região, compostas por datacenters distintos dentro da mesma área geográfica. As AZs são projetadas para serem altamente disponíveis e resistentes a falhas, garantindo que seus serviços permaneçam online mesmo em caso de interrupções em uma AZ.
* **Objetivo:** Aumentar a disponibilidade e a tolerância a falhas dos seus aplicativos e dados, isolando-os de eventos que podem afetar uma única AZ.

**Locais de Borda:**

* **Definição:** Infraestruturas AWS localizadas em pontos de presença fora das regiões, mais próximas dos usuários finais. Os Locais de Borda oferecem acesso a serviços AWS de baixa latência e alta velocidade de transferência de dados para aplicações sensíveis à latência.
* **Objetivo:** Reduzir a latência e melhorar o desempenho dos seus aplicativos para usuários em locais remotos, com acesso direto à infraestrutura da AWS.

**Resumindo:**

* **Regiões:** Ampla área geográfica com datacenters independentes.
* **Zonas de Disponibilidade:** Subdivisões de uma região com alta disponibilidade.
* **Locais de Borda:** Infraestrutura AWS em locais remotos com baixa latência.

**Benefícios:**

* **Disponibilidade aprimorada:** Maior resiliência a falhas e interrupções.
* **Baixa latência:** Melhor desempenho para usuários em todo o mundo.
* **Conformidade com regulamentações:** Atenda às exigências de armazenamento de dados em regiões específicas.

**Lembre-se:**

* Escolha a região e as AZs adequadas para suas necessidades de disponibilidade, latência e conformidade e também para recuperação de desastres.
* Utilize os Locais de Borda para workloads sensíveis à latência em locais remotos.

**Recursos Adicionais:**

* [Regiões e Zonas de Disponibilidade da AWS](https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/)
* [Locais da Borda da AWS](https://aws.amazon.com/pt/about-aws/global-infrastructure/localzones/)


## Amazon EC2

O Amazon EC2 (Elastic Compute Cloud) é um serviço de computação em nuvem que oferece servidores virtuais sob demanda, chamados de instâncias. Você pode usá-lo para executar uma ampla variedade de cargas de trabalho, incluindo:

* **Aplicativos web:** Servidores web para hospedar sites e aplicativos web.
* **Aplicativos de servidor:** Servidores para executar banco de dados, cache e outros softwares de servidor.
* **Desktop virtual:** Crie desktops virtuais para seus usuários.
* **Computação de alto desempenho (HPC):** Execute cargas de trabalho HPC que exigem grandes recursos de computação.
* **Big data e análise:** Processe e analise grandes conjuntos de dados.

**Planos de Compra EC2:**

O EC2 oferece três planos de compra principais para atender às suas necessidades:

* **Sob demanda:** Pague por hora pelas instâncias que você usa. Ideal para cargas de trabalho variáveis ​​ou de curto prazo.
* **Reservado:** Obtenha descontos em instâncias reservando-as por um ou três anos. Ideal para cargas de trabalho previsíveis de longo prazo.
* **Spot:** Lance lances em instâncias inativas com desconto. Ideal para cargas de trabalho que podem tolerar interrupções.

**Tipos de Instâncias EC2:**

O EC2 oferece uma ampla variedade de tipos de instâncias para diferentes casos de uso:

* **Família Geral (A):** Ideal para cargas de trabalho de propósito geral, como sites e aplicativos web.
* **Família Computacional (C):** Ideal para cargas de trabalho que exigem alto desempenho de CPU, como jogos e aplicativos de desktop virtual.
* **Família Memória (M):** Ideal para cargas de trabalho que exigem grande quantidade de memória, como bancos de dados e análise de big data.
* **Família Armazenamento (H):** Ideal para cargas de trabalho que exigem alto desempenho de I/O, como bancos de dados NoSQL e aplicativos de big data.
* **Família Acelerada por GPU (G):** Ideal para cargas de trabalho que exigem alto desempenho gráfico, como machine learning e aplicativos de inteligência artificial.

**Escolhendo o Tipo de Instância Correto:**

A escolha do tipo de instância correto depende das suas necessidades específicas. Considere fatores como:

* **CPU:** Quantidade e velocidade dos núcleos da CPU.
* **Memória:** Quantidade de RAM.
* **Armazenamento:** Tipo e capacidade de armazenamento.
* **Rede:** Desempenho da rede.
* **Custo:** Preço da instância.

**Recursos Adicionais:**

* **Guia do Usuário do Amazon EC2:** [https://docs.aws.amazon.com/ec2/](https://docs.aws.amazon.com/ec2/)
* **Preços do Amazon EC2:** [https://aws.amazon.com/ec2/pricing/](https://aws.amazon.com/ec2/pricing/)
* **Instâncias do Amazon EC2:** [https://aws.amazon.com/es/ec2/instance-types/](https://aws.amazon.com/es/ec2/instance-types/)

**Amazon S3 (Simple Storage Service):**

* Armazenamento de objetos em nuvem escalável e durável.
* Ideal para armazenar grandes volumes de dados não estruturados, como arquivos, imagens e vídeos.
* Acessado por meio da API REST ou da AWS CLI.
* **Modelo de pagamento:** Paga por GB armazenado e por solicitações.

**Amazon EBS (Elastic Block Store):**

* Armazenamento em bloco persistente para instâncias EC2.
* Fornece volumes de armazenamento de alto desempenho e baixa latência.
* Ideal para armazenar dados estruturados, como sistemas de arquivos e bancos de dados.
* Acessado diretamente pela instância EC2 a ele conectada.
* Um por zona de disponibilidade. 
* **Modelo de pagamento:** Paga por GB provisionado por hora, por snapshots e por transferência de dados para fora da AWS.

**Integração EBS com EC2:**

* As instâncias EC2 são inicializadas a partir de AMIs (Amazon Machine Images) armazenadas no S3.
* O EBS fornece volumes de armazenamento persistentes para as instâncias EC2.
* Você pode criar, anexar, destacar e gerenciar volumes EBS a partir do console da AWS ou da AWS CLI.
* O EBS oferece várias opções de volume, incluindo SSDs de alto desempenho para cargas de trabalho exigentes.

**Recursos Adicionais:**

* **Comparação de tecnologias de armazenamento AWS:** [https://medium.com/@lucasfpo/comparando-as-tecnologias-de-armazenamento-aws-s3-ebs-e-efs-d2ad8a2a56c4](https://medium.com/@lucasfpo/comparando-as-tecnologias-de-armazenamento-aws-s3-ebs-e-efs-d2ad8a2a56c4)


## Conectividade Segura

**1. VPC (Virtual Private Cloud):**

Uma rede virtual privada na AWS, isolada de outras redes VPC e da internet pública. Crie redes seguras e customizáveis para seus recursos AWS, controlando o tráfego de entrada e saída.

**2. VPN (Virtual Private Network):**

Crie um túnel criptografado e seguro para conectar sua rede local à sua VPC na AWS. Estabeleça uma conexão privada e protegida entre sua infraestrutura on-premises e a nuvem, permitindo acesso seguro aos recursos da AWS.

**3. Internet Gateway:**
 Um roteador virtual que permite que as instâncias em sua VPC se conectem à internet pública. O Internet Gateway atua como ponto de entrada para o tráfego de internet, permitindo que suas instâncias acessem recursos externos.

**4. Direct Connect:**
 Uma conexão de rede dedicada e de alta velocidade entre sua rede local e a AWS. O Direct Connect oferece uma conexão privada e confiável para grandes volumes de dados, com menor latência e custos mais baixos do que a internet pública.
 
**5. AWS Load Balancer::**
 Distribua o tráfego de rede para suas instâncias de forma eficiente e automatizada.

**6. AWS Route 53:**
 Gerencie seus nomes de domínio e DNS com alta disponibilidade e escalabilidade.
 
**7.AWS Network Firewall:**
 Implemente firewalls de rede robustos para proteger suas VPCs.
 
**8.AWS VPC Flow Logs:**
  Monitore o tráfego de rede de entrada e saída em suas VPCs.
  
* **Considerações de segurança:**
    * **Grupos de Segurança:** Controle o tráfego de entrada e saída para suas instâncias EC2.
    * **Listas de Controle de Acesso (ACLs):** Proteja suas instâncias EC2 dentro da VPC(sub-redes).
    * **IAM (Identity and Access Management):** Gerencie o acesso de usuários e serviços aos seus recursos da AWS.


## Aplicações Sem Servidor

Com a AWS, você pode construir e gerenciar aplicações sem se preocupar com a infraestrutura, permitindo maior foco na lógica de negócio e na entrega de valor aos seus clientes.

* **Serviços sem servidor da AWS:**
    * **AWS Lambda:** Execute código sem provisionar ou gerenciar servidores.
    * **Amazon API Gateway:** Crie APIs RESTful escaláveis e seguras.
    * **Amazon DynamoDB:** Banco de dados NoSQL totalmente gerenciado.
    * **Amazon S3:** Armazenamento de objetos escalável e durável.
    * **Amazon SNS:** Serviço de notificação por push.
    * **AWS Step Functions:** Orquestre workflows sem servidor.
    * **Fargate:** Plataforma serveless para executar containers sem servidor na AWS.

**Recursos Adicionais:**

* **Introdução à Computação Sem Servidor na AWS:** [https://aws.amazon.com/serverless/getting-started/](https://aws.amazon.com/serverless/getting-started/)
* **Guia do Desenvolvedor do AWS Lambda:** [https://aws.amazon.com/lambda/](https://aws.amazon.com/lambda/)
* **Exemplos de Arquitetura Sem Servidor:** [https://serverlessland.com/patterns](https://serverlessland.com/patterns)
* **Blog da AWS sobre Computação Sem Servidor:** [https://www.amazon.com/Serverless-Architectures-AWS-examples-Lambda/dp/1617293822](https://www.amazon.com/Serverless-Architectures-AWS-examples-Lambda/dp/1617293822)



**Boa sorte em seus estudos!**


