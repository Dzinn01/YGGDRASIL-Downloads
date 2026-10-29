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

Atualização de 29/10/2026:

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
  As regressões das bibliotecas anteriores e do arqueiro passaram.
- Os lanceiros de Alfheim e Niflheim receberam pegada com duas mãos,
  transições corrigidas e queda com a lança acompanhando o corpo. A inspeção
  e calibração foram feitas no Blender, preservando os modelos e texturas.
  O combo do Einherjar de Alfheim agora mostra uma estocada em cada um dos
  três contatos, mantendo os tempos e danos existentes. O soldado de Niflheim
  foi revisado como asset, sem acrescentar um encontro novo.
  A nova jornada completa passou por 57 salas, cinco reinos e cinco armas,
  com 16 compras, 650 contatos e vitória. Usa save isolado e bot invencível
  para validar o fluxo; não é aprovação de dificuldade ou arte final.
- O Vigia de Geada de Niflheim recebeu arco reconstruído no Blender, com
  empunhadura, corda deformável e flecha física alinhadas. A mão de apoio
  acompanha a puxada; o arco passa afastado do antebraço e a queda evita
  a torção brusca do pulso. O ataque comum continua com três projéteis e
  o Elite com cinco, saindo da ponta da flecha. Os dois foram conferidos
  com IA ativa e câmera normal. O corpo antigo ainda precisa de acabamento.
  Uma nova jornada, com essa correção ativa, percorreu 57 salas dos cinco
  reinos e cinco armas, com 16 compras, 703 contatos e vitória. O teste usa
  bot invencível e áudio Dummy; não aprova dificuldade humana ou mixagem.
- O Berserker de Midgard recebeu pegada de duas mãos com os ombros adaptados
  ao corpo largo, punhos corrigidos e maça à frente. O combo agora mostra os
  três golpes que já causavam dano; a investida usa corrida com a arma firme.
  Foram preservados os danos, tempos, modelo texturizado e esqueleto.
  Os testes incluíram a variante normal, o Elite, a investida e regressões
  dos personagens já corrigidos. Há uma cópia Blender com nove animações
  para edição. O acabamento visual desse personagem ainda não é o final.
  A jornada com essa alteração ativa chegou à vitória após 57 salas, cinco
  reinos e cinco armas, com 16 compras e 713 contatos. Usa save isolado,
  bot invencível e áudio Dummy; a validação de dificuldade e mixagem segue
  pendente.
- O Jötunn de Gelo de Niflheim recebeu pegada de duas mãos, joelhos
  articulados e pancada voltada ao chão no instante da explosão de gelo.
  Normal e Elite preservam dano, Armadura e tempo de preparação. Foram usados
  Blender e animações Quaternius CC0 adaptadas; há seis ações editáveis.
  A jornada com essa correção percorreu 57 salas, cinco reinos e cinco armas,
  com 16 compras, 823 contatos e vitória. Usa bot invencível e áudio
  Dummy, sem aprovar dificuldade humana ou mixagem. O corpo antigo do gigante
  ainda precisa da reconstrução visual solicitada.
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

[Terceira estocada do Einherjar em Alfheim](previews/V73-Alfheim-Combo-20261028.png) ·
[Pegada vista de perto no Godot](previews/V73-Alfheim-Grip-20261028.png).
A primeira captura usa a câmera normal do jogo e IA ativa; a segunda usa
câmera de inspeção. Animações Quaternius CC0 adaptadas para a lança.
O acabamento dos modelos antigos continua pendente.

[Vigia de Geada preparando o disparo em Niflheim](previews/V73-Niflheim-Archer-20261028.png) ·
[Arco e puxada vistos de perto](previews/V73-Niflheim-Bow-20261028.png).
Capturas reais do Godot: câmera normal e IA ativa na primeira, câmera de
inspeção na segunda. O arco foi reconstruído no Blender; o corpo ainda é
o modelo antigo. Animações Kevin Iglesias Human Archer FREE (2.0), adaptadas
sob licença do autor; reação e morte Quaternius CC0.


[Terceiro golpe do Berserker Elite](previews/V73-Midgard-Berserker-20261028.png) ·
[Investida com a maça à frente](previews/V73-Midgard-Charge-20261028.png) ·
[Preparação vista de lado](previews/V73-Midgard-Heavy-Grip-20261028.png).
Capturas reais do Godot em segundo plano. As duas primeiras usam câmera normal
e IA ativa em encontros controlados; a terceira usa câmera de inspeção.
O teste da investida começa com o ataque pronto, à distância apropriada.
Animações Quaternius CC0 adaptadas à anatomia e à maça de duas mãos.
Os prints mostram a correção de movimento, sem aprovar o acabamento final.

[Jötunn de Gelo no impacto](previews/V73-Niflheim-Giant-20261029.png) ·
[Variante Elite](previews/V73-Niflheim-Giant-Elite-20261029.png) ·
[Pegada e postura vistas de lado](previews/V73-Niflheim-Giant-Grip-20261029.png).
Capturas reais do Godot em segundo plano: câmera normal/IA ativa nas duas
primeiras e câmera de inspeção na terceira. Documentam movimento e contato
da arma; não representam o acabamento final dos materiais e do personagem.
