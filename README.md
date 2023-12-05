# Builder-Design-Pattern--Fast-food-order
We implemented the simplified Builder design pattern (not a Fluent Builder) for a FastFoodOrder.
The FastFoodOrder class has the following String attributes: burger, drink, side, toy.
We need three concrete builders to build the FastFoodOrder object as follows:
1. The HappyMeal Builder class assigns the following values to the attributes of the Fast-FoodOrder object:
• burger = "Hamburger"
• drink = "Coke Zero"
• side = "French Fries"
• toy = "Toy Bundle 1"
2. The KidsMeal Builder class assigns the following values to the attributes of the FastFoodOr-der object:
• burger = "Chicken Burger"
• drink = "Apple Juice"
• side = "Chicken Nuggets"
• toy = "Toy Bundle 2"
3. The AdultMealBuilder class assigns the following values to the attributes of the Fast-FoodOrder object:
• burger = "Double Cheeseburger"
• drink = "Coke XLarge"
• side = "Onion Rings"
• toy = "No Toy"

Using the implemented Builder pattern, The client code should create 3 representations of FastFoodOr-der object (Happy MealBuilder, KidsMeal Builder, and AdultMealBuilder) and display the values of the attributes of the FastFoodOrder objects.
