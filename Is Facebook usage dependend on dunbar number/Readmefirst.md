Robin Dunbar a famous anthropologist argued that humans only have the capacity to keep
track of so many people at a time. He argued that the maximum number of people humans
could keep track of is 150. This number is called Dunbar's number (Links to an external site.).
Some have interpreted this to mean that any individual person has on average about 150
friends.
Some technologists have argued that social media and modern information technology allow
individuals to keep track of more people. For example, Facebook algorithmically organizes
and presents information about our Facebook friends in a centralized feed lowering the costs
associated with keeping in contact with all these people.
Fortunately we can evaluate this claim because our colleague Prof. Vitak has collected data
on Facebook usage among college students at a large university. Using this dataset named
“Sample data” and the “codebook” which explains the variables evaluate the technologists's
claim.

Question 1: Using the theoretical population mean and the sample provided conduct a onesample
t-test (with significance level alpha = 0.05) to determine whether individuals have more
friends than would be expected by Dunbar's number.

a. Graph the total Facebook friend values for the sample. What is the shape?

b. State your null and alternative hypotheses.

c. Calculate your t-statistic

d. Look up the probability for the t-statistic

e. What is the effect size?

f. What would you conclude?

g. What are the limitations, if any?


Question 2: Are individuals who have 150 or more friends on Facebook using Facebook in a
fundamentally different way from those that have fewer than 150 friends? Use two sample ttests
with a significance level of 0.05 to compare Facebook users who have 150 Facebook
friends or more to those with fewer than 150 Facebook friends for the 6 items that make up
question 28 "How likely are you to use Facebook to do the following things, either now or in
the future?". Feel free to do the calculations using t.test in R. Treat these Likert items as
interval variables.

Hints: 1) Use the ifelse function in R to create a new variable binary variable to categorize
users with 150 or more Facebook friends from those with fewer than 150 Facebook friends 2)
You will need to run 6 t tests 3) for this problem you don't need to write out the null and
alternative hypotheses (although you should know what these are!), 4) for this problem you
don't need to calculate effect sizes (although if you have time and want the practice feel free to
do so for an extra challenge).

a) Calculate 6 independent t-tests and organize results into a table with independent variable,
dependent variable, and results of the statistical tests (i.e. t-statistic, degrees of freedom, and pvalue)

b) Explain any significant differences in how the two groups of users, those with more and
fewer Facebook friends, are using Facebook by reporting the means and standard deviations
for the two groups for the relevant type of use (e.g. “Those with more friends are more likely to
use Facebook to find someone to date (Mean = X, SD = Y) than those who have fewer friends
(Mean = Z, SD = W)”).

c) What would you conclude?
d) What are the limitations, if any?
