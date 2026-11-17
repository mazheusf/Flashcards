# Flashcards — iPhone PWA

Aplicativo web instalável no iPhone pelo Safari, com baralhos, cartões frente/verso, revisão espaçada inicial, estatísticas básicas e backup JSON.

## Publicar no GitHub Pages
1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione **main** e **/(root)** e salve.
4. Aguarde a publicação. O endereço esperado é https://mazheusf.github.io/Flashcards/.
5. No iPhone, abra esse endereço no Safari, toque em Compartilhar → Adicionar à Tela de Início.

Os dados ficam no armazenamento local do navegador. Para levar cartões a outro aparelho, use Backup e Importar. A sincronização automática entre aparelhos ainda não está implementada.

## Nota técnica
O agendamento atual é uma implementação simplificada inspirada no SM-2, não o algoritmo FSRS oficial do Anki.
