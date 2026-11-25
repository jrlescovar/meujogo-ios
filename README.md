Meu jogo para iOS com HS e ESP Name até 150 metros, fonte pequena e sem linha de distância.

**V6 para testar: aliados em amarelo.**

- Somente os nomes dos aliados recebem amarelo (#FFFF00), usando a identificação de equipe do próprio jogo.
- Os demais nomes mantêm as cores que já tinham na V5.
- A fonte, alcance, ícones de estado e rotina de HS/luneta da V5 são preservados.

[Abrir o IPA V6 para baixar](./meujogoHS-espname-iOS-v6.ipa)

O arquivo `meujogoHS-espname-iOS-v6.ipa` aparece ao lado deste README. Abra o arquivo e toque no botão de download (↓).

[Download alternativo da V6 pela Release](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-hs-esp-1.28-teste6/meujogoHS-espname-iOS.ipa)

A alteração de cor passou em 12 testes ARM64 e 8 de integridade com APIs de cena simuladas. Ainda precisa ser confirmada no iPhone em uma partida com aliados.

**Comportamento de HS/luneta herdado da V5:**

- Com a luneta aberta, o dano usa a classificação original: peito é peito, cabeça é cabeça.
- Sem luneta, o peito usa o HS da V4.
- A cabeça original e o ESP são preservados nos dois modos.

[V5 preservada para baixar](./meujogoHS-espname-iOS-v5.ipa)

**V4 confirmada pelo usuário e preservada:**

[Baixar V4](./meujogoHS-espname-iOS-v4.ipa)

O usuário confirmou na V4 o HS no peito, a cabeça funcionando e o personagem sem deformações. O umbigo mantém dano de peito, podendo mostrar o indicador visual de capa. O arquivo sem sufixo de versão, `meujogoHS-espname-iOS.ipa`, também continua sendo a V4.

Para testar a V6 no iPhone:

1. No Safari conectado à sua conta do GitHub, baixe o arquivo V6 e importe no ESign para assinar e instalar.
2. Em uma partida com aliados, confira os nomes amarelos. Os demais devem continuar com suas cores anteriores.
3. Abra a luneta e teste peito e cabeça com dano normal.
4. Feche a luneta e confira se o HS do peito voltou.

A V5 passou em 24 testes ARM64 da alternância e ciclo de vida, 13 do ESP e 8 de integridade, com APIs simuladas. A alternância ainda precisa ser confirmada numa partida no iPhone.

Outras versões preservadas: [V2](./meujogoHS-espname-iOS-v2.ipa), [V3](./meujogoHS-espname-iOS-v3.ipa).

Os IPAs estão sem assinatura; a assinatura e a instalação são feitas pelo ESign.

SHA-256 da V5: `6af0553c6b7b4d83f831d52f7749ba4fbde24186868d925640ced3d55eec9089`

SHA-256 da V6: `c9e603c93d82b7cdbc9525b9c9028d3d7e71963ab03c404a2c31cee012f3b89a`

SHA-256 da V4 preservada: `0de06c67a3b944a80566ef86af886c0c739121358a27781779f250cabe49a33d`
