# Projeto Vortex-01

[![en-us](https://img.shields.io/badge/lang-pt--BR-green.svg)](README.md)
[![es](https://img.shields.io/badge/lang-es-red)](README.es.md)
[![fr](https://img.shields.io/badge/lang-fr-blue)](README.fr.md)
[![ru](https://img.shields.io/badge/lang-ru-yellow.svg)](README.ru.md)

## Objetivo
Criar um satélite de baixo custo, chamado Vortex-01, que fornece uma rede Wi-Fi gratuita através de uma conexão via satélite. O satélite será equipado com sensores, sistemas de energia e um sistema de segurança remoto.

## Especificações do Satélite

- **Nome:** Vortex-01
- **Função:** Fornecer internet gratuita via satélite

### Componentes Principais

- **Raspberry Pi 4B:** Computador central para processamento de dados e controle.
  
### Sensores

- **Sensor de Pressão Atmosférica:** **BMP180** - Sensor acessível para medir pressão e altitude.
- **Sensor de Aceleração (IMU):** **MPU-6050** - Combina acelerômetro e giroscópio, ideal para monitorar movimento e orientação.
- **Sensor de Radiação:** **RADFET** - Opcional, para monitoramento de exposição à radiação de forma econômica.

### Antenas

- **Antena Dipolo de Banda Larga:** Antena dipolo caseira para comunicação de RF de baixo custo.
- **Antena Yagi:** Antena Yagi DIY para melhorar a direção e o ganho da comunicação, construída com materiais acessíveis.

### Sistemas de Energia

- **Painéis Solares:** **Painéis Policristalinos** - Econômicos e suficientes para geração de energia em pequenos projetos espaciais.
- **Controlador de Carga Solar:** **Controlador PWM** - Solução acessível para gerenciamento básico de carga de painéis solares.
- **Bateria:** Baterias de carro ou **baterias 18650 recondicionadas** - Alternativa barata para armazenamento de energia, utilizando baterias reutilizadas de laptops antigos.

### Controle Térmico

- **Mantas Térmicas:** **Mantas de Mylar** - Solução barata para isolamento térmico, usando materiais leves e refletivos.

### Sistema de Propulsão

- **Propulsores de Gás Frio:** Propulsores DIY utilizando garrafas de CO2 de paintball, válvulas de liberação, para manobras seguras e econômicas.

### Sistemas de Navegação e Controle

- **GPS:** **Módulo GPS NEO-6M** - Módulo GPS acessível, adequado para navegação básica e rastreamento de posição.

## Sistema de Segurança

- **Função:** Desativar o sistema de combustível e ativar um paraquedas gigante em caso de falha ou perigo.
- **Mecanismo:** Ativado remotamente para garantir a segurança em caso de falha crítica.

## Software

- **Desenvolvimento:** Utilização de Ubuntu, Python, C, Assembly, e Java
- **Comunicação:** Via sinais RF

### Recursos

- Código para o gerenciamento de sensores
- Código para comunicação e transmissão de dados
- Código para o sistema de segurança

## Design do Satélite

- **Estrutura:**
  - **Formato:** Compacto e leve, utilizando aço e alumínio
  - **Painéis Solares:** Para geração de energia
  - **Bateria:** Bateria de carro ou baterias 18650 para armazenamento de energia

## Lançamento

- **Preparação:** Montagem no local de lançamento
- **Combustível:** Gasolina será adicionada no local de lançamento
- **Procedimentos de Segurança:** Distância segura e acionamento remoto do sistema de segurança

### Planejamento do Lançamento

- **Fase de Montagem:** Montar o satélite e adicionar o combustível no local de lançamento
- **Acionamento Remoto:** Sistema de segurança ativado remotamente para cortar o combustível e abrir o paraquedas em caso de emergência

## Repositórios

- **Modelo 3D:** [GitHub - Vortex-01 Model](https://github.com/Vortex-01/Model)
- **Código Fonte:** [GitHub - Vortex-01 Source Code](https://github.com/Vortex-01/Source-Code)

## Objetivo de Reconhecimento

- **Meta:** Usar o projeto Vortex-01 como uma vitrine para demonstrar habilidades técnicas e inovadoras, visando atrair a atenção de instituições como o MIT.
