 Desafio: Gerenciamento de Instâncias EC2 na AWS
 Objetivo
Consolidar conhecimentos em criação e gerenciamento de instâncias EC2 na AWS, aplicando conceitos aprendidos durante o curso.
 Etapas Realizadas

1. Criação da instância EC2
   - Tipo de instância: t2.micro (free tier)
   - Sistema operacional: Amazon Linux 2
   - Par de chaves criado para acesso SSH
   - Grupo de segurança configurado permitindo acesso na porta 22 (SSH)

2. Conexão com a instância
   - Utilização do arquivo `.pem` para autenticação segura
   - Conexão via terminal com comando:
     ```bash
     ssh -i "chave.pem" ec2-user@ip-da-instancia
     ```

3. Configurações realizadas
   - Atualização dos pacotes:
     ```bash
     sudo yum update -y
     ```
   - Instalação de Apache:
     ```bash
     sudo yum install httpd -y
     sudo systemctl start httpd
     sudo systemctl enable httpd
     ```
   - Teste de acesso via navegador (IP público da instância)

4. Encerramento da instância
   - Verificação de status
   - Encerramento seguro da instância após testes

 Imagens
As capturas de tela estão na pasta /images, demonstrando:
- Criação da instância
- Conexão SSH
- Página web rodando no navegador

 Insights e Aprendizados
Durante o laboratório, aprendi:
- A importância das chaves privadas no acesso seguro via SSH.
- Como funcionam os grupos de segurança e o controle de portas.
- Boas práticas de encerramento e limpeza de recursos na AWS.
  
 Recursos Consultados
- [Documentação oficial da AWS - EC2](https://docs.aws.amazon.com/pt_br/ec2/)
- [Guia de Markdown do GitHub](https://docs.github.com/pt/get-started/writing-on-github)

---
Desenvolvido por Beatriz Soares como parte da Formação AWS Cloud Practitioner - DIO.
