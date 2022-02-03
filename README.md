# assignment2-kanneti
<h1>Yashahsri</h1>
<h3>KFC</h2>
Kukatpally is a bustling locality and so is our KFC Restaurant. Situated on the Lower Ground Floor of a **famous shopping mall**, in northwestren part of of Hyderabad in **Telangana state**.
<hr>

# Nearest Airport Location and Address details

## Shamshabad Airport 

1. Take Bus from the airport to JNTUH
2. OR Take a cab from the airport to the Restaurant
3. Step down at KFC Restaurant


### Recommended food

* Mingles Bucket
* Rice Bowl
* Wraps
* Brownie

[Goto AboutMe] (AboutMe.md)


<hr>



## Recomended Games



Below table gives a breif intro about gaming activites and the location of gaming arena along with amount payable for any additional equipment opted.




|Sport | Location | Money Payable|
|  ---  |   ---   | :--- |
|Badminton| Kansas | $ 2500|
|Cricket| Florida | $ 3070|
|Surfing| texas | $ 3400|
|Karting| Chicago | $1700|

<hr>

# Pithy Quotes

> “It's always darkest before you're blinded by the light”.”<br>

>***- josh stern***



>“Money is a tool, so I don't have to be.”<br>

>***- Eddie Mumford***

<hr>


# Code Fencing


# combinatorial work


>In the course of our combinatorial work over the past several years, we have been fond of going to the computer from time to time in order to see some examples of the things we were studying. We have built up a fairly extensive library of programs, and we feel that other might be interested in learning about the methods and/or use of the programs. This book is the result. It can be read as a collection of mathematical algorithms, and as such we hope the reader will find much that is new and interesting. Yet to do so would be to miss something that to us seems essential: the interchange between the computer programs per se, the computer, the algorithms, and ultimately the mathematics.[-Goto Source](https://mathshistory.st-andrews.ac.uk/Extras/Combinatorial_algorithms/).



we can implement `combinatorial work` as follows <https://cp-algorithms.com/combinatorics/binomial-coefficients.html>



```const int maxn = ...;
int C[maxn + 1][maxn + 1];
C[0][0] = 1;
for (int n = 1; n <= maxn; ++n) {
    C[n][0] = C[n][n] = 1;
    for (int k = 1; k < n; ++k)
        C[n][k] = C[n - 1][k - 1] + C[n - 1][k];
}
```




 


