# DevOps-Challenge-1

Desafio InfiniteBit by Quantye: Avaliação de habilidades em AWS, Terraform, ECS e API em Python.

## Descrição do Desafio

Este desafio consiste em criar uma infraestrutura na AWS utilizando Terraform e implementar uma API simples em Python. O objetivo é provisionar uma arquitetura escalável e confiável usando ECS para deploy da API, garantindo boas práticas de DevOps em provisionamento, deploy e monitoramento.

## Níveis do Desafio

### Terraform (Infraestrutura)

**Nível 1 - Básico**
- Criar recursos AWS básicos usando Terraform
- Implementar VPC, subnets, security groups e ECS cluster
- Configurar roles e permissões necessárias

**Nível 2 - Intermediário**
- Implementar backend remoto usando S3 para tfstate
- Configurar DynamoDB para lock state

**Nível 3 - Avançado**
- Refatorar código usando módulos Terraform
- Implementar variáveis locais e outputs
- Criar módulos reutilizáveis para componentes comuns

**Nível 4 - Expert**
- Deploy multi-ambiente (dev, staging, prod)
- Implementar diferentes configurações por ambiente (Terragrunt?)

### API Python

**Nível 1 - Básico**
- Criar API REST simples com Flask/FastAPI
- Implementar endpoints básicos
- Documentação básica da API

**Nível 2 - Intermediário**
- Adicionar autenticação e autorização
- Implementar logging e tratamento de erros
- Testes unitários básicos

**Nível 3 - Avançado**
- Implementar cache
- Adicionar rate limiting
- Testes de integração
- Documentação OpenAPI/Swagger

**Nível 4 - Expert**
- Implementar circuit breakers
- Monitoramento avançado com métricas
- Testes de performance
- Versionamento da API

### Container e ECS

**Nível 1 - Básico**
- Criar Dockerfile básico
- Deploy manual no ECS
- Configuração básica de task definition

**Nível 2 - Intermediário**
- Otimização do Dockerfile (multi-stage builds)
- Implementar health checks
- Configurar auto scaling básico

**Nível 3 - Avançado**
- Implementar service discovery
- Configurar logs centralizados
- Implementar blue/green deployment

**Nível 4 - Expert**
- Implementar service mesh
- Configurar observabilidade avançada
- Implementar disaster recovery

### CI/CD

**Nível 1 - Básico**
- Pipeline básico de build e deploy
- Configuração de variáveis de ambiente
- Deploy manual aprovado

**Nível 2 - Intermediário**
- Testes automatizados no pipeline
- Scan de segurança básico
- Notificações de status do pipeline

**Nível 3 - Avançado**
- Deploy automatizado por ambiente
- Scan de vulnerabilidades avançado
- Rollback automatizado

**Nível 4 - Expert**
- Pipeline como código
- Métricas de pipeline
- Integração com gestão de mudanças
- Testes de chaos engineering

## Entregáveis

### Repositório GitHub com a estrutura completa do projeto:

- Configurações do Terraform para provisionamento da infraestrutura
- Código da API Python com instruções de uso e dependências
- Pipeline de CI/CD para deploy automático

### Documentação no README:

- Passos para provisionamento da infraestrutura
- Configuração e deploy da API no ECS
- Variáveis de ambiente e configuração para segurança dos dados sensíveis
- Como realizar testes e monitoramento básicos da API

## Critérios de Avaliação

- **Infraestrutura como Código (IaC)**: Implementação eficiente da infraestrutura AWS utilizando Terraform.
- **API e Containers**: Criação e deploy adequado da API usando containers.
- **Automação**: Pipeline CI/CD funcional e seguro.
- **Documentação e Boas Práticas**: Instruções claras e configurações que seguem boas práticas de segurança e DevOps.
