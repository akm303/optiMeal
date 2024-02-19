Users 
User Subpages
    [User main panel]
        - username/name
        - location 
            address (for local grocery stores)
            radius
                version 1 - distance; easiest to implement, simply increase the radius by constant amount (mi/km)
                version 2 - time; determine, based on map apis which grocery store is easiest/quickest to reach(?) 
                    im still not convinced about this but def worth keeping on our brainstorm list for now imo

    [user recipes panel] //stocastic
        Subpages for User Recipes:
            - saved recipes (bookmarks, something to track recipes user wants to try)
                any recipe with ingredients added to cart should automatically be added to 'Saved Recipes'
            - favorited recipes 
                marked by a star or smth, different from saved recipes in that these are known favorites
            - last viewed recipes / recipe history
                maybe 50 to 100 of cached recipes 
                    either opened, or viewed on the main recipe panel or something
            - custom recipes/modifications
                maybe we can allow users to input their personal changes to available recipes
                    in case they want to do it again
                    if other users have similar preferences/profiles, we could pitch modified versions of recipes to them that "they might like"

    [User Preferences Panel]
        - Ideal Nutritional info
            query for fda recommended nutritional values
            adjustment sliders/knobs
                calories, fats, sodiums, vitamins, other macros
        - dietary preferences/restrictions
            affects both recipes appearing on recipe panel, and ingredients searched for price optimization
            things like:
                allergies, organic vs other labels, flavors, cuisines, etc.

    [User Current ingredients]
        Version 1: just a list of a users current ingredients
            define behavior for shopping list/recipe selection interface to either:
                1. ignore these ingredients when accounting for price, or 
                2. override, and add these ingredients anyways (maybe ask user "you already have these ingredients, are you sure you want to add?")
            
        Version 2: take a picture of fridge, get ai to detect current items, add to "current ingredients" list
        Version 3: Track expiration information
        Version 4: Track equipment(?)
            appliances, utensils, knives, tools, etc.
            useful for determining what recipes a user can make