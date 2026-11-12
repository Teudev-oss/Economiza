Você vai gerar TODOS os assets de um minidocumentário do YouTube usando o conector da Higgsfield. A montagem final será feita depois, em outra sessão. Siga as regras à risca.

## REGRAS GERAIS
- Use SEMPRE as minhas gerações ilimitadas: `use_unlim: true` em toda geração. Se algum modelo recusar o ilimitado, NÃO gaste créditos. Pare e me avise.
- Não crie projeto/pasta na Higgsfield, a menos que seja necessário.
- Nada de rostos realistas de pessoas reais. Pessoas aparecem só em silhueta, de costas ou em contraluz.
- Nada de logos reais de marcas.
- Use os batches (`generate_image_batch`, `generate_video_batch`, `generate_audio_batch`) e `jobs_wait` para ir mais rápido.
- Se uma geração falhar, tente 1 vez de novo. Se falhar de novo, pule e anote no relatório.
- NO FINAL, me entregue o MANIFESTO (formato no fim deste prompt). Ele é o mais importante.

---

## ETAPA 1 — NARRAÇÃO (voz masculina, português do Brasil, o mais realista possível)

1. Rode `list_voices` e liste as vozes masculinas que falam bem português brasileiro.
2. Escolha a mais realista, grave e com tom de documentário: narrador sério e dramático, estilo canal Magnates Media.
3. Modelo preferido: `text2speech_v2` com `variant: "elevenlabs"`. Se o ElevenLabs não tiver voz boa em PT-BR ou recusar o ilimitado, use `seed_audio`.
4. Gere primeiro um TESTE curto com a frase "Mas trinta anos antes, essa mesma empresa estava a um mês de fechar as portas." Me diga qual voz escolheu e por quê, e siga em frente.
5. Gere os 11 blocos abaixo com a MESMA voz (mesmo voice_id), um áudio por bloco. Não altere o texto.

**N00 — Gancho**
Em vinte e nove de outubro de dois mil e vinte e cinco, uma empresa fez algo que nenhuma outra na história tinha feito. Ela passou a valer cinco trilhões de dólares. Mais do que a economia inteira do Japão. Mais do que a da Índia. Mais que Brasil, Argentina e México… somados. Mas trinta anos antes, essa mesma empresa estava a um mês de fechar as portas. Sem dinheiro. Com um produto que ninguém queria. E com o único cliente que tinha prestes a abandoná-la. Essa é a história de como uma placa de vídeo para videogame virou a empresa mais valiosa do planeta. E de como ela quase não sobreviveu para ver isso.

**N01 — Uma mesa no Denny's**
Mil novecentos e noventa e três. San Jose, Califórnia. Numa mesa de uma lanchonete Denny's, três engenheiros tomam café e rabiscam ideias. Jensen Huang, Chris Malachowsky e Curtis Priem. Jensen tinha trinta anos, e uma história que parece roteiro de filme: nasceu em Taiwan, foi mandado para os Estados Unidos ainda criança, e, ironia do destino, já tinha trabalhado lavando pratos… no Denny's. A aposta deles era simples de explicar e difícil de executar: os computadores do futuro iam precisar de um chip só para desenhar imagens. Gráficos em três dimensões. Videogames. Em abril de mil novecentos e noventa e três, nasce a empresa. O nome vem de "invidia", inveja, em latim. A ideia era fazer um chip que deixasse todo mundo… com inveja.

**N02 — O primeiro fracasso**
Dois anos depois, sai o primeiro produto: o NV1. E ele foi… um desastre. O NV1 desenhava o 3D de um jeito diferente do resto da indústria, usando curvas, em vez de triângulos. Era tecnicamente inteligente. Mas o mercado escolheu os triângulos. E a Microsoft, com o DirectX, cravou esse padrão. A NVIDIA tinha um contrato com a Sega para criar o chip do próximo console. Mas quanto mais o projeto andava, mais claro ficava: a tecnologia estava errada. Então Jensen fez algo que quase nenhum CEO faz. Ele procurou a Sega e admitiu: a nossa tecnologia está errada, vocês deveriam procurar outra empresa. E pediu mais uma coisa: que a Sega pagasse o contrato mesmo assim. Era isso, ou a NVIDIA morria.

**N03 — Um mês de vida**
O executivo da Sega, Shoichiro Irimajiri, decidiu acreditar no jovem engenheiro. A Sega investiu cinco milhões de dólares na NVIDIA. Parece muito. Não era. Era combustível para poucos meses. Jensen demitiu mais da metade da empresa. E apostou tudo num único chip. Para ganhar tempo, eles fizeram algo arriscado: em vez de fabricar protótipos físicos, caros e lentos, testaram o chip inteiro num simulador. Se tivesse um erro, não haveria segunda chance. Em agosto de mil novecentos e noventa e sete, sai o RIVA 128. Quando ele chegou às lojas, a NVIDIA tinha dinheiro para pagar os funcionários por mais um mês. E então… vendeu. Cerca de um milhão de unidades em quatro meses. A NVIDIA sobreviveu. E Jensen nunca mais esqueceu essa sensação. Durante anos, ele repetiria para os funcionários: a nossa empresa está a trinta dias de quebrar.

**N04 — A guerra dos games**
Em janeiro de mil novecentos e noventa e nove, a NVIDIA abre capital na bolsa. E no mesmo ano lança a GeForce 256, que ela mesma batiza de "a primeira GPU do mundo". Graphics Processing Unit. O nome pegou. A sigla virou categoria. A grande rival da época, a 3dfx, dona das famosas placas Voodoo, não acompanhou o ritmo. No fim de dois mil, a NVIDIA comprou o que restava dela. A NVIDIA também colocou seu chip dentro do primeiro Xbox, da Microsoft. Em poucos anos, aquela empresa que quase morreu tinha virado a rainha dos gamers. Mas Jensen estava olhando para outra coisa.

**N05 — A aposta que ninguém entendeu**
Uma GPU tem uma característica curiosa. Um processador comum, a CPU, é como um gênio: resolve um problema difícil de cada vez, muito rápido. A GPU é como um exército: milhares de soldados simples, fazendo contas pequenas… todos ao mesmo tempo. Jensen percebeu que esse exército servia para muito mais do que desenhar jogos. Servia para ciência. Para simulações. Para qualquer conta gigante. Em dois mil e seis, a NVIDIA lança o CUDA: uma plataforma que deixava qualquer programador usar a GPU para qualquer coisa. O problema? Quase ninguém pediu isso. A NVIDIA gastou bilhões, por anos, colocando CUDA em todos os seus chips, inclusive nos de jogos, onde ninguém ia usar. Wall Street não entendeu. As margens caíram. Analistas perguntavam para que aquilo servia. Por seis anos, pareceu um erro caro. Até que, em dois mil e doze, alguém finalmente encontrou o uso perfeito.

**N06 — A faísca**
Universidade de Toronto, dois mil e doze. Dois alunos, Alex Krizhevsky e Ilya Sutskever, orientados pelo professor Geoffrey Hinton, treinam uma rede neural para reconhecer imagens. Eles não usam um supercomputador. Usam duas placas de vídeo NVIDIA, de videogame, programadas com CUDA. A rede se chama AlexNet. E ela esmaga a maior competição de visão computacional do mundo. Foi o big bang da inteligência artificial moderna. E a peça central era… o exército de soldados da NVIDIA. Jensen entendeu na hora. A NVIDIA não ia mais ser uma empresa de games. Ia ser a empresa da inteligência artificial.

**N07 — A entrega**
Em dois mil e dezesseis, a NVIDIA lança o DGX-1: um supercomputador de inteligência artificial dentro de uma única caixa. E Jensen entrega pessoalmente o primeiro deles para uma pequena organização sem fins lucrativos de São Francisco. Uma tal de OpenAI. Na caixa, ele escreveu uma dedicatória, para o futuro da computação e da humanidade. Seis anos depois, essa organização lançaria o produto que mudou tudo.

**N08 — A tempestade**
Mas antes do topo, mais uma queda. Em dois mil e dezoito, o boom das criptomoedas fez as placas da NVIDIA voarem das prateleiras. Muita gente comprava para minerar. Quando as criptos desabaram, a demanda sumiu. Estoque encalhado. A ação perdeu cerca de metade do valor em poucos meses. Parecia que a NVIDIA tinha voltado a ser só mais uma fabricante de chips. Até trinta de novembro de dois mil e vinte e dois.

**N09 — A explosão**
A OpenAI lança o ChatGPT. Em dois meses, cem milhões de usuários. O aplicativo que cresceu mais rápido da história, até então. E toda empresa de tecnologia do planeta percebeu a mesma coisa, ao mesmo tempo: para entrar nessa corrida, ela precisava de GPUs. Muitas GPUs. GPUs da NVIDIA. O chip H100 virou o objeto mais disputado do mundo da tecnologia. Empresas faziam fila de meses. Bilionários contavam quantos chips tinham como quem conta ouro. E o valor da NVIDIA começou a subir como nada antes. Maio de dois mil e vinte e três: um trilhão de dólares. Junho de dois mil e vinte e quatro: a empresa mais valiosa do mundo. Julho de dois mil e vinte e cinco: a primeira da história a valer quatro trilhões. Outubro: cinco trilhões. Nem tudo foi linha reta. Em janeiro de dois mil e vinte e cinco, uma startup chinesa, a DeepSeek, mostrou um modelo de inteligência artificial treinado com muito menos poder computacional. E a NVIDIA perdeu quase seiscentos bilhões de dólares em valor num único dia. A maior perda diária da história da bolsa americana. E mesmo assim, meses depois, ela estava mais valiosa do que nunca.

**N10 — A coroa**
Hoje a NVIDIA disputa, mês a mês, o posto de empresa mais valiosa do planeta. A coroa muda de cabeça. O mercado sobe e desce. Mas a pergunta que importa é outra: como uma empresa de placas de videogame chegou aqui? Não foi sorte. Foi uma empresa que errou feio no começo, e admitiu. Que esteve a um mês de morrer, e nunca esqueceu. E que gastou anos e bilhões numa aposta que ninguém entendia… até o mundo inteiro precisar dela. Tudo começou com três engenheiros, numa mesa de lanchonete, com uma ideia que parecia pequena demais. E você? Qual aposta você está fazendo hoje que ninguém entende?

---

## ETAPA 2 — IMAGENS-CHAVE (32 imagens)

- Modelo: `nano_banana_pro`, `resolution: "2k"`, `aspect_ratio: "16:9"`, `use_unlim: true`.
- Adicione SEMPRE este sufixo de estilo ao final de cada prompt:
  `, cinematic documentary film still, dark moody low-key lighting, deep blacks, subtle green accent light (#76B900), anamorphic lens, 35mm film grain, ultra realistic, highly detailed, no text, no logos, no recognizable faces`
- Exceção: S08 pode ter o texto "NV1" na etiqueta. Nesse caso tire o "no text" do sufixo.

| ID | Prompt (em inglês) |
|---|---|
| S01 | extreme macro of a single glowing green transistor on a silicon die, surrounded by darkness |
| S02 | endless AI data center aisle, rows of black server racks with green status lights stretching to infinity, volumetric haze |
| S03 | dark empty 1990s startup office at night, beige CRT monitors switched off, desk covered with stacks of unpaid bills and invoices |
| S04 | rainy night 1993, exterior of a classic American roadside diner with a glowing generic neon sign, wet asphalt reflecting warm amber neon, 1990s cars parked, amber and teal grade |
| S05 | inside a 1990s American diner booth at night, three men seen only as dark backlit silhouettes, coffee mugs and paper napkins with hand-drawn circuit sketches on the table, warm amber light |
| S06 | close-up of a paper napkin on a diner table with a pen sketch of a computer chip diagram and a coffee ring stain, warm amber light |
| S07 | old 1990s CRT monitor in a dark room displaying a simple low-poly 3D wireframe shape, green phosphor glow |
| S08 | 1990s grey computer graphics card emerging from darkness, studio product shot, small sticker label reading "NV1", dramatic rim light |
| S09 | dark 1990s corporate boardroom, contracts and documents on a long table, a generic retro video game controller, cold blue light through blinds |
| S10 | man in a black leather jacket seen from behind as a silhouette, standing at a rainy office window at night, city lights blurred |
| S11 | rows of empty office chairs in a half-empty 1990s tech office, cold fluorescent light, sense of layoffs and loss |
| S12 | green wireframe blueprint of a microchip being drawn line by line on a black computer terminal screen, 1990s style |
| S13 | 1997 computer store shelf with stacked generic graphics card boxes, warm retail light |
| S14 | late 1990s teenager bedroom at night, beige PC tower and glowing CRT monitor showing a 3D video game, posters on wall, nostalgic |
| S15 | graphics card hero product shot on black background, a sweep of green light running across the cooler and heatsink |
| S16 | early 2000s LAN gaming cafe, long rows of PCs with glowing monitors, gamers as silhouettes, blue and green light |
| S17 | inside a GPU chip seen from above like a city at night, thousands of tiny cores lighting up in green grid patterns |
| S18 | macro of green programming code scrolling on a black terminal screen, shallow depth of field |
| S19 | dim Wall Street trading floor, silhouettes of traders, screens with red falling stock charts |
| S20 | university computer lab at night in 2012, an open desktop PC case with two graphics cards glowing green LEDs, cables, cold winter window |
| S21 | three silhouettes in front of large monitors showing grids of thousands of small photos of cats, dogs and cars being classified with bounding boxes |
| S22 | explosion of green glowing particles forming a vast three-dimensional neural network of connected nodes in black space |
| S23 | 2016 modern San Francisco office corridor, a large black server box on a delivery cart, soft daylight |
| S24 | close-up of a hand writing with a silver marker on the lid of a black metal server box, handwriting not readable |
| S25 | dark warehouse filled with stacked cardboard boxes of graphics cards up to the ceiling, dust in light beams, abandoned |
| S26 | cryptocurrency mining rig, rows of open-frame graphics cards with fans, lights slowly turning off, red tint |
| S27 | laptop in a dark room showing a blank minimal chat interface with a blinking cursor, screen light on the desk |
| S28 | colossal modern AI data center hall seen from a high angle, thousands of server racks, green lights, workers as tiny silhouettes |
| S29 | a single advanced AI chip displayed inside a bank vault, lit like a gold bar, reflections, luxury and power |
| S30 | wall of stock exchange screens showing a violent red crash, red light flooding a dark room |
| S31 | empty 1990s diner booth at dawn, three coffee mugs left on the table and a napkin with a chip sketch, soft blue morning light through rainy window |
| S32 | macro of a microchip surface with one single green light point glowing in the center, everything else fading to black |

**THUMB** (thumbnail, 16:9, modelo `nano_banana_pro` 2k, SEM o sufixo padrão):
`YouTube documentary thumbnail, dramatic: a glowing green computer chip on a black background, cracked on one side with red light leaking out, giant bold white text "30 DIAS DE MORRER", high contrast, cinematic, clean composition`

---

## ETAPA 3 — CLIPES DE VÍDEO (animar cada imagem)

- Modelo: `seedance_2_0`, `mode: "std"`, `resolution: "1080p"`, `aspect_ratio: "16:9"`, `generate_audio: false`, `use_unlim: true`.
- Para cada imagem S01–S32, use a imagem gerada como `start_image` (passe o job_id dela em `medias`, role `start_image`).
- Duração: 6 segundos (S01, S02, S22, S28 e S32 com 8 segundos).
- Prompt de movimento: a base é sempre `slow cinematic camera movement, subtle realistic motion, documentary style, no text, no morphing`, mais o movimento específico abaixo.

| ID | Movimento |
|---|---|
| S01 | slow continuous pull back from the transistor revealing the whole chip |
| S02 | fast smooth dolly forward through the aisle |
| S03 | slow push in toward the desk with the bills |
| S04 | slow dolly toward the diner window, rain falling, neon flickering |
| S05 | slow lateral dolly, steam rising from coffee mugs |
| S06 | slow top-down push in on the napkin |
| S07 | slow push in, wireframe rotating on screen, CRT flicker |
| S08 | slow orbit around the card, light sweep |
| S09 | slow lateral dolly along the table, dust in light |
| S10 | static camera, rain running down the window, slight breathing movement |
| S11 | slow dolly back revealing more empty chairs |
| S12 | lines drawing progressively on screen, slow push in |
| S13 | slow lateral dolly along the shelf |
| S14 | slow push in toward the glowing monitor |
| S15 | slow orbit, green light sweep across the card |
| S16 | slow dolly along the rows of PCs, screens flickering |
| S17 | slow drone-like flyover, cores lighting up in waves |
| S18 | slow lateral slide, code scrolling |
| S19 | slow push in, red charts flickering on screens |
| S20 | slow push in toward the glowing graphics cards |
| S21 | slow push in over the shoulders toward the screens, images flashing |
| S22 | particles expanding and connecting, camera slowly moving through the network |
| S23 | cart rolling slowly down the corridor, camera following |
| S24 | hand writing slowly, shallow depth of field |
| S25 | slow dolly through the warehouse, dust floating |
| S26 | fans slowing down, lights turning off one by one |
| S27 | slow push in, cursor blinking |
| S28 | slow majestic crane down across the hall |
| S29 | slow orbit around the chip, reflections moving |
| S30 | handheld shake, screens glitching red |
| S31 | slow push in on the table, morning light growing |
| S32 | slow push in until the green point fills the frame, then fade to black |

---

## ETAPA 4 (opcional) — TRILHA
Se `suno_music` estiver disponível E aceitar o ilimitado, gere 1 trilha instrumental de 180 segundos com o estilo: `dark cinematic documentary score, tense pulsing synthesizers, deep bass drones, slow build, epic tech atmosphere, instrumental`. Se não aceitar o ilimitado, pule esta etapa (não gaste créditos).

---

## MANIFESTO FINAL (OBRIGATÓRIO)
Ao terminar, me responda com um único bloco de código neste formato, uma linha por asset, sem nada faltando:

```
VOICE: <nome da voz> | <voice_id> | <modelo/variant>
N00 | <job_id>
...
N10 | <job_id>
S01_IMG | <job_id>
S01_VID | <job_id>
...
S32_IMG | <job_id>
S32_VID | <job_id>
THUMB | <job_id>
MUSIC | <job_id ou SKIP>
FALHAS: <lista de IDs que falharam, ou NENHUMA>
```
