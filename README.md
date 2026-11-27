# Meu jogo iOS — 2019, 2021 e 2026

As versões são independentes. Escolha o IPA correspondente ao seu servidor. Repositório público; downloads disponíveis sem login.

## 2026 — versão 1.132.1, Teste 2 revisão 1

[Arquivo IPA 2026 — meujogo2026.ipa](./meujogo2026.ipa) · [Baixar diretamente](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-1.132.1-teste2-rev1/meujogo2026.ipa) · [Release e instruções](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2026-1.132.1-teste2-rev1)

Revisão da inicialização do Teste 2. O executável principal foi reconstruído com a estrutura e as dependências originais, usando o código já legível da referência fornecida. O segmento extra herdado da referência foi removido. **Somente o executável principal mudou em relação ao Teste 2**; o framework das três funções e os outros 3.474 membros do IPA foram conferidos por SHA-256 e permanecem iguais.

Menu **67 / Xit Boladin**: **Hs Peito**, **Esp Name** e **Hs + Mira**. HS Peito e ESP começam ligados; HS + Mira começa desligado. Alcance de 150 m. O menu pode aparecer somente após carregar o jogador. Radar Gelo não está incluído.

**Para testar:** importe este novo `meujogo2026.ipa` no ESign, assine e instale usando as mesmas opções do Teste 2. Primeiro verifique se a cópia passa do carregamento após o login e entra no lobby; depois entre numa partida para testar as funções. A checagem estrutural e oito cenários de inicialização ARM64 passaram localmente, com Foundation/Unity simulados. As 63 verificações anteriores das funções continuam associadas ao mesmo framework, que não foi alterado. Isso não confirma login no aparelho nem dano aceito pelo servidor.

**Diagnóstico:** o Teste 2 anterior e a base sem funções ficaram presos após o login; a IPA original exata fechou ao abrir e mostrou aviso de código criptografado no ESign. A revisão atual ainda precisa de teste no iPhone; a causa do carregamento preso não está confirmada. O código de login e as decisões de integridade não foram alterados.

[Teste 2 anterior e base de controle](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-2026-1.132.1-teste2) · [IPA original exata recebida](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-2026-original/Versao2026.ipa)

SHA-256 desta revisão: `c21e9d876bfd5ba89ba02f85c3f426af9b44ec42f790b24e59a65f4148af7e7f`

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
