# Backtest Replay PRO V2
Plateforme de simulation de trading avec replay historique.

### Inclus
- Replay 0.5x à 5x
- Bougie suivante/précédente
- Départ historique ou aléatoire
- BUY/SELL
- SL/TP
- Risque en %
- Taille de position calculée à partir du risque et de la distance SL
- Spread et commission simulés
- RR prévu
- Equity, profit, win rate, profit factor, R, drawdown
- Courbe d'équité
- Journal et export JSON
- Import CSV réel
- XAUUSD / EURUSD / BTCUSD
- Aucun ordre réel

### CSV
Colonnes : time (ou date), open, high, low, close.
Le CSV doit contenir des données historiques réelles si l'objectif est de mesurer une stratégie.

### Limites V2
La version ne gère pas encore les tick-by-tick, plusieurs positions simultanées, trailing stop, sessions avancées, optimisation automatique ni données historiques intégrées.
