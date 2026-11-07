# Don't Wake the Moon! — Design Rationale

**Premises: Temporality + Feedback**

## Idea

I designed a game where timing matters as much as movement. In *Don't Wake the Moon!*, the player controls a star and tries to save five Golden Dreams without using up the moon's five patience hearts. Moving clouds make the route risky, but the main challenge is thinking about what the player's earlier actions will cause next.

## Combining the premises

I combined **Temporality** and **Feedback** because they depend on each other in this game. A ghost repeats the player's path two seconds later. To unlock a dream, the player first waits on a blue seal so the ghost can repeat that pause. The progress indicator helps the player understand when the seal is opening. Hearts, collected dreams and the shield countdown show the consequences of each decision. The player needs both the delayed movement and the visible information to plan the next move.

## Theory

Vallgårda et al. (2015) describe time as something designers can shape through interaction. This helped me treat waiting and replaying a path as gameplay rules, not just visual effects. One limitation is that a delay can feel confusing when its purpose is not obvious. Norman (2013) discusses how feedback helps people understand what a system is doing. That idea influenced the seal indicator and the visible shield timer. However, feedback cannot remove every difficulty: the player still has to decide when it is safe to move between clouds.

## Design changes and reflection

I revised several rules while developing the game. At first, there were too many clouds, so I reduced them to five and made them move faster. This kept the danger but made the screen easier to read. I also made the shield activate as soon as the player collects it, rather than waiting for the ghost. The ghost became immune to clouds and responsible for unlocking seals. Finally, I placed the hearts, dream counter and shield status inside the game area. The Quick Echo and Patient Echo modes change only the required seal wait, from 0.5 to 2 seconds. In testing, the participant found Patient Echo harder because moving clouds made waiting near the seal and escaping safely more difficult. They preferred Quick Echo, which felt more manageable. This showed how waiting changes planning.

## References

- Norman, D. A. (2013). *The design of everyday things* (Revised and expanded ed.). Basic Books. https://www.hachettebookgroup.com/titles/don-norman/the-design-of-everyday-things/9780465050659/
- Vallgårda, A., Winther, M., Mørch, N., & Vizer, E. (2015). Temporal form in interaction design. *International Journal of Design, 9*(3). https://ijdesign.org/index.php/IJDesign/article/view/2212/710

**Game:** https://delfinsaltuk.github.io/dont-wake-the-moon/
