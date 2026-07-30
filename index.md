---
layout: null
title: Sottelli Flosum
---

# Sottelli Flosum

**Finalidade do Aplicativo:** 
O **Sottelli Flosum** é uma ferramenta interna desenvolvida com o objetivo exclusivo de simplificar o acesso dos colaboradores à plataforma de gerenciamento Flosum. O aplicativo atua como uma ponte de autenticação segura (Single Sign-On), permitindo que os usuários façam login utilizando suas contas corporativas do Google da empresa, eliminando a necessidade de criar novas senhas e garantindo um ambiente de trabalho mais ágil e seguro.

---

## Funcionalidades
* **Autenticação Segura:** Permite o login direto no sistema utilizando a infraestrutura de segurança da conta Google da empresa.
* **Simplificação de Acesso:** Facilita a rotina do colaborador ao unificar o acesso através do e-mail corporativo.
* **Validação de Identidade:** Garante que apenas colaboradores autorizados e com contas ativas na organização acessem os dados.

## Transparência e Uso de Dados
Para realizar a autenticação e cumprir sua finalidade, o aplicativo solicita acesso estritamente aos seguintes escopos básicos do Google:
1. **Endereço de e-mail (`email`):** Utilizado unicamente para identificar o usuário e validar se ele possui uma conta corporativa autorizada para acessar a plataforma.
2. **Informações de perfil básico (`profile`, `openid`):** Utilizado para exibir o nome do usuário na interface de boas-vindas e gerenciar o tempo de sessão ativa.

> **Aviso de Privacidade:** Este aplicativo **não** armazena, **não** coleta e **não** compartilha nenhuma informação pessoal ou dados de outras ferramentas do Google com terceiros. O fluxo de dados serve apenas para concluir o processo de login.

---

## Links Oficiais
* [Política de Privacidade](./privacy)
