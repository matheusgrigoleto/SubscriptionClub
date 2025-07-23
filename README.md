# 💳 SubscriptionClub

[![Deploy on Vercel](https://img.shields.io/badge/Deploy-Vercel-000?style=for-the-badge&logo=vercel&logoColor=white)](https://subscriptionclub.vercel.app/)

Um projeto visual desenvolvido com foco no **aperfeiçoamento de técnicas de CSS**, especialmente em **animation** e **transition**, simulando uma interface de clube de assinaturas moderna, responsiva e interativa.

> 🌐 [Acesse o projeto ao vivo aqui](https://subscriptionclub.vercel.app/)

---

## ✨ Objetivo

Este projeto visa consolidar conhecimentos avançados de **CSS puro**, criando uma experiência visual sem uso de JavaScript. A ideia central foi usar:

- ✳️ `animation` com `@keyframes`
- 🔄 `transition` e `transform` (`scale`, `rotate`)
- 📱 `media queries` e `scroll snapping`
- 🎨 pseudo-elementos e efeitos de hover

---

## 🛠 Tecnologias Utilizadas

- **HTML5**
- **CSS3 (vanilla)**
- Responsividade com Flexbox + Scroll Snap
- Deploy via **Vercel**

---

## 🖼️ Funcionalidades Visuais

- 🎯 Cards com interações dinâmicas ao passar o mouse
- 🎢 Animações suaves e coerentes em diferentes tamanhos de tela
- 🎠 Carrossel responsivo em mobile usando apenas CSS
- 🎯 Destaque visual com `z-index` e efeitos visuais em camadas
- 🎨 Botões com efeitos interativos (`::before`, `hover`, etc.)

---

## 📱 Responsivo?

Sim! O layout foi feito pensando em **todos os tamanhos de tela**, com destaque para o **carrossel mobile** usando:

```css
scroll-snap-type: x mandatory;
overflow-x: auto;
