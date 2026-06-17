<div align="center">

# Matheus Henrique

**Backend Software Engineer**

*Java · Spring Boot · Fiscal Integrations · Enterprise Systems*

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mattenglish2177@gmail.com)
[![Synapse IT](https://img.shields.io/badge/Synapse_IT-6366f1?style=for-the-badge&logo=lightning&logoColor=white)](https://www.synapseit.dev/)

![Profile Views](https://komarev.com/ghpvc/?username=mattHenriq&style=for-the-badge&color=6366f1&label=PROFILE+VIEWS)

</div>

---

## 👨‍💻 About

Backend engineer com **3+ anos** de experiência em sistemas Java em ambientes enterprise, pipelines fiscais, integrações SAP, bancos Oracle e sistemas de conformidade tributária processando **milhares de NF-e por dia em produção**.

Atualmente como **Backend em uma compania Multinacional**, sou desenvolvedor backend Java responsável por ~10 aplicações fiscais e operacionais: serviços Spring Boot, APIs REST integradas ao Thomson Reuters MasterSAF/OneSource, sistema legado Java adaptado para a Reforma Tributária Brasileira (IBS/CBS/IS) e pipelines ETL em Python.

Além disso, sou **founder da [Synapse IT](https://www.synapseit.dev/)** — software house focada em desenvolvimento web moderno, automação de processos e soluções orientadas a resultado para negócios reais.

---

## 🏢 Synapse IT

<img align="right" width="120" src="https://img.shields.io/badge/Synapse_IT-Founder-6366f1?style=for-the-badge&logoColor=white" />

> *Construindo produtos digitais que resolvem problemas reais.*

Software house que fundei com foco em:
- 🌐 Aplicações web modernas (Next.js, TypeScript, TailwindCSS)
- ⚙️ Automação de processos e pipelines de dados
- 🔗 Integrações entre sistemas legados e plataformas modernas
- 🤖 Soluções orientadas a IA para operações de negócio

---

## 🛠️ Stack Técnica

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### Banco de Dados
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### Testes & Build
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

### Cloud & DevOps
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Frontend (Synapse IT)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

## 📌 Projetos em Destaque

### 🧾 Reforma Tributária — Integração Backend IBS/CBS/IS
Extensão de sistema legado NF-e em Java para suportar os novos tributos da Reforma Tributária Brasileira de 2024. Inclui validação XSD, marshalling/unmarshalling JAXB, integração SAP RFC e comunicação com SEFAZ — rodando em produção para milhares de documentos por dia.

`Java` `Spring Boot` `SAP RFC` `XML/XSD/JAXB` `SEFAZ` `Oracle DB`

---

### 🛠️ Ferramenta Interna de Correção de Documentos Fiscais
Aplicação desktop Java construída para substituir fluxos manuais com Postman/Burp Suite na correção de payloads de ação fiscal. Faz parse de XML bruto, renderiza como editor estruturado e despacha documentos corrigidos para a API MasterSAF via POST autenticado. Inclui autenticação via Windows Active Directory e restrições deliberadas de segurança na edição de payloads.

`Java 21` `Spring Boot` `XML/DOM` `REST API` `MasterSAF` `Active Directory`

---

### 📦 API REST de Gerenciamento de Invoices Fiscais
API REST para ciclo de vida completo de invoices fiscais: criação, consulta paginada, atualização de status e transições de entidade. Arquitetura em camadas (Controller/Service/Repository/DTOs), exception handler centralizado, testes automatizados com JUnit 5 e Mockito, pipeline de build/deploy com Maven, Docker, GitHub Actions e Kubernetes.

`Java 17` `Spring Boot` `Spring Data JPA` `H2` `JUnit 5` `Mockito` `Docker` `GitHub Actions` `Kubernetes`

---

### 🔄 Bridge SAP–Oracle
Middleware de sincronização bidirecional mantendo consistência entre SAP ERP e sistemas Oracle. Trata incompatibilidades de schema, resolução de conflitos e integridade de dados financeiros para reconciliação diária e relatórios de conformidade.

`Java` `SAP RFC` `Oracle DB` `Python` `PL/SQL`

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mattHenriq&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mattHenriq&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mattHenriq&theme=tokyonight&hide_border=true)

</div>

---

## 🎯 Foco Atual

- 📖 Lendo *Designing Data-Intensive Applications* — system design e arquitetura distribuída
- ⚡ Aprofundando Spring Batch, processamento assíncrono e Kafka
- 🏗️ Expandindo a Synapse IT — produtos web, automação e soluções com IA
- 🌎 Buscando posições Backend Java Pleno/Sênior — aberto a remoto

---

## 🌐 Idiomas

🇧🇷 Português — Nativo  
🇺🇸 Inglês — Avançado (leitura técnica, documentação e comunicação)  
🇫🇷 Francês — Básico / Em aprendizado

---

<div align="center">

*São Paulo, Brazil · Disponível para oportunidades remotas*

</div>
