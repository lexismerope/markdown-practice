# markdown-practice

## Project Secret


## Back-cover blurb
    When dark‑robed students from a Voidwright Institute  burn her village and abduct her mother, a daughter of a nonbinary sea deity is forced into the divine world, where she must master her rising powers, uncover the truth of her missing parent, and confront a prophecy that declares she will either save the world or let it be remade in darkness.

## Character information

### Main characters
- Lirienne
  - The protagonist of Project Secret. She is exploring her newfound identity as a half-blood. While the Sanctum students use "Spells" (rigid, structured). **Lirienne's magic should be Relational.** **She doesn't "cast" water;** *she asks it, or becomes it.* This highlights the difference between the "thief" gods and her parent.
  - Traits: Resilient, intuitive, impulsive, and deeply protective. She has a natural affinity for water but lacks the "refined" control taught at the Sanctum.
  - Motivations: Primarily driven by the need to rescue her mother. Secondarily, she wants to understand her nonbinary parent's legacy and why they were erased from history.
- The Arch-Voidwright *the antagonist*
  - Traits: Dogmatic, power-hungry, and manipulative. They view the world as "broken" and see the forgotten deities as raw fuel for their own ascension.
  - Motivations: To trigger the "remake in darkness" part of the prophecy. They believe the current world is stagnant and only the Void can "purify" it.

### Supporting characters

1. Elowen
   - Traits: Gentle, observant, and grounded. She's the "emotional glue" of the group.
   - Motivations: To find a place where she belongs. As a daughter of a forest deity, she feels the "wilting" of the world and wants to restore the natural balance.
   - Role: The Confidante. She helps Lirienne navigate the social hierarchy of the Sanctum.
2. Kaelen
   - Traits: Disciplined, arrogant(initially), and studious. He is a perfectionist who hides his insecurities behind rules.
   - Motivations: To uphold the "order" he was taught. He fears that if the forgotten gods return, his own status and the world's safety will vanish.
   - Role: The Rival-to-Ally. He provides the historical context Lirienne lacks, even if he delivers it with a sneer at first.
3. Vaelora
   - Domain: Weather and Guidance, Storms, Rain
   - Personality: Brave, Restless and Empathetic
   - Role: Lirienne's guide on her journey to the Aetherwave Sanctum.

https://ellipsus.com/read/7FAURYhQGc4jWvHhaGzq4M/Project-Secret-for-public

```python
import datetime
from pathlib import Path

DAILY_GOAL = 500
def tally_daily_scrolls():
    today = datetime.date.today()
    words_today = 0

    for scroll in MANUSCRIPT_DIR.glob("*.md")
        modified_date = datetime.date.fromtimestamp(scroll.stat().st_mtime)
        if mofied_date == today:
            text = scroll.read_text(encoding="utf-8")
            words_today += len(text.split())

    remaining = max(0, DAILY_GOAL - words_today)
    bar_filled =min(20, int((words_today / DAILY_GOAL) * 20))
    progress_bar = "█" * bar_filled + "░" * (20 - bar_filled)

    print(f" Chronicle Date : {today}")
    print(f" Ink Spilled : {words_today} / {DAILY_GOAL} words [{progress_bar}]")
    if words_today >= DAILY_GOAL:
        print(f" Quest Complete! (+{words_today - DAILY_GOAL} bonus words added to the tome)")
    else:
        print(f" Keep writing : {remaining} words remain before the inkwell dries.")
if __name__ == "__main__":
    tally_daily_scrolls()
```
