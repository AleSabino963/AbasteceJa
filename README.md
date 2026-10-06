# ⛽ AbasteceJá

**AbasteceJá** é um aplicativo de celular projetado para transformar a experiência de abastecimento em postos de combustível. O foco principal é a **autonomia total do usuário**: pague pelo app antes mesmo de sair de casa, chegue na bomba, abasteça e vá embora — sem filas, sem maquininhas e sem interagir com nada.

Além da conveniência, o app conta com um ecossistema de **metas e recompensas** estruturado para fidelizar o cliente e incentivar o consumo recorrente na mesma rede de postos.

---

## 🚀 Principais Funcionalidades

### 💳 Pagamento Sem Atrito & Liberação Antecipada
*   **Abastecimento rápido:** O usuário escolhe o valor ou a quantidade de litros diretamente no aplicativo enquanto está a caminho ou parado no posto.
*   **Pix Automatizado:** Integração com APIs bancárias para geração de Pix Copia e Cola ou QR Code com confirmação instantânea (via Webhooks).
*   **Adiantamento de Crédito:** Um sistema de microcrédito ou parcelamento integrado (via provedores de BaaS), permitindo que o usuário parcele o combustível ou pague na próxima fatura do app.
*   **Integração com a Bomba:** Assim que o pagamento é confirmado, o app gera um Token e indica o número da bomba para abastecimento, o próprio sistema do posto libera a bomba correspondente via geolocalização na mesma hora.

### 🏆 Sistema de Metas e Recompensas
Para manter o cliente na sua rede de postos, o app utiliza mecânicas como de um jogos:
*   **Metas Mensais de Consumo:** "Abasteça 80L este mês e ganhe R$ 0,10 de desconto por litro no próximo abastecimento".
*   **Desafios Temáticos:** "Complete 3 abastecimentos no final de semana e ganhe um café expresso na loja de conveniência".
*   **Clube de Níveis/Ranking:** Usuários evoluem de categoria: Ferro, Bronze, Prata, Ouro, Esmeralda e Diamante conforme a recorrência. Níveis mais altos liberam cashback maior e parcerias exclusivas.

### 💡 Ideias Adicionais Inclusas no Escopo
*   **Geofencing:** O aplicativo detecta quando o usuário entra no raio do posto de combustível e envia uma notificação push: *"Detectamos que você está no Posto X. Deseja liberar a bomba 04 agora?"*.
*   **Histórico e Gráficos de Consumo:** Ferramenta financeira interna que mostra a média de consumo de combustível do veículo, gastos mensais e projeções.
*   **Integração com a loja de Conveniência:** Compre itens da loja de conveniência pelo app junto com o combustível e retire pela janela do carro / drive-thru.

---

## 🛠️ Tecnologias Utilizadas

*   **Mobile:** ![Static Badge](https://img.shields.io/badge/React-native?logo=react&logoSize=auto&labelColor=black&color=darkturquoise)
*   **Front-end:** ![Static Badge](https://img.shields.io/badge/Figma-white?logo=Figma&logoColor=White&labelColor=black&color=orange)
*   **Back-end:** ![Static Badge](https://img.shields.io/badge/Python-white?logo=Python&logoColor=White&labelColor=black&color=steelblue)
*   **Banco de Dados:** ![Static Badge](https://img.shields.io/badge/PostgreSQL-passing?logo=postgresql&logoSize=auto&labelColor=black&color=darkblue) ![Static Badge](https://img.shields.io/badge/React-native?logo=redis&logoSize=auto&labelColor=black&color=firebrick)
*   **Integração de Pagamentos:** ![Static Badge](https://img.shields.io/badge/MercadoPagoAPI-passing?logo=mercadopago&logoSize=auto&labelColor=black&color=deepskyblue)

---

## 🏁 Diagramas e Telas
*  [Caso de Uso ](https://github.com/AleSabino963/AbasteceJa/blob/6e766f4a1790894a48ab6f5e2c75e112d0c82445/Diagramas/Caso%20de%20Uso.md)
*  [AbasteceJá no Figma](https://www.figma.com/design/jh5I3sZkDSugKUpsIROcoR/AbasteceJ%C3%A1?node-id=0-1&t=6fPYohsxdcIdkTqX-1)
---

## 🎯 Próximos Passos do Desenvolvimento

1. [ ] Validar a viabilidade técnica de integração com o hardware das bombas (Ex: Concentradores de Bombas Companytec, Telemetria).
2. [ ] Desenhar o protótipo de alta fidelidade das telas (UI/UX).
3. [ ] Criar o MVP (Mínimo Produto Viável) focado exclusivamente no fluxo de Pagamento Pix -> Liberação de Código.
4. [ ] Implementar as regras de negócio da gamificação.

---

Desenvolvido com ☕ por ***Alexandre Vieira Sabino***
