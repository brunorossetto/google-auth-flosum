# Sottelli Flosum

O **Sottelli Flosum** é um aplicativo interno desenvolvido para simplificar e centralizar o mecanismo de autenticação de usuários na plataforma Sottelli Flosum. 

Nossa única finalidade é atuar como uma ponte de **Single Sign-On (SSO)**, permitindo que os colaboradores utilizem suas credenciais corporativas do Google para acessar o sistema de forma rápida e segura.

---

## Funcionalidades do Aplicativo
* **Autenticação Segura:** Permite o login direto no Sottelli Flosum utilizando o ecossistema de segurança da conta Google da empresa.
* **Simplificação de Acesso:** Elimina a necessidade de criar, gerenciar e memorizar múltiplas senhas adicionais para a plataforma Flosum.
* **Validação de Identidade:** Garante que apenas colaboradores autorizados e com contas corporativas ativas tenham acesso ao ambiente de trabalho.

## Transparência e Uso de Dados
Para realizar a autenticação, o aplicativo solicita acesso estritamente aos escopos básicos do Google:
1. **Endereço de e-mail (`email`):** Utilizado exclusivamente para identificar o usuário e associá-lo ao seu perfil correspondente dentro do Sottelli Flosum.
2. **Informações de perfil básico (`profile`, `openid`):** Utilizado para exibir o nome do usuário na interface e validar a sessão ativa.

> **Importante:** Este aplicativo **não** coleta, **não** armazena, **não** altera e **não** compartilha nenhuma informação pessoal ou dados de outras ferramentas do Google com terceiros. O fluxo de dados é temporário e serve apenas para concluir o login.

---

## Links Oficiais
* [Política de Privacidade](./privacy)
