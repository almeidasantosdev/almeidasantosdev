### Kleidson Almeida Santos

Cofundador & Desenvolvedor Full Stack (PJ) na Korven Lab. Mais de 5 anos com aplicações web: interface, API, banco de dados, contêiner e publicação.

Portfólio: [almeida.korvenlab.com](https://almeida.korvenlab.com/)

## Tecnologias

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

TypeScript, React e Node.js nas interfaces e nas APIs públicas. PostgreSQL no Delivery Lab e no estudo de caso do Papufy. Docker empacota o serviço. No laboratório, o GitHub Actions testa e analisa a imagem, o Terraform descreve uma VPC, uma instância e um bucket na AWS, e o Kubernetes executa o mesmo contêiner em Kind ou k3s.

## Produtos

O código de produção do Wagoo e do Papufy não está no GitHub. Os links abaixo são estudos de caso e a interface pública.

| Projeto | O que está público | Onde ver |
| --- | --- | --- |
| [Wagoo](https://github.com/almeidasantosdev/wagoo) | Estudo de caso do produto de agenda no ar: WhatsApp, sinal, comissões e painel. O repositório traz um recorte da regra de agenda, com testes. | [wagoobot.com](https://wagoobot.com/) |
| [Papufy](https://github.com/almeidasantosdev/papufy) | Estudo de caso da plataforma de serviços locais. A interface web está em [papufy-frontend](https://github.com/almeidasantosdev/papufy-frontend): busca, anúncio, chat e carteira, em React, TypeScript e Vite. A API é externa. | [papufy.com](https://papufy.com/) |

## Entrega

| Projeto | O que contém |
| --- | --- |
| [Delivery Lab](https://github.com/almeidasantosdev/delivery-lab) | API de laboratório que recebe um webhook de pagamento fictício, grava o evento uma única vez e reentrega com espera crescente. Dockerfile, Compose, Prometheus, Grafana, GitHub Actions e Terraform (VPC, EC2 e bucket S3). A esteira analisa a imagem e não a publica. |
| [Delivery Lab no Kubernetes](https://github.com/almeidasantosdev/delivery-lab-k8s) | O mesmo contêiner em Kind ou k3s, com Deployment, Service, sondas, escala de 1 a 3 réplicas e PostgreSQL. |

## Interfaces

| Projeto | O que contém |
| --- | --- |
| [Ponto Digital](https://github.com/almeidasantosdev/ponto-frontend) | Tela em React, TypeScript e Vite para registrar entrada ou saída e consultar o próprio histórico. A [API](https://github.com/almeidasantosdev/ponto-backend) guarda os registros em memória. |
| [Calendar Plus](https://github.com/almeidasantosdev/calendarplus-frontend) | Painel em React, TypeScript e Vite: conecta Google e WhatsApp, exibe o QR Code da sessão e liga ou desliga o agendamento. A [página do produto](https://github.com/almeidasantosdev/calendarplus-landingpage) fica em outro repositório. |
| [Lobby Leilão](https://github.com/almeidasantosdev/LobbyLeilao) | Catálogo em React, TypeScript e Vite para buscar itens de leilão. Os exemplos são dados locais e o PDF é lido no navegador. |

## Dados

Base fictícia de pedidos, sem cliente nem documento.

| Projeto | O que contém |
| --- | --- |
| [Análise operacional](https://github.com/almeidasantosdev/analise-operacional) | O pandas trata duplicidade, quantidade, desconto e data, e calcula receita, margem, prazo e cancelamento. As medidas DAX estão versionadas. O arquivo do Power BI fica de fora do Git. |
| [Indicadores em SQL](https://github.com/almeidasantosdev/sql-indicadores) | Prazo por centro, margem por canal, pareto de produtos e variação mensal. A receita conferida fecha no CSV. |

## Monitoramento

Material de estudo. Não é um ambiente de operação.

| Projeto | O que contém |
| --- | --- |
| [SOC Homelab](https://github.com/almeidasantosdev/soc-homelab) | Docker Compose com rsyslog e um coletor de alertas em arquivo. Elasticsearch e Kibana entram num perfil opcional. O Wazuh está descrito na documentação de arquitetura. |
| [SOC Detections](https://github.com/almeidasantosdev/soc-detections) | Regras Sigma, consultas KQL e SPL, e um mapa de alerta, gravidade e ação. |

## Também

- [ka.dev](https://github.com/almeidasantosdev/ka.dev) — site pessoal em React, Vite e Tailwind.
