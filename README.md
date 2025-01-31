# 🎬 Gerador de Metadados TMDb e XML (Projeto Descontinuado)

> **⚠ Atenção:** Este projeto foi descontinuado e não recebe mais atualizações. Ele foi substituído por uma versão em Java.

## 📌 Sobre o Projeto

Este script Bash automatiza o processo de obtenção de metadados do The Movie Database (TMDb), codificação de vídeos, renomeação de arquivos e geração de arquivos XML para as plataformas **Vizer** e **Dooplay**.

## 🚀 Funcionalidades

✅ Obtém metadados de filmes e séries do TMDb, incluindo pôsteres, cenários, elenco, diretor e gêneros.  
✅ Suporta informações detalhadas de temporadas e episódios.  
✅ Codifica vídeos para diferentes resoluções **(540p e 360p)** com suporte a áudio dual.  
✅ Gera streams de vídeo compatíveis com **HLS (HTTP Live Streaming)**.  
✅ Cria arquivos **XML** para importação no **Vizer** e **Dooplay**, incluindo metadados e links de vídeo.  
✅ Renomeia arquivos `.mp4` para `.mkv`.  
✅ Verifica a existência de arquivos XML antes de gerar novos.  
✅ Lida com trilhas de áudio duplas e detecção de idioma.  
✅ Baixa automaticamente **pôsteres e cenários**.  
✅ Inclui metadados **Yoast SEO** nos arquivos XML gerados.  
✅ Suporta o gênero **Anime**.  

## 🔧 Requisitos

- `bash`
- `curl` ou `wget` ou `httpie` ou `fetch`
- `python2` ou `python`
- `jq`
- `ffmpeg`
- `ffprobe`
- `wp-cli` (para importação no WordPress)

## 📥 Instalação

Clone o repositório (observe que este repositório é apenas para fins de referência e não será atualizado):

```bash
git clone https://github.com/ruan89cf/mp4_to_hls_old/
