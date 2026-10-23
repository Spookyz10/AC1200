# Roteiro de fala — Archer C6 (AC1200)

Total ≈ 13 min. Cada "→" é um aperto de seta/espaço.

## Pessoa 1

### 1. Abertura (≈ 0:40)

**→ Entrada do roteador**

Bom dia/boa tarde! Nosso trabalho é sobre um roteador Wi-Fi da classe AC1200. Antes de começar, uma coisa importante: “AC1200” não é o nome de um aparelho, é uma classe de velocidade. Vários fabricantes vendem roteadores AC1200.

**→ Roteador acende**

Por isso escolhemos um modelo específico e real: o TP-Link Archer C6. Ele é bastante vendido no Brasil e o fabricante publica toda a documentação, o que permite apresentar dados confiáveis.

### 2. Identificação (≈ 1:20)

**→ Ficha de identificação**

Fabricante: TP-Link. Modelo: Archer C6, que a própria TP-Link chama de “AC1200 Wireless MU-MIMO Gigabit Router”. A versão de hardware que estudamos é a V3. A versão importa porque o fabricante às vezes muda componentes entre versões, e o manual certo depende dela. Ela aparece na etiqueta embaixo do aparelho.

> Nota: Se perguntarem: a versão fica na etiqueta inferior, ao lado do número de série, no formato “Ver: 3.20”, por exemplo.

**→ Foto oficial**

Aqui está a foto oficial do produto, da página da TP-Link. E ao lado, o modelo 3D que vamos usar durante toda a apresentação para mostrar cada parte do roteador.

### 3. Características técnicas (≈ 2:00)

**→ Padrões e bandas**

O Archer C6 é dual band: ele transmite em duas frequências ao mesmo tempo. Em laranja, a rede de 2,4 GHz, que usa os padrões b, g e n e chega a 300 megabits por segundo. Em azul, a de 5 GHz, com os padrões a, n e ac, que chega a 867 megabits. O padrão mais moderno dele é o 802.11ac, também chamado de Wi-Fi 5.

> Nota: 2,4 GHz alcança mais longe e atravessa melhor paredes; 5 GHz é mais rápido e menos congestionado, mas tem alcance menor.

**→ De onde vem o 1200**

O número 1200 vem da soma das duas bandas: 300 mais 867, aproximadamente 1200. Mas atenção: essa é a velocidade nominal, o máximo teórico do padrão. Nenhum aparelho sozinho recebe 1200, e a velocidade real depende da distância, das paredes, das interferências e, claro, do plano de internet contratado. Se o plano é de 200 mega, a internet não passa de 200.

> Nota: A própria TP-Link avisa que as taxas máximas são taxas físicas derivadas das especificações IEEE 802.11.

**→ Antenas**

Ele tem cinco antenas: quatro externas, essas que vocês veem acesas, e uma interna. Também tem duas tecnologias importantes. MU-MIMO, que permite ao roteador conversar com até dois aparelhos ao mesmo tempo em vez de um de cada vez. E beamforming, que concentra o sinal na direção do dispositivo, em vez de espalhar igual para todo lado.

**→ Segurança**

Na segurança, o Wi-Fi é protegido por criptografia: os dados são embaralhados com uma chave, e só quem tem a senha consegue ler. O recomendado aqui é o WPA2. Ele ainda aceita WEP, mas esse é antigo e fácil de quebrar, então não deve ser usado. Também tem firewall, proteção contra ataques de negação de serviço e uma rede de convidados, para visitas não acessarem seus dispositivos.

> Nota: Versões mais novas do firmware de alguns modelos adicionaram WPA3; não afirmamos isso para a V3.

## Pessoa 2

### 4. Portas e hardware (≈ 2:00)

**→ Gira para a traseira**

Agora vamos para a parte de trás do roteador, onde ficam as conexões.

**→ Porta WAN**

Esta é a porta WAN, a de cor azul. WAN significa rede de longa distância: é por aqui que a internet entra. Ela é ligada com cabo ao modem ou à ONT da operadora. É Gigabit, aguenta até 1000 megabits.

**→ Portas LAN**

Ao lado, as quatro portas LAN, de rede local. Servem para ligar com cabo computador, videogame, TV. Também são Gigabit. Cabo é sempre mais estável que Wi-Fi, então para jogo online e chamada de vídeo é a melhor opção.

**→ Botões**

Também temos os botões. O liga e desliga, ao lado da entrada de energia. O botão WPS, que permite conectar um aparelho apertando um botão em vez de digitar a senha. E o Reset, que fica escondido dentro de um buraquinho, para ninguém apertar sem querer: segurando ele, o roteador volta às configurações de fábrica.

**→ LEDs**

Na frente ficam os LEDs, as luzinhas de status. Eles mostram se o roteador está ligado, se cada rede Wi-Fi está ativa, se há algo nas portas LAN, se a internet está conectada e se o WPS está em uso. Quando a internet cai, olhar o LED de internet é o primeiro passo para descobrir o problema.

> Nota: Pode clicar no LED ou nas portas para mostrar o painel de explicação.

**→ Por dentro**

Por dentro, de forma simplificada, há uma placa com o processador, os rádios Wi-Fi de cada banda e a memória. Isso que vocês veem é só um esquema didático, não é foto da placa real.

### 5. Funções e modos (≈ 2:00)

**→ Modo roteador**

O modo principal é o modo roteador. A internet chega pelo modem, entra na porta WAN, e o roteador cria a rede da casa: ele dá um endereço IP para cada aparelho, que é o DHCP, e separa a rede interna da internet, com NAT e firewall. É o modo de uso mais comum.

**→ Modo ponto de acesso**

O segundo modo é o ponto de acesso, ou Access Point. Aqui já existe um roteador na casa, e o Archer C6 é ligado nele por cabo. Ele deixa de “mandar” na rede e só passa a criar Wi-Fi. É útil, por exemplo, para levar sinal para outro andar usando um cabo.

**→ Modo repetidor**

Repetidor é quando o aparelho pega o Wi-Fi de outro roteador, sem cabo, e repete o sinal mais longe. É importante dizer: a TP-Link não lista o modo repetidor para o Archer C6. Os modos oficiais são só roteador e ponto de acesso. Para isso existem aparelhos próprios, os repetidores, ou o sistema OneMesh, que o C6 suporta.

> Nota: OneMesh: o C6 pode ser o roteador principal de uma rede OneMesh com extensores TP-Link compatíveis.

**→ WDS**

Por último, o WDS, Sistema de Distribuição Sem Fio. Ele cria uma ponte sem fio entre dois roteadores, então os dois ficam na mesma rede. No Archer C6, isso não aparece como modo de operação, e sim como uma função chamada WDS Bridging, nas configurações avançadas. Funciona melhor quando os dois aparelhos são compatíveis.

> Nota: Confirme no emulador oficial/no seu aparelho: Avançado › Ferramentas do Sistema › Parâmetros do Sistema › WDS Bridging.

## Pessoa 3

### 6. Configuração (≈ 2:00)

**→ Acesso ao painel**

Para configurar, primeiro você se conecta ao roteador, por cabo ou pelo Wi-Fi. O nome da rede e a senha padrão estão na etiqueta embaixo dele. Depois abre o navegador e digita tplinkwifi.net ou o IP 192.168.0.1. Também dá para configurar pelo aplicativo Tether, da TP-Link, no celular.

**→ Passo a passo**

O passo a passo básico é: com o modem desligado, liga o cabo dele na porta WAN. Liga o modem e o roteador. Acessa o endereço. No primeiro acesso, o roteador pede para criar uma senha de administrador, que protege o painel. Depois, o assistente de Configuração Rápida pede o fuso horário, o tipo de conexão de internet, que a operadora informa, e o nome e a senha do Wi-Fi. Salva e pronto.

**→ Telas do painel**

Aqui estão as três telas mais importantes. A de status, que mostra se a internet está conectada e quem está usando a rede. A de Wireless, onde se troca o nome e a senha das redes 2,4 e 5 GHz. E a de modo de operação, onde se escolhe entre roteador e ponto de acesso. Essas são representações; as telas reais podem ser vistas no emulador oficial da TP-Link.

> Nota: Se tiver internet na hora, dá para mostrar o emulador oficial ao vivo. Se tirarem prints do emulador, substitua as representações.

### 7. Pontos fortes e limitações (≈ 2:00)

**→ Pontos fortes**

Os pontos fortes: todas as portas são Gigabit, então não limitam planos de internet comuns. É dual band, com MU-MIMO e beamforming. É fácil de configurar, pelo navegador ou pelo aplicativo. Aceita expansão com OneMesh. E é barato.

**→ Limitações**

As limitações: ele é Wi-Fi 5, então não tem as tecnologias do Wi-Fi 6, como o OFDMA, que divide melhor o canal entre muitos aparelhos. O MU-MIMO dele atende só dois aparelhos por vez. Não tem porta USB. Em casas com muitos dispositivos ao mesmo tempo, o desempenho cai. E não tem modo repetidor oficial.

**→ Comparação**

Comparando com os roteadores mais novos, de Wi-Fi 6, 6E e 7: eles lidam melhor com muitos aparelhos, por causa do OFDMA. Os de 6E e 7 têm uma terceira banda, de 6 GHz. E a certificação Wi-Fi 6 exige WPA3, que é mais seguro.

**→ Quando vale a pena**

Então, vale a pena? Para uma casa ou apartamento pequeno ou médio, com poucos aparelhos e plano de internet de até algumas centenas de mega, sim: ele cumpre bem o papel e é barato. Para casa grande, muitos dispositivos ou plano de internet muito alto, um roteador Wi-Fi 6 é a melhor escolha.

### 8. Fontes (≈ 1:00)

**→ Fontes**

Estas são as nossas fontes: a página oficial do produto, a área de suporte com os manuais da versão 3, o guia oficial de portas e botões, o emulador da interface e a Wi-Fi Alliance, que é quem certifica os padrões Wi-Fi.

**→ Encerramento**

Resumindo: o Archer C6 é um roteador AC1200 dual band, Wi-Fi 5, com portas Gigabit, simples de configurar, ótimo custo-benefício para casas menores, mas já superado pelos roteadores Wi-Fi 6 em ambientes com muitos aparelhos. Obrigado! Alguma pergunta?
