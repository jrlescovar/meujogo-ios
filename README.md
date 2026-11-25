Meu jogo para iOS com HS e ESP Name.

**V8 de teste — JR arrastável, metros reais e Gelo azul**

[Abrir o IPA V8 para baixar](./meujogoHS-espname-iOS-v8.ipa)

Abra o arquivo ao lado deste README e toque no botão de download (↓).

[Download alternativo da V8 pela Release](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-hs-esp-1.28-teste8/meujogoHS-espname-iOS.ipa)

Durante uma partida:

- Toque em **JR** para abrir/fechar o painel. Arraste o botão JR para mover; ele permanece dentro da área útil da tela.
- **HS:** liga/desliga o HS do peito. Desligado, peito e cabeça usam a classificação original, com ou sem luneta.
- **ESP:** liga/desliga os nomes e os metros reais abaixo deles. Mantém o raio de 150 metros, nomes pequenos e aliados amarelos; demais cores anteriores preservadas.
- **HS com luneta:** permite HS com mira aberta quando o HS principal estiver ligado. Desligado, o dano com luneta fica normal, como na V5.
- **Gelo azul:** marcador experimental para a granada de gelo caída no chão, com feixe azul vertical e alcance de até 150 metros. Pode ficar ligado independentemente dos nomes.

**Limite do marcador de gelo:** depende de o cliente carregar o modelo do item no chão. Não garante localizar todo gelo existente no mapa. A identificação segue a categoria usada pelo botão original de gelo, sem fixar um ID. O feixe acompanha a posição projetada do objeto e deixa de marcar quando o modelo é retirado após coleta. Não altera o tamanho dos personagens.

Padrão ao iniciar: **HS, ESP e Gelo azul ligados; HS com luneta desligado**. As opções e a posição reiniciam quando o processo é fechado.

Para instalar e testar:

1. No Safari conectado à sua conta do GitHub, baixe a V8.
2. Importe no ESign, assine e instale usando as opções anteriores. O IPA está sem assinatura.
3. Entre em uma partida, toque e arraste o JR, e confira os metros abaixo dos nomes.
4. Procure uma granada de gelo no chão e compare o feixe com a chave Gelo azul ligada/desligada. Colete o item e confira se o feixe some.
5. Teste as três opções de HS/ESP como nas versões anteriores.

**Validação local:** 151 testes com emulação ARM64 e APIs simuladas: 28 de JR/arrasto/metros/gelo, 57 de HS, 46 do filtro ESP, 12 de cores e 8 de integridade. Os 5.424 membros do IPA foram conferidos; somente executável principal e referência de integridade do SDK mudaram desde a V7.

A interface e o comportamento real ainda precisam ser confirmados no iPhone. Os testes locais não substituem essa confirmação.

**Versões anteriores preservadas**

- [V7: menu com três chaves](./meujogoHS-espname-iOS-v7.ipa).
- [V6: aliados amarelos](./meujogoHS-espname-iOS-v6.ipa).
- [V5: HS sem luneta e dano normal com luneta](./meujogoHS-espname-iOS-v5.ipa).
- [V4 confirmada pelo usuário](./meujogoHS-espname-iOS-v4.ipa): HS do peito e cabeça funcionando, personagem sem deformação; umbigo mantém dano de peito e pode mostrar indicador visual de capa.
- Outras versões: [V2](./meujogoHS-espname-iOS-v2.ipa), [V3](./meujogoHS-espname-iOS-v3.ipa).

O arquivo sem sufixo de versão, `meujogoHS-espname-iOS.ipa`, continua sendo a V4 confirmada.

SHA-256 da V8: `1b3ad8492f49d24580e354774406d54db7923c9848671557ba6901eae18b936a`
