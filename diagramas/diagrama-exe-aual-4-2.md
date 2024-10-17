
```mermaid
SequenceDiagram
flowchart TD
    Start[Início do Jogo] --> RollDice[Rolar Dado de 6 Faces]
    RollDice --> |Número de Movimentos| Move[Movimentar no Tabuleiro]
    Move --> |Obstáculo| Obstacle[Encontrar Obstáculo]
    Obstacle --> |Número 6 no Dado| Destroy[Destruir Obstáculo]
    Obstacle --> |Portal Vermelho| RedPortal[Portal Vermelho]
    Obstacle --> |Portal Azul| BluePortal[Portal Azul]
    RedPortal --> LowerPart[Parte Inferior do Tabuleiro]
    BluePortal --> UpperPart[Parte Superior do Tabuleiro]
    Destroy --> Move
    Move --> |Casa Adjacente ao Objetivo| Action[Ação Ativada]
    Action --> |Chave| Key[Obter Chave]
    Key --> |Abrir Porta| OpenDoor[Abrir Porta]
    OpenDoor --> End[Objetivo Alcançado]
```