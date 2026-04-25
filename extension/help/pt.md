---
layout: bare
title: Extensão IPA Reader - Guia do Utilizador
lang: pt
---

# IPA Reader - Guia do Utilizador

> Versão: v1.4.4

## Introdução

O IPA Reader é uma extensão de navegador concebida para estudantes de inglês. Adiciona anotações de pronúncia IPA (Alfabeto Fonético Internacional) a palavras em inglês em páginas web e em PDFs, suportando sotaques americanos e britânicos. Inclui também um dicionário de inglês integrado, conversão de texto em voz e funcionalidades de tradução — ajudando-o a aprender a pronúncia inglesa mais facilmente.

---

## Principais Funcionalidades

- **Modo IPA em toda a página** — Adicione anotações IPA a todas as palavras em inglês na página com um clique; os símbolos IPA estão codificados por cor (vogais, consoantes, marcas de acento) para leitura fácil
- **Dicionário ao passar o rato** — Passe o rato sobre palavras para ver definições em inglês (mais de 82 mil palavras do WordNet), IPA com símbolos codificados por cor e botões de pronúncia; escolha entre modo Dicionário, modo Tooltip ou Desligado
- **Leitor de PDF** — Leitor de PDF integrado com anotações IPA, dicionário, voz e tradução; suporta arrastar e largar, carregamento por URL e deteção automática de PDF com redirecionamento inteligente
- **Formas fracas/fortes** — Exibição automática das variantes de pronúncia fraca e forte de palavras funcionais (ex. «the», «to», «can»), para dominar a fala natural
- **Sotaques Americano e Britânico** — Alterne entre IPA em inglês americano (en-US) e britânico (en-GB)
- **Text-to-Speech** — Clique no botão do altifalante para ouvir a pronúncia conforme o sotaque selecionado
- **Fala de seleção com efeito karaoke** — Selecione texto em inglês: aparece uma barra compacta com botões falar e traduzir; a reprodução inclui realce palavra a palavra em tempo real (efeito karaoke) sincronizado com o áudio
- **Tradução da seleção** — Selecione qualquer texto, clique em traduzir na barra para obter tradução instantânea via Bing ou Google Tradutor, mostrada numa bolha integrada
- **Desambiguação de homógrafos** — Identificação automática de palavras com múltiplas pronúncias (ex. «read», «live») e seleção da correta com base no contexto
- **Atalhos de teclado** — Acesso rápido às funções principais através de atalhos personalizáveis
- **Interface Multilingue** — Suporta 41 idiomas de interface

---

## Como Usar

### Passo 1: Instalar a Extensão

Instale o **IPA Reader** na [Chrome Web Store](https://chromewebstore.google.com/), ou carregue-o localmente no modo de programador.

### Passo 2: Abrir Qualquer Página Web

Visite qualquer página web com conteúdo em inglês.

### Passo 3: Ativar o IPA

Clique no ícone da extensão na barra de ferramentas do navegador. Ative «Ativar IPA» e depois «IPA em toda a página» para anotar todas as palavras da página. Também pode usar o botão flutuante no canto inferior direito.

### Passo 4: Ver o IPA

Passe o rato sobre as palavras para ver os tooltips IPA com símbolos fonéticos codificados por cor. Clique no ícone do altifalante para ouvir a pronúncia. Para palavras com formas fracas/fortes, o tooltip mostra ambas as variantes.

### Passo 5: Falar e traduzir o texto selecionado

Selecione texto em inglês com o rato. Aparece uma barra compacta perto da seleção com dois botões:
- **🔊 Falar** — Lê o texto selecionado em voz alta com realce palavra a palavra estilo karaoke
- **🌐 Traduzir** — Mostra uma bolha de tradução integrada por baixo da barra

Também pode clicar com o botão direito e escolher «IPA Reader > Speak Selection» ou «IPA Reader > Translate Selection».

> **Dica:** Clique no ícone da extensão na barra de ferramentas do navegador para abrir o painel de definições e ajustar o tipo de sotaque, velocidade de fala, modo ao passar o rato, motor de tradução e mais.

---

## Modo IPA em toda a página

Com o modo IPA em toda a página ativo, cada palavra em inglês na página recebe uma anotação IPA acima do texto em formato ruby. Os símbolos IPA estão codificados por cor para leitura fácil:

- **Vogais** — realçadas a azul
- **Consoantes** — a cinzento
- **Marcas de acento** (ˈ ˌ) — realçadas a vermelho
- **Marcas de comprimento** (ː) — realçadas a roxo

A extensão ajusta automaticamente o espaçamento entre linhas para evitar que as anotações se sobreponham ao texto e escala o tamanho da fonte IPA conforme o comprimento da palavra para um aspeto limpo.

---

## Dicionário ao passar o rato

A extensão inclui um dicionário de inglês integrado baseado no WordNet (mais de 82 000 palavras). Pode escolher entre vários modos ao passar o rato nas definições:

| Modo | Comportamento |
|------|---------------|
| **Dicionário** | Ao passar o rato: IPA + definição em inglês + botão de pronúncia |
| **Tooltip** | Ao passar o rato: IPA + botão de pronúncia (sem definições) |
| **Desligado** | Sem efeito ao passar o rato |

No **modo Dicionário**, o tooltip mostra:
- A palavra e a sua transcrição IPA
- Um botão de pronúncia (clique para ouvir)
- Definições em inglês do WordNet

> **Dica:** Os dados do dicionário são carregados sob demanda quando o modo Dicionário está ativo e libertados ao mudar para outros modos, para poupar memória.

---

## Leitor de PDF

O IPA Reader inclui um leitor de PDF integrado que permite ler documentos PDF com anotações IPA, dicionário, voz e tradução — as mesmas funcionalidades que usa nas páginas web, agora também em PDFs.

### Abrir um PDF

**Método 1: A partir do popup**  
Clique no ícone da extensão e depois em «Abrir leitor de PDF». Arraste e largue um ficheiro PDF ou clique em «Escolher ficheiro» para abrir um PDF local. Também pode colar um URL de PDF.

**Método 2: Menu de contexto**  
Clique com o botão direito numa ligação `.pdf` numa página web e escolha «Abrir PDF com o IPA Reader».

**Método 3: Deteção automática**  
Quando «Deteção inteligente de PDF» está ativa nas definições, a extensão redireciona automaticamente URLs `.pdf` para o leitor integrado. Quando um PDF é detetado mas não é redirecionado (ex.: visualizador integrado do Chrome), verá notificações e pedidos para o abrir no IPA Reader.

### Funcionalidades do leitor de PDF

- **Anotações IPA** — Todas as funcionalidades IPA funcionam no texto do PDF, incluindo modo de página inteira e tooltips ao passar o rato
- **Dicionário por clique** — Clique em qualquer palavra para ver a definição (no PDF usa-se o clique em vez do hover para leitura sem distrações)
- **Barra de seleção** — Selecione texto para falar, traduzir ou copiar
- **Barra lateral** — Índice e miniaturas das páginas
- **Pesquisa** — Pesquisa de texto no PDF
- **Temas** — Temas de leitura Escuro, Claro e Sépia
- **Zoom** — Vários níveis de zoom, incluindo Automático, Ajustar à página e Largura da página
- **Atalhos de teclado** — Setas para navegar, +/- para zoom, Ctrl/Cmd+F para pesquisar

---

## Formas fracas/fortes

Muitas palavras funcionais comuns em inglês têm duas pronúncias:

- **Forma fraca** — a pronúncia reduzida na fala natural (ex. «the» → /ðə/)
- **Forma forte** — a pronúncia completa para ênfase ou isolada (ex. «the» → /ðiː/)

Quando «Mostrar formas fracas/fortes» está ativo, ao passar o rato sobre estas palavras o tooltip mostra ambas as variantes com as etiquetas «WEAK» e «STRONG».

Inclui, entre outras: artigos (the, a, an), preposições (to, for, of, from, at, as, than), conjunções (and, or, but), pronomes (you, your, her, him, his, them, us, our, there), auxiliares (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), e mais.

---

## Fala de seleção e karaoke

A fala de seleção permite selecionar texto em inglês e lê-lo em voz alta com um clique — ideal para aprender pronúncia de frases e prática de leitura.

**Método 1: Barra de seleção**  
Selecione texto em inglês com o rato. Aparece uma barra compacta com botão 🔊 falar e 🌐 traduzir. Clique em falar para reproduzir. Durante a leitura, cada palavra é realçada em tempo real (efeito karaoke).

**Método 2: Menu de clique direito**  
Após selecionar texto em inglês, clique com o botão direito e escolha «IPA Reader > Speak Selection».

**Método 3: Atalho de teclado**  
Selecione texto e prima `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Dica:** O efeito karaoke funciona melhor quando o navegador suporta eventos de limites de palavras TTS. Caso contrário, a extensão usa um recurso baseado em tempo para um realce suave.

---

## Tradução

Selecione qualquer texto na página e use a tradução para obter traduções instantâneas.

**Método 1: Barra de seleção**  
Selecione texto, clique em 🌐 traduzir na barra. Aparece uma bolha por baixo com o resultado e um botão copiar.

**Método 2: Menu de clique direito**  
Selecione texto, clique com o botão direito e escolha «IPA Reader > Translate Selection».

**Método 3: Atalho de teclado**  
Selecione texto e prima `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motores de tradução:**
- **Bing Tradutor** (predefinido) — com tecnologia Microsoft Translator
- **Google Tradutor** — com tecnologia Google

Ambos os motores suportam **108 idiomas de destino**.

Pode alterar o motor e a língua de destino nas definições da extensão. A língua de destino é detetada automaticamente a partir da língua do navegador.

> **Dica:** Clique fora da barra ou da bolha para as fechar.

---

## Atalhos de teclado

| Atalho | Atalho Mac | Ação |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Ativar/desativar anotações IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Falar a seleção |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduzir a seleção |

> **Dica:** Pode personalizar estes atalhos no Chrome em `chrome://extensions/shortcuts`.

---

## Guia de Definições

| Definição | Descrição |
|---------|-------------|
| **Ativar IPA** | Interruptor principal para ativar ou desativar a funcionalidade de anotação IPA |
| **IPA em Toda a Página** | Quando ativado, mostra IPA codificado por cor acima de todas as palavras em inglês |
| **Tipo de Sotaque** | Escolha entre IPA e pronúncia em inglês americano e britânico |
| **Modo ao passar o rato** | Escolha o comportamento ao passar o rato: Dicionário (IPA + definições + áudio), Tooltip (IPA + áudio) ou Desligado |
| **Formas fracas/fortes** | Exibir variantes de pronúncia fraca e forte de palavras funcionais |
| **Velocidade de Fala de Frases** | Ajuste a velocidade de leitura de frases (a fala de palavra única não é afetada) |
| **Motor de tradução** | Escolha entre Bing Tradutor e Google Tradutor |
| **Língua de destino** | Defina a língua de destino da tradução (detetada automaticamente a partir do navegador) |
| **Deteção inteligente de PDF** | Quando ativa, redireciona automaticamente URLs de PDF para o leitor integrado e mostra notificações quando PDFs são detetados |

---

## Perguntas Frequentes

**P: Por que não funciona em algumas páginas?**  
R: Por razões de segurança, as extensões de navegador não podem executar em páginas especiais como `chrome://`, definições do navegador ou a Chrome Web Store.

**P: E se faltar IPA para algumas palavras?**  
R: O dicionário IPA cobre mais de 134 000 palavras em inglês americano e mais de 67 000 em inglês britânico. Para palavras fora do dicionário, a extensão usa lematização e conversão G2P (grafema–fonema) baseada em regras para gerar IPA aproximado. Estas entradas são marcadas com ≈ ou ~ no tooltip.

**P: Sem som no text-to-speech?**  
R: Verifique as definições de volume do sistema e certifique-se de que os pacotes de voz em inglês estão instalados. O suporte de voz varia entre navegadores e sistemas operativos.

**P: O modo de página inteira afeta o layout?**  
R: As anotações IPA requerem espaço extra. A extensão ajusta o espaçamento entre linhas para reduzir o impacto. Se afetar a leitura, desative o modo de página inteira e use os tooltips ao passar o rato.

**P: O que significam os símbolos ~ e ≈ nas dicas?**  
R: ~ significa que o IPA foi gerado por conversão baseada em regras (G2P) e não a partir do dicionário. ≈ significa que o IPA foi derivado de uma palavra base relacionada por lematização. Podem ser menos precisos que as entradas do dicionário.

**P: A tradução não funciona?**  
R: A tradução requer ligação à Internet. Se o Bing Tradutor falhar, tente mudar para o Google Tradutor nas definições. Alguns ambientes de rede podem bloquear o acesso aos serviços de tradução.

**P: Como abro um PDF no IPA Reader?**  
R: Pode abrir PDFs de várias formas: clique em «Abrir leitor de PDF» no popup, clique com o botão direito numa ligação PDF e escolha «Abrir PDF com o IPA Reader», ou ative «Deteção inteligente de PDF» nas definições para redirecionar automaticamente URLs de PDF para o leitor integrado.

**P: A Deteção inteligente de PDF está ativa mas alguns PDFs não redirecionam?**  
R: O redirecionamento automático funciona para URLs que terminam em `.pdf`. Para PDFs servidos sem extensão `.pdf` ou abertos no visualizador integrado do Chrome, verá uma notificação e um indicador a convidá-lo a abrir no IPA Reader.

**P: Posso usar o dicionário offline?**  
R: Sim. O dicionário WordNet (mais de 82 000 palavras) está incluído na extensão. Todas as consultas são feitas localmente, sem ligação à Internet.

---

## Ligações Relacionadas

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
