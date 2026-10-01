# Acervo de Prompts V3A

Página de consulta em duas partes, no design system da V3A:

1. **Lei do realismo.** São 16 artigos em cinco capítulos (Pessoas, Luz e cor, Câmera e quadro, Lugar, O pedido) que valem para toda imagem gerada a partir do acervo. Cada artigo tem uma cláusula que pode ser copiada, e há um bloco único que se cola no fim de qualquer prompt.
2. **Acervo.** São 156 fichas em 13 módulos, com busca, comparação e prompts expansíveis. Referências visuais ainda aguardam curadoria.

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

Um repositório público permite que qualquer pessoa consulte e baixe os arquivos. A publicação do repositório, por si só, não cria um site navegável; o HTML pode ser baixado e aberto localmente.
