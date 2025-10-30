 Meu Primeiro Desafio – Aprendizado Prático de Arquitetura na AWS

*Primeiro Desafio de Arquitetura: Gerenciamento de Instâncias EC2 na AWS  
Este projeto faz parte do meu aprendizado em Arquitetura de Sistemas e tem como objetivo **consolidar conhecimentos sobre gerenciamento de instâncias EC2 na AWS.  
Durante este estudo, explorei os conceitos principais do EC2, sua integração com outros serviços da AWS e aprendi a diagramar arquiteturas no Draw.io.

---

 Objetivos

- Compreender os fundamentos do serviço EC2  
- Conhecer os diferentes tipos de instâncias e seus usos  
- Entender como a EC2 se conecta a outros serviços (EBS, S3, Lambda)  
- Consolidar a habilidade de documentar projetos técnicos 
- Produzir diagramas de arquitetura no Draw.io  

---

 Estudos sobre

 1. EC2 (Elastic Compute Cloud)
- Serviço de computação em nuvem sob demanda da AWS.  
- Permite executar aplicações em servidores virtuais.  

---

2. Tipos de instâncias EC2
As instâncias são categorizadas conforme o propósito de uso:

| Categoria | Exemplos de Instâncias | Características |
|------------|------------------------|-----------------|
| **General Purpose** | A1, T4g, T3, T3a, T2, M6g, M5, M5a, M5n, M4 | Equilíbrio entre CPU, memória e rede |
| **Compute Optimized** | C6g, C5n, C5, C4, C5a | Desempenho ideal para processamento intensivo |
| **Memory Optimized** | R6g, R5, R5a, R5n, R4, X1e, X1, z1d | Projetadas para cargas com uso intensivo de memória |
| **Storage Optimized** | I3, I3en, D2, H1 | Voltadas para aplicações que exigem alto desempenho de I/O |
| **Accelerated Computing** | P3, P2, Inf1, G4, G3, F1 | Utilizam GPUs e hardware especializado |

---

3. Integração com outros serviços

- EBS (Elastic Block Store): armazenamento em blocos associado a uma instância EC2.  
- S3 (Simple Storage Service): armazenamento de objetos acessível via internet.  
- Lambda: usado para automação de tarefas, validação, organização e geração de links de download.

---

 4. Documentação de Arquitetura

- Criação de diagramas no Draw.io para representar arquiteturas na nuvem.  
- Facilita a visualização da relação entre instâncias, armazenamento e rede.  

---

Aprendizados Fixados

- Diferença entre EBS (armazenamento em blocos) e S3 (armazenamento de objetos).  
- Uso do S3 como armazenamento acessível a usuários.  
- Criação de diagramas de arquitetura no Draw.io para documentar projetos de forma clara e didática.  

---

 Arquitetura do Projeto

- EC2: hospeda a aplicação web  
- EBS: disco da EC2 para código, configurações e logs  
- S3: repositório de documentos  
- Lambda: automação de validação e geração de links de download  


<img width="549" height="512" alt="PROJETO1 drawio" src="https://github.com/user-attachments/assets/41aa38b1-2035-41ec-a15f-462de73748f7" />



---

 Tecnologias e Ferramentas

-  **AWS Lambda** — funções serverless  
-  **Amazon S3** — armazenamento de arquivos  
-  **Amazon EC2 + EBS** — instâncias e volumes persistentes  
- **Draw.io** — criação de diagramas  
-  **Git / GitHub** — versionamento e documentação  
-  **Markdown** — formatação técnica para README  


---
Desenvolvido por Beatriz Soares como parte da Formação AWS Cloud Practitioner - DIO.
