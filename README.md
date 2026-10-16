# Shih Tzu em Busca dos Petiscos
  
## Como jogar
- **Setas** ou **A / D**: correr
- **Espaço**, **W** ou **seta para cima**: pular (segure para pular mais alto)
- Pule **em cima** dos gatos e aspiradores para tirá-los do caminho
- Passe pelo **esguicho** quando a água estiver desligada
**Vitória:** juntar todos os ossinhos, petiscos e patinhas das 2 fases.
**Derrota:** perder todas as vidas (você começa com 3; corações dão vida extra).
 
## Fases
1. **Quintal de casa**: parallax com nuvens, casas, árvores e cerca de madeira
2. **Parque da cidade**: parallax com nuvens, prédios, árvores e grade de ferro
## Como rodar
1. Abra o projeto no Unity.
2. Menu **Shih Tzu › Gerar Jogo (todas as cenas)**.
3. Abra `Assets/Scenes/Menu.unity` e aperte **Play**.
## Estrutura
- `Assets/Resources/Sprites/`: sprites em pixel art (16 px por unidade)
- `Assets/Scripts/`: jogador, inimigos, itens, HUD, menu e tela final
- `Assets/Scripts/Editor/LevelMaps.cs`: mapas das fases em texto (edite e gere de novo)
- `Assets/Scripts/Editor/GameBuilder.cs`: monta cenas, prefabs e tiles
## Pontuação
| Item / ação | Pontos |
|---|---|
| Ossinho | 100 |
| Patinha | 50 |
| Petisco | 25 |
| Pisar num inimigo | 50 |
