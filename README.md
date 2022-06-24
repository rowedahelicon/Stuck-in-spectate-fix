# Stuck in spectate fix [SourceMod]
Corrects unassigned/spectate glitch when players join a team simultaneously

When a group of players try and join a team at once, like during a map switch, the game may bug out and leave them stuck in an unassigned team.
This is normally fixed by means of using the jointeam X command, the spectate command, or sometimes trying motd and going through the motd menu.

This mod solves this issue by detecting if a player is trying to join a team that would become unbalanced and forcing open their team selection window again.
