# Tic-Tac-Toe MCTS (Máquina vs Máquina)

Simulador de **Gato (Tic-Tac-Toe)** con **Monte Carlo Tree Search (MCTS)**, jugando **máquina vs máquina**.  
Permite variar **rollouts por turno** y el **peso de exploración (UCT)** para observar cambios en resultados (ganas/empates) y estilo.

## Requisitos
- Python 3.9+  
- Solo usa librerías estándar (no requiere instalar paquetes).

## Archivos
- `gato_mvm.py` — Implementación del juego y MCTS, con:
  - Agentes X y O controlados por MCTS.
  - Parámetros de configuración arriba del archivo.
  - Helpers para correr **experimentos por lotes** y obtener métricas.
