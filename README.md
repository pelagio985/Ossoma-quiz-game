# Ossoma Quiz Game — PWA 4.0

Aplicação web instalável (PWA), com funcionamento offline após a primeira visita. Inclui jogo de perguntas, perfis e ranking locais, revisão educativa, gestão local de perguntas e importação/exportação JSON.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `ossoma-quiz-game`.
2. Carregue todos os ficheiros desta pasta para a raiz do repositório, mantendo a pasta `icons`.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/(root)` e guarde.
6. Aguarde a publicação. O endereço será `https://SEU-USUARIO.github.io/ossoma-quiz-game/`.

## Instalar no Android
Abra o endereço publicado no Chrome e escolha **Instalar app** ou **Adicionar ao ecrã inicial**.

## Limites desta versão
- Perguntas personalizadas e pontuações são guardadas no navegador do dispositivo.
- Contas seguras e ranking global ainda não estão ativos. Para isso é necessário configurar um backend/base de dados, por exemplo Supabase, com políticas de segurança; GitHub Pages por si só não fornece autenticação nem base de dados.
- A tradução Makua precisa de validação por falantes competentes.
