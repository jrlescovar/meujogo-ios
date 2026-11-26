# Meu jogo iOS — V11 corrigida 1

[Arquivo V11](./meujogoHS-espname-iOS-v11.ipa) · [Release V11](https://github.com/jrlescovar/meujogo-ios/releases/tag/ios-hs-esp-1.28-teste11) · [Download](https://github.com/jrlescovar/meujogo-ios/releases/download/ios-hs-esp-1.28-teste11/meujogoHS-espname-iOS.ipa)

Baixe a nova cópia, importe no ESign, assine e instale. Repositório privado; somente V11 disponibilizada. A cópia anterior está preservada localmente.

Botão **67**, título **Xit Boladin**, menu arrastável. Ordem: **Hs Peito → Esp Name → Hs + Mira → Radar Gelo → Radar Rush → Radar AR**.

**Somente Hs Peito e Esp Name iniciam ligados.** Hs + Mira e os três radares iniciam desligados.

**Correção dos aliados:** a coleta anterior em AddTeammateHud também recebia etiquetas de inimigos. Agora a identificação usa as chaves da lista real do painel de squad, capturada em UIHudTeammatesInfoController.OnUIOpen/OnDataChanged. Sem classificação por prefixo do ID. Códigos de cor embutidos nos apelidos são removidos dos nomes monitorados. Os nomes de aliados no ESP e no painel lateral ficam amarelos; ícones de estado e marcadores do squad são preservados.

**Radar Rush:** MP40 e M1014, laranja. **Radar AR:** SCAR, **AK**, M4A1 e Groza, verde. O identificador interno antigo AK47 também é aceito. Gelo segue azul. Chaves independentes, 150 m de alcance, feixe de 25 m, até 64 itens no chão por radar disponíveis ao cliente. Ajustes anteriores do ESP ao espectar mantidos. Squad Mapa Rd removido.

**264 testes locais passaram com emulação ARM64 e APIs simuladas.** Os 5.424 membros do IPA foram verificados. As correções ainda precisam ser confirmadas no iPhone.

SHA-256: `5dd47f950049af8c122a579594d81125992c9d7ff07c54a856c8e52f53d53dd9`
