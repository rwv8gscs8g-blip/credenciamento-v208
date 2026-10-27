# Sistema de Credenciamento V208

Sistema para a gestão do **credenciamento e do rodízio** de prestadores de serviço em municípios, segundo a Lei nº 14.133/2021 (arts. 6º, XLIII, 74, IV, e 79).

**Página do projeto:** https://rwv8gscs8g-blip.github.io/credenciamento-v208/

> O código-fonte é **privado**. Só os contribuidores autorizados têm acesso. Este repositório contém apenas a apresentação pública do projeto.

## Situação atual
- **Versão piloto 11.2** (27/10/2026), em avaliação controlada por município.
- Programa para Windows 10/11, 64 bits. A base de dados fica no próprio computador, cifrada, e funciona sem internet.

## O que o sistema faz
- Cadastra entidades demandantes, empresas, atividades e serviços, com preços fixados pela Administração.
- **Rodízio objetivo por atividade:** só o rodízio indica a empresa, e ninguém escolhe à mão.
- Pré-OS com prazo de resposta (em dias ou horas), aceite com empenho, Ordem de Serviço, recusa, cancelamento de Pré-OS e de OS.
- Medição final e única, avaliação com 10 critérios (C01 a C10) e pagamento só do que foi executado.
- Faltas, suspensões e reativação automáticas, conforme os parâmetros do edital.
- Dossiê por empresa, relatórios e trilha de auditoria de cada ato, com data e hora de Brasília.

## Regras do rodízio, em resumo
1. Uma fila por atividade; a empresa da vez é a de menor posição entre as disponíveis.
2. Quem aceita a Pré-OS recebe a OS e vai para o fim da fila.
3. Quem recusa, ou deixa o prazo vencer, perde a vez e recebe 1 falta.
4. Média da avaliação abaixo da nota de corte gera 1 falta. A avaliação não move a fila.
5. Ao atingir o limite de faltas de uma origem, a empresa fica suspensa pelo prazo do edital e volta sozinha depois.
6. Paga-se só o executado e medido, uma vez por OS.

## Novidades da 11.2
- Cancelamento de Ordem de Serviço (motivo obrigatório, sem falta, sem pagamento).
- Nomes dos campos alinhados em todas as telas.
- Diagnóstico local de erros, sem dados pessoais.

## Contato
Para conhecer o projeto ou pedir acesso como contribuidor, fale com a equipe responsável pelo credenciamento do seu município.
