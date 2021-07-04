# stock-analysis
## Overview of Project:
The main objective of this analysis is to quickly identify potentially attractive stocks for new investors, based on positive performing stocks from 2017 & 2018. 

## Results:
In 2017, most stocks provided positive results, with the exception of "TERP", and could therefore be considered attractive for investment in 2018. However, only two of the stocks analyzed actually had positive results in 2018,"ENPH" and "RUN", which also had considerable Trading Volume. This factors make them the most attractive stocks to recommend for further investment.

<img width="278" alt="Screen Shot 2021-07-04 at 1 51 30 PM" src="https://user-images.githubusercontent.com/86029436/124398072-56f76580-dcd9-11eb-8c4f-f80e315907df.png"> 
<img width="273" alt="Screen Shot 2021-07-04 at 1 51 46 PM" src="https://user-images.githubusercontent.com/86029436/124398098-79897e80-dcd9-11eb-9eff-351add5fbe2c.png">

### Code refactored performance:
The original code ran in 0.84 seconds for 2017 & 0.82 seconds for 2018 data.

<img width="273" alt="Screen Shot 2021-07-04 at 1 51 57 PM" src="https://user-images.githubusercontent.com/86029436/124398130-b48bb200-dcd9-11eb-8934-3374912784ab.png"> <img width="267" alt="Screen Shot 2021-07-04 at 1 52 08 PM" src="https://user-images.githubusercontent.com/86029436/124398135-b81f3900-dcd9-11eb-8aed-6fd09f77d2d0.png">

While the refactored code ran much faster, at 0.16 seconds for 2017 data & 0.15 seconds for the 2018 dataset.
<img width="275" alt="Screen Shot 2021-07-04 at 1 51 25 PM" src="https://user-images.githubusercontent.com/86029436/124398153-dc7b1580-dcd9-11eb-9a5c-28d2f1b225cc.png">
<img width="270" alt="Screen Shot 2021-07-04 at 1 51 42 PM" src="https://user-images.githubusercontent.com/86029436/124398159-e43aba00-dcd9-11eb-9a38-865c34abcfe9.png">

Which means it ran 5 times faster! 👍 And is therefore ready for much bigger datasets without compromising performance.

## Summary:
### 1. What are the advantages or disadvantages of refactoring code?
#### Advantages:
- Usually, the refactored code will be more efficient than the original, as this is the objective of refactoring. As is the case in this excercise.
- Refactoring code provides opportunities to find & fix bugs or unnecessary code in the original.
- Refactoring code, especially if it's not your own, provides opportunities to learn.
- In many cases, it's difficult to know where to start. Refactoring code helps in this sense, as you have a base to begin with.

#### Disadvantages:
- The new code might be more elegant and efficient, but it could could be more difficult to follow for other programmers.
- The difference in logic between programmers could also lead to cases in which it's more efficient to re-start code, rather than spending time to decode another programmer's logic and refactor.

### 2. How do these pros and cons apply to refactoring the original VBA script?
In this case, since Steve's request is to expand the scope of analysis for a much larger dataset, reducing the time to run is critical. Plus, a more elegant and slimer code will also decrease the size of the file used.
