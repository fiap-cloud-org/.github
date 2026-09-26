<h1 align="center">
  FIAP · Projetos acadêmicos
</h1>

<p align="center">
  <b>Checkpoints e Global Solutions da FIAP.</b><br>
  Cada repositório é uma entrega completa, com arquitetura, código e como validar.
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=kubernetes,docker,terraform,aws,azure,githubactions,jenkins,python,flask,spring" alt="Stacks" />
  </a>
</p>

## Global Solutions

### [fiap-k8s-gs2](https://github.com/fiap-cloud-org/fiap-k8s-gs2) · Kubernetes

**UniFIAP Pay**: PIX e liquidação no BACEN com dois microserviços Flask, livro-razão num **PVC**, **CronJob** de fechamento, **RBAC** e **Pod Security** restrito, testado no **kind** e no **Rancher**.

### [fiap-iac-gs2](https://github.com/fiap-cloud-org/fiap-iac-gs2) · Infraestrutura como Código

**Nagios Core** na AWS com **Terraform** modular: duas VPCs com peering, **ALB**, agentes monitorados e `terraform test` no CI.

### [fiap-docker-gs1](https://github.com/fiap-cloud-org/fiap-docker-gs1) · Cloud Developer

**lojas-service** em Flask e MySQL no **Docker**: ambientes de dev e prod separados, imagem multi-stage sem root e zero CVEs no **Trivy**.

### [fiap-devops-gs1](https://github.com/fiap-cloud-org/fiap-devops-gs1) · DevOps

Pipeline **Jenkins** com testes, **SonarQube**, imagem no **Docker Hub** e deploy no **Azure Web App** de um painel Flask de status.

## Checkpoints

### Kubernetes

| Repositório | O que é |
|---|---|
| [fiap-k8s-cp1](https://github.com/fiap-cloud-org/fiap-k8s-cp1) | **SafeBank Digital**: Pod, Service e Deployment no kind, com página própria via ConfigMap e probes |
| [fiap-k8s-cp2](https://github.com/fiap-cloud-org/fiap-k8s-cp2) | **TechFleet App Portal**: 3 réplicas, NodePort e rolling update sem perder requisições |

### Infraestrutura como Código

| Repositório | O que é |
|---|---|
| [fiap-iac-cp2](https://github.com/fiap-cloud-org/fiap-iac-cp2) | Terraform AWS modular: VPC em 2 AZs, **ALB** e **Auto Scaling**, com **Checkov** no CI |
| [fiap-iac-cp3](https://github.com/fiap-cloud-org/fiap-iac-cp3) | Terraform **multicloud**: redes com peering na AWS e na Azure e VMs por chave SSH |

### Docker

| Repositório | O que é |
|---|---|
| [fiap-docker-cp2](https://github.com/fiap-cloud-org/fiap-docker-cp2) | Microserviço Flask com MySQL, volume persistente, Compose e imagem Alpine sem root |

### DevOps

| Repositório | O que é |
|---|---|
| [fiap-devops-cp2](https://github.com/fiap-cloud-org/fiap-devops-cp2) | CI/CD com **GitOps** na Oracle Cloud: Spring Boot, **GitHub Actions**, Docker Hub e **ArgoCD** no OKE |

### Inteligência Artificial

| Repositório | O que é |
|---|---|
| [fiap-ia-cp2](https://github.com/fiap-cloud-org/fiap-ia-cp2) | Chatbot do **Will Japanese Restaurant** com Flask e **NLTK**: intenções, preços e pedidos |
| [fiap-ia-cp3](https://github.com/fiap-cloud-org/fiap-ia-cp3) | Site do **Sakura Sushi** com chatbot de 17 intenções e receitas pela **API do Gemini** |

### Segurança

| Repositório | O que é |
|---|---|
| [fiap-sec-cp3](https://github.com/fiap-cloud-org/fiap-sec-cp3) | Threat model do **FinanceShop** na AWS: **STRIDE**, **DREAD**, 29 vulnerabilidades e **PCI DSS** |

## Padrão de nomenclatura

| Tipo | Padrão | Exemplo |
|---|---|---|
| Checkpoint | `fiap-<matéria>-cp<N>` | `fiap-devops-cp2` |
| Global Solution | `fiap-<matéria>-gs<N>` | `fiap-k8s-gs2` |

## Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/willtechdev">
        <img src="https://github.com/willtechdev.png" width="100px;" alt="William Coelho"/><br>
        <sub><b>William Coelho</b></sub>
      </a>
    </td>
  </tr>
</table>
