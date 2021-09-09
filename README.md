# assignment2-Yethappu
# Ravi Teja Yethappu
## India
*India is on the bucket list for many travelers, and it’s no mystery why! The diverse landscape, colorful festivals, and spicy-hot cuisine are already reasons enough to pack your bags to visit Mumbai or Varanasi.Also India is tagged as the mother of so many inventions like algebra, number zero, shampoo, chess, value of pi and diamond mining * 
**India is the land of spices**

***

## directions from Maryville to NewYork

1. Reach kansas from Maryville by roadway.
2. Board a flight to Newyork Airport from Kansas.
3. Then go by car to your final destination.

### Things to carry 

1. Electronic gadgets.
2. Clothes
3. Outdoor game equipments 

[AboutME](/AboutMe.md)

***

## Food/Drinks 

This table consists of recommended food/drinks , where they are available and the price tag .

| Food/Drinks      | Location    | Price |
| :---             | :---:       | ---:  |
|Chicken Keema     | Hyderabad   | $10   |
|Mutton bryani     | Kansas      | $20   |
|Egg bhurji        | Delhi       | $5    |
| Badam milk       | Kansas      | $3    |

***
## Quotes 

>Big dreams Dont lead to success , need to hustle. - *Ravi Teja Yethappu* 

>Money cannot buy happiness , happiness is state of mind. - *Ravi Teja Yethappu*

***

## Binomial Coefficients

>The binomial coefficient (n; k) is the number of ways of picking k unordered outcomes from n possibilities, also known as a combination or combinatorial number. The symbols _nC_k and (n; k) are used to denote a binomial coefficient, and are sometimes read as "n choose k." (n; k) therefore gives the number of k-subsets possible out of a set of n distinct items. For example, The 2-subsets of {1,2,3,4} are the six pairs {1,2}, {1,3}, {1,4}, {2,3}, {2,4}, and {3,4}, so (4; 2)=6. The number of lattice paths from the origin (0,0) to a point (a,b) is the binomial coefficient (a+b; a) (Hilton and Pedersen 1991).



[Content](https://mathworld.wolfram.com/BinomialCoefficient.html)

```
int C(int n, int k) {
    int res = 1;
    for (int i = n - k + 1; i <= n; ++i)
        res *= i;
    for (int i = 2; i <= k; ++i)
        res /= i;
    return res;
}

```
[AlgorithmCode](https://cp-algorithms.com/combinatorics/binomial-coefficients.html)






