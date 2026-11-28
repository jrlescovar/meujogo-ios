# Meu jogo iOS — 2019, 2021 e 2026

As versões são independentes. Escolha o IPA correspondente ao seu servidor. Repositório público; downloads disponíveis sem login.

## 2026 — versão 1.132.1, somente Esp Name

[Arquivo IPA 2026](./meujogo2026.ipa) · [Baixar meujogo2026-ESP.ipa](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-1.132.1-esp-only-v1/meujogo2026-ESP.ipa) · [Release](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2026-1.132.1-esp-only-v1)

**Somente Esp Name, sempre ativo durante a partida.** Sem HS Peito, sem HS + Mira, sem menu, sem botão 67 e sem controles para ativar ou desativar. O alcance de 150 m, os nomes pequenos, a distância real, os inimigos vermelhos e os aliados brancos foram mantidos.

As duas modificações dos métodos de colisão usadas pelo HS foram removidas, restaurando as instruções originais da base. Não há rotina de mudança de classificação corpo/cabeça nesta cópia. O executável de inicialização da revisão anterior foi preservado; apenas o framework dos recursos foi substituído. Os outros 3.474 membros foram verificados por SHA-256.

**Validação:** 30 verificações ARM64 com engine e UIKit simulados passaram, incluindo ESP automático, ausência dos controles, alcance e preservação dos pontos de acerto. Esta cópia não foi testada no iPhone. Assine no ESign antes de instalar.

**Proteção:** a versão anterior gerou relato de suspensão por “Uso de modificador”. Esta alteração remove funções; não neutraliza verificações de proteção e não garante ausência de suspensão.

[Revisão anterior preservada](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2026-1.132.1-teste2-rev1) · [IPA original recebido](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-original/Versao2026.ipa)

SHA-256: `2da33cf7ed160b9782a950d2c455812beef98f0050f482d15d6dbed79801d80b`

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
