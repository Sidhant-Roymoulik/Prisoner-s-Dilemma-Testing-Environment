# Prisoner's Dilemma Testing Environment

Testing environment setup with some basic strategies for the Iterated Prisoner's Dilemma with No State.

##  Parameters

Copies - Number of copies of a single strategy present in the tournament.

Rounds - Number of rounds to play between two strategies in a match.

## Strategies Implemented

All C - Always cooperate

All D - Always defect

Random - Randomly choose between cooperate and defect

Tit For Tat - Cooperate on the first move. Use the opponent's previous move for the current move.

Tit For 2 Tats - Cooperate on the first move. Defect twice if the opponent defects once.

2 Tits For Tat - Cooperate on the first two moves. Defect if the opponent defects twice in a row.

Slow TFT - Cooperate on the first two moves. If the opponent makes two of the same move, copy, otherwise use my previous move.

Majority - Defect if the opponent has defected more than they have cooperated.

Pavlov - Cooperate on the first move. If the opponent makes the same move as us, cooperate, otherwise defect.

Punisher - Cooperate until the opponent defects once. Then only defect.

Mistrust - Defect on the first move. Use the opponent's previous move for the current move.

Prober - Cooperate on the first move and defect on the next two. If the opponent responded to the defects with C, defect, otherwise use their previous move.