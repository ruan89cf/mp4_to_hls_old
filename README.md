# Gerador de Metadados TMDb e XML

Este script bash automatiza o processo de obtenção de metadados do The Movie Database (TMDb), codificação de vídeos, renomeação de arquivos e geração de arquivos XML para as plataformas Vizer e Dooplay.

## Funcionalidades

* Obtém metadados de filmes e séries do TMDb, incluindo pôsteres, cenários, elenco, diretor, gêneros e muito mais.
* Suporta filmes e séries, incluindo informações de temporadas e episódios.
* Codifica vídeos para diferentes resoluções (540p e 360p) com suporte a áudio dual.
* Gera streams de vídeo compatíveis com HLS (HTTP Live Streaming).
* Cria arquivos XML para importação nas plataformas Vizer e Dooplay, incluindo metadados e links de vídeo.
* Renomeia arquivos `.mp4` para `.mkv`.
* Verifica se existem arquivos XML antes de gerar novos.
* Lida com trilhas de áudio duplas e detecção de idioma.
* Baixa automaticamente pôsteres e cenários.
* Inclui metadados Yoast SEO nos arquivos XML gerados.
* Suporta o gênero Anime.

## Requisitos

* `bash`
* `curl` ou `wget` ou `httpie` ou `fetch`
* `python2` ou `python`
* `jq`
* `ffmpeg`
* `ffprobe`
* `wp-cli` (para importação no WordPress)

## Instalação

1. Clone o repositório:

```bash
git clone [URL inválido removido]
cd seu-nome-de-repositório
