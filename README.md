# 🎯 Valorant Lineups — SPA

Sistema web simples para compartilhamento de **lineups de agentes Valorant**.  
Desenvolvido como projeto final da disciplina de Implantação de Sistemas Web (SENAI).

---

## 📘 Requisitos e Funcionalidades

- **Cadastro e login local** (armazenado no navegador via LocalStorage).
- Senha obrigatória com critérios de segurança:
  - ≥8 caracteres  
  - Maiúscula, minúscula, número e caractere especial  
- Cadastro inclui **pergunta secreta** para recuperação de senha.
- Recuperação de senha via **modal estilizado**:
  - Usuário informa login → responde pergunta secreta → redefine senha.
- Postagem de lineups com:
  - Agente
  - Mapa
  - URL do YouTube
  - Título
  - Descrição
- Visualização em **grid estilo Instagram**.
- Modal para cada lineup com:
  - Vídeo embutido do YouTube
  - Likes / Dislikes (apenas 1 por usuário)
  - Contador de visualizações
  - Sessão de comentários
- Ordenação de posts:
  - Por data (lineups de hoje aparecem primeiro)
  - Por engajamento (likes, comentários, visualizações)
- **Painel admin** (usuário `admin`):
  - Listar e remover usuários
  - Listar e remover posts

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

## ⚠️ Funcionalidades Não Implementadas
Autenticação real com backend (senhas salvas em texto no LocalStorage).

Controle avançado de visualizações (atualmente cada abertura soma uma view).

Moderação avançada de conteúdo no admin.

##💡 Desafios e Aprendizados
Manipulação de LocalStorage para simular banco de dados.

Implementar ordenadores customizados (data + engajamento).

Criar fluxo de recuperação de senha com pergunta secreta em modal.

Trabalhar responsividade (desktop, tablet e mobile).

Tratar URLs do YouTube para gerar embed automático.

## 🔗 Links
Deploy (Hostinger): https://wrsdev.com.br/valorant-lineups/

Repositório no GitHub: https://github.com/wesurex/senai-implanta--o-de-sistemas

## 📘 Manual do Usuário — Valorant Lineups
Bem-vindo ao sistema de lineups Valorant!
Aqui você pode cadastrar sua conta, postar estratégias e interagir com outros jogadores.

## 👤 Cadastro e Login
Clique em Entrar / Cadastrar na barra superior.

No painel:

Cadastrar → crie um novo usuário com nome, senha forte e pergunta secreta.

Entrar → use seu usuário e senha já criados.

Após logar, você verá o feed de lineups.

Caso esqueça a senha, clique em Esqueci minha senha e siga os passos no modal.

## 📝 Postar um Lineup
Clique no botão vermelho ＋ Postar lineup (canto inferior direito).

Preencha os campos:

Agente

Mapa

URL do vídeo (YouTube)

Título

Descrição

Clique em Salvar → o lineup aparece no feed.

## 📺 Visualizar Lineups
Os lineups aparecem em cards em grade.

Clique em um card para abrir o modal:

Vídeo em tela embutida

Autor, agente, mapa e data

## Likes 👍, Dislikes 👎 e Visualizações 👁️

Caixa de comentários

## 💬 Interagir
Curtir / Não curtir um lineup.

Comentar dando feedback ou dicas.

Os lineups mais recentes e com mais engajamento aparecem primeiro.

## ⚙️ Painel Admin
Se logar com o usuário admin, você terá acesso ao painel administrativo.

No admin é possível:

Listar e remover usuários

Listar e remover posts

## 📱 Responsividade
Desktop: 3 colunas no grid

Tablet (≤768px): 2 colunas

Mobile (≤600px): 1 coluna

## 🧑‍💻 Exemplos de Uso
Postar lineup da Viper no mapa Bind com link de vídeo.

Outro usuário comentar “muito bom para pós-plant!”.

Comparar diferentes lineups no grid para decidir setups de partida.

## ❓ Perguntas Frequentes
Preciso de internet para usar?
Apenas para abrir o site e carregar os vídeos do YouTube.

Posso usar em mais de um navegador?
Sim, mas seus dados ficam salvos localmente. Cada navegador é independente.

Existe moderação?
Apenas via admin local. Em uso real, seria necessário backend.
