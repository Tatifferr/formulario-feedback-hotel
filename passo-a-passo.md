# Hotel Feedback Form

Este projeto consiste na criação de um **Formulário de Feedback para Hotel** utilizando **HTML semântico**, desenvolvido como parte de um workshop/prática de formulários HTML (baseado no freeCodeCamp).

O objetivo é aplicar conceitos fundamentais de formulários, acessibilidade e estrutura correta de elementos HTML.

---

## 🧱 Estrutura do Projeto

O formulário foi desenvolvido em **um único arquivo HTML**, utilizando uma estrutura semântica clara:

- `header` para o título e texto introdutório
- `main` para o conteúdo principal
- `form` para coleta de dados do usuário
- `fieldset` e `legend` para agrupar informações relacionadas

---

## 📋 Funcionalidades do Formulário

### 🔹 Informações Pessoais
- Nome completo (obrigatório)
- E-mail (obrigatório)
- Idade (opcional, com limite mínimo e máximo)

### 🔹 Experiência no Hotel
- Pergunta sobre primeira estadia (radio buttons)
- Motivos da escolha do hotel (checkboxes com múltipla seleção)

### 🔹 Avaliações
- Avaliação do serviço (select)
- Avaliação da comida (select)

### 🔹 Comentários Adicionais
- Campo de texto multilinha para feedback livre

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- Elementos semânticos
- Formulários e validação nativa do navegador

---

## ✅ Boas Práticas Aplicadas

- Associação correta entre `label` e `input`
- Uso adequado de atributos como `required`, `placeholder`, `name`, `id`
- Agrupamento de campos com `fieldset` e `legend`
- Código organizado e indentado, pronto para versionamento no GitHub

---

## 🚀 Envio do Formulário

O formulário está configurado para envio via método **POST** para a URL.

