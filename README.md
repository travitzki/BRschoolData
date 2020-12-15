# BRschoolData
Helps to import and label (in portuguese) Brazilian school microdata

For now works like a charm only with 2019 data.

## Pacote R para importar e rotular os microdados do Censo Escolar

O próposito deste pacote é contribuir para a política de dados abertos, facilitando o acesso a bases detalhadas sobre educação disponibilizadas pelo INEP (Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira). Qualquer colaboração nesse sentido será muito bem vinda!

Até o momento, foi testado para todas as tabelas do Censo Escolar de 2019, mas funciona razoavelmente para anos anteriores não muito distantes (o que devo melhorar e aceito ajuda).

## Funcionamento básico

Os microdados precisam ser baixados e descompactados. Veja a função auxiliar (download_microdata) ou vá direto no site: http://inep.gov.br/microdados 

Há uma função (import_csv2rda) para importar os dados para o R, especialmente importante para as bases maiores (professores e matriculas).

Outra função (insert_labels) troca a codificação original dos microdados em rótulos compreensíveis, e também cria algumas variáveis adicionais por padrão (default).

Mais informações:

?insert_labels

