# Exercise Snacks Hourly Tracker

Aplicação web *one-page* e *mobile-first* em um único arquivo `index.html` para acompanhar rotinas curtas de **exercise snacks** ao longo do dia, com lembretes por hora, notificações e alarme.

## Funcionalidades

- **Contagem regressiva e agenda diária:** Calcula os horários do dia e alterna automaticamente entre **Bloco A** (pausas ímpares) e **Bloco B** (pausas pares).
- **Dia Normal vs. Dia de Treino Pesado:** Ajusta o volume e a seleção de movimentos para não sobrecarregar a recuperação em dias de treino mais intenso.
- **Execução guiada com timer de prancha:** Checklist interativo por rodada, cronômetro embutido para isometria e registro diário salvo no `localStorage`.
- **Alertas e notificações:** Suporte a notificações do navegador, vibração em dispositivos compatíveis, alertas visuais na tela e sons gerados via Web Audio API.

## Como usar no GitHub Pages

1. Envie o arquivo `index.html` para a branch principal (`main`) do repositório.
2. Vá em **Settings > Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**, escolha a branch `main` e a pasta `/ (root)`.
4. Acesse a URL gerada pelo GitHub Pages no celular e, se quiser, adicione à tela inicial do navegador.

> **Nota sobre lembretes no celular:** Navegadores móveis podem suspender abas ou áudios em segundo plano. Para alertas mais confiáveis durante o expediente, mantenha a página aberta ou adicionada à tela inicial e acione um teste de som ao iniciar o uso.
