# Mini CRM de Perfis (POO - Versão Simples)

Projeto simples em Python que cadastra perfis profissionais, armazena competências básicas
e gera recomendações de carreira com base nas competências informadas.

## Funcionalidades
- Cadastro de perfis com: nome, perfil, e-mail e 4 competências (0–5)
  - Lógica
  - Criatividade
  - Colaboração
  - Adaptabilidade
- Listagem e busca de perfis
- Exportação para CSV (`data/profiles.csv`)
- Recomendador simples baseado em regras

## Estrutura
app.py # interface de linha de comando (menu)
repo.py # persistência (JSON + export CSV)
stages.py # classe Profile (POO)
data/ # pasta gerada automaticamente com profiles.json e profiles.csv

## Como executar
1. Clone o repositório:
   ```bash
   git clone <SEU_REPO>
   cd <SEU_REPO>
execute:
python app.py
