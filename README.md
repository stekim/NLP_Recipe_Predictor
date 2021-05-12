# Auto Encoder - NLP autoencoder to predict ingredients for a given recipe name

In this project, I look at how a Sequence to Sequence model can be used to predict what 
food ingredients are needed for a given recipe. 

Example: “Chile con Carne” 
Ground Truth: “ground beef, onions, salt, olive oil, chili peppers, oregano, water, beans”
Predicted: “ground beef, beans, onions, salt, oil, peppers, oregano, water"

```
search('chicken pot pie')
dist: 1.02
boneless skinless chicken breasts, margarine, water, ritz cracker crumbs, parmesan cheese, cream of chicken soup, sour cream, mushrooms

dist: 1.02
chicken fat, onions, carrot, celery, green pepper, apple, chicken broth, all-purpose flour, canned tomato, salt, pepper, curry powder, cooked chicken

dist: 1.03
boneless skinless chicken breasts, "aunt janes krazy mixed up salt", olive oil, onion, cream of mushroom soup, cream of chicken soup, sour cream, ritz cracker, butter

dist: 1.03
milk, flour, cream of mushroom soup, dry onion soup mix, margarine, chicken

dist: 1.03
chicken breasts, mushroom soup, white wine, milk, pepperidge farm stuffing

```
```
search('iced tea')
dist: 1.02
limoncello, vodka, cranberry juice

dist: 1.02
cranberries, vodka

dist: 1.03
triple sec, grand marnier, light rum, orange juice, creme de almond

dist: 1.03
vodka, pomegranate liqueur, unsweetened cranberry juice

dist: 1.03
rum, chambord raspberry liquor, apple juice
```
```
search('chocolate chip cookie')
butter, graham cracker crumbs, sweetened condensed milk, butterscotch chips, semi-sweet chocolate chips, flaked coconut, nuts

dist: 1.01
graham cracker crumbs, butter, sweetened condensed milk, semi-sweet chocolate chips, milk chocolate chips, vanilla extract, pecans

dist: 1.01
butter, graham cracker crumbs, coconut, butterscotch chips, semi-sweet chocolate chips, sweetened condensed milk, nuts

dist: 1.01
butter, graham crackers, chocolate chips, butterscotch chips, coconut, walnuts, condensed milk

dist: 1.01
butter, graham wafer crumbs, sweetened flaked coconut, chocolate chips, butterscotch chips, sweetened condensed milk, walnuts
```
