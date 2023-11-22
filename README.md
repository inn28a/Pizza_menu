## First React Single Page App 

This project is my first React-based application, that leverages several key methods, rendering multiple components of the same type - conditional rendering. 

### App overview
React Key Components and Methods:
1. React components
* App Component: The central component orchestrating the application structure, incorporating the Header, Menu, and Footer components.
* Header Component: Displays the application's name, providing a visual introduction to users.
* Menu Component: Utilizes the map method to dynamically render Pizza components based on the pizzaData array. It also employs conditional rendering to handle scenarios where the menu is still under construction.
* Pizza Component: Represents an individual pizza, using props to dynamically display details such as name, ingredients, price, and availability status. The 'map()' method is employed to iterate through the pizzaData array and render each Pizza component.
* Footer Component: Determines the current time and uses it to conditionally render either the Order component or a message about the restaurant's opening hours.

2.Dynamic Styling:
* CSS Classes: Dynamically assigns CSS classes to elements based on the availability status of pizzas, allowing for visual differentiation between available and sold-out items.

3.Online Ordering:
* Order Component: This component is conditionally rendered in the Footer, providing information about the restaurant's opening hours and encouraging users to order online. It incorporates the current opening and closing hours.4.Conditional Rendering:

4.Conditional Rendering
* Conditional Statements: Conditional rendering is applied in various places, such as displaying the menu when pizzas are available and showing a message when the menu is still in progress. It also checks the availability status of each pizza to determine whether to display the "SOLD OUT" label.

  
![first_reactApp](https://github.com/inn28a/Pizza_menu/assets/49073623/2823e26d-cc22-4fc3-98bb-1cd06fed22fa)

![pizza_menu_empty](https://github.com/inn28a/Pizza_menu/assets/49073623/95739c04-76fe-49be-bc7d-5b7c70072a0e)


##### Acknowledgments

* [Project based on this course](https://www.udemy.com/course/the-ultimate-react-course/)

