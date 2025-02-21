# Heineken-InteligenciaArtificialAplicadaDadosCopilot

# 🚗 Sistema de Gerenciamento de Oficina Mecânica  

## 📝 Descrição do Projeto  

Este repositório contém o esquema conceitual de um sistema para controle e gerenciamento de ordens de serviço em uma oficina mecânica. O objetivo do projeto é modelar as entidades, relacionamentos e atributos necessários para o funcionamento da oficina, garantindo rastreabilidade e eficiência na execução dos serviços.  

## 🔍 Escopo do Sistema  

O sistema deve permitir o registro de clientes, veículos, ordens de serviço (OS), mecânicos e os serviços executados. A modelagem considera os seguintes pontos:  

- 👨‍🔧 Os clientes levam seus veículos para conserto ou revisão periódica.  
- 🚘 Cada veículo é associado a uma equipe de mecânicos, que diagnostica e registra os serviços a serem realizados.  
- 🛠️ Os serviços e peças utilizados são registrados na OS e devem ser aprovados pelo cliente antes da execução.  
- 💰 O custo total da OS é calculado com base na mão de obra e no valor das peças utilizadas.  
- 🏅 Os mecânicos responsáveis pela execução possuem especialidades registradas no sistema.  
- 📊 O status da OS acompanha a evolução do serviço até sua conclusão.  

## 🗂️ Estrutura do Banco de Dados  

O esquema conceitual inclui as seguintes entidades principais:  

1. **👤 Cliente** – Armazena informações dos clientes que utilizam a oficina.  
2. **🚗 Veículo** – Associado a um cliente, contendo informações como modelo, placa e ano.  
3. **📄 Ordem de Serviço (OS)** – Contém os serviços aprovados, valores e status.  
4. **🛠️ Mecânico** – Identificado por código, nome, endereço e especialidade.  
5. **👨‍🔧 Equipe** – Conjunto de mecânicos responsáveis por uma OS.  
6. **🔧 Serviço** – Descrição das atividades realizadas e seu custo de mão de obra.  
7. **🛒 Peça** – Itens utilizados nos reparos, associados à OS.  
8. **💵 Tabela de Referência de Mão de Obra** – Define os valores cobrados por serviço.  

Caso sejam necessárias informações adicionais para refinar o modelo, ajustes poderão ser feitos conforme o contexto operacional da oficina.  

## 📜 Licença  
Este projeto é aberto para estudo e melhorias. Contribuições são bem-vindas.  

