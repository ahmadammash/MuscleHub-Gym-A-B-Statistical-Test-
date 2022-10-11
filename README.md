# MuscleHub-Gym-A-B-Statistical-Test-
This project is about a statistical A/B test done at a fictional gym: Muscle Hub. The objective of the test is to prove whether a fitness test done by visitors is increasing the number of conversions to members. 

Visitors to Muscle Hub were randomly and evenly split into two groups. One grouped was asked to complete a fitness test ahead of applying for their membership while the other group was not. The goal is to test whether the presence of a fitness test is encouraging more people to apply and pay for a Muscle Hub membership.

The experiment compares the two visitor groups on 3 levels:

1) Those who picked up an application vs those who did not
2) Those who picked up an application and purchased a membership (as a % of the visitors who applied)
3) The visitors who purchased a membership (as a % of total visitors from the group)

Four data frames were combined to one: visits, fitness_tests, applications and purchases.

The first hypothesis test used a chi-squared test to determine whether the fitness test had a significant effect on the number of applicants (visitors who applied).

The second hypothesis test also used a chi-squared test to determine whether the fitness test had a significant effect on the number of applicants who became members.

The third hypothesis test also used a chi-squared test to examine the significance of the fitness test's effect on the overall conversion rate of visitors to members.

The results from the third hypothesis test are what the gym should act upon as the third test considers the overall conversion rate of visitors to members instead of applicants to members.
