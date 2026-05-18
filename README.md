# Sprint_Solu-es_Energias_Renov-veis_Sustent-veis
# ChargeGrid Intelligence

## Integrantes
Matheus Pimenta RM:569400
Leonardo Soares Rodrigues RM:572986 
Rubens Henrique RM 572667
Guilherme Cedro RM: 571050
Gabriel Carvalho RM: 571381

## Visão Geral

O ChargeGrid Intelligence é uma plataforma inteligente de gerenciamento energético desenvolvida para otimizar operações de recarga em eletropostos comerciais, alinhada ao contexto do EV Challenge GoodWe 2026.

A proposta surge diante do crescimento da mobilidade elétrica e dos desafios relacionados ao carregamento simultâneo de múltiplos veículos, que podem gerar sobrecarga elétrica, desperdício energético e aumento dos custos operacionais.

A solução utiliza conceitos de Smart Charging, Internet das Coisas (IoT) e Inteligência Artificial, permitindo monitoramento em tempo real, distribuição dinâmica de potência e gerenciamento inteligente do consumo energético.

Além dos benefícios operacionais, o projeto foi desenvolvido considerando princípios de sustentabilidade e energias renováveis, possibilitando integração futura com sistemas fotovoltaicos e tecnologias do ecossistema GoodWe. Dessa forma, o ChargeGrid Intelligence busca promover maior eficiência energética, redução de impactos ambientais e uma infraestrutura de recarga mais inteligente e sustentável.

## Problema

O crescimento da mobilidade elétrica tem impulsionado a expansão dos eletropostos comerciais em locais como estacionamentos, centros empresariais, shoppings, condomínios e frotas corporativas. No entanto, esse aumento no número de veículos elétricos conectados simultaneamente gera novos desafios relacionados ao gerenciamento energético dessas infraestruturas.

Um dos principais problemas encontrados em sistemas comerciais de recarga é a sobrecarga da rede elétrica causada pela alta demanda energética em horários de pico. Diferentemente dos carregamentos residenciais, onde normalmente existe apenas um usuário utilizando a infraestrutura, os ambientes comerciais precisam atender diversos veículos ao mesmo tempo, aumentando significativamente a potência exigida pela instalação.

A ausência de mecanismos inteligentes para gerenciamento dessa demanda pode provocar distribuição inadequada de energia, desperdício energético, aumento dos custos operacionais e necessidade de investimentos elevados para ampliação da infraestrutura elétrica disponível. Além disso, a falta de monitoramento em tempo real dificulta o controle do consumo individual de cada usuário, comprometendo a eficiência operacional dos eletropostos.

Outro fator relevante é a necessidade de integração entre diferentes carregadores, sistemas de monitoramento e plataformas digitais, permitindo que os dados sejam utilizados para otimização da operação. Sem essa integração, os sistemas podem apresentar baixa escalabilidade e dificuldades no gerenciamento centralizado.

Dessa forma, torna-se necessário o desenvolvimento de soluções capazes de realizar gerenciamento inteligente da energia disponível, garantindo eficiência energética, estabilidade operacional e sustentabilidade na infraestrutura de recarga de veículos elétricos.

## Solução Proposta

Para solucionar os desafios relacionados ao gerenciamento energético dos eletropostos comerciais, foi proposta a criação do ChargeGrid Intelligence, uma plataforma inteligente de gerenciamento e monitoramento de recarga de veículos elétricos integrada ao ecossistema GoodWe.

A solução tem como principal objetivo transformar eletropostos convencionais em ambientes inteligentes capazes de controlar a distribuição energética de forma automática, segura e eficiente. O sistema utiliza conceitos de Smart Charging, Internet das Coisas (IoT) e Inteligência Artificial para realizar o gerenciamento dinâmico da potência disponível.

O funcionamento ocorre em etapas lógicas. Inicialmente, sensores e dispositivos conectados realizam a coleta contínua de dados sobre o consumo energético, quantidade de veículos conectados, potência utilizada e disponibilidade da infraestrutura elétrica. Essas informações são enviadas para uma plataforma central responsável pelo processamento dos dados.

Com base nessas informações, algoritmos inteligentes analisam a demanda energética em tempo real e redistribuem automaticamente a potência entre os carregadores conectados, evitando que a capacidade máxima da rede seja ultrapassada.

Além disso, o sistema também permite monitoramento em tempo real das sessões de recarga, controle individual de consumo, acompanhamento do histórico de utilização e futura implementação de sistemas automatizados de cobrança.

A solução foi projetada considerando princípios de escalabilidade e interoperabilidade, permitindo futuras integrações com equipamentos GoodWe, sistemas fotovoltaicos, armazenamento energético por baterias e plataformas digitais de gerenciamento.

Dessa forma, o ChargeGrid Intelligence busca oferecer uma infraestrutura mais eficiente, inteligente e preparada para atender o crescimento da mobilidade elétrica.

## Sustentabilidade e Energias Renováveis

A proposta do ChargeGrid Intelligence foi desenvolvida com base nos princípios de sustentabilidade, eficiência energética e utilização inteligente de recursos energéticos, buscando reduzir impactos ambientais e contribuir para o desenvolvimento de sistemas de mobilidade elétrica mais sustentáveis.

Um dos principais objetivos da solução é minimizar desperdícios energéticos por meio do gerenciamento inteligente da demanda elétrica. Em sistemas tradicionais, a distribuição inadequada da potência pode gerar consumo excessivo, sobrecargas e utilização ineficiente dos recursos disponíveis. Com o uso de monitoramento contínuo e controle dinâmico da energia distribuída, torna-se possível otimizar o aproveitamento de cada quilowatt disponível.

Outro aspecto importante está relacionado à integração com fontes renováveis de energia. Considerando o contexto do ecossistema GoodWe, a solução foi projetada para possibilitar integração futura com sistemas fotovoltaicos, permitindo que parte da energia utilizada no processo de recarga seja proveniente de fontes limpas e renováveis.

A utilização da energia solar pode reduzir significativamente a dependência da rede elétrica convencional, diminuir custos operacionais e contribuir para redução das emissões indiretas de gases associados à geração energética baseada em combustíveis fósseis.

Além dos benefícios ambientais, a aplicação de sistemas inteligentes também promove sustentabilidade operacional, pois possibilita melhor utilização da infraestrutura existente, reduzindo a necessidade de investimentos em expansão física da rede elétrica.

Dessa forma, o projeto contribui não apenas para a evolução tecnológica dos eletropostos comerciais, mas também para construção de uma infraestrutura energética mais limpa, eficiente e alinhada aos princípios de desenvolvimento sustentável.

## Tecnologias Utilizadas

Para o desenvolvimento do ChargeGrid Intelligence foram selecionadas tecnologias capazes de atender aos requisitos de automação, conectividade, gerenciamento energético e escalabilidade exigidos pelo contexto dos eletropostos comerciais inteligentes.

A arquitetura da solução considera a integração entre dispositivos físicos, sensores e plataformas digitais responsáveis pelo processamento e gerenciamento das informações coletadas.

O ESP32 será utilizado como microcontrolador principal devido à sua capacidade de processamento, conectividade Wi-Fi integrada e facilidade de aplicação em projetos IoT. Esse componente será responsável pela comunicação entre sensores, carregadores e a plataforma de gerenciamento.

Sensores IoT poderão ser utilizados para monitoramento de variáveis relacionadas ao sistema, como corrente elétrica, potência consumida e status das sessões de recarga. A coleta dessas informações permitirá maior controle operacional e suporte à tomada de decisões inteligentes.

Para gerenciamento da comunicação entre dispositivos e plataformas, poderão ser utilizados protocolos abertos como OCPP (Open Charge Point Protocol), permitindo interoperabilidade entre carregadores e sistemas de gerenciamento, independentemente do fabricante.

A solução também considera a utilização de algoritmos de Inteligência Artificial, responsáveis pela análise de padrões de consumo, previsão de demanda energética e otimização automática da distribuição de potência entre os carregadores.

Para visualização dos dados, acompanhamento do consumo e monitoramento das sessões de recarga, poderá ser implementado um dashboard web ou aplicativo integrado ao sistema.

Além disso, a arquitetura foi planejada para permitir futura integração com tecnologias do ecossistema GoodWe, incluindo sistemas fotovoltaicos, armazenamento por baterias e plataformas de gerenciamento energético.

## Impactos Esperados

Impacto Ambiental

O projeto busca reduzir desperdícios energéticos e incentivar o uso de fontes renováveis, contribuindo para diminuição da dependência de fontes convencionais de energia e redução indireta das emissões de carbono.

Impacto Econômico

O gerenciamento inteligente da potência permite reduzir custos operacionais e melhorar o aproveitamento da infraestrutura existente, evitando investimentos imediatos em expansão elétrica.

Impacto Tecnológico

A utilização de sensores, Internet das Coisas e Inteligência Artificial promove maior automação, monitoramento e eficiência operacional dos eletropostos comerciais.
