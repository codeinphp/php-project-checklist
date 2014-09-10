A PHP Project Checklist
=====================

NOTE: Please Fork this repo if you want to Add/Modify this checklist for project best practices.
---

+ **Open Source Specific**
  + ReadMe
      - It should contain the "Usage" section
      - It should contain the "Installation" section
      - It should contain the "Requirements" section
      - It should contain the "Contributing" section (via CONTRIBUTING file)
      - It should contain the "Credits" if you prefer
      - It should contain the "License" if you prefer (file "LICENSE" must be present in project root)
          - GPL: If you want any modified versions of your code to be used only in open-source software
          - LGPL: If your code is designed to be a standalone component that may be included in other applications without modification
          - MIT: Allows for use and redistribution of code so long as the license and copyright are included along with it.
  - Semantic Versioning (http://semver.org/)
  - Github page (https://pages.github.com/)
  - A Getting Started Document
  - Continuous Integration (http://en.wikipedia.org/wiki/Continuous_integration)
  - Bug Tracking integrated with the source control
  - A style guide to keep the code consistent
  - A forum for the community to get support, share ideas, etc.
  - Should allow installation via composer (https://getcomposer.org/)
  - Auto-Generated Documentation
  - Manual  
  
+ **Project Specific**
  - Project Architecture Planning (decide which framework to use, which design patterns to follow: MVC, HMVC, DDD, etc)
  - Automated unit tests and builds to push update to the website  
  - Proper folder structure such as **src** for source, **vendor** for dependencies, **tests** for tests, **config**, etc
  + Coding Specific (PHP, CSS, Javascript)
      - PSR standards (http://www.php-fig.org/)
      + Write **SOLID** code (http://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29)
          - Single Responsibility Principle
          - Open/Closed Principle
          - Liskov Substitution Principle
          - Interface Segregation Principle
          - Dependency Inversion Principle
      + Avoid **STUPID** code (http://nikic.github.io/2011/12/27/Dont-be-STUPID-GRASP-SOLID.html)
          - Singleton
          - Tight coupling
          - Untestability
          - Premature Optimization
          - Indescriptive Naming
          - Duplication
      - Monolog (psr-compliant logger)
      - Validators: CSSLint, JSHint, PHPCI, etc
      - Use SPL Exceptions (http://php.net/manual/en/spl.exceptions.php)
      - For CSS, use preprocessor like SASS or LESS
      - Tools: Choose from Awesome PHP (https://github.com/ziadoz/awesome-php)
