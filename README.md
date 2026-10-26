# Projeto EcoCampus

## Participantes
Leonardo Hiroshi Dondo de Freitas - RGM: 46610049 ;

Rafael Marques de Oliveira - RGM: 47877081

## Sobre o Projeto 
O EcoCampus é um programa desenvolvido em linguagem C para analisar o consumo de água em diferentes locais de um campus universitário. O sistema lê os dados de um arquivo, realiza cálculos e gera um relatório com os principais indicadores de consumo.

## Objetivos
Calcular o consumo total e médio de água.

Identificar o local com maior consumo.

Contabilizar os locais que ultrapassaram o limite estabelecido.

Exibir e salvar o relatório final.

## Tecnologias Utilizadas
Linguagem C.

Bibliotecas stdio.h e stdlib.h.

Manipulação de arquivos.

Estruturas condicionais e de repetição.

Funções e variáveis.

## Funcionamento do Programa
Leitura dos dados:
O programa abre o arquivo consumo_campus.txt, que contém o nome de cada local, seu consumo de água e o limite estabelecido.

Processamento das informações:
Utilizando fscanf() e uma estrutura while, o programa lê os registros e calcula o consumo total, identifica o maior consumo e verifica quais locais ultrapassaram seus limites.

Cálculo da média:
A média é calculada dividindo o consumo total pela quantidade de locais analisados.

Geração do relatório:
A função imprimirRelatorio() organiza os resultados, exibindo a quantidade de locais, o consumo total e médio, o local com maior consumo e a quantidade de alertas.

Salvamento dos resultados:
O relatório é exibido no terminal e salvo no arquivo relatorio_consumo.txt, permitindo consultar os resultados posteriormente.

## Arquivos do Projeto
projeto3_ecocampus.c: código-fonte do programa.

consumo_campus.txt: arquivo com os dados de entrada.

relatorio_consumo.txt: arquivo gerado automaticamente com o relatório final.

## Conclusão
O projeto EcoCampus aplica conceitos fundamentais da linguagem C para automatizar a análise do consumo de água. A solução facilita a identificação de locais com consumo elevado e gera relatórios organizados, contribuindo para o acompanhamento do consumo no campus.

