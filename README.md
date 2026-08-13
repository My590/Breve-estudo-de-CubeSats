# Contexto
Tenho interesse em programar e entender mais sobre satélites, pois são bem curiosos como são tão importantes e ficam no espaço de forma inacessível. Além de indiretamente aprender a manusear o NotebookLM, ferramenta onde farei essa pesquisa. 

## Objetivos: 
-  Saber valores de Cubesats
- Entender funções principais
- Saber linguagem necessária e tempo de estudo
- O qual viável é um projeto desses

## Fontes: 
Links que usei como fonte para o NotebookLM
- [PDF1](https://bipes.net.br/b/download.php?file=eBook_Kits_OBSAT_23_02_2022.pdf)
- [PDF2](https://www.nasa.gov/wp-content/uploads/2017/03/nasa_csli_cubesat_101_508.pdf?emrc=05d3e2)
- [Vídeo1](https://youtu.be/6UP9RMiMsJE?si=xXfCtB5AqFBvhLSR)
- [Vídeo2](https://youtu.be/EcbGyIlDnZ0?si=GmthrcdTTdwQQoca)
- [Vídeo3](https://youtu.be/B0R-UMum5VY?si=k-8LKEEQChh18mb0)
- [Vídeo4](https://youtu.be/UpjFDnWfRF0?si=3nQ2PFuSIoQ60Npu)
- [Site](https://aerojr.com/blog/cubesats-a-grande-tecnologia-dos-pequenos-satelites/)

## Prompts
Prompts usados e um pouco das devolutivas que recebi do NotebookLM baseado nessas fontes.

**Prompt:** Explique a importância, os valores gerais de um CubeSat e outros satélites pequenos e como é possível usa-los de diferentes jeitos.

Devolutiva:
`
...Importância dos CubeSats Democratização do Espaço: A principal mudança de paradigma é o aumento massivo no acesso à exploração espacial por amadores, universidades e países que anteriormente não possuíam essa capacidade . `

`Valor Educacional: Foram criados em 1999 com o objetivo original de permitir que estudantes passassem por todo o processo de projeto, construção e operação de um satélite real . No Brasil, iniciativas como a OBSAT (Olimpíada Brasileira de Satélites) utilizam pequenos satélites como ferramentas de aprendizado prático . `

`Inovação e Aceitação de Risco: Devido ao baixo custo e tempo de desenvolvimento curto (geralmente entre 18 a 24 meses), os CubeSats permitem realizar missões de alto risco ou testar tecnologias experimentais que seriam proibitivas em satélites maiores e mais caros ... `

`Valores Gerais (Custos e Padrões) Padronização (O Padrão 1U): O CubeSat padrão é um cubo de 10 cm de lado com massa de até 1,33 kg, denominado 1U . Eles podem ser combinados para formar unidades maiores, como 3U, 6U ou 12U . `

`Custo de Desenvolvimento: Estima-se que o desenvolvimento completo de um CubeSat custe em torno de US$ 100 mil, embora esse valor varie conforme a complexidade e a carga útil . `

`Custo de Lançamento: O valor é reduzido pois os CubeSats costumam "pegar carona" como carga secundária em foguetes maiores . Os preços históricos giram entre US$ 30.000 e US$ 55.000 por quilograma... `

**Prompt:** Como desenvolver e conseguir custear um CubeSat?

Devolutiva:

` ...O processo pode ser dividido em três grandes etapas:`

`1.Pré-formulação e Formulação:
Concepção e Viabilidade: Define-se o objetivo da missão (científica, educacional ou tecnológica) e analisa-se se o projeto é realizável dentro do orçamento e tempo previstos. Design Preliminar e Final: Desenvolvem-se os subsistemas (energia, comunicações, computador de bordo) e a carga útil. Recomenda-se o uso de componentes comerciais prontos (COTS) para reduzir custos e riscos.`

`2.Implementação: Fabricação e Montagem: Construção do hardware e desenvolvimento do software de voo
. Projetos educacionais costumam usar plataformas como Arduino ou ESP32 com linguagem Python (MicroPython) pela facilidade de uso.
Testes Rigorosos: Antes do lançamento, o satélite deve passar por testes de vibração (para suportar o lançamento), vácuo térmico (TVAC) e o teste DITL (Day In The Life), que simula o funcionamento autônomo do satélite no espaço.`

`3.Operação e Fechamento:
Após o lançamento, a equipe opera o satélite por meio de uma estação de solo para receber dados (telemetria) e enviar comandos
. A missão termina com o encerramento das atividades e a reentrada na atmosfera...`

## Miniguia de Estudo

**Resumo:**
  Consegui entender melhor o funcionamento de satélites e entender suas utilidades, como: pesquisas sobre o clima, ciência biológica, monitoramento de detritos orbitais, missões em espaço profundo, monitoramento diário de desmatamento, incêndios florestais, derramamento de óleo nos oceanos, agricultura de precisão e diversas outras possibilidades.
  Vi que é possível ter acesso a um CubeSat ou outros satélites pequenos, mas é necessário participar de algum projeto de pesquisa estudantil, porém ainda é caro para um grupo pequeno ou um individuo só, sendo necessário parcerias, financiamento ou subsídios para custear o equipamento.  
  Também descobri que todas etapas de desenvolvimento podem demorar muitos anos e que é extremamente complexo varias etapas de desenvolvimento incluindo lançamento para o espaço. Isso contando também com tempo de estudo e desenvolvimento.
  A programação é em Python (MicroPython). 

**Glossário com os principais conceitos aprendidos:**
Telemetria: É o processo de receber dados e informações enviados pelo satélite para a estação de solo, permitindo monitorar o estado e o funcionamento do equipamento no espaço.

TVAC (Vácuo Térmico): É um teste ambiental onde o satélite é colocado em uma câmara de alto vácuo e submetido a temperaturas extremas para simular as condições espaciais e garantir que os materiais não liberem contaminantes prejudiciais (outgassing).

DITL (Day In The Life): É um teste de simulação que recria os primeiros momentos do satélite no espaço logo após ser liberado do lançador, servindo para verificar se o software de voo, os temporizadores e a abertura de antenas/painéis funcionam como planejado.

CSLI (CubeSat Launch Initiative): É uma iniciativa da NASA que oferece oportunidades de lançamento gratuito para CubeSats qualificados de universidades e organizações sem fins lucrativos, permitindo que eles "peguem carona" como carga secundária em missões espaciai

**Conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema:**
- Liste as principais iniciativas que permitem um lançamento (ou desenvolvimento) de um CubeSat
- Em quais fontes é possível ter conteúdo acessível e de qualidade para estudo e pesquisa sobre esse tema?
- Possíveis projetos para desenvolver numa jornada estudantil de (Ensino Médio/ Universidade/ outro de sua preferencia) que sejam viaveis e possiveis recursos necessarios.
