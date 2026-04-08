# Playbooks — day-trip

> CLI command sequences. Knowledge is for parameter mapping — never answer without executing.

---

## Playbook A: City Day Trip

**Trigger:** "one day in {city}"

```bash
flyai search-poi --city-name "{city}" --poi-level 5
flyai search-poi --city-name "{city}" --category "{interest}"
```

**Output emphasis:** Full day city exploration.

---

## Playbook B: Nearby Day Trip

**Trigger:** "day trip from {city}"

```bash
flyai search-poi --city-name "{nearby}" --poi-level 5
```

**Output emphasis:** Day trip to nearby destination.

---

## Playbook C: Theme Day

**Trigger:** "museum day"

```bash
flyai search-poi --city-name "{city}" --category "博物馆"
```

**Output emphasis:** Theme-focused single day.

---

