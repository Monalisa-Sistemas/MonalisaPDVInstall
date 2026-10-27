# MonalisaPDVInstall

Página de download do **instalador personalizado do MonalisaPDV**, para primeira instalação ou atualização, destinada ao time de suporte.

## Página (GitHub Pages)

**https://monalisa-sistemas.github.io/MonalisaPDVInstall/**

Abra o link, clique em **"Baixar instalador"** e siga o assistente. Os três botões de download apontam para o instalador da release oficial marcada como **Latest**.

## Link direto do instalador

https://github.com/Monalisa-Sistemas/MonalisaReleases/releases/latest/download/monalisapdv_install.exe

## Atualização automática do download

Cada nova versão oficial de [MonalisaPdv](https://github.com/Monalisa-Sistemas/MonalisaPdv) publica, na mesma release em [MonalisaReleases](https://github.com/Monalisa-Sistemas/MonalisaReleases/releases), o ZIP de atualização e o arquivo `monalisapdv_install.exe` da mesma versão.

O instalador WPF personalizado é preparado a partir do pacote dessa versão pelo fluxo de publicação do PDV, tanto na publicação local quanto no workflow `release-windows.yml`. Ao publicar a nova release como **Latest**, o endereço acima passa a baixar o novo instalador sem editar esta página. A antiga tag `pdv_installer` não é utilizada pelo site.

O EXE já contém o sistema e os componentes de instalação. Depois do download, não precisa abrir o antigo Monalisa Downloader. O assistente identifica instalação ou atualização, permite conferir destino e componentes e solicita a autorização do Windows para instalar. Ao concluir, o suporte abre o PDV pelo atalho ou pelo menu Iniciar; o aplicativo não inicia automaticamente.

Este repositório contém somente a página e suas instruções. O código do instalador e seu processo de geração permanecem no repositório `MonalisaPdv`.
