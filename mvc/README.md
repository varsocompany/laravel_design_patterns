# Model View Controller Architecture in Laravel

MVC is one of the most popular modern architectural models in software engineering. Laravel itself is a framework that follows the MVC (Model View Controller) architecture. **The fundamental principle behind MVC is that application logic should be separate from its presentation.** The division of logic and presentation is as follows:

| Class type | Responsibility |
| ---------- | -------------- |
| Model      | Logic          |
| Controller | Logic          |
| View       | Presentation   |

#### Advantages of MVC

- Decoupling front-end from back-end.
- Testing is easier (thanks to decoupling).
- Re-use logic code through different presentations (through templated views)
