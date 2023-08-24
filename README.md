<h1><span style="font-size: 1.2em; vertical-align: middle;">📚</span> MyEnumerable</h1>

In this project we will learn how to use a module inside your class. For this we will create a class MyList and a module MyEnumerable. Our module MyEnumerable will implement a subset of the functionality of Enumerable.


<br>
# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [❓ FAQ](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 [MyEnumerable] <a name="about-project"></a>

In this project, we delve into using modules within a class to create a MyList class and a MyEnumerable module. The purpose of the MyEnumerable module is to replicate a subset of the functionality found in the Enumerable module.


## 🛠 Built With <a name="built-with"></a>
This project is built using Ruby, a dynamic, open-source programming language known for its simplicity and productivity. Ruby's elegant syntax and powerful features make it a popular choice among developers.

Visit the official [Ruby Website](https://www.ruby-lang.org/) website to learn more about the language and its capabilities.

## 💻 Getting Started <a name="getting-started"></a>
To begin using MyEnumerable, follow these steps:

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/PabloBona/my_enumerable.git
    ```
   ```sh
   cd my_enumerable
    ```


<a name="readme-top"></a>


### Tech Stack <a name="tech-stack"></a>

This project is implemented using the Ruby programming language, known for its elegant syntax and flexibility. Ruby provides a suitable foundation for this code decoding project due to its ease of use and string manipulation capabilities.

## Usage of Ruby

Ruby plays a pivotal role in the MyEnumerable project, fulfilling various functionalities such as:

- Implementing the `MyList` class to manage collections and provide a structured data handling mechanism.
- Defining the `MyEnumerable` module to extend the capabilities of the `MyList` class with powerful methods.
- Employing Ruby's inherent features to execute the test cases and verify the correctness of the implemented methods.

Throughout the MyEnumerable project, Ruby's versatility empowers us to create an organized and efficient solution for handling collections and performing operations akin to those offered by the built-in `Enumerable` module.



### Key Features <a name="key-features"></a>


- **Code Reusability:**
  To ensure clean and efficient code, the project follows the DRY (Don't Repeat Yourself) principle. Methods are designed to be reusable, reducing redundancy and promoting maintainability.

- **Flexible Adaptation:**
  The script's modular structure facilitates future expansion or customization. Additional decoding methods or enhancements can be integrated seamlessly.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### 🛠 Setup <a name="setup"></a>

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/PabloBona/my_enumerable.git
    ```
   ```sh
   cd my_enumerable
    ```
2. To verify the solution :
Start IRB:
   ```sh
   irb
   ```
3. Require_relative:
   ```sh
   require_relative 'my_list'
   ```
4. Instance MyList and test the methods:
   ```sh
   list = MyList.new(1, 2, 3, 4)
   puts(list.all? { |e| e < 5 })
   puts(list.all? { |e| e > 5 })
   puts(list.any? { |e| e == 2 })
   puts(list.any? { |e| e == 5 })
   puts(list.filter(&:even?))`
  <br>
  <p align="right">(<a href="#readme-top">back to top</a>)</p>

  ## 👥 Authors <a name="authors"></a>


👤 **Pablo Bonasera**

- GitHub: [@Pablobona](https://github.com/PabloBona)
- LinkedIn: [@Pablobona](https://www.linkedin.com/in/pablo-bonasera/)

👤 **lRebornsl**
- GitHub: [@lRebornsl](https://github.com/lRebornsl)
- Twitter: [@RebornsDev](https://twitter.com/RebornsDev)
- LinkedIn: [Anthony Vásquez](https://www.linkedin.com/in/avvm98/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>


If you like this project or if it helped you, please give a ⭐️. I'd really appreciate it!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

 

I would like to thank Microverse and all my peers and colleagues at Microverse for giving me the opportunity to work on this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

- **[What is the purpose of this project]**

  The main purpose of this project is to provide hands-on experience with using modules within a class in Ruby. It involves creating a MyList class that utilizes the functionalities defined in the MyEnumerable module, simulating a subset of the capabilities offered by the Enumerable module.

- **[What are the key methods being implemented]**

  The core methods being replicated in the MyEnumerable module are #all?, #any?, and #filter. These methods are fundamental in working with collections and determining whether certain conditions are met within them.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>