# Desafio Técnico: Implementação de Comunicação em Tempo Real

## Objetivo

Este desafio tem como objetivo avaliar suas habilidades e conhecimentos técnicos em Next.js, Node.js e TypeScript, com foco especial em sua capacidade de estabelecer uma comunicação eficiente e em tempo real entre o frontend e o backend.

## Descrição

Desenvolver uma aplicação utilizando Next.js (React.js) no frontend e Node.js no backend, que estabeleça uma comunicação em tempo real entre essas duas partes. O desafio específico consiste em monitorar todos os processos em execução na memória do sistema operacional do servidor e transmitir informações sobre esses processos para o frontend de forma imediata e eficiente.

## Especificações Técnicas

### Frontend

A página deve receber e exibir as informações dos processos em tempo real.

**Importante:** Não deve haver uso de polling (temporizadores) para verificar atualizações; a atualização deve ser verdadeiramente em tempo real.

### Backend

O servidor deverá monitorar em tempo real todos os processos em execução na memória do sistema operacional (incluindo aplicações e serviços). Ao detectar o início de um novo processo, deve enviar para o frontend o nome do processo e a data/hora em que foi iniciado. Da mesma forma, quando um processo é encerrado, essa informação deve ser imediatamente comunicada ao frontend.

## Critérios de Avaliação

### Estratégia de Comunicação

Avaliaremos a tecnologia, protocolo ou metodologia escolhida para a comunicação em tempo real.

### Monitoramento de Processos

Avaliaremos sua abordagem em monitorar processos no sistema operacional usando Node.js e como você detecta e monitora os processos a nível de sistema operacional.

### Otimização e Desempenho

A solução deve ser eficiente em termos de consumo de tráfego de rede, leveza e desempenho. Deve-se evitar soluções que sobrecarreguem o sistema com requisições desnecessárias ou que consumam excessivamente recursos do servidor.

## Considerações

- Não se preocupe com autenticações e permissões, handshakes com tokens ou certificados. O foco é na estratégia de comunicação e monitoramento.
- A solução deve ser desenvolvida usando Next.js, Node.js e TypeScript. A escolha de bibliotecas adicionais e abordagens de design é deixada a seu critério.

## Entrega

- Compartilhe o código em um repositório no GitHub.
- Adicione um README explicando a configuração e execução do projeto.

**Boa sorte!** 🚀

