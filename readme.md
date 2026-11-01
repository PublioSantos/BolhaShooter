# 🫧 Bolha Shooter

Um jogo de bolhas (estilo *bubble shooter*) feito em HTML5 Canvas + JavaScript puro, sem dependências. Roda direto no navegador — só abrir o arquivo `index.html`.

https://publiosantos.github.io/BolhaShooter/

## 🎮 Como jogar

- **Mova o mouse** (ou arraste o dedo) para mirar.
- **Clique** (ou solte o dedo) para atirar.
- Também funciona com teclado: **← →** para mirar e **Espaço** para atirar.
- Estoure **3 ou mais bolhas** da mesma cor para eliminá-las.
- Bolhas que perdem contato com o topo **caem** e valem pontos extras.
- **Limpe todo o campo** para avançar de nível.

---

## ⚠️ Mecânicas de tensão

O jogo tem **duas** formas de a linha descer — o que acontecer primeiro:

1. **Por tiros** — a cada N tiros (varia por nível) uma nova linha aparece no topo.
2. **Por tempo** — há um cronômetro por nível (de 45s até 18s). Se o tempo acabar, a linha desce do mesmo jeito.

E ainda:

3. **Mira que encolhe** — cada tiro que **não** elimina bolhas reduz a linha-guia de mira. Ela só volta ao tamanho cheio no próximo nível. Errar tem custo!

Se as bolhas chegarem à **linha de perigo** (perto do canhão), é **fim de jogo**.

---

## 🏆 Sistema de níveis

- **10 níveis** com dificuldade crescente (mais cores, menos tempo, mais linhas iniciais).
- A cada nível completo você ganha **+100 × nível** de bônus.
- Pontuação final é salva no **`localStorage`** como recorde pessoal.
- Terminar o nível 10 = **vitória**.

---

## ✨ Recursos

- 🎨 Bolhas com gradiente, brilho e sombra (Canvas puro).
- 🔊 Efeitos sonoros gerados via **Web Audio API** (sem arquivos de áudio).
- 📱 Layout responsivo e suporte a **touch**.
- 🌌 Fundo estrelado com parallax suave.
- 💥 Partículas, popups de pontos e *screen shake*.
- 🎯 Linha de mira com **rebote nas paredes**.
- 💾 Recorde persistente via `localStorage`.
