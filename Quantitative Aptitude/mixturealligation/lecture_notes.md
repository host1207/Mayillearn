# Mixture and Alligation - Lecture Notes
if the price of variety 1 and variety 2 and finally the mean price is also given then we can find ratio of variety 1 and 2 by using the diagram below 

![Alligation Cross Diagram](../diagrams%20for%20mixture%20and%20alligation/mean_price_diagram.png)
 alligation is just like a rule it uses weight based scales to arrive on the value eg in the above diagram the price of variety 1 and pice of variety 2 are the inputs and the average is a balancing cone and this alligation just meansures the distance at which they can balance it that is the ratio is just a quantity at which v1 and p2 must be taken to arrive at mean price 

![Example: P1=60, P2=90, Mean=70, Ratio 2:1](../diagrams%20for%20mixture%20and%20alligation/p1_60_p2_90_mean_70_ratio_2_1.png)

now here is the important thing when a question says something like 10% profit that value is actually the selling price and not the cost price because profit is always calculated on top of the cost price so if cp is 100 and profit is 10% then sp becomes 110 so whenever you see profit or loss percentages in alligation questions remember that the mean value they are giving you is actually the sp not the cp

the reason this matters is because alligation only works on mean weights meaning it works on values that are directly mixable like cost prices you can mix two things at their cost prices and get an average cost price that makes sense but selling price is not something you mix directly because sp already has profit or loss added on top of it so it is a derived value not a base value

think of it like this when you mix two types of rice at rs 60 per kg and rs 90 per kg the resulting mixture has a cost price somewhere in between depending on the ratio and alligation finds that ratio perfectly but if someone tells you the mixture is sold at 10% profit that 10% is applied after mixing so the sp is not the value you plug into the alligation cross directly you first need to work backwards from sp to find the actual mean cp and then use that mean cp in your alligation diagram

so the rule is always convert everything to cost price before applying alligation because alligation is a weighted average method and weighted averages only work correctly when all the values are on the same base which is cost price if you mix sp values directly you will get wrong ratios because sp already includes profit margins which distort the true mixing proportion

<h1 style="color: green; font-weight: bold;">How To Find Mean If P1, P2 And Ratios Are Given</h1>
 now if the question gives you the ratio of the two varieties and the prices of the two varieties and asks you to find the mean price then you can use the formula below 

![Find Mean: P1=20, P2=30, Mean=x, Ratio 2:3](../diagrams%20for%20mixture%20and%20alligation/find_mean_x_diagram.svg)

traditional method 

$$\frac{30 - x}{x - 20} = \frac{2}{3}$$

$$90 - 3x = 2x - 40$$

$$5x = 130 \implies x = \frac{130}{5} = 26$$

easy method 

step 1 take the difference of p1 and p2 so here 30 - 20 = 10

step 2 divide that difference by the total ratio so total ratio is 2 + 3 = 5 and 10 / 5 = 2 so each unit is worth 2

step 3 now multiply each unit with the individual ratios so for ratio 2 we get 2 × 2 = 4 and for ratio 3 we get 2 × 3 = 6

step 4 now either add the value opposite to the smallest price or subtract the value opposite to the largest price

way 1 the smallest price is 20 and its opposite ratio is 3 so we take the value of 3 units which is 6 and add it to 20 so 20 + 6 = 26

way 2 the largest price is 30 and its opposite ratio is 2 so we take the value of 2 units which is 4 and subtract it from 30 so 30 - 4 = 26
both ways give us mean price = 26

![Solved: P1=20, P2=30, Mean=26, Ratio 2:3](../diagrams%20for%20mixture%20and%20alligation/p1_20_p2_30_mean_26_ratio_2_3.svg)


now sometimes the question gives you p1 p2 and the ratio and then asks at what price should the mixture be sold to get a certain profit or loss so in that case first find the mean price using the methods above and then apply the profit or loss on top of it

for example if the mean price comes out to be 26 and the question says find the selling price at 50% profit then just multiply the mean price by 1.5 so 26 × 1.5 = 39 thats your selling price because 50% profit means you are selling at 150% of the cost price which is the same as multiplying by 1.5

similarly if the question says sell at 50% loss then multiply the mean price by 0.5 so 26 × 0.5 = 13 because 50% loss means you are selling at only 50% of the cost price

the general rule is for x% profit multiply the mean cp by (1 + x/100) and for x% loss multiply the mean cp by (1 - x/100) so 20% profit means multiply by 1.2 and 30% loss means multiply by 0.7 and so on

remember alligation gives you the mean cost price first and profit or loss is always the last step you apply after getting the mean cp never mix profit loss into the alligation step itself

<h1 style="color: green; font-weight: bold;">Three Variety Mixture Problems</h1>

now lets jump into three variety problems because in ssc they love these kinds of questions so heres the problem a trader mixes three varieties of rice at prices p1 = 16 p2 = 25 and p3 = 42 and the mean price of the mixture is 30 find the ratio in which they are mixed

we have two methods to solve this

<h2 style="color: green; font-weight: bold;">Method 1 - Alligation Pairs</h2>

we already know that alligation works like a balance so what we do is we take the cheapest and the dearest and apply alligation between them through the mean and then we do the same with the middle one and the dearest

step 1 apply alligation between p1 = 16 and p3 = 42 with mean = 30

p1 gets quantity = (42 - 30) = 12
p3 gets quantity = (30 - 16) = 14

so p1 : p3 = 12 : 14 which simplifies to 6 : 7

step 2 apply alligation between p2 = 25 and p3 = 42 with mean = 30

p2 gets quantity = (42 - 30) = 12
p3 gets quantity = (30 - 25) = 5

so p2 : p3 = 12 : 5

step 3 now combine the ratios by adding p3 from both because p3 is the one pulling both p1 and p2 towards the mean so p3 appears in both pairs and we add its parts together

p1 : p2 : p3 = 6 : 12 : (7 + 5) = 6 : 12 : 12 = 1 : 2 : 2

why do we add p3 because p3 is the dearest variety and it is the one that balances against both p1 and p2 separately to reach the mean of 30 so its total contribution is the sum of what it gives to each pair

<h2 style="color: green; font-weight: bold;">Method 2 - Above and Below Mean Balancing</h2>

this is a quick method where we find how much each variety is above or below the mean and then balance them

p1 = 16 is (30 - 16) = 14 below the mean
p2 = 25 is (30 - 25) = 5 below the mean
p3 = 42 is (42 - 30) = 12 above the mean

now the rule is whatever is below the mean on one side must equal whatever is above the mean on the other side so we write

14x + 5y = 12z

where x y z are the quantities of p1 p2 p3

now we just substitute random numbers that make this equation work so lets try x = 1 and y = 2

14(1) + 5(2) = 14 + 10 = 24

so 12z = 24 which gives z = 2

so the ratio is x : y : z = 1 : 2 : 2

this method is faster because you just need to find the distances from the mean and plug in numbers that balance the equation its like a seesaw the total weight below the mean must equal the total weight above the mean






