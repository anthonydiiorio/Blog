---
title: "Anthony's Pizza Dough"
date: 2022-08-10T00:00:00-04:00
draft: false
description: "My foolproof pizza dough for a home oven."
tags: ["Pizza","Food","Recipe"]
aliases:
    - /pizza
cover:
    image: "Pizza-2.jpg"
    alt: "The greatest pizza of all time"
    relative: true # To use relative path for cover image, used in hugo Page-bundles
---

After months of experimentation, I have finally published my pizza dough recipe! This foolproof dough makes delicious pizzas at home. I hope you enjoy it as much as I do!

## Recipe

🕐 Prep time: 30 minutes · 🕐 Cook time: 6 minutes · 🍕 Yield: {{< rawhtml >}}<span id="yield">4</span>{{< /rawhtml >}} pizzas

| Ingredients   | Bakers % | Grams |
| ------------- | -------: | ----: |
| Flour (AP/Bread) | 100%  | {{< rawhtml >}}<span id="flour">608</span>{{< /rawhtml >}} |
| Water         | 60%      | {{< rawhtml >}}<span id="water">365</span>{{< /rawhtml >}} |
| Yeast (IDY)   | 0.50%    | {{< rawhtml >}}<span id="yeast">3</span>{{< /rawhtml >}} |
| Salt          | 2%       | {{< rawhtml >}}<span id="salt">12</span>{{< /rawhtml >}} |
| Oil           | 2%       | {{< rawhtml >}}<span id="oil">12</span>{{< /rawhtml >}} |
| Total         |          | {{< rawhtml >}}<span id="total">1000</span>{{< /rawhtml >}} |

{{< rawhtml >}}
    <label for="numBalls" style="padding-right: 0.2em;">Number of Dough Balls:</label>
    <input type="number" id="numBalls" value="4" min="1" oninput="calculateIngredients()" style="width:80px; font-weight: bold;">
{{< /rawhtml >}}

**Makes {{< rawhtml >}}<span id="doughBalls">4</span>{{< /rawhtml >}} x 12" 250g dough balls**

{{< rawhtml >}}
       <script>
        function calculateIngredients() {
            const numBalls = document.getElementById('numBalls').value;
            const doughWeight = 250; // Weight of each dough ball in grams
            const totalDoughWeight = numBalls * doughWeight;
            const flour = totalDoughWeight / (1 + 0.60 + 0.005 + 0.02 + 0.02);
            const water = flour * 0.60;
            const yeast = flour * 0.005;
            const salt = flour * 0.02;
            const oil = flour * 0.02;
            const totalWeight = flour + water + yeast + salt + oil;
            document.getElementById('flour').textContent = Math.round(flour);
            document.getElementById('water').textContent = Math.round(water);
            document.getElementById('yeast').textContent = Math.round(yeast);
            document.getElementById('salt').textContent = Math.round(salt);
            document.getElementById('oil').textContent = Math.round(oil);
            document.getElementById('total').textContent = Math.round(totalWeight);
            document.getElementById('doughBalls').textContent = numBalls;
            document.getElementById('yield').textContent = numBalls;
        }
        // Initial calculation
        calculateIngredients();
    </script>
{{< /rawhtml >}}

[Print PDF 🖨️](pizza.pdf)

### Instructions 🍕

1. Mix the water, yeast, flour, and salt until fully incorporated
2. Add the olive oil after the flour is fully hydrated
3. Mix until the dough starts to become smooth and elastic
4. If the dough is tough, let it rest for 5-10 minutes to relax the gluten, then continue mixing until smooth.
5. Cover the bowl and let the dough  rise for 2-3 hours or until doubled in size. Weigh and form dough balls. Store in oiled, individual containers or in a proofing box. Refrigerate the dough balls for 1 to 7 days. Remove from the fridge 2-3 hours before baking.

### Baking 👨‍🍳

* Preheat the oven to its highest setting. My oven goes to 555°F.
* **Pizza Stone**: bake for 5-6 minutes or until golden

## Photos 📷

![Always use a scale!](Pizza-3.jpg)

I start by measuring the water, yeast, flour and salt. In that order.

Always use a scale, if you see a pizza or bread recipe with measuring cups and spoons throw it in the trash! Using measuring cups can cause unnecessary variation and uncertainty.
 
![Mixing](Pizza-4.jpg)

Mixing the water, yeast and flour.

![A touch of olive oil](Pizza-6.jpg)

Add the olive oil after the flour and water have been incorporated. If the dough is tough at this stage I stop mixing and let the gluten relax for 5-10 minutes.

![Dough balls](Pizza-7.jpg)

Finally weigh and form the dough balls. Place in individual oiled containers or a proofing box. Into the fridge for a few days to cold ferment!

![Ready to launch](Pizza-1.jpg)

My assembled pizza on the peel ready to launch. Be generous with the flour or semolina on the peel so it doesn't stick and throw all your toppings into your oven (Don't ask me how I know).

![Pizza](Pizza-2.jpg)

6 minutes later we have an excellent homemade pizza! Enjoy 😊

---

### Notes 📝

#### Yeast

I use Instant Dry Yeast (IDY)

#### Flour

For a home oven I recommend bread flour or all purpose flour (AP).   

#### Salt

Salt helps gluten development and slows fermentation. We want the dough to ferment slowly in the fridge. More time fermenting equals better flavour and aromas. 

2% is the ideal amount of salt.

#### Oil

Oil (fat) weakens gluten, reduces stickiness, and speeds up cooking for better crust. Oil should be added near the end of the mixing process. Oil should **never** be added to raw flour as it will coat the flour and inhibit the water from hydrating it. 

#### Water

The amount of water can vary depending on the flour. This is something you can adjust if your dough is too sticky or too dry. Higher hydration will make bigger bubbles, but at the expense of more time in the oven. Expect the crust to be crispier. Lower hydration will bake slightly faster and have a nice soft, dense, chewy texture. It's also easier to handle.


### A side note 📝

If you use about 500g of dough you can make a really delicious and fluffy focaccia or a fantastic Sicilian red pizza. Just bake it a little longer.

![Focaccia](focaccia-min.jpg)

---

### Changelog

`2022-11-28:` Reduced hydration to 60% and oil to 2%. I find the dough easier too work with and less sticky. Cook time is also reduced by 1 minute.

`2024-05-16:` Added pizza dough calculator ✨

{{< rawhtml >}}
<script type="application/ld+json">
{
	"@context": "http://schema.org/",
	"@type": "Recipe",
	"name": "Anthony's Pizza Dough",
	"image": [
		"https://diiorio.me/posts/pizza/Pizza-2.jpg"
	],
	"recipeCategory": "dinner",
	"recipeCuisine": "Italian",
	"prepTime": "PT30M",
	"cookTime": "PT6M",
	"totalTime": "PT1H",
	"recipeYield": "4",
	"datePublished": "2024-07-08",
	"description": "After months of experimentation, I have finally published my pizza dough recipe! This foolproof dough makes delicious pizzas at home. I hope you enjoy it as much as I do!",
	"keywords": "pizza, dough, italian",
	"author": {
		"@type": "Person",
		"name": "Anthony DI Iorio"
	},
	"recipeIngredient": [
		"608g of Flour (All Purpose/Bread Flour)",
		"365g of Water",
		"3g of Instant Dry Yeast",
		"12g of Salt",
		"12g of Oil"
	],
	"recipeInstructions": [
		{
			"@type": "HowToStep",
			"text": "Mix the water, yeast, flour, and salt until fully incorporated"
		},
		{
			"@type": "HowToStep",
			"text": "Add the olive oil after the flour is fully hydrated"
		},
		{
			"@type": "HowToStep",
			"text": "Mix until the dough starts to become smooth and elastic"
		},
		{
			"@type": "HowToStep",
			"text": "If the dough is tough, let it rest for 5-10 minutes to relax the gluten, then continue mixing until smooth."
		},
		{
			"@type": "HowToStep",
			"text": "Cover the bowl and let the dough rise for 2-3 hours or until doubled in size. Weigh and form dough balls. Store in oiled, individual containers or in a proofing box. Refrigerate the dough balls for 1 to 7 days. Remove from the fridge 2-3 hours before baking."
		},
		{
			"@type": "HowToStep",
			"name": "Baking",
			"text": "Preheat the oven to its highest setting. My oven goes to 555°F. Bake on a pizza stone for 5 to 6 minutes or until golden."
		}
	]
}
</script>
{{< /rawhtml >}}