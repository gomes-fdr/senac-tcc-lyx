COMO INSTALAR
=============

O modelo de TCC para o Lyx pode ser utilizado sem preocupação com a 
instalação, uma vez que basta descompactar o ZIP, ou baixar o 
repositório para que possa ser editado. No entanto, algumas opções 
podem não estar disponíveis na instalação padrão da sua 
distribuição LaTeX, e pode ser necessário a instalação de alguns 
pacotes extras.

Cada seção deste documento descreve pacotes que devem estar 
instalados nos sistemas onde o modelo foi testado.

## Linux ##

### Debian / Ubuntu ###

Devem ser instalados os pacotes:

* biber
* texlive-lang-portuguese
* texlive-bibtex-extra

### Fedora (24)  ###

Devem ser instalados os pacotes:

* texlive-biblatex
* texlive-sectsty
* texlive-hyphenat
* texlive-tocloft
* texlive-abstract
* texlive-babel-portuges

## Mac OS X ##

Para instalar o LyX no Mac OS X, você irá precisar de, aproximadamente,
5GB livres de espaço em disco para os downloads e instalação. Se você
estiver com pouco espaço disponível em disco, pode ser necessária a
remoção dos pacotes de instalação após cada passo, além da "limpeza"
do disco com a remoção de arquivos desnecessários.

Baixe e instale o pacote LaTeX disponibilizado pela distribuição MacTeX
a partir do endereço:

    http://www.tug.org/mactex/

Baixe o DMG do LyX a partir de:

    http://www.lyx.org

Para a instalação do LyX, basta copiá-lo para o diretório Applications.

Caso o LyX não consiga encontrar os modelos de Artigo, basta executar
o comando de reconfigurar e reiniciar o LyX.

Após a instalação, o modelo de TCC deste projeto abre corretamente no
LyX 2.2.1 para Mac OS X (testado na versão 10.11.6 El Camino), com o
MacTex versão 2016-06-03. O único erro ocorre na imagem disponível no
arquivo com a Descrição do Sistema, pois o LyX armazena o caminho
completo para a imagem. Basta corrigir o caminho para o arquivo que o
modelo pode ser novamente gerado.

## Observações ##

1. No documento exemplo, existe uma imagem na seção "Descrição da
Solução", que deve ser corrigida após a instalação do modelo de
TCC, uma vez que o LyX utiliza caminho absolutos para a localização
das imagens.
