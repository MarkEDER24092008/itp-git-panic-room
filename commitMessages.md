# "Commit Master"

## Klassifizierung von Commit Messages:
#### Klassifizierung – Legende
        ✓: Gute Message
        ✗: Schlechte Message  
---

#### Messages:
- Update: ✗
- Fix bug: ✗ **– Grenzfall: Positiv, jedoch sollte der Bug mit einem Reizwort beschrieben werden**
- Add login validation: ✓
- stuff: ✗
- Refactor Calculator for readability: ✓
- Changes in app: ✗
- Remove unused imports: ✓
- final version: ✗
- Improve performance: ✓ **– Grenzfall: Im Prinzip positiv, jedoch beschreibt es nicht, was an Performance verbessert wurde (e.g: Runtime)**
- Fix issue #23: ✓ *- Begründung: Es gibt genaue Fehlernummer an, wobei man direkt die Änderungen zurückverfolgen kann*
- Refactor code: ✗
- Add null check: ✗
- Cleanup: ✗ *- Begründung: Es beschreibt nicht den aufgeräumten Inhalt, daher ist es eine schlechte Message*
- Update Calculator: ✗
- Handle edge cases: ✗ **– Grenzfall: Verbessert zwar Einzelheiten am Projekt, werden jedoch nicht beschrieben**
- Small fixes: ✗ 
- Rename variables: ✗
- Adjust logic: ✗ **– Grenzfall: Gute Änderung, jedoch wird keine Änderung beschrieben**
- Temporary fix: ✗
- Improve readability: ✓ *– Begründung: Da es generelle Lesbarkeit eines Codes verbessert, benötigt es keine detallierte Beschreibung*
---

## Regeln für Commit -Messages:

    1. Messages sollten sich im breitesten Rahmen um den Inhalt enthalten
    2. Messages sollten ein bestimmtes 'Blueprint' folgen  (Beispiel: "Code - Style Anpassung"), wenn keine fixe Beschreibung angegeben werden kann
    3. Bei repetiven Messages einen eigenen Branch mit einer sinvollen End-Message erstellen