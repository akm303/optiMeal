[Groceries]
Subpages:
    - [Map Panel]
        Nearby stores, determined based on User location
        adjust radius? idk if we should do this here or in user panel, but it might make more sense here
    - [Grocery list Panel]
        add/remove ingredients to list
            1. manually (add/remove)
            2. from Recipes page (add)
        [dynamically update optimally-priced store as you add items]
            back end work needed here
                get prices for each item of list via api from all local stores
                store prices in a cache
                each time this panel is opened, or list is modified, update the "optimal store" by recalculating cheapest grocery trip
                    grocery trip = sum(every item in list per store)
