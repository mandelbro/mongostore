# Railscast #238 Mongoid (revised)

A Ruby on Rails store app with products and reviews. Based on [Railscast #238](http://railscasts.com/episodes/238-mongoid-revised)

## Models
* Product
  * Name (String): Name of the product
  * Price (big_decimal): Price of the product
  * realeased_on (Date): The date string the product was released on
* Review (Embedded by Product)
  * content (String): The User's review text
