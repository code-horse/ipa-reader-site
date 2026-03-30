---
layout: bare
title: Extensão IPA Reader - Guia do Utilizador
lang: pt
---

# IPA Reader - Guia do Utilizador

> Versão: v1.3.0

## Introdução

O IPA Reader é uma extensão de navegador concebida para estudantes de inglês. Adiciona anotações de pronúncia IPA (Alfabeto Fonético Internacional) a palavras em inglês em páginas web, suportando sotaques americanos e britânicos, ajudando-o a aprender a pronúncia inglesa mais facilmente.

---

## Principais Funcionalidades

- **Modo IPA em toda a página** — Adicione anotações IPA a todas as palavras em inglês na página com um clique, com símbolos IPA codificados por cor (vogais, consoantes, acentos) para leitura fácil
- **Formas fracas/fortes** — Exibição automática das variantes de pronúncia fraca e forte de palavras funcionais (ex. the, to, can) para dominar a fala natural
- **Sotaques Americano e Britânico** — Alterne entre IPA em inglês americano (en-US) e britânico (en-GB)
- **Text-to-Speech** — Clique no botão do altifalante para ouvir a pronúncia conforme o sotaque selecionado
- **Fala de seleção com efeito karaoke** — Selecione texto em inglês: aparece uma barra compacta com botões falar e traduzir; a reprodução inclui realce palavra a palavra em tempo real (efeito karaoke) sincronizado com o áudio
- **Tradução da seleção** — Selecione qualquer texto, clique em traduzir na barra para obter tradução instantânea via Bing ou Google Tradutor, mostrada numa bolha integrada
- **Tooltips ao Passar o Rato** — Passe o rato sobre palavras anotadas para ver IPA e botões de pronúncia
- **Desambiguação de homógrafos** — Identificação automática de palavras com múltiplas pronúncias (ex. read, live) e seleção da correta com base no contexto
- **Atalhos de teclado** — Acesso rápido às funções principais através de atalhos personalizáveis
- **Interface Multilingue** — Suporta 38 idiomas de interface

---

## Como Usar

### Passo 1: Instalar a Extensão

Instale o **IPA Reader** na [Chrome Web Store](https://chromewebstore.google.com/), ou carregue-o localmente no modo de programador.

### Passo 2: Abrir Qualquer Página Web

Visite qualquer página web com conteúdo em inglês.

### Passo 3: Ativar o IPA

Clique no ícone da extensão na barra de ferramentas do navegador. Ative «Ativar IPA» e depois «IPA em toda a página» para anotar todas as palavras da página. Também pode usar o botão flutuante no canto inferior direito.

### Passo 4: Ver o IPA

Passe o rato sobre as palavras para ver os tooltips IPA, clique no ícone do altifalante para ouvir a pronúncia. Para palavras com formas fracas/fortes, o tooltip mostra ambas as variantes.

### Passo 5: Falar e traduzir o texto selecionado

Selecione texto em inglês com o rato. Aparece uma barra compacta perto da seleção com dois botões:
- **🔊 Falar** — Lê o texto selecionado em voz alta com realce palavra a palavra estilo karaoke
- **🌐 Traduzir** — Mostra uma bolha de tradução integrada por baixo da barra

Também pode clicar com o botão direito e escolher «IPA Reader > Speak Selection» ou «IPA Reader > Translate Selection».

> **Dica:** Clique no ícone da extensão na barra de ferramentas do navegador para abrir o painel de definições e ajustar o tipo de sotaque, velocidade de fala, motor de tradução e mais.

---

## Modo IPA em toda a página

Com o modo IPA em toda a página ativo, cada palavra em inglês na página recebe uma anotação IPA acima do texto em formato ruby. Os símbolos IPA estão codificados por cor:

- **Vogais** — realçadas a azul
- **Consoantes** — a cinzento
- **Marcas de acento** (ˈ ˌ) — realçadas a vermelho
- **Marcas de comprimento** (ː) — realçadas a roxo

A extensão ajusta automaticamente o espaçamento entre linhas e escala o tamanho da fonte IPA conforme o comprimento da palavra.

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
| **Tooltips ao Passar o Rato** | Mostrar tooltip IPA com botão de pronúncia ao passar o rato |
| **Formas fracas/fortes** | Exibir variantes de pronúncia fraca e forte de palavras funcionais |
| **Velocidade de Fala de Frases** | Ajuste a velocidade de leitura de frases (a fala de palavra única não é afetada) |
| **Motor de tradução** | Escolha entre Bing Tradutor e Google Tradutor |
| **Língua de destino** | Defina a língua de destino da tradução (detetada automaticamente a partir do navegador) |

---

## Perguntas Frequentes

**P: Por que não funciona em algumas páginas?**  
R: Por razões de segurança, as extensões de navegador não podem executar em páginas especiais como `chrome://`, definições do navegador ou a Chrome Web Store.

**P: E se faltar IPA para algumas palavras?**  
R: O dicionário IPA cobre palavras comuns em inglês. Para palavras fora do dicionário, a extensão gera IPA aproximado por lematização e G2P, marcado com ≈ ou ~ na dica.

**P: Sem som no text-to-speech?**  
R: Verifique as definições de volume do sistema e certifique-se de que os pacotes de voz em inglês estão instalados. O suporte de voz varia entre navegadores e sistemas operativos.

**P: O modo de página inteira afeta o layout?**  
R: As anotações IPA requerem espaço extra. A extensão ajusta o espaçamento entre linhas para reduzir o impacto. Se afetar a leitura, desative o modo de página inteira e use os tooltips ao passar o rato.

**P: O que significam os símbolos ~ e ≈ nas dicas?**  
R: ~ significa que o IPA foi gerado por regras (G2P) e ≈ que foi derivado de uma palavra base relacionada. Podem ser menos precisos que as entradas do dicionário.

**P: A tradução não funciona?**  
R: A tradução requer ligação à Internet. Se o Bing Tradutor falhar, tente mudar para o Google Tradutor nas definições. Alguns ambientes de rede podem bloquear o acesso aos serviços de tradução.

---

## Ligações Relacionadas

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
