# 🌊 A Grande Arca — Mesa do Professor

App-companion (página única, sem back-end) para um desafio temático de **Pokémon Leaf Green**:
o treinador **Noé** crê que o apocalipse vem, e seu inimigo é o **anticristo do tipo Água** (o dilúvio).
A missão é cruzar Kanto convertendo os 8 líderes de ginásio e montando uma **arca** de Pokémon de funções de sobrevivência — **sem nenhum Pokémon de Água**.

Tudo vive em um único arquivo **`index.html`** (HTML + CSS + JS), com visual inspirado numa mesa de Professor Pokémon: **Pokédex**, **Badge Case** e **Poké Ball**.

---

## ✨ Recursos

- **Pokédex da equipe** — 6 vagas, 1 vaga = 1 função (Heavy, Driver, Fuelmaster, Forrageiro, Medic, Hacker).
- **Poké Ball 3D** — clique e ela abre o formulário de registro por dentro (nome, espécie, função, foto).
- **Badge Case horizontal** — abre dobrando de altura; tampa com o ID do treinador e emblema, base com as **8 insígnias de Kanto** (importáveis).
- **✝ Baixa & Memorial** — registre quem tombou; aperte **F** e os túmulos surgem de baixo pra cima (Torre Pokémon de Lavender).
- **Linha do tempo** — capturas, conversões e baixas entram sozinhas, com horário real; marcos manuais também.
- **Exportar / Importar** — salva e restaura **toda** a jornada num arquivo `arca-jornada.json`.
- **Imagens por URL** — fotos de Pokémon, do treinador e das badges podem ser coladas por link (carregam para todo mundo).

---

## 🚀 Publicar no GitHub Pages

1. Crie um repositório **público** (ex.: `arca-noe`) e suba o `index.html`.
2. Vá em **Settings → Pages**.
3. Em *Build and deployment*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
4. Em ~1 minuto o site fica no ar em: `https://SEU-USUARIO.github.io/arca-noe/`

> O GitHub Pages no plano grátis só serve repositórios públicos.

---

## 💾 Como salvar o progresso

Não há salvamento automático: o estado é mantido via **Exportar / Importar**.

- **Exportar jornada** baixa `arca-jornada.json` com treinador, equipe, badges, memorial e linha do tempo.
- **Importar jornada** restaura tudo de volta a partir desse arquivo.
- Fotos importadas por **arquivo** ficam embutidas no JSON; já as importadas por **URL** carregam para qualquer pessoa que abrir o site.

---

## 🛠️ Rodar localmente

É só abrir o `index.html` no navegador. Sem instalação, sem dependências
(as fontes vêm do Google Fonts via CDN, então a primeira carga precisa de internet).

---

## 📄 Licença

Projeto pessoal de fã, sem fins comerciais. Pokémon é marca da Nintendo / Game Freak / The Pokémon Company.
