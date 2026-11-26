# Grimório do Multiverso

Site do **Escolhidos pelo Multiverso RPG (EPM)**: magias, rituais e habilidades, com o criador guiado de habilidades, magias, rituais e da Habilidade Única Inicial.

**Endereço:** https://katsur1369.github.io/grimorio-do-multiverso/

## Acompanha o módulo

Este repositório só publica. O site e os dados ficam no módulo [`epm-ficha`](https://github.com/KaTsUr1369/epm-ficha):

- `site/index.html`: o site;
- `scripts/grimorio-dados.mjs`: as magias e rituais (viram o `grimorio.json`).

O workflow **Publicar o Grimório** pega a `main` do módulo a cada 15 minutos e publica. Para publicar na hora: aba **Actions** → **Publicar o Grimório** → **Run workflow**. O rodapé do site mostra a versão do EPM publicada.

O `index.html` e o `grimorio.json` daqui só são usados se o módulo ainda não tiver a pasta `site/`.

## No Foundry (módulo `epm-ficha` 0.9.2 ou mais novo)

O módulo abre este site numa janela do Foundry (botão **Grimório** na aba Habilidades, **Site** na aba Magias, **Site do Grimório** no Escudo do Mestre).

- **Arraste** qualquer cartão para a ficha, ou clique em **Adicionar à ficha**.
- Magias e rituais entram direto na ficha.
- Habilidades de exemplo abrem a janela de aprender.
- A habilidade montada no **Criar** abre o criador da ficha já preenchido e vira projeto (PH, horas e teste).
- A Habilidade Única Inicial é montada pelo Mestre.

O endereço do site pode ser trocado nas configurações do módulo (**Endereço do Grimório do Multiverso**).
