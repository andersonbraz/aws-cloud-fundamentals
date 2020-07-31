# AWS Fundamentals: Going Cloud-Native


---

O que é nuvem? O que é a AWS? Existem muitas definições por aí, mas o que vamos seguir neste curso é a ideia de um pedido, serviços de TI pagos conforme o uso, fornecidos pela Internet. Cada uma dessas partes é importante. A ideia de um serviço sob demanda, que você não precisa fazer nenhum contrato avançado conosco, você não precisa nos informar o que é necessário. No momento em que você precisar de serviços como armazenamento e computação ou rede, eles estão disponíveis imediatamente sem nenhum contrato avançado, que é igual ao pagamento conforme o uso.

[AWS Free](https://aws.amazon.com/free/)

---

## Amazon CloudWatch

O Amazon CloudWatch é um serviço de monitoramento dos recursos da AWS Cloud e dos aplicativos executados na AWS. Você pode usar o Amazon CloudWatch para coletar e rastrear métricas, coletar e monitorar arquivos de log, definir alarmes e reagir automaticamente a alterações nos recursos da AWS.

## Eventos do Amazon CloudWatch

O Amazon CloudWatch Events fornece um fluxo quase em tempo real de eventos do sistema que descrevem alterações nos recursos da AWS. Usando regras simples que você pode configurar rapidamente, você pode corresponder eventos e rotea-los para uma ou mais funções ou fluxos de destino. O CloudWatch Events fica ciente das mudanças operacionais à medida que elas ocorrem.

## Métricas do Amazon CloudWatch Logs

Você pode usar o Amazon CloudWatch Logs para monitorar, armazenar e acessar seus arquivos de log a partir de instâncias do Amazon EC2, AWS CloudTrail, Amazon Route 53 e outras fontes. Em seguida, você pode recuperar os dados de log associados do CloudWatch Logs.

Você pode coletar métricas de servidores instalando o agente CloudWatch no servidor. Você pode instalar o agente nas instâncias do Amazon EC2 e nos servidores locais e nos servidores que executam o Linux ou o Windows Server.

---

## Elastic Load Balancing

O Elastic Load Balancing distribui automaticamente o tráfego de entrada de aplicativos entre diversos destinos, como instâncias do Amazon EC2, contêineres, endereços IP e funções Lambda. O serviço pode lidar com a carga variável de tráfego dos aplicativos em uma única zona de disponibilidade ou em diversas zonas de disponibilidade. O Elastic Load Balancing oferece três tipos de load balancers, todos eles com a alta disponibilidade, a escalabilidade automática e a segurança robusta necessárias para tornar os aplicativos tolerantes a falhas.

### Application Load Balancer

O Application Load Balancer é mais adequado ao balanceamento de carga de tráfego HTTP e HTTPS e oferece roteamento avançado de solicitações para a entrega de arquiteturas modernas de aplicativos, incluindo microsserviços e contêineres. Operando no nível de solicitação individual (camada 7), o Application Load Balancer roteia tráfego a destinos dentro do Amazon Virtual Private Cloud (Amazon VPC) de acordo com o conteúdo da solicitação.

### Network Load Balancer

O Network Load Balancer é mais adequado ao balanceamento de carga de tráfego TCP (Transmission Control Protocol), UDP (User Datagram Protocol) e TLS (Transport Layer Security) que exige performance extrema. Operando no nível de conexão (camada 4), o Network Load Balancer roteia tráfego a destinos dentro do Amazon Virtual Private Cloud (Amazon VPC) e é capaz de lidar com milhões de solicitações por segundo, mantendo latências ultrabaixas. O Network Load Balancer também é otimizado para lidar com padrões de tráfego súbitos e voláteis.

### Classic Load Balancer

O Classic Load Balancer fornece load balancing básico entre diversas instâncias do Amazon EC2 e opera com solicitações e conexões. O Classic Load Balancer é destinado a aplicativos criados dentro da rede EC2-Classic