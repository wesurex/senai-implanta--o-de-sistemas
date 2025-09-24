# 🎯 Valorant Lineups — SPA

Sistema web simples para compartilhamento de **lineups de agentes Valorant**.  
Desenvolvido como projeto final da disciplina de Implantação de Sistemas Web (SENAI).

---

## 📘 Requisitos e Funcionalidades

- Cadastro e login local (armazenado no navegador via LocalStorage).
- Postagem de lineups com:
  - Agente
  - Mapa
  - URL do YouTube
  - Título
  - Descrição
- Visualização em **grid estilo Instagram**.
- Modal para cada lineup com:
  - Vídeo embutido do YouTube
  - Likes / Dislikes
  - Contador de visualizações
  - Sessão de comentários
- Ordenação de posts:
  - Por data (lineups de hoje aparecem primeiro)
  - Por engajamento (likes, comentários, visualizações)

---

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (vanilla)
- **Armazenamento**: LocalStorage do navegador
- **Hospedagem**: Hostinger

---

## 🚀 Como Replicar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/wesurex/senai-implanta--o-de-sistemas.git
   cd senai-implanta--o-de-sistemas
Abra o arquivo index.html no navegador (não precisa de servidor).

Pronto: o sistema já estará funcionando localmente.

⚠️ Funcionalidades Não Implementadas
Autenticação real com backend (senhas estão salvas em texto no LocalStorage).

Painel admin completo para moderação de posts.

Controle de visualizações por usuário (atualmente cada abertura soma uma view).

💡 Desafios e Aprendizados
Manipular LocalStorage para simular banco de dados.

Implementar ordenadores customizados (data + engajamento).

Trabalhar responsividade (desktop, tablet e mobile).

Tratar URLs do YouTube para gerar embed automático.

🔗 Links
Deploy (Hostinger): https://wrsdev.com.br/valorant-lineups/

Repositório no GitHub: https://github.com/wesurex/senai-implanta--o-de-sistemas


---


# 📘 Manual do Usuário — Valorant Lineups

Bem-vindo ao sistema de **lineups Valorant**!  
Aqui você pode cadastrar sua conta, postar estratégias e interagir com outros jogadores.



## 👤 Cadastro e Login

1. Clique em **Entrar / Cadastrar** na barra superior.
2. No painel:
   - **Cadastrar** → crie um novo usuário com nome e senha.
   - **Entrar** → use seu usuário e senha já criados.
3. Após logar, você verá o feed de lineups.

---

## 📝 Postar um Lineup

1. Clique no botão vermelho **＋ Postar lineup** (canto inferior direito).
2. Preencha os campos:
   - Agente
   - Mapa
   - URL do vídeo (YouTube)
   - Título
   - Descrição
3. Clique em **Salvar** → o lineup aparece no feed.

---

## 📺 Visualizar Lineups

- Os lineups aparecem em **cards em grade**.
- Clique em um card para abrir o modal:
  - Vídeo em tela embutida
  - Autor, agente, mapa e data
  - Likes 👍, Dislikes 👎 e Visualizações 👁️
  - Caixa de comentários

---

## 💬 Interagir

- **Curtir / Não curtir** um lineup.
- **Comentar** dando feedback ou dicas.
- Os lineups mais recentes e com mais engajamento aparecem primeiro.

---

## 📱 Responsividade

- **Desktop:** 3 colunas no grid
- **Tablet (≤768px):** 2 colunas
- **Mobile (≤600px):** 1 coluna

---

## 🧑‍💻 Exemplos de Uso

- Postar lineup da **Viper no mapa Bind** com link de vídeo.
- Outro usuário comentar “muito bom para pós-plant!”.
- Comparar diferentes lineups no grid para decidir setups de partida.

---

## ❓ Perguntas Frequentes

- **Preciso de internet para usar?**  
  Apenas para abrir o site e carregar os vídeos do YouTube.
- **Posso usar em mais de um navegador?**  
  Sim, mas seus dados ficam salvos localmente. Cada navegador é independente.
- **Existe moderação?**  
  Ainda não, mas pode ser implementado no futuro.
