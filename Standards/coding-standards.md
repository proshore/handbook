# PHP Coding Standards

The best definition good: The code must be readable and maintainable.

**Readable** 
Readable Code starts with the code that you find easy to read. It varies between the teams, programming languages, and companies. There are two people who are the judge of how readable the code is: You and everyone else who will later try to read the code. Think about how you could make the code more readable. Perhaps you see some functions that do too many things and are too long. Perhaps you find that renaming a variable would make its purpose clearer. Make changes until you feel like the code is as expressive, concise, and pretty as it can be.

**Maintainable:** 
Maintainable Code simply means The ease with which a software system or component can be modified to correct faults, improve performance or other attributes, or adapt to a changing environment. Maintainable code is directly related to the Readable Code


**To maintain the readability and maintainability of code following points must be followed**

 - Coding Standard: [PSR12](https://www.php-fig.org/psr/psr-12/)
 - Nomenclature 
	 - Variable names must follow the snake case. 
	 - The name of the variables should be definitive. (should describe what the variable is for) 
		 - `$a = “John”` (Bad) 
		 - `$employee_name = “John”` (Good) 

		 - `$mf = new Form();` (Bad) 
		 - `$monitoring_form = new Form();` (Good)

	 - The method name must be in the camel case. Long variable/method names are also allowed.
	 - The name of the methods should be definitive.
		 - `getProducts($id) { }` (bad)
		 - `getProductsByCategoryId($category_id) { }` (Good)

 - **Principle of CLEAN code**
	 - **KISS**: Keep It Simple Stupid. 
	 - **DRY**: Don’t Repeat Yourself. 
	 - **YAGINI**: You Aren’t Gonna Need IT 
	 - **Favor Readibility** 
	 - **Practice Consistency**

 - **Single Responsibility. from (SOLID Principle)** 
	 - https://www.digitalocean.com/community/conceptual_articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design#singleresponsibility-principl
