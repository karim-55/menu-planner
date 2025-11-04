### MealMaker — Planificateur de menus

Objectif: Générer un menu de N jours à partir d'un catalogue de recettes et produire une liste de courses agrégée.

#### Installation
- Python 3.11+
- `pip install -r requirements.txt`

#### Utilisation
```bash
python -m mealmaker.cli --recipes data/recipes.sample.json --days 7 --min-vege 2 --max-time 30 --avg-budget 2.5 --output plan.json