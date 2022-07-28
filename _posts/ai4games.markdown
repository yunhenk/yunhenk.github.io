---
layout: post
title:  "AI For Games"
color:  teal
width:   6 
height:  1
date:   2022.07.28
categories: jekyll update
---
# Knowledge - Ai4Game

## BotAI

早期主要的思想是行为主义的，即只要bot的行为看起来智能即可。

- move
    - Path finding
        - representation: 
            - Grid
            - Waypoint
            - NavMesh
            - Voxel
        - algo: 
            - A*
            - ==improved A*==: 
                - IDA*
                - RTA*
                - D-Lite *
            - hierarchical A*
            - ==Jump Point Search==
            - Dijkstra, Floyd-Warshall
        - path smoothing
    - steering
        - seek, flee, wander, pursue, obstacle avoidance, collision avoidance
        - flocking
        - formation
- sensing - knowledge
    - internal state
    - static env
    - dynamic spatial
        - influence map
    - entity - specific
- (intelligent) behavior
    - designed behavior
        - FSM
        - BT
        - HTN
    - search / planning
        - GOAP
            - A*
        - MCTS 
            - 适合turned based game, 如GO,Civilization
            - pacman这类也可以，需要精心设计[AI and Games P48]
    - learning
        - RL
- intelligent chating/dialog
- what is future
    - 智能，个性，emotional, has own life and story
        - more characteristic[独特，个性，风格化]
    - human bot more human like
        - 建模，表情，肢体语言
        - speech, talking
        - unreal-metahuman
    
## PCG

- high level
    - 世界设定，背景故事
    - ==游戏规则==
- middle level [environment]
    - terrian, ecology
    - maze, dungeons
    - city, building
- detail level
    - trees, guns, animals,道具..
    - npc
        - model, looklike
        - action(what it can do) 
        - ==story, talking==
    - effects
- other
    - animation ..

## 其他

- 三维视觉
- animation
- physics
- CG
    - autolod..

