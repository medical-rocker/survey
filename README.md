# About this repository

事前調査用のスクリプト置き場

## system_prerequisites/

RStudio Package Maneger をつかって、コンパイル済のRパッケージを Ubuntu 20.04 (rocker/tidyverse:4.0.4 のベース）に導入する際に必要なシステム側のパッケージ（apt/deb）を抽出するスクリプト

- Tcl/Tk 関係は、Ubuntu 20.04 の標準的なインストールには含まれるようだが、rocker/tidyverse のコンテナには含まれていないので追加が必要
- rocker/rstudio -> rocker/tidyverse では Pandoc については手動で導入されているので不要
- TeXLive は {tinytex} を使って R 上でインストールするので不要

