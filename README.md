# Acervo de Prompts V3A

Página de consulta em duas partes, no design system da V3A:

1. **Lei do realismo.** São 16 artigos em cinco capítulos (Pessoas, Luz e cor, Câmera e quadro, Lugar, O pedido) que valem para toda imagem gerada a partir do acervo. Cada artigo tem uma cláusula que pode ser copiada, e há um bloco único que se cola no fim de qualquer prompt.
2. **Acervo.** São 156 fichas em 13 módulos, organizados em quatro grupos: Quadro, Luz e cor, Câmera, Cena e lugar.
   - A busca procura em todas as fichas.
   - A ficha abre num painel ao lado (em tela cheia no celular), com o prompt em destaque e a opção de incluir a Lei ao copiar.
   - Dá para marcar fichas para revisão e comparar duas lado a lado, com os prompts completos.
   - Fichas e artigos têm endereço próprio, por exemplo `#acervo/ref-12` e `#lei/art-7`.
   - Referências visuais ainda aguardam curadoria.

A Lei e os módulos Câmeras e suportes, Lentes, Dramaturgia brasileira e Rio e Brasil vêm de um estudo de produção sobre o look de séries e novelas brasileiras e sobre como evitar a aparência de imagem gerada por IA. Parte deles adapta prompts testados em inglês. As versões em português, assim como os demais prompts, ainda não foram testadas em geradores.

## Abrir

Baixe este repositório e abra `index.html` em um navegador moderno. Não é preciso instalar dependências nem iniciar um servidor. As seleções ficam guardadas no navegador quando o armazenamento local está disponível e não são sincronizadas entre pessoas.

## Arquivos

- `index.html`: página independente. Estilos, fontes Geologica (subconjunto latino), logotipo, dados e interações estão todos incorporados.
- `catalogo-visual.json`: cópia estruturada das fichas do acervo.
- `lei-realismo.json`: cópia estruturada da Lei do realismo.

Alterar apenas os arquivos JSON não atualiza o HTML automaticamente.

O pacote não inclui PDFs, documentos de referência nem fotografias dos materiais consultados.

## Compartilhamento

O repositório é público, e qualquer pessoa pode consultar e baixar os arquivos. A página é publicada pelo GitHub Pages a partir da branch `main`. O HTML também pode ser baixado e aberto localmente.
