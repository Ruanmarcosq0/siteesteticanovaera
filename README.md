# Estúdio Nova Era

Site institucional preparado para publicação contínua com GitHub e Vercel.

## Como funciona a automação

1. Uma alteração é enviada para a branch `main` no GitHub.
2. A Vercel detecta o novo commit automaticamente.
3. A nova versão entra no ar e permanece no histórico da Vercel.

## Configuração inicial na Vercel

- Importe este repositório do GitHub.
- Em **Framework Preset**, selecione `Other`.
- Em **Root Directory**, mantenha `./`.
- Deixe **Build Command** e **Output Directory** vazios.
- Clique em **Deploy**.

Depois do primeiro deploy, cada `git push` na branch `main` atualizará o site automaticamente.

## Desenvolvimento local

Abra `index.html` no navegador. O projeto é estático e não exige instalação ou compilação.
