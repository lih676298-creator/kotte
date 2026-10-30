# Bomberman World — [Super Bomberman]

**Student:** [Huishan Li]

## How to play

- **Controls:** [WASD--> movement; Space--> place bombs; R--> restart the game; Q/ESC--> quit the game]
- **Objective and rules:** [Win by eliminating all enemies using bombs. Lose if the player touches an enemy or is caught in a bomb blast.]
- **Configurations / demo setup:** [default]

## Features and validation

| 1. Player damage and death | [what I tested, what I observed, and whether it matched the expected behaviour] |
| 2. Round states and objective | [what I tested, what I observed, and whether it matched the expected behaviour] |
| [# and name of chosen extension 1] | [what I tested, what I observed, and whether it matched the expected behaviour] |
| Feature                          | Check, observed result, and expected behaviour                                                                                                                                                                                                 |
| 3. Safe restart                  | [When I lost the game and pressed R, the game restarted successfully, everything was reset, and all leftover trace from the previous run was cleaned up.]                                                                                      |
| 4. Solid bombs with owner escape | [When I dropped a bomb, it acted like a wall and successfully blocked both my path and the enemy's, and only one bomb can be placed on this tile.]                                                                                             |
| 5. Blast-range pickup            | [After creating a power-up, it appears on the map, but the player can't pick it up and the boost isn't applied, which is not the expected behavior.]                                                                                           |
| 6. Multiple bombs per owner      | [I set the maximum bomb count to 5. Before any of the 5 bombs explode, I cannot place a 6th bomb, which matches the expected behavior.]                                                                                                        |
| 7. Chain reactions               | [I placed a second bomb within the blast radius of the first one, and it was successfully triggered early by the first bomb's explosion while still on its countdown, causing both bombs to detonate together. This is the expected behavior.] |
| 11. Scoring and combos]          | [When I kill an enemy and secure another kill within my set 3-second window, the combo count increases. If I fail to get another kill within that 3 seconds, the combo resets to x1. This is the expected behavior.]                           |

**Known issues:** [None known after testing]

## Sources and assistance

This project builds on the shared Kotte foundations.

[All my help comes from my good friends. We basically have online study sessions on Discord every day.]

