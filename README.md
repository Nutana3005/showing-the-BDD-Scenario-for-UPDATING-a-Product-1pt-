# showing-the-BDD-Scenario-for-UPDATING-a-Product-1pt-
Scenario: Updating a product
  Given the following products
    | name   | category | available |
    | ToyCar | Toys     | true      |
  When I update the product "ToyCar" with category "Electronics"
  Then I should see the product with name "ToyCar" and category "Electronics"
