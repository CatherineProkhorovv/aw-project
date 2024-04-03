Número do ADR: 04 <br>
Título: QRmeat <br>
Data: 2024-03-09 <br>
Responsável: Afonso Carreira & Catherine Prokhorov 

## Context and Problem Statement
A crescente preocupação dos consumidores com a qualidade e segurança dos alimentos tem impulsionado o desenvolvimento de soluções inovadoras no setor de varejo de alimentos. Uma dessas inovações é o uso de aplicativos móveis que utilizam códigos QR para fornecer informações detalhadas sobre os produtos, incluindo origem, características nutricionais, métodos de produção e preços. Apesar da disponibilidade de uma variedade de aplicativos móveis que utilizam códigos QR para fornecer informações sobre produtos alimentícios, ainda há desafios significativos a serem enfrentados. Portanto, o desenvolvimento de um aplicativo eficaz e abrangente que aborde esses desafios é essencial para melhorar a experiência do consumidor e promover uma maior transparência no setor de varejo de alimentos. 
Este projeto de ADR visa explorar e propor soluções para esses desafios, a fim de criar um aplicativo de QR code de carne que atenda às necessidades e expectativas dos consumidores, ao mesmo tempo em que promove a confiança e a transparência no fornecimento de informações sobre alimentos.

## Decision Drivers and Considered Options

Decidimos adotar esta arquitetura com o objetivo de desenvolver um sistema robusto e complexo, que pode ser decomposto em componentes individuais. Essa abordagem permite-nos utilizar cada funcionalidade e micro frontend de forma independente, sem depender de outros elementos. Isso promove a modularidade e facilita a manutenção, oferecendo uma maior flexibilidade e escalabilidade ao sistema.

## Decision Outcome

Decidimos dividir o sistema em componentes distintos, cada um correspondendo a um micro - frontEnd específico. Esta escolha visa facilitar a distribuição eficiente de tarefas entre os membros da equipa e mitigar potenciais conflitos entre os serviços. Ao atribuir tarefas de forma clara e precisa, evitamos conflitos de integração e garantimos uma implementação mais suave e eficiente. Esta abordagem promove uma melhor distribuição de responsabilidades e competências, resultando em desenvolvimento mais ágil e eficaz.

## Consequences

### Positivos
#### Flexibilidade e escalabilidade: 
A decomposição do sistema em componentes individuais permite escalar e modificar partes específicas do sistema de forma independente, facilitando a adaptação a mudanças nos requisitos e no volume de tráfego.

#### Facilidade de manutenção: 
Com cada funcionalidade e micro frontend agindo de forma independente, as atualizações e correções podem ser implementadas de forma mais direcionada e controlada, reduzindo o impacto em outras partes do sistema.

#### Reutilização de componentes: 
Componentes individuais podem ser reutilizados em diferentes partes do sistema ou até mesmo em projetos futuros, economizando tempo e esforço de desenvolvimento e aumentando a consistência e padronização do código.

#### Desenvolvimento paralelo:
A independência dos componentes permite que equipes de desenvolvimento trabalhem de forma paralela em diferentes partes do sistema, acelerando o desenvolvimento e reduzindo os gargalos.

#### Resiliência e tolerância a falhas:
Com a arquitetura distribuída e independente, o sistema pode ser mais resiliente a falhas, já que uma falha em um componente específico não afetará necessariamente todo o sistema.


### Negativos:
#### Complexidade da gestão de múltiplos componentes: 
Com a decomposição do sistema em componentes individuais, surge a necessidade de gerenciar e coordenar esses componentes de forma eficaz. Isso pode aumentar a complexidade operacional e administrativa.
#### Possíveis problemas de integração: 
A independência dos componentes pode tornar a integração entre mais desafiadora, especialmente quando há mudanças ou atualizações num componente que afetam outros componentes relacionados.


## More Information
