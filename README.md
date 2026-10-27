# YGGDRASIL — Downloads

Action roguelike 3D com câmera top-down/isométrica, Einar e cinco reinos da mitologia nórdica.

## Versão disponível: V7.1 — build de teste

A V7.3 está em desenvolvimento. Os downloads abaixo são da **V7.1**; não incluem
as alterações da V7.3 ainda em revisão.

### Windows

[Baixar Yggdrasil-V7.1-Windows.zip](https://github.com/Dzinn01/YGGDRASIL-Downloads/releases/download/v7.1/Yggdrasil-V7.1-Windows.zip)

1. Baixe o ZIP pelo link acima.
2. Extraia os arquivos.
3. Abra **Yggdrasil.exe**.

Godot e Blender não precisam estar instalados. O ZIP inclui instruções, créditos e licenças dos recursos utilizados. O download é público e pode ser compartilhado com amigos.

## Controles

- WASD: mover; mouse: mirar.
- Botão esquerdo: Attack. No Arco, segure e solte para disparar.
- Botão direito: Special.
- Espaço: Dash; E: interagir; Tab: mapa; Esc: pausa.
- Controle Xbox: analógicos movem/miram; X ataca, Y usa Special, A faz Dash e B interage.

### Android

[Baixar Yggdrasil-V7.1-Android.apk](https://github.com/Dzinn01/YGGDRASIL-Downloads/releases/download/v7.1/Yggdrasil-V7.1-Android.apk)

Versão de teste com controles por toque e tela em paisagem. O Galaxy A34 é a
referência de desenvolvimento; testes de desempenho no aparelho físico continuam
pendentes.

[Notas e todos os arquivos da V7.1](https://github.com/Dzinn01/YGGDRASIL-Downloads/releases/tag/v7.1)
· [Verificação SHA-256 dos downloads](https://github.com/Dzinn01/YGGDRASIL-Downloads/releases/download/v7.1/Yggdrasil-V7.1-Downloads-SHA256.json)

## V7.3 — trabalho em andamento

Atualização de 27/10/2026:

- Os Deuses que concedem Dádivas permanecem aliados. Os encontros hostis de Thor,
  Odin e Hel foram retirados da versão em desenvolvimento.
- Correções de áudio de combate, quebra de Armadura dos Elites e retorno dos menus
  estão no código da V7.3.
- Animações externas gratuitas estão sendo adaptadas aos esqueletos existentes.
  Os soldados de espada de Midgard, Helheim e Muspelheim receberam correções de
  pegada e movimento. O Huscarl de Midgard agora segura o escudo pela alça e usa
  preparação, golpe e recuperação próprios, mantendo a espada em guarda.
  O arqueiro de Midgard também recebeu animações de arco adaptadas no Blender:
  mão na empunhadura, corda acompanhando a puxada e flecha saindo da ponta real.
  O arco gira para fora durante a elevação para liberar espaço para o antebraço.
  Os testes individuais de movimento, geometria e disparo passaram.
  A jornada mais recente terminou com 57 salas, cinco reinos/armas, 16 compras
  e vitória; usa bot invencível para validar o fluxo, não dificuldade humana.
  Os demais continuam passando por revisão individual.
- Os escudos antigos de Alfheim, Helheim e Muspelheim foram separados no
  Blender e passaram a acompanhar a mão, preservando ossos, pesos e texturas.
  Alfheim usa golpe com escudo; Muspelheim prepara sua descarga de área.
  O guarda de Helheim foi revisado como asset, sem criar novo encontro.
  A revisão anatômica dos 35 humanoides e a regressão do arqueiro passaram.
  Esta é uma correção de rig e movimento; os modelos antigos ainda precisam
  do acabamento visual solicitado para a V7.3.
- O Cavaleiro de Cristal de Niflheim também recebeu o escudo preso à mão
  e animações adaptadas de estocada e golpe com escudo. O rig e as texturas
  foram preservados e reimportados no Blender. Foram conferidos a anatomia,
  as transições e os contatos de dano, incluindo os dois golpes do Elite.
  As regressões das bibliotecas anteriores e do arqueiro passaram. A run
  completa citada acima é do checkpoint de 26/10; nesta revisão foram
  executados encontros controlados específicos de Niflheim.
- A reconstrução de todos os modelos, a avaliação final de desempenho e os novos
  executáveis ainda não estão concluídos.

Esta página será atualizada quando houver uma nova build validada para download.

[Captura do guarda com escudo durante o combate](previews/V73-Midgard-Shield-20261024.png).
Essa captura documenta a correção de movimento na versão em desenvolvimento;
o acabamento antigo do modelo ainda não representa a arte final da V7.3.

[Arqueiro preparando o disparo](previews/V73-Midgard-Archer-20261025.png).
Captura real do Godot, na câmera normal, em encontro controlado com IA ativa
e jogador parado/invencível. Registra o movimento; o acabamento visual do
personagem continua pendente. Animações: Kevin Iglesias, Human Archer Animations
FREE (2.0), adaptadas sob licença do autor; reações Quaternius CC0.

[Guarda de Alfheim em defesa](previews/V73-Alfheim-Guard-20261026.png) ·
[Guarda de Muspelheim preparando descarga](previews/V73-Muspelheim-Guard-20261026.png).
Capturas reais do Godot, com câmera normal, IA ativa e encontros isolados para
inspeção. O jogador fica parado e invencível nesses testes. Não são arte final.

[Cavaleiro de Cristal preparando a estocada](previews/V73-Niflheim-Spear-20261027.png) ·
[Segundo golpe do Elite com escudo](previews/V73-Niflheim-Elite-20261027.png).
Capturas reais do Godot em Niflheim, câmera normal e IA ativa, com jogador
parado/invencível. Documentam a correção de movimento, não a arte final.
