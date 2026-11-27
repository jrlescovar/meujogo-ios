# Meu jogo iOS — 2019, 2021 e 2026

As versões são independentes. Escolha o IPA correspondente ao seu servidor. Repositório público; downloads disponíveis sem login.

## 2026 — versão 1.132.1, Teste 2

**Para comparar a entrada:** [baixar a IPA original recebida — Versao2026.ipa](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-original/Versao2026.ipa), com 631.355.060 bytes, sem alterar nenhum byte do arquivo fornecido.

**Diagnóstico atual:** o usuário informou que o Teste 2 e a base de controle também ficaram presos após o login. A causa continua sem confirmação; a IPA original será testada para comparação.

[Baixar Teste 2 — HS e ESP](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-1.132.1-teste2/meujogo-2026-HS-ESP-teste2.ipa) · [Release e instruções](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2026-1.132.1-teste2)

O Teste 2 adia as consultas do HS até existir uma partida e um jogador válidos. Essa mudança não resolveu o carregamento no aparelho do usuário.

Menu **67 / Xit Boladin**: **Hs Peito**, **Esp Name** e **Hs + Mira**. HS Peito e ESP começam ligados; HS + Mira começa desligado. Alcance de 150 m. O menu pode aparecer somente após carregar o jogador. Radar Gelo não está incluído.

Se o Teste 2 continuar preso, baixe a [base de controle — sem HS, ESP ou menu](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-1.132.1-teste2/meujogo-2026-base-controle.ipa). Ela usa a mesma base, sem os quatro hooks JR, para isolar o problema. **Na base de controle não aparece botão 67.**

Importe a cópia escolhida no **ESign** e use as mesmas opções de assinatura do Teste 1. Passaram **63 verificações ARM64 emuladas**; isso não valida o login real nem o dano no servidor.

SHA-256 Teste 2: `d604c643c5223f61ba15812f62bb22787dbbd8400e19bae91f4f653fe415bbd8`

SHA-256 controle: `74dba7bb0b917db6154cce6856e4b57219e1574ce3527a78d5731ff732e6de0d`

## 2021 — versão 1.60.1, V1 de teste

[Arquivo IPA 2021](./meujogo-2021-HS-ESP-v1.ipa) · [Release 2021](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2021-1.60.1-v1)

Adaptação experimental para o IPA 2021, versão 1.60.1. Separada da versão 2019.

Menu arrastável: botão 67, título Xit Boladin. Hs Peito, Esp Name, Hs + Mira, Radar Gelo, Radar Rush e Radar AR. Somente HS e ESP iniciam ligados. Alcance de 150 m, nomes pequenos e distância real. Aliados em branco e inimigos em vermelho. Gelo azul; MP40/M1014 em laranja; SCAR/AK/M4A1/Groza em verde.

O login pelo Discord, os recursos e os segmentos originais da camada FFP de atualização foram preservados. As novas rotinas encaminham primeiro as chamadas à implementação original.

Passaram 58 testes locais executando ARM64 com engine e UIKit simulados. Os 5.371 arquivos do IPA foram conferidos; somente o executável foi alterado. Isso não confirma login no aparelho nem dano aceito pelo servidor.

Importe no ESign, assine com as mesmas opções usadas no original e instale. O executável está sem assinatura; a abertura após assinatura e os recursos ainda precisam de teste no iPhone.

SHA-256: `545fde2874b06bfa4422c662459f79daef1a5fd94c8971b9008b653a201152ef`

## 2019 — versão 1.28, V11 corrigida 1

[Arquivo IPA 2019](./meujogoHS-espname-iOS-v11.ipa) · [Release 2019](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-hs-esp-1.28-teste11)

Arquivo e release preservados. Menu 67 / Xit Boladin, HS, ESP, mira e três radares. Esta versão mantém as próprias configurações anteriores, inclusive a cor amarela dos aliados.

SHA-256 2019: `5dd47f950049af8c122a579594d81125992c9d7ff07c54a856c8e52f53d53dd9`
