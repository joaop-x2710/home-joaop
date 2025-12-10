#!/bin/bash
# Exemplo de Script Bash simples para atualizar o README
# (Você pode usar Python para tarefas mais complexas)

CURRENT_TIME=$(date +"%Y-%m-%d %H:%M:%S")

echo "
# Olá, sou o João Vitor - Engenharia Informática
┌───────────────────────────┐
│ User: João Vitor Salles Peixoto
│ Kernel: $(uname -r)
│ Shell: Bash
│ Last Update: ${CURRENT_TIME}
└───────────────────────────┘

### Habilidades Principais
- Linguagens: C, C++ (básico)
- SO: Arch Linux, Linux CLI
- Ferramentas: VS Code, Git
" > README.md
