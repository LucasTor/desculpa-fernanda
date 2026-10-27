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

O tópico está no código-fonte, então quem ler o repositório consegue vê-lo. Se quiser trocar, edite `NTFY_TOPIC` em `index.html`.
