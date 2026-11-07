# Don't Wake the Moon! — Design Rationale

**Premises: Temporality + Feedback**

## Idea

I designed a game where timing matters as much as movement. In *Don't Wake the Moon!*, the player controls a star and tries to save five Golden Dreams without using up the moon's five patience hearts. Moving clouds make the route risky, but earlier actions matter most.

## Combining the premises

I combined **Temporality** and **Feedback** because they depend on each other in this game. A ghost repeats the player's path two seconds later. To unlock a dream, the player first waits on a blue seal so the ghost can repeat that pause. The progress indicator helps the player understand when the seal is opening. Hearts, collected dreams and the shield countdown show the consequences of each decision. Both systems help the player plan.

## Theory

Benford and Giannachi (2008) explain how an interactive experience can involve different paths through time, including what a participant does and how earlier actions can be remembered. This connects to my ghost mechanic: the player's movement becomes a recorded path that returns two seconds later. I used that idea to make the past affect what the player can unlock in the present. Their work concerns shared narratives, whereas my game is single-player.

Norman (2013) emphasizes feedback that helps people understand the results of their actions. This influenced the seal progress indicator, patience hearts, and shield countdown. However, feedback does not guarantee a safe route.

## Design changes and reflection

I revised several rules while developing the game. At first, there were too many clouds, so I reduced them to five and made them move faster. This kept the danger but made the screen easier to read. I also made the shield activate as soon as the player collects it, rather than waiting for the ghost. The ghost became immune to clouds and responsible for unlocking seals. I placed status indicators inside the game. The Quick Echo and Patient Echo modes change only the required seal wait, from 0.5 to 2 seconds. In testing, the participant found Patient Echo harder because moving clouds made waiting near the seal and escaping safely more difficult. They preferred Quick Echo. Waiting changed their planning.

## References

- Norman, D. A. (2013). *The design of everyday things* (Revised and expanded ed.). Basic Books. https://www.hachettebookgroup.com/titles/don-norman/the-design-of-everyday-things/9780465050659/
- Benford, S., & Giannachi, G. (2008). Temporal trajectories in shared interactive narratives. *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems*, 73–82. https://doi.org/10.1145/1357054.1357067

**Game:** https://delfinsaltuk.github.io/dont-wake-the-moon/
