The task should take a maximum of 2 hours to complete. Please do
not spend more time than this.

* Prepare this project to be continued on a next round.
* Use Node.js preferably.
* Try to make your code as readable as understandable as possible.

## Technical Assignment

At X, our aim is to give everyone easy acces to anything in their citi. As I'm
sure you know we're experts in bringingthid delicious food to your door. Wouldn't it
be great to accompanny this food with some exotic cocktails?! Your job id to find 
some cocktails and look up the ingredients we need to make them so that we
can include them in your app.

1. Take a look at The Cocktail DB public API [https://www.thecocktaildb.com/api.php](https://www.thecocktaildb.com/api.php).
You can see some example queries in the documentation so check it out a bit.

2. Since we're X, we want to keep our cocktails in theme with the
company. Fetch all the cocktails which have a name beginning with "G".
Check the API documentation on how to do this.

3. Log the names of all the cocktails found as well as the total number.

4. Cocktails should be extravagant, right? Let's just keep the cocktails that
have more than 4 ingredients. Log the name for each of the results,

5. The results are not very easy to read, can you help us to parse the list so it's
a bit easier to read. For each cocktail, we only need the id, name, and an
array of ingredients. Log the results.

6. Ooops, we forgot about the ingredient quantities. Update the parsed list.

7. We want to be able to offer our customers both alcoholic and non-alcoholic
cocktails. Separate the results into two lists based in this. Log the results.

8. Great!. We're done!

## Results

In the end, your results should look like this (doesn't have to match exactly):

```
** Cocktails beginning with G:**
Total: x
Names: "cocktail A", "Cocktail B", ...

**Cocktails with more than 4 ingredients:**
Gin Sour
Gin Daisy
Gin Sling

** Cocktails with just id/name/ingredients:**
{ name: "Cocktail B", id: 47328, ingredients: ["vodka", "apple juice", ...] },
{ name: "Cocktail D", id: 12398, ingredients: ["gin", "tomato juice", ...] }

**Cocktails with ingredient quantities:**
{ name: "Cocktail B", id: 47328, ingredients: [{ name:"vodka", quantity: "1 oz" }, ...] }
{ name: "Cocktail D", id: 47328, ingredients: [{ name:"gin", quantity: "1/2 oz" }, ...] }

**Alcoholic / Non-alcoholic cocktails:**
Alcoholic:
{ name: "Cocktail B", id: 47328, ingredients: [{ name:"vodka", quantity: "1 oz" }, ...] }

Non-Alcoholic
{ name: "Cocktail E", id: 82349, ingredients: [{ name:"lime juice", quantity: "1 oz" }, ...] }
```
