# Me desculpa, Fernanda 💗

Pagininha de pedido de desculpas, com o clássico botão "Não" que foge.

- Arquivo único: `index.html` (sem build, sem dependências)
- Funciona no celular (toque) e no computador (mouse)
- Pra publicar: ative o GitHub Pages na branch `main` e pronto

Pra personalizar, edite o texto da cartinha e o nome dentro de `index.html`.

## Avisos quando ela abrir

A página manda notificações pelo [ntfy.sh](https://ntfy.sh) (grátis, sem conta) quando ela abre a página, abre a pergunta, tenta o "Não" e clica em "Sim".

1. Instale o app **ntfy** (iOS/Android) ou abra `https://ntfy.sh/desculpa-fernanda-41bq76gk4yz3` no navegador.
2. Assine o tópico `desculpa-fernanda-41bq76gk4yz3`.
3. Abra o site uma vez com `?eu=1` no final da URL em **cada** aparelho seu, pra seus testes não disparar avisos (fica salvo no navegador). Abrindo via `file://` ou localhost também não dispara.

Avisos que chegam: abriu a página (só quando a aba está de fato na tela), rolou até o botão (celular), passou o mouse no botão (desktop), abriu a pergunta, 1ª e 5ª tentativa no "Não", clicou em "Sim", e um resumo ao sair (segundos de leitura, % rolado, se viu o botão, tentativas no "Não"). Cada navegador ganha um id curto (`#a3f9`) e um contador de visitas, pra saber se é a mesma pessoa voltando.

Aberturas vindas de robôs (preview de link, crawler) ou de aparelhos com fuso fora do Brasil chegam marcadas como "🤖 provável robô", em prioridade mínima (sem som). Cada aviso traz aparelho, app e fuso entre colchetes, por exemplo `[iPhone · Safari · America/Sao_Paulo]`.

O tópico está no código-fonte, então quem ler o repositório consegue vê-lo. Se quiser trocar, edite `NTFY_TOPIC` em `index.html`.
