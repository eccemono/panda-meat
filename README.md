# Panda Meat Spigot Plugin

A lightweight, high-compatibility Spigot 26.3 plugin that adds custom Panda Meat to the game without requiring any client-side resource packs.

## Specification

- **Compatibility:** Spigot 26.3 (`26.3-R0.1-SNAPSHOT`), pure public Spigot API, zero client resource pack required (reuses vanilla mutton textures).
- **Items:**
  - **Raw Panda Meat:** Custom display name, raw mutton appearance, tagged internally with plugin metadata.
  - **Cooked Panda Meat:** Custom display name, cooked mutton appearance, tagged internally.
- **Drops:**
  - **Baby Pandas:** 0–1 Raw Panda Meat.
  - **Adult Pandas:** 2–3 Raw Panda Meat.
  - **Burning Pandas:** Drops Cooked Panda Meat directly (like cattle dropping steak when burning).
  - **Looting:** Standard strict ranges (no looting multipliers).
- **Cooking:** Can be cooked in Furnaces, Smokers, and Campfires to convert Raw Panda Meat into Cooked Panda Meat.
- **Nutrition:**
  - **Raw Panda Meat:** Nutrition matching raw beef.
  - **Cooked Panda Meat:** Restores 8 hunger points (4 drumsticks) with 14.4 saturation (slightly superior to steak).
- **Behavior:** Normal sheep mutton is entirely unaffected.
