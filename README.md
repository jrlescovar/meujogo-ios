Meu jogo para iOS: HS e ESP Name, raio de 150 metros, fonte pequena e aliados amarelos.

**V7 de teste — menu na tela**

[Abrir o IPA V7 para baixar](./meujogoHS-espname-iOS-v7.ipa)

Abra o arquivo ao lado deste README e toque no botão de download (↓).

[Download alternativo da V7 pela Release](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-hs-esp-1.28-teste7/meujogoHS-espname-iOS.ipa)

Durante uma partida, aparece o botão **Menu** na lateral esquerda. Toque para abrir ou fechar as três opções:

- **HS:** liga ou desliga o HS do peito. Desligado, peito e cabeça usam a classificação original, inclusive com luneta.
- **ESP:** mostra ou oculta os nomes acima dos jogadores. Ligado, mantém 150 metros, fonte pequena e aliados amarelos; demais cores anteriores preservadas.
- **HS com luneta:** com o HS principal ligado, permite HS também ao abrir a luneta. Desligado, o dano com luneta fica normal, como na V5.

Ao iniciar: **HS ligado**, **ESP ligado**, **HS com luneta desligado**. A terceira chave fica indisponível enquanto o HS principal estiver desligado. As opções reiniciam quando o processo do jogo é fechado.

Para testar no iPhone:

1. No Safari conectado à sua conta do GitHub, baixe a V7.
2. Importe no ESign, assine e instale usando as opções anteriores.
3. Entre em uma partida e abra o botão Menu.
4. Desligue/ligue o ESP e confira os nomes. Teste HS desligado, HS sem luneta e HS com luneta separadamente.

**Validação local:** 103 testes com emulação ARM64 e APIs simuladas: 13 do menu/ações/layout, 41 de HS e alternância, 29 do ESP, 12 das cores e 8 de integridade. Os 5.424 arquivos do IPA foram conferidos; somente executável principal e referência de integridade do SDK mudaram em relação à V6.

A interface e o comportamento real ainda precisam ser confirmados no iPhone. O IPA está sem assinatura; o ESign faz a assinatura para instalação.

**Versões anteriores preservadas**

- [V6: aliados amarelos](./meujogoHS-espname-iOS-v6.ipa).
- [V5: HS sem luneta e dano normal com luneta](./meujogoHS-espname-iOS-v5.ipa).
- [V4 confirmada pelo usuário](./meujogoHS-espname-iOS-v4.ipa): HS do peito e cabeça funcionando, personagem sem deformação; umbigo mantém dano de peito e pode mostrar indicador visual de capa.
- Outras versões: [V2](./meujogoHS-espname-iOS-v2.ipa), [V3](./meujogoHS-espname-iOS-v3.ipa).

O arquivo sem sufixo de versão, `meujogoHS-espname-iOS.ipa`, continua sendo a V4 confirmada.

SHA-256 da V7: `c292392a2b7b702e9ae8500b041fcd8641e7e758be49a234ec9bdc72e1a321eb`
