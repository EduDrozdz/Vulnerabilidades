# Vulnerabilidades
Segurança em Sistemas Computacionais — Exercício 2

Este projeto apresenta dois exemplos simples em Java usados para demonstrar falhas comuns de segurança e suas correções.

📂 Arquivos incluídos

VulnerableLogin.java → versão vulnerável com 8 erros identificados e comentados.

VulnerableLoginFixed.java → versão corrigida (uso de PreparedStatement, hash de senha, mensagens seguras, etc.).

BadLogger.java → versão com 3 falhas de segurança relacionadas a logs e segredos.

BadLoggerFix.java → versão corrigida com boas práticas de logging.

🧠 Objetivo

Identificar vulnerabilidades em código-fonte e aplicar boas práticas de programação segura, como:

Evitar SQL Injection com PreparedStatement.

Não armazenar senhas em texto puro.

Evitar exposição de informações sensíveis em logs ou mensagens.

Substituir printStackTrace() por mensagens genéricas.

Fechar corretamente recursos (Scanner, Connection, etc.).

⚙️ Como executar

Compile o arquivo com javac NomeDoArquivo.java

Execute com java NomeDoArquivo

Insira um nome de usuário e senha quando solicitado.

⚠️ Atenção: os códigos vulneráveis servem apenas para fins educacionais. Não devem ser utilizados em sistemas reais.

🧾 Créditos

Exercício desenvolvido para a disciplina Segurança em Sistemas Computacionais, com foco em análise de vulnerabilidades e correção prática em Java.
