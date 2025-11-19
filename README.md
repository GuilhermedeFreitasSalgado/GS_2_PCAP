Mini CRM de Perfis (POO - Versão Simples)

Projeto simples em Python que cadastra perfis profissionais, armazena competências básicas e gera recomendações de carreira com base nas competências informadas.

Descrição

Este repositório contém uma implementação simples orientada a objetos de um mini CRM de perfis. O objetivo é cadastrar perfis profissionais, registrar quatro competências (0–5) e gerar recomendações de carreira a partir de regras simples. O projeto é leve, fácil de entender e adequado para entrega acadêmica ou para uso como exemplo em portfólio.

Funcionalidades

Cadastro de perfis com:

nome

perfil (descrição breve, ex.: desenvolvedor, designer)

e-mail

4 competências com nota de 0 a 5:

Lógica

Criatividade

Colaboração

Adaptabilidade

Listagem de perfis

Busca por nome / perfil / e-mail

Exportação para CSV (data/profiles.csv)

Recomendador simples baseado em regras (gera sugestões de carreiras / trilhas a partir das notas)

Estrutura do projeto
.
├── app.py          # interface de linha de comando (menu)
├── repo.py         # persistência (JSON + export CSV)
├── stages.py       # classe Profile (POO)
└── data/           # pasta gerada automaticamente com profiles.json e profiles.csv

Como executar

Clone o repositório:

git clone <SEU_REPO>
cd <SEU_REPO>


Garanta que você possui Python 3.8+ instalado:

python --version


Execute o aplicativo:

python app.py


Ao executar, utilize o menu para adicionar perfis, listar, buscar, exportar e gerar recomendações.

Exemplo de fluxo

Escolha "Adicionar perfil".

Informe Nome, Perfil e E-mail.

Informe as notas de 0 a 5 para: Lógica, Criatividade, Colaboração e Adaptabilidade.

Salve e utilize a opção de recomendação para obter sugestões baseadas nas notas informadas.

Observações técnicas

Os perfis são salvos em data/profiles.json; a pasta data/ é criada automaticamente quando necessário.

A exportação gera data/profiles.csv com as colunas de competências.

O recomendador é baseado em regras simples (por exemplo: Lógica alta → carreiras técnicas; Criatividade alta → design/marketing; Colaboração + Adaptabilidade altas → papéis de produto/gestão).
