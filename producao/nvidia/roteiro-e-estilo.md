# NVIDIA | A empresa que estava a 30 dias de morrer

**Formato:** minidocumentário para o YouTube, 16:9, 1080p (master em 4K se o render permitir), 24 fps
**Duração estimada:** 11 a 12 minutos (cerca de 1.650 palavras de narração em ritmo dramático)
**Idioma:** português do Brasil
**Referências:** Magnates Media e Daniel Penin

**Opções de título** (formato do Penin, "Nome | frase provocativa"):
1. NVIDIA | A empresa que estava a 30 dias de morrer
2. NVIDIA | De uma mesa no Denny's a US$ 5 trilhões
3. NVIDIA | A aposta que ninguém entendeu

---

# PARTE 1 — ESTILO VISUAL

## O que define o estilo das referências

Pesquisei o Magnates Media e o Daniel Penin. A pesquisa usou a lista de vídeos e views dos dois canais e tutoriais de editores que recriam o estilo. Não houve análise quadro a quadro dos vídeos.

- **Cor-tema por episódio.** Cada vídeo do Magnates tem uma paleta própria (ex.: vermelho para Coca-Cola, azul para Pepsi).
- **Motion graphics em camadas.** VFX, textos animados e overlays (grão, luz, poeira) são empilhados de forma intencional.
- **Transições fluidas e tipografia cinética**, com design de som forte (whooshes, impactos, drones graves).
- **Fotos em 2.5D**, com recortes em camadas e câmera se movendo com profundidade.
- **Objetos e mundos em 3D:** globos, mapas e produtos girando.
- **Manchetes de jornal, gráficos de ação e números gigantes** na tela.
- **Gancho forte** nos primeiros 30–60 segundos, mostrando o clímax antes da história.

## Identidade visual deste episódio

| Item | Definição |
|---|---|
| **Cor-tema** | Verde NVIDIA (#76B900) sobre preto profundo (#0A0A0A). Verde = vida/sucesso; vermelho (#E5322D) para quedas e crises; dourado (#E8B04B) para os anos 90 e nostalgia |
| **Textura** | Grão de filme leve, vinheta, flares sutis, poeira volumétrica |
| **Tipografia** | Títulos em sans condensada pesada (ex.: Bebas Neue / Oswald), números em monoespaçada (ex.: JetBrains Mono), estilo "terminal" |
| **Câmera** | Sempre em movimento: push-ins lentos, dolly laterais, nunca plano parado |
| **Ritmo** | Corte a cada 2–4 s nas partes de tensão, 5–8 s nas partes contemplativas |
| **Som** | Trilha tensa e eletrônica (sintetizadores graves), whoosh em toda transição, "impacto" em cada número grande, silêncio antes das viradas |

## Os 6 tipos de plano do vídeo

| Código | Tipo de plano | Como vou produzir |
|---|---|---|
| **[CIN]** | Cena cinematográfica realista (escritório, restaurante, cidade, data center) | Imagem gerada no Higgsfield → animada em vídeo no Higgsfield |
| **[3D]** | Macro do chip / GPU / wafer de silício, globo, data center em 3D | Blender 5.2 remoto (Higgsfield 3D Jutsu), render em vídeo |
| **[2.5D]** | Ilustração/foto em camadas com movimento de profundidade | Imagem gerada + parallax em camadas (Blender ou ffmpeg) |
| **[MG]** | Gráfico de ação, linha do tempo, números gigantes, comparação | Motion graphics por código (Remotion), exportado em vídeo |
| **[JORNAL]** | Manchetes e recortes de jornal animados | Manchetes recriadas (texto meu, sem logos de jornais reais) + animação |
| **[SIL]** | Pessoas reais (Jensen Huang, cientistas) | **Silhueta / de costas / contraluz**, nunca o rosto realista; a jaqueta de couro preta é o símbolo do Jensen |

> **Regra de segurança do canal:** nenhuma imagem gerada mostra rosto realista de pessoa real. Quando o roteiro fala do Jensen, ele aparece de costas, em silhueta ou como "jaqueta de couro preta" estilizada. Logos de empresas aparecem só de forma informativa (documentário), sem imitar material oficial.

---

# PARTE 2 — ROTEIRO

Legenda: **NARRAÇÃO** é o texto falado. **VISUAL** é o que aparece na tela. **SOM** é trilha e efeitos.

---

## 0. GANCHO (0:00 – 0:50)

**VISUAL:** [3D] Tela preta. Um único ponto verde acende. A câmera recua: é um transistor, depois um chip, depois um wafer inteiro brilhando, depois um data center infinito.
**SOM:** Drone grave crescendo. Batida de coração eletrônica.

**NARRAÇÃO:**
> Em 29 de outubro de 2025, uma empresa fez algo que nenhuma outra na história tinha feito.
> Ela passou a valer **cinco trilhões de dólares**.

**VISUAL:** [MG] O número "US$ 5.000.000.000.000" se monta dígito por dígito, verde. Impacto.

> Mais do que o PIB do Japão. Mais do que o PIB da Índia. Mais que o Brasil, a Argentina e o México… somados.

**VISUAL:** [MG] Barras comparando PIBs subindo, e a da NVIDIA atravessando o topo da tela.

> Mas trinta anos antes, essa mesma empresa estava a **um mês** de fechar as portas.
> Sem dinheiro. Com um produto que ninguém queria. E com o único cliente que tinha prestes a abandoná-la.

**VISUAL:** [CIN] Escritório escuro, anos 90, monitores CRT desligados, uma mesa com contas empilhadas. Corte seco para preto.

> Essa é a história de como uma placa de vídeo para videogame virou a empresa mais valiosa do planeta.
> E de como ela quase não sobreviveu para ver isso.

**VISUAL:** [MG] Título do vídeo: **NVIDIA** em verde, com glitch. Subtítulo: "A empresa que estava a 30 dias de morrer".
**SOM:** Impacto + silêncio.

---

## 1. UMA MESA NO DENNY'S (0:50 – 2:00)

**VISUAL:** [CIN] Noite chuvosa, 1993. Fachada de lanchonete americana com neon, em San Jose, Califórnia. A câmera entra pela janela.
**SOM:** Chuva, louça, jukebox abafada. Trilha nostálgica com sintetizador.
**COR:** dourado/âmbar.

**NARRAÇÃO:**
> 1993. San Jose, Califórnia.
> Numa mesa de uma lanchonete Denny's, três engenheiros tomam café e rabiscam ideias.

**VISUAL:** [SIL] Três silhuetas na mesa, de contraluz. Uma delas com jaqueta. Canecas de café, guardanapos com desenhos de circuitos.

> Jensen Huang, Chris Malachowsky e Curtis Priem.
> Jensen tinha 30 anos, e uma história que parece roteiro de filme: nasceu em Taiwan, foi mandado pros Estados Unidos ainda criança, e — ironia do destino — já tinha trabalhado lavando pratos… no Denny's.

**VISUAL:** [2.5D] Linha do tempo ilustrada da vida do Jensen: Taiwan → EUA → universidade → empresas de chips (LSI Logic). Texto na tela com nomes dos três fundadores.

> A aposta deles era simples de explicar e difícil de executar:
> os computadores do futuro iam precisar de um chip só para desenhar imagens. Gráficos 3D. Videogames.

**VISUAL:** [3D] Um polígono 3D simples, de baixa resolução, girando e ganhando detalhe aos poucos.

> Em abril de 1993, nasce a empresa. O nome vem de "invidia" — inveja, em latim.
> A ideia era fazer um chip que deixasse todo mundo… com inveja.

**VISUAL:** [MG] "INVIDIA" em latim → letras se reorganizam → "NVIDIA". Data: 5 de abril de 1993.
**SOM:** Whoosh + impacto.

---

## 2. O PRIMEIRO FRACASSO (2:00 – 3:30)

**VISUAL:** [3D] Uma placa de vídeo dos anos 90, cinza, emergindo da escuridão. Etiqueta: "NV1 — 1995".
**COR:** dourado → começa a esfriar para cinza.

**NARRAÇÃO:**
> Dois anos depois, sai o primeiro produto: o NV1.
> E ele foi… um desastre.

**SOM:** Música corta. Um único som grave.

> O NV1 desenhava o 3D de um jeito diferente do resto da indústria — usando curvas, em vez de triângulos.
> Era tecnicamente inteligente. Mas o mercado escolheu os triângulos. E a Microsoft, com o DirectX, cravou esse padrão.

**VISUAL:** [MG] Lado a lado: uma esfera feita de curvas (NV1) vs. uma esfera feita de triângulos (padrão da indústria). O lado do NV1 fica vermelho e "racha".

> A NVIDIA tinha um contrato com a Sega para criar o chip do próximo console. Mas quanto mais o projeto andava, mais claro ficava: a tecnologia estava errada.

**VISUAL:** [CIN] Sala de reunião escura, documentos sobre a mesa, um controle de videogame genérico dos anos 90.

> Então Jensen fez algo que quase nenhum CEO faz.
> Ele procurou a Sega e admitiu: "a nossa tecnologia está errada. Vocês deveriam procurar outra empresa."

**VISUAL:** [SIL] Silhueta de costas olhando por uma janela com chuva.
**SOM:** Silêncio. Só chuva.

> E pediu mais uma coisa: que a Sega pagasse o contrato mesmo assim.

**VISUAL:** [JORNAL] Nada de jornal aqui — corte para tela preta com a frase em verde, digitada: *"Paguem mesmo assim."*

> Era isso, ou a NVIDIA morria.

---

## 3. UM MÊS DE VIDA (3:30 – 4:40)

**VISUAL:** [MG] Um relógio / contagem regressiva em vermelho: 30… 29… 28…
**COR:** vermelho.
**SOM:** Tique-taque eletrônico acelerando.

**NARRAÇÃO:**
> O executivo da Sega, Shoichiro Irimajiri, decidiu acreditar no jovem engenheiro.
> A Sega investiu 5 milhões de dólares na NVIDIA.

**VISUAL:** [MG] "US$ 5 milhões" caindo como moeda pesada numa mesa. Impacto.

> Parece muito. Não era. Era combustível para uns poucos meses.
> Jensen demitiu mais da metade da empresa. E apostou tudo num único chip.

**VISUAL:** [2.5D] Escritório se esvaziando — cadeiras vazias aparecendo uma a uma.

> Para ganhar tempo, eles fizeram algo inédito: em vez de fabricar protótipos físicos — caro e lento — testaram o chip inteiro num simulador. Se tivesse um erro, não haveria segunda chance.

**VISUAL:** [3D] Wireframe de um chip sendo "desenhado" linha por linha em verde, num fundo de terminal.

> Em agosto de 1997, sai o RIVA 128.
> Quando ele chegou às lojas, a NVIDIA tinha dinheiro para pagar os funcionários por mais **um mês**.

**VISUAL:** [MG] Contagem regressiva para em "1". Tela preta.
**SOM:** Silêncio total por 1 segundo.

> E então… vendeu.
> Cerca de um milhão de unidades em quatro meses.

**VISUAL:** [MG] Gráfico de vendas explodindo para cima, em verde. A contagem regressiva vira contagem progressiva.
**SOM:** Drop da trilha — batida volta forte.

> A NVIDIA sobreviveu. E Jensen nunca mais esqueceu essa sensação.
> Durante anos, ele repetiria para os funcionários: "a nossa empresa está a 30 dias de quebrar."

**VISUAL:** [MG] Citação em tela cheia, tipografia grande, verde sobre preto.

---

## 4. A GUERRA DOS GAMES (4:40 – 5:40)

**VISUAL:** [CIN] Quarto de adolescente no fim dos anos 90, PC bege, monitor CRT brilhando com um jogo 3D genérico.
**COR:** verde volta.

**NARRAÇÃO:**
> Em janeiro de 1999, a NVIDIA abre capital na bolsa.
> E no mesmo ano lança a GeForce 256 — que ela mesma batiza de "a primeira GPU do mundo". Graphics Processing Unit.

**VISUAL:** [3D] A GeForce 256 girando, luz verde passando pelo cooler. Texto: "GPU".

> O nome pegou. A sigla virou categoria.
> A rival da época, a 3dfx — dona das famosas placas Voodoo — não acompanhou o ritmo. No fim de 2000, a NVIDIA comprou o que restava dela.

**VISUAL:** [MG] Dois logos genéricos em "ringue" (verde vs. azul). O azul se desfaz em partículas que são absorvidas pelo verde.

> A NVIDIA também colocou seu chip dentro do primeiro Xbox, da Microsoft.
> Em poucos anos, aquela empresa que quase morreu tinha virado a rainha dos gamers.

**VISUAL:** [2.5D] Montagem rápida: caixas de placas de vídeo, LAN houses, monitores, jogos (sem logos de jogos reais).

> Mas Jensen estava olhando para outra coisa.

**SOM:** Música desacelera. Corte.

---

## 5. A APOSTA QUE NINGUÉM ENTENDEU (5:40 – 6:50)

**VISUAL:** [3D] Dentro de uma GPU: milhares de pequenos núcleos se acendendo ao mesmo tempo, como uma cidade à noite vista de cima.

**NARRAÇÃO:**
> Uma GPU tem uma característica curiosa.
> Um processador comum, a CPU, é como um gênio: resolve um problema difícil de cada vez, muito rápido.
> A GPU é como um exército: milhares de soldados simples, fazendo contas pequenas… todos ao mesmo tempo.

**VISUAL:** [MG] Metáfora animada: de um lado, um único personagem resolvendo contas em sequência; do outro, um exército de pontos verdes fazendo tudo em paralelo.

> Jensen percebeu que esse exército servia para muito mais do que desenhar jogos.
> Servia para ciência. Para simulações. Para qualquer conta gigante.

> Em 2006, a NVIDIA lança o CUDA: uma plataforma que deixava qualquer programador usar a GPU para qualquer coisa.

**VISUAL:** [MG] Linhas de código em verde rolando na tela, estilo terminal. A palavra "CUDA" se forma.

> O problema? Quase ninguém pediu isso.
> A NVIDIA gastou bilhões, por anos, colocando CUDA em todos os seus chips — inclusive nos de jogos, onde ninguém ia usar.
> Wall Street não entendeu. As margens caíram. Analistas perguntavam pra que aquilo servia.

**VISUAL:** [JORNAL] Manchetes recriadas (texto fictício, sem nome de jornal real): *"Por que a NVIDIA está gastando com algo que ninguém usa?"* / *"Investidores questionam aposta da fabricante de chips"*. Gráfico de ação caindo em vermelho no fundo.

> Por seis anos, pareceu um erro caro.
> Até que, em 2012, alguém finalmente encontrou o uso perfeito.

---

## 6. A FAÍSCA (6:50 – 7:50)

**VISUAL:** [CIN] Um quarto/laboratório universitário à noite, em Toronto. Duas placas de vídeo num PC aberto, LEDs verdes piscando.
**SOM:** Ventoinhas, teclado. Trilha começa a crescer.

**NARRAÇÃO:**
> Universidade de Toronto, 2012.
> Dois alunos, Alex Krizhevsky e Ilya Sutskever, orientados pelo professor Geoffrey Hinton, treinam uma rede neural para reconhecer imagens.

**VISUAL:** [SIL] Três silhuetas diante de monitores. Nas telas: imagens de gatos, carros e cachorros sendo classificadas com etiquetas.

> Eles não usam um supercomputador. Usam duas placas de vídeo NVIDIA, de videogame, programadas com CUDA.
> A rede se chama AlexNet. E ela esmaga a maior competição de visão computacional do mundo.

**VISUAL:** [MG] Gráfico da competição ImageNet: as barras dos concorrentes, e a AlexNet com uma vantagem enorme, em verde.

> Foi o "big bang" da inteligência artificial moderna.
> E a peça central era… o exército de soldados da NVIDIA.

**VISUAL:** [3D] Explosão de partículas verdes saindo de uma GPU e formando uma rede neural brilhante.
**SOM:** Impacto grande.

> Jensen entendeu na hora. A NVIDIA não ia mais ser uma empresa de games.
> Ia ser a empresa da inteligência artificial.

---

## 7. A ENTREGA (7:50 – 8:40)

**VISUAL:** [CIN] 2016. Um prédio de escritórios em São Francisco. Uma caixa grande sendo levada num carrinho por um corredor.

**NARRAÇÃO:**
> Em 2016, a NVIDIA lança o DGX-1: um supercomputador de IA dentro de uma única caixa.
> E Jensen entrega pessoalmente o primeiro deles para uma pequena organização sem fins lucrativos de São Francisco.
> Uma tal de OpenAI.

**VISUAL:** [SIL] Silhueta de jaqueta de couro, de costas, ao lado da caixa. Uma caneta escrevendo uma dedicatória na tampa.

> Na caixa, ele escreveu uma dedicatória — para o futuro da computação e da humanidade.

**VISUAL:** [MG] Corte rápido para preto. Texto: "OpenAI — 2016". Embaixo, devagar, aparece: "ChatGPT — 2022".
**SOM:** Batida de suspense.

> Seis anos depois, essa organização lançaria o produto que mudou tudo.

---

## 8. A TEMPESTADE (8:40 – 9:30)

**VISUAL:** [MG] Gráfico de ação da NVIDIA de 2017 a 2018 subindo… e despencando em vermelho.
**COR:** vermelho.

**NARRAÇÃO:**
> Mas antes do topo, mais uma queda.
> Em 2018, o boom das criptomoedas fez as placas da NVIDIA voarem das prateleiras — muita gente comprava para minerar.
> Quando as criptos desabaram, a demanda sumiu. Estoque encalhado. A ação perdeu cerca de metade do valor em poucos meses.

**VISUAL:** [2.5D] Armazém escuro cheio de caixas de placas de vídeo empilhadas até o teto. Poeira.

> Parecia que a NVIDIA tinha voltado a ser só mais uma fabricante de chips.
> Até 30 de novembro de 2022.

**SOM:** Silêncio. Um som de "notificação".

---

## 9. A EXPLOSÃO (9:30 – 10:50)

**VISUAL:** [MG] Uma caixa de chat em branco. Um cursor piscando. Texto: "ChatGPT — 30 nov 2022".

**NARRAÇÃO:**
> A OpenAI lança o ChatGPT.
> Em dois meses, 100 milhões de usuários. O app que cresceu mais rápido da história, até então.

**VISUAL:** [MG] Contador de usuários disparando.

> E toda empresa de tecnologia do planeta percebeu a mesma coisa ao mesmo tempo:
> para entrar nessa corrida, ela precisava de GPUs. Muitas GPUs. GPUs da NVIDIA.

**VISUAL:** [3D] Data center gigantesco, corredores infinitos de servidores com luz verde. A câmera voa rápido por eles.
**SOM:** Trilha no máximo. Batida forte.

> O chip H100 virou o objeto mais disputado do mundo da tecnologia. Empresas faziam fila de meses. Bilionários contavam quantos chips tinham como quem conta ouro.

**VISUAL:** [3D] Um chip H100 estilizado (genérico) dentro de um cofre, iluminado como uma barra de ouro.

> E o valor da NVIDIA começou a subir como nada antes:

**VISUAL:** [MG] Linha do gráfico subindo, com marcos aparecendo como "checkpoints" que explodem em verde:
- **Maio de 2023 — US$ 1 trilhão**
- **Junho de 2024 — empresa mais valiosa do mundo pela primeira vez**, passando a Microsoft
- **Julho de 2025 — primeira empresa da história a valer US$ 4 trilhões**
- **Outubro de 2025 — primeira a valer US$ 5 trilhões**
- **Abril de 2026 — recorde de cerca de US$ 5,3 trilhões**

**SOM:** Impacto a cada marco.

> Nem tudo foi linha reta. Em janeiro de 2025, uma startup chinesa de IA, a DeepSeek, mostrou um modelo treinado com muito menos poder computacional — e a NVIDIA perdeu cerca de 590 bilhões de dólares em valor num único dia. A maior perda diária da história da bolsa americana.

**VISUAL:** [MG] O gráfico dá um tranco vermelho violento para baixo. Tela treme.

> E mesmo assim, meses depois, ela estava mais valiosa do que nunca.

**VISUAL:** [MG] A linha se recupera e passa o topo anterior.

---

## 10. FINAL — A COROA (10:50 – 12:00)

**VISUAL:** [3D] Volta ao início: o data center infinito, a câmera se aproximando até um único chip, depois um único transistor… um ponto verde.
**SOM:** Trilha desacelera, emocional.

**NARRAÇÃO:**
> Hoje a NVIDIA disputa, mês a mês, o posto de empresa mais valiosa do planeta.
> A coroa muda de cabeça. O mercado sobe e desce.
> Mas a pergunta que importa é outra: como uma empresa de placas de videogame chegou aqui?

**VISUAL:** [2.5D] Montagem rápida em flashback, de trás pra frente: data center → OpenAI → AlexNet → CUDA → GeForce → RIVA 128 → mesa do Denny's.

> Não foi sorte.
> Foi uma empresa que errou feio no começo — e admitiu.
> Que esteve a um mês de morrer — e nunca esqueceu.
> E que gastou anos e bilhões numa aposta que ninguém entendia… até o mundo inteiro precisar dela.

**VISUAL:** [CIN] O Denny's de 1993 de novo, agora vazio. A mesa com três canecas de café. Um guardanapo com um rabisco de chip.

> Tudo começou com três engenheiros, numa mesa de lanchonete, com uma ideia que parecia pequena demais.

**VISUAL:** [MG] O ponto verde do início pulsa uma última vez e se apaga.
**SOM:** Silêncio.

> E você? Qual aposta você está fazendo hoje que ninguém entende?

**VISUAL:** [MG] Tela final: logo do canal + "Inscreva-se" + sugestão de próximo vídeo.

---

# PARTE 3 — CHECAGEM DE FATOS (antes de publicar)

| Afirmação | Status |
|---|---|
| Fundação em abril de 1993 por Huang, Malachowsky e Priem; reunião no Denny's em San Jose | Confirmado em várias fontes |
| NV1 (1995) fracassou; Sega investiu US$ 5 mi por decisão de Shoichiro Irimajiri | Confirmado |
| RIVA 128 em agosto de 1997, com caixa para ~1 mês de folha; ~1 milhão vendidos em 4 meses | Confirmado |
| Jensen pediu à Sega para pagar o contrato mesmo assim e cortou mais da metade da equipe | Contado pelo próprio Jensen em entrevistas; manter como "ele contou" se quiser mais cautela |
| IPO em janeiro de 1999; GeForce 256 em 1999 ("primeira GPU") | Confirmado |
| Compra dos ativos da 3dfx no fim de 2000; chip do primeiro Xbox | Conhecimento geral; vale conferir datas |
| CUDA em 2006 | Confirmado (linha do tempo oficial da NVIDIA) |
| AlexNet em 2012 treinada em duas GPUs NVIDIA com CUDA | Confirmado |
| DGX-1 entregue por Jensen à OpenAI em 2016, com dedicatória | Confirmado (Fortune) |
| Queda de ~metade da ação em 2018 após o boom cripto | Conhecimento geral; conferir percentual |
| ChatGPT em 30/11/2022; 100 mi usuários em ~2 meses | Conhecimento geral; amplamente noticiado |
| US$ 1 tri em maio de 2023; mais valiosa em junho de 2024 | Conhecimento geral; conferir datas |
| US$ 4 tri em julho de 2025; US$ 5 tri em 29/10/2025 | Confirmado |
| Recorde de ~US$ 5,3 tri em abril de 2026 | Confirmado (Forbes) |
| DeepSeek: perda de ~US$ 590 bi num dia (jan/2025) | **A confirmar** — não achei fonte na pesquisa |
| Comparação com PIBs (Japão, Índia, Brasil+Argentina+México) | **A confirmar** com dados de PIB atuais antes do render |
| Situação em nov/2026: Apple e NVIDIA disputando o 1º lugar | Fontes divergem; o final foi escrito como "disputa a coroa" para não ficar desatualizado |
