# 🧠 PsicoConnect

PsicoConnect é uma **plataforma web para atendimento psicológico**, desenvolvida com o objetivo de simular um sistema real de conexão entre **usuários** e **psicólogos**.

O projeto foi construído com foco em **organização, modularização e escalabilidade**, servindo como base para futura evolução para uma aplicação **full stack**, com backend em **.NET**.

---

## 🚀 Funcionalidades

- 👤 Perfis distintos (Usuário e Psicólogo)
- 💬 Chat em tempo real utilizando Firebase
- 🧠 Listagem de especialidades psicológicas
- 📋 Estrutura de prontuário psicológico
- 🧩 Organização modular por páginas e funcionalidades
- 🎨 Interface simples e objetiva, focada em usabilidade

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Firebase** (chat em tempo real)

---

## 📂 Estrutura do Projeto

| Caminho | Conteúdo |
| --- | --- |
| `tela principal/Tela-Principal.html` | Página inicial |
| `Chat/chat.html` | Interface do chat |
| `Chat/script-chat/script-chat.js` | Login/cadastro no chat e mensagens |
| `Chat/script-chat/configFirebase.js` | Configuração Firebase |
| `Especialidades/` | Páginas de especialidades |
| `Perfil-Psicologo/` e `Perfil-Usuario/` | Telas de perfis |
| `Prontuario/` | Tela de prontuário |
| `cadastro-paciente/` e `cadastro-psicologo/` | Telas de cadastro |
| `login-paciente/` e `login-psicologo/` | Telas de login |

A organização do projeto prioriza **separação de responsabilidades**, facilitando manutenção e evolução futura.

---

## ▶️ Como Executar o Projeto

Este projeto **não utiliza frameworks ou npm**.

Abra a raiz do repositório no VS Code e use **Live Server** no arquivo `tela principal/Tela-Principal.html`.

Alternativamente, com Python instalado, execute na raiz:

```bash
python -m http.server 8000
```

Acesse [a página inicial local](http://localhost:8000/tela%20principal/Tela-Principal.html) ou [o chat](http://localhost:8000/Chat/chat.html). Use um servidor HTTP local, pois o chat utiliza módulos JavaScript.

Para testar o chat, configure um projeto Firebase próprio em `Chat/script-chat/configFirebase.js`, com Authentication por e-mail/senha e Realtime Database. As regras de acesso do banco precisam ser configuradas no Firebase; a seleção de perfil no JavaScript não substitui autorização no servidor.

O chat já possui funções de login e cadastro com Firebase. A API .NET e a autorização integrada por perfis continuam como evolução planejada.

---

## 🎯 Objetivo do Projeto

Este projeto tem como principais objetivos demonstrar:

- Capacidade de estruturar um **sistema web real**
- Organização de código front-end
- Pensamento voltado para **aplicações escaláveis**
- Preparação para integração com backend
- Visão de produto, não apenas telas isoladas

---

## 🔮 Próximos Passos (Evolução Planejada)

- Integração com **API REST em .NET**
- Integração da autenticação existente com autorização por perfis em toda a aplicação
- Persistência de dados em banco relacional
- Controle de permissões por perfil
- Histórico de atendimentos e prontuários

---

## 👨‍💻 Autor

**Rodrigo Abade**  
Desenvolvedor de Software  

🔗 GitHub: https://github.com/RodrigoAbade  
🔗 LinkedIn: https://www.linkedin.com/in/rodrigo-abade  
🌐 Portfólio: https://rodrigo-abade.vercel.app/

---

> Este projeto faz parte do meu portfólio profissional e foi desenvolvido com fins educacionais e demonstrativos.
