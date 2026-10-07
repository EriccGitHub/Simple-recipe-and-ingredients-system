# Simple-recipe-and-ingredients-system

Small system I made for a professional project, in Unreal Engine.

IngredientsContainerComponent is a simple recipe and ingredients system. It is a component you would add to an actor to save the indredients it has and to know when a certain recipe is made.

LiquidContainerComp is another component so an actor could have liquid inside. The liquid is visible, so it changes depending on the amount and the nature of the liquid. It also detect if the liquid container is dripping depending on the liquid height and container orientation.

All the Pipette classes are another component that can control IngredientContainerComponent. They are all a child of the base Pipette class, and it was made to add or remove to and from a liquid container.
