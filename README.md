# AppTechLogistics

# App Cronograma de Entregas - Simulação de Tempo no Euro Truck Simulator 2

## Descrição

Aplicativo Android desenvolvido em Kotlin para cálculo e simulação de tempo de entregas, baseado na mecânica de tempo acelerado do Euro Truck Simulator 2 (ETS2). O app converte o tempo do jogo para o tempo real, calcula a distância percorrida a velocidades médias reais, e estima o valor das entregas considerando tipos de carga.

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)


## Funcionalidades

- Entrada de dados: origem, destino, distância, tempo no jogo (HH:mm ou HH.mm), tipo de caminhão.
- Conversão do tempo do jogo (aceleração 20x) para tempo real.
- Cálculo de distância percorrida em tempo real a 120 km/h.
- Aplicação de bônus percentuais para tipos de carga (frágil, importante, alto valor).
- Estimativa de valor total da entrega.
- Cálculo do tempo mínimo e máximo considerando velocidades entre 70 e 130 km/h.
- Interface amigável e validação de entradas.

## Tecnologias

- Kotlin
- Android SDK
- Layout XML com ScrollView e animações de fundo

## Como usar

1. Informe origem, destino e distância em km.
2. Informe o tempo do jogo no formato HH:mm ou HH.mm (ex: 6:51 ou 6.51).
3. Informe o tipo de caminhão.
4. Selecione os tipos de carga (se houver).
5. Clique em Calcular para visualizar o resultado.

## Resultados apresentados

- Tempo estimado no jogo
- Tempo real aproximado
- Distância real percorrida a 120 km/h
- Valor estimado da entrega
- Tempo estimado real mínimo e máximo

## Contato

Para dúvidas, sugestões ou contribuições: 

- 📧 Email: [joaoigor1103@gmail.com](mailto:joaoigor1103@gmail.com)
- 🔗 LinkedIn: [João Igor](https://www.linkedin.com/in/joao-igor-25b090250/)
---

<img width="350" height="289" alt="Screenshot_2" src="https://github.com/user-attachments/assets/8e348296-bf38-484e-af54-369804fde378" />
<img width="1366" height="767" alt="Screenshot_3" src="https://github.com/user-attachments/assets/65209703-68c6-4ff2-9c7b-59e9431a39ef" />

<img width="237" height="490" alt="Screenshot_5" src="https://github.com/user-attachments/assets/a46a0c8a-50d8-4839-8166-cb783069ba35" />
<img width="227" height="491" alt="Screenshot_6" src="https://github.com/user-attachments/assets/70935c95-7c1c-4eb4-abf4-c0eb692fa97d" />


