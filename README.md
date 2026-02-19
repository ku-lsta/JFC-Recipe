# JFC-Recipe: A Dataset for Nutrient Estimation from Japanese User-Generated Cooking Recipes

Japanese Food Composition Recipe (JFC-Recipe) is a novel dataset for nutrient estimation from recipes.
- based on 1,985 Japanese recipes from [Cookpad dataset](https://www.nii.ac.jp/dsc/idr/cookpad/) (in Japanese).
- each ingredient corresponds to a food item in [the Standards Tables of Food Composition in Japan (日本食品標準成分表)](https://www.mext.go.jp/a_menu/syokuhinseibun/mext_01110.html) (in Japanese).

## Annotation files

- annotation.csv
  - recipeID: recipe ID in the original dataset
  - Num. of servings: number of servings of the recipe
  - ID: food item ID
  - Food name: name of the food item
  - Amount: amount of the ingredient
  - Unit: counting unit of the ingredient
- conversion.csv
  - ID: food item ID
  - Food name: name of the food item
  - 無単位 ... g
    - gram per unit
    - "-1" means the (food item, unit) pair is not annotated

## Citing JFC-Recipe (TBA)

```
@inproceedings{shirai2026jfc-recipe,
  title={JFC-Recipe: A Dataset for Nutrient Estimation from Japanese User-Generated Cooking Recipes},
  author={Shirai, Keisuke and Yamakata, Yoko and Kameko, Hirotaka and Sunto, Akiko and Harashima, Jun and Mori, Shinsuke},
  booktitle={Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  year=2026,
}
```
