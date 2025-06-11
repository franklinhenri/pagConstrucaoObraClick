# Obra Click

Repositório privado para o desenvolvimento da aplicação **Obra Click**.

## 🔧 Visão Geral do Projeto

Obra Click é uma plataforma voltada para otimizar a gestão de compras e fornecimento de materiais de construção, conectando empresas a fornecedores por meio de um sistema de leilão, controle de estoque, rastreamento de entregas e mais.

> ⚠️ Este repositório é **privado** e está em fase ativa de desenvolvimento. A publicação de código na branch `main` está restrita a versões estáveis e testadas.

---

## 🧠 Estrutura de Branches (Fluxo de Desenvolvimento)

Abaixo está o fluxograma que ilustra o fluxo de trabalho com Git usado neste repositório:

### 📌 Descrição das Branches

- **`main`**: Contém apenas código estável e pronto para produção.
- **`preMain`**: Branch de integração e preparação para produção. Recebe código testado vindo das branches `front` e `back`.
- **`front`**: Contém os arquivos relacionados ao front-end.
- **`back`**: Contém os arquivos relacionados ao back-end.
- **`taskXX`**: Branches de tarefas individuais (ex: `task01`, `task02`), criadas a partir da `front` ou `back`, usadas pelos desenvolvedores para trabalhar em funcionalidades específicas.
- **`preBack`**: Branch intermediária antes da junção do back-end em `preMain`.

---

## 👥 Desenvolvedores

- **Artur** — Desenvolvimento Front-End
- **Henrique** — Desenvolvimento Front-End e Back-End

---

## 📦 Tecnologias Utilizadas

- Front-end: React + Tailwind CSS
- Back-end: Laravel
- Controle de versão: Git

---

## ✅ Regras de Commit

1. Commits devem ser claros e descritivos.
2. Prefixar com tipo, ex: `feat:`, `fix:`, `refactor:`, `docs:`
3. Trabalhe em branches de tarefa (`taskXX`) e faça pull requests para `front` ou `back`.

---

## 🔐 Aviso

Este repositório é exclusivo para uso interno da equipe Obra Click. Qualquer tentativa de acesso ou redistribuição não autorizada será considerada uma violação de direitos.
