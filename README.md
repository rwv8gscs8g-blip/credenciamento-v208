# Sistema de Credenciamento V208

Sistema para a gestão do **credenciamento e do rodízio** de prestadores de serviço em municípios, segundo a Lei nº 14.133/2021 (arts. 6º, XLIII, 74, IV, e 79).

**Página do projeto:** https://rwv8gscs8g-blip.github.io/credenciamento-v208/

> **Licença TPGL v1.1** — licença *source-available* para software de interesse público. Garante a transparência e a auditabilidade do código (Lei nº 12.527/2011, Lei de Acesso à Informação) e converte cada versão para a Apache License 2.0 quatro anos após a sua publicação. A validação do código é aberta aos contribuidores cadastrados. Texto completo da licença: [LICENSE](LICENSE).

## Baixar

**Versão atual: Beta 11.3** (versão de testes). Baixe direto para o seu computador:

- **Windows 10 ou 11, 64 bits:** [baixar o instalador](https://github.com/rwv8gscs8g-blip/credenciamento-v208/releases/download/v208.0.0-beta.11.3/Setup-Credenciamento-Beta11-x64-cbba645a0277c28d.exe). Abra o arquivo e siga as instruções na tela.
- **Linux Intel ou AMD de 64 bits:** [pacote .deb](https://github.com/rwv8gscs8g-blip/credenciamento-v208/releases/download/v208.0.0-beta.11.3/Credenciamento-Linux-208.11.3-amd64.deb) ou [AppImage](https://github.com/rwv8gscs8g-blip/credenciamento-v208/releases/download/v208.0.0-beta.11.3/Credenciamento-Linux-208.11.3-amd64.AppImage). Abra no instalador de programas do seu Linux e procure Credenciamento no menu.
- **Mac com chip Apple:** em preparação. Estamos concluindo a assinatura digital da Apple.

Prefere um passo a passo? A **[página do projeto](https://rwv8gscs8g-blip.github.io/credenciamento-v208/)** traz tutoriais e as regras explicadas por tema.

## Como funciona

O programa roda no computador do município. A base de dados fica nesse computador, cifrada, e funciona sem internet. Comece com uma base de treinamento e dados fictícios, e faça cópias de segurança durante o uso.

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

## Licença
O Sistema de Credenciamento V208 é distribuído sob a **TPGL v1.1** (Copyright © 2026 Luís Maurício Junqueira Zanin e contribuintes):
- **Validação pública:** a licença assegura a transparência e a auditabilidade do sistema, em linha com a Lei de Acesso à Informação.
- **Validação do código pelos contribuidores:** o código-fonte é auditado pelos contribuidores cadastrados no repositório do projeto. O acesso é concedido pela equipe responsável.
- **Uso por órgão público:** o uso interno pela Administração é permitido nos termos da licença. O uso comercial concorrente é reservado.
- **Abertura futura:** cada versão passa a valer como Apache License 2.0 quatro anos depois da sua publicação.

Leia o texto completo em [LICENSE](LICENSE). Em caso de dúvida, vale o texto da licença.

## Contato
Para conhecer o projeto ou pedir acesso como contribuidor, fale com a equipe responsável pelo credenciamento do seu município.
