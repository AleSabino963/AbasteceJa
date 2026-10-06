```mermaid
graph BT
    subgraph App AbasteceJá
        UC1((Cadastrar/Login))
        UC2((Pagar Abastecimento))
        UC3((Pague Depois))
        UC4((Loja de Conveniência))
        UC5((Metas e Desafios))
        UC6((Minha Conta))
        UC7((Histórico e Consumo))
        UC8((Meu Ranque))
        UC9((Configurações))
    end

    Usuário((Usuário))

    %% Ações do Usuário

    Usuário --> UC1
    UC1 --> UC2
    UC1 --> UC3
    UC1 --> UC4
    UC1 --> UC5
    UC1 --> UC6

    UC6 --> UC7
    UC6 --> UC8
    UC6 --> UC9

%% Objetivo futuro: Alinhar
