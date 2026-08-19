# Catálogo de Parcerias

Catálogo de potenciais parceiros para massoterapia em um raio de 100 km centralizado em São João del-Rei/MG.

## Estrutura

- `index.html`: shell pequeno da aplicação.
- `assets/css/style.css`: estilos separados da marcação.
- `assets/js/app.js`: busca, filtros, status persistentes e exportação CSV.
- `data/index.json`: metadados, cidades e arquivos disponíveis.
- `data/partners/`: um arquivo JSON por cidade, facilitando futuras inclusões e atualizações.

## Critério de parceiros

Foram removidos estabelecimentos explicitamente identificados como massoterapia, massoterapeuta, massagista, massagem ou terapias corporais. Permanecem clínicas, estéticas, spas, coworkings, clubes, hotéis, pousadas e hospedarias com potencial de parceria.

## Persistência

Os status são salvos no navegador com `localStorage`. O botão de exportação gera uma cópia CSV do acompanhamento.

## Escopo

Pesquisa inicial realizada em 18/08/2026. O filtro geográfico usa um raio de 100 km a partir de São João del-Rei. Telefones e links devem ser confirmados antes do contato.
