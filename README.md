# GUROchan Image Downloader
#### Um simples programa em Python + PyQt4 que baixa imagens e vídeos do GUROchan!

### Descrição:

###### Este é um simples programa escrito em Python e utiliza PyQt4 para a utilização de uma interface gráfica (GUI) simples e leve.

###### Este programa realiza o download de imagens (.jpg, .png e .gif) e vídeos (.webm, se houver) do tópico escolhido em uma board específica do GUROchan.

###### Ao escolher a board e o tópico desejado, o programa irá fazer uma varredura para determinar a quantidade de imagens e vídeos disponíveis. Ele então irá fazer o download de todos os arquivos do tópico para a pasta que você tenha escolhido ou para a pasta GUROchan do usuário atual, caso não tenha escolhido nenhuma pasta de destino.

![GUROchan Image Downloader](https://raw.githubusercontent.com/Wolfterro/wolfterro.github.io/master/posts/img/imagens_de_projetos/gurochan_image_downloader.png)

### Requisitos:

#### Compilando:
- Python 2.7
- PyQt4 para Python 2.7
- PyInstaller

###### Execute o PyInstaller para compilar o programa:

      - Linux:
      pyinstaller --icon="Icon.ico" --noconsole --onefile "GUROchan Image Downloader.py"
      
      - Windows
      pyinstaller --icon="Icon.ico" --noconsole --onefile "GUROchan Image Downloader.pyw"

#### Binário:
- Pode ser executado diretamente, sem qualquer requisito ou dependência.

### Download:

#### Linux: https://github.com/Wolfterro/GUROchan-Image-Downloader/releases/tag/v1.0-Linux

#### Windows: https://github.com/Wolfterro/GUROchan-Image-Downloader/releases/tag/v1.0-Windows

###### Caso não possua o git e queira também baixar o repositório por completo, baixe através deste [Link](https://github.com/Wolfterro/GUROchan-Image-Downloader/archive/master.zip) ou clique em "Clone or Download", no topo da página.
