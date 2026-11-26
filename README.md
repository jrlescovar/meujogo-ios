Meu jogo para iOS com HS e ESP Name.

**V9 de teste — 67 / Xit Boladin / Squad Mapa Rd**

[Abrir o IPA V9 para baixar](./meujogoHS-espname-iOS-v9.ipa)

Abra o arquivo ao lado deste README e toque no botão de download (↓).

[Download alternativo da V9 pela Release](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-hs-esp-1.28-teste9/meujogoHS-espname-iOS.ipa)

O botão arrastável agora mostra **67**. Toque para abrir/fechar o painel, cujo título é **Xit Boladin**.

As opções aparecem nesta ordem:

1. **Hs Peito** — liga/desliga o HS do peito. Desligado, o dano usa a classificação original.
2. **Esp Name** — liga/desliga nomes pequenos, com metros reais abaixo e limite de 150 metros. Aliados continuam amarelos; demais cores anteriores preservadas.
3. **Hs + Mira** — permite HS com luneta quando Hs Peito estiver ligado. Desligado, a luneta mantém dano normal.
4. **Radar Gelo** — marcador azul experimental para o modelo da granada de gelo caída no chão. Depende de o cliente carregar o modelo, com alcance máximo de 150 metros.
5. **Squad Mapa Rd** — mostra marcadores adicionais de inimigos somente com o mapa grande aberto em partida de squad.

**Squad Mapa Rd**

- Preserva os marcadores verdes originais da sua equipe.
- Agrupa inimigos pelo identificador de equipe do próprio jogo. Membros do mesmo squad recebem a mesma cor e número de equipe.
- Usa 16 cores distintas, embaralhadas uma vez por partida. As cores permanecem estáveis nessa partida.
- Acompanha a posição atual, o movimento e o zoom do mapa, com recorte dentro do painel.
- É independente de Hs Peito e Esp Name, com limite de 64 marcadores e sem o corte de 150 metros dos nomes.
- Usa apenas as posições atuais disponíveis no cliente. Não cria dados que o jogo não recebeu.
- Não acrescenta esses marcadores ao minimapa, solo ou duo.
- Os marcadores extras não recebem toques. O mapa continua podendo ser arrastado e ampliado.
- Os raios de gelo ficam ocultos enquanto o mapa estiver aberto e retornam após fechar.

Padrão ao iniciar: **Hs Peito, Esp Name, Radar Gelo e Squad Mapa Rd ligados; Hs + Mira desligado**. As opções e a posição do botão reiniciam quando o processo é fechado.

Para instalar e testar:

1. No Safari conectado à sua conta do GitHub, baixe a V9.
2. Importe no ESign, assine e instale usando as opções anteriores. O IPA está sem assinatura.
3. Confira o botão 67, título Xit Boladin e os cinco nomes na ordem indicada.
4. Entre em squad, abra o mapa grande e compare os marcadores de cada equipe.
5. Desligue/ligue Squad Mapa Rd, mova/amplie o mapa e depois feche-o. Os pontos extras devem acompanhar o mapa e sumir ao fechar.
6. Confira também as funções anteriores de HS, nomes, metros e gelo.

**Validação local:** 233 testes com emulação ARM64 e APIs simuladas: 46 de menu/gelo/mapa, 89 de HS, 78 de ESP, 12 de cores e 8 de integridade. O gancho do mapa e a rotina original de projeção do jogo foram executados nos testes. Os 5.424 membros do IPA foram conferidos; somente executável principal e referência de integridade do SDK mudaram desde a V8.

A interface e as posições reais ainda precisam ser confirmadas no iPhone. Os testes locais não substituem essa confirmação.

**Versões anteriores preservadas**

[V8](./meujogoHS-espname-iOS-v8.ipa), [V7](./meujogoHS-espname-iOS-v7.ipa), [V6](./meujogoHS-espname-iOS-v6.ipa), [V5](./meujogoHS-espname-iOS-v5.ipa), [V4 confirmada](./meujogoHS-espname-iOS-v4.ipa), [V3](./meujogoHS-espname-iOS-v3.ipa) e [V2](./meujogoHS-espname-iOS-v2.ipa).

O arquivo sem sufixo de versão, `meujogoHS-espname-iOS.ipa`, continua sendo a V4 confirmada.

SHA-256 da V9: `f60204830fcee74063acb5543075919bd9eafb7bdd89d02454bfdd64dd6fb40b`
