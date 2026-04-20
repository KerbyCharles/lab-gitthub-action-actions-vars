# 1. Por que a Secret aparece como **?

## rp: Porque o GitHub mascara automaticamente valores sensíveis para evitar vazamento de dados

# 2. O job deploy_app consegue ler BUILD_VERSION do build_app?

## Não consegue diretamente.

#Por quê?

## Porque no GitHub Actions:

## ● cada job roda em uma máquina isolada
## ● variáveis de um job não passam automaticamente para outro
