# Challenge13 - Object-Relational Mapping (ORM) Challenge: E-commerce Back End 
![badge](https://img.shields.io/badge/license-apache-blue)


  ## Table-of-Contents
  * [Description and Task](#description)
  * [Video](#video)   
  * [License](#license)   
  * [Contributing](#contributing)
  * [Questions](#questions)


 ## [Description](#table-of-contents)
 
 Application Design and Function

 As a manager at an internet retail company, I want to a back end for
 my e-commerce website that uses the latest technologies so that my company 
 can compete with other e-commerce companies.


 # My Task and Application Requirments

  - Given a functional Express.js API, I want to add database name, MySQL username, 
    and MySQL password to an environment variable file.

  - Then I want to be able to connect to a database using Sequelize when I I enter 
    schema and seed commands.

  - Then a development database is created and is seeded with test data when 
    I enter the command to invoke the application.

  - Then server is started and the Sequelize models are synced to the MySQL database when
    I open API GET routes in Insomnia for categories, products, or tags

  - Then the data for each of these routes is displayed in a formatted JSON when 
    I test API POST, PUT, and DELETE routes in Insomnia.

  - Then I am able to successfully create, update, and delete data in my database.

  Data Base Tags: 

    Category

        id

        Integer

        Doesn't allow null values

        Set as primary key

        Uses auto increment

        category_name

        String

        Doesn't allow null values

    Product

        id

        Integer

        Doesn't allow null values

        Set as primary key

        Uses auto increment

        product_name

        String

        Doesn't allow null values

        price

        Decimal

        Doesn't allow null values

        Validates that the value is a decimal

        stock

        Integer

        Doesn't allow null values

        Set a default value of 10

        Validates that the value is numeric

        category_id

        Integer

        References the category model's id

    Tag

        id

        Integer

        Doesn't allow null values

        Set as primary key

        Uses auto increment

        tag_name

        String

    ProductTag

        id

        Integer

        Doesn't allow null values

        Set as primary key

        Uses auto increment

        product_id

        Integer

        References the product model's id

        tag_id

        Integer

        References the tag model's id

  
  ## [Video](#table-of-contents)
 
   - Video Guide SEED & MYSQL- [video guide](https://www.awesomescreenshot.com/video/8212028?key=c7bd96a5e6b4bb979d54ddb8934fc0b9)
   - Video Guide - [video guide](https://www.awesomescreenshot.com/video/8212028?key=c7bd96a5e6b4bb979d54ddb8934fc0b9)
   - Video Guide - [video guide](https://www.awesomescreenshot.com/video/8212028?key=c7bd96a5e6b4bb979d54ddb8934fc0b9)
   - Video Guide - [video guide](https://www.awesomescreenshot.com/video/8212028?key=c7bd96a5e6b4bb979d54ddb8934fc0b9)
  
  ## [License](#table-of-contents)
  The application is covered under the following license:
  
  [apache](https://choosealicense.com/licenses/apache)
    
    
  ## [Contributing](#table-of-contents)
  
    Feel free to contact me if there are any issues or ideas to implement.
    
  ## [Questions](#table-of-contents)
  Contact Information Below:
  [GitHub](https://github.com/arbinazari)

  [Email: arbinazari@hotmail.com](mailto:arbinazari@hotmail.com)