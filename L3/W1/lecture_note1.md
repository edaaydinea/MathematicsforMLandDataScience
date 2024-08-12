# What is Probability?

1. **Definition of Probability**
   - Probability measures how likely an event is to occur.
   - Example: The probability of a fair coin landing heads is 50% or 1/2.
   - Example: The probability of a dice landing on 4 is 1/6.

2. **Example Problem: Probability of Playing Soccer**
   - Scenario: A school with 10 kids; 3 play soccer, 7 don't.
   - Objective: Find the probability that a randomly picked kid plays soccer.
   - Notation: $P(\text{soccer})$ represents the probability of a kid playing soccer.
   - Formula: $\text{Probability} = \frac{\text{Number of favorable outcomes}}{\text{Total number of outcomes}}$.
   - Calculation: $P(\text{soccer}) = \frac{3}{10} = 0.3$ or 30%.

3. **Venn Diagram Representation**
   - Total population (10 kids) is represented by a green rectangle.
   - Kids who play soccer are inside a circle within the rectangle (30%).
   - Kids who don't play soccer are outside the circle but within the rectangle.

4. **Coin Flipping Example**
   - Experiment: Flipping a fair coin.
   - Probability of heads: $P(\text{heads}) = \frac{1}{2} = 0.5$ or 50%.
   - Probability of tails: $P(\text{tails}) = \frac{1}{2} = 0.5$ or 50%.

5. **Two Coins Flipping**
   - Possible outcomes: Heads-heads, heads-tails, tails-heads, tails-tails.
   - Total outcomes: 4.
   - Probability of both coins landing heads: \( P(\text{HH}) = \frac{1}{4} = 0.25 \) or 25%.

6. **Three Coins Flipping**
   - Possible outcomes: All heads, heads-heads-tails, heads-tails-heads, heads-tails-tails, tails-heads-heads, tails-heads-tails, tails-tails-heads, tails-tails-tails.
   - Total outcomes: 8.
   - Probability of all three coins landing heads: \( P(\text{HHH}) = \frac{1}{8} = 0.125 \) or 12.5%.
  
# What is Probability? Dice Example

1. **Rolling a Single Die**
   - **Scenario:** Rolling a fair six-sided die.
   - **Objective:** Find the probability of rolling a six.
   - **Sample Space:** 6 possible outcomes (1, 2, 3, 4, 5, 6).
   - **Favorable Outcome:** Rolling a six.
   - **Calculation:** Probability \( P(6) = \frac{1}{6} \).

2. **Rolling Two Dice**
   - **Scenario:** Rolling two fair six-sided dice.
   - **Objective:** Find the probability of rolling double sixes (6,6).
   - **Sample Space:** Each die has 6 possibilities, so there are \( 6 \times 6 = 36 \) possible outcomes.
   - **Favorable Outcome:** Rolling double sixes (6,6).
   - **Calculation:** Probability \( P(\text{6,6}) = \frac{1}{36} \).

3. **Interactive Tool**
   - **Purpose:** To explore probability concepts by flipping coins or rolling dice repeatedly.
   - **Observation:** Frequency of each outcome approaches the theoretical probability with more flips or rolls.

# Complement of Probability

1. **Complement of an Event**
   - **Definition:** The complement of an event is the probability that the event does not occur.
   - **Calculation:** If the probability of an event occurring is \( P(A) \), then the probability of the event not occurring (complement) is \( 1 - P(A) \).

2. **Example: Kids Playing Soccer**
   - **Scenario:** 10 kids, 3 play soccer, 7 don't.
   - **Objective:** Find the probability that a randomly picked child does not play soccer.
   - **Calculation:**
     - Probability that a child plays soccer: \( P(\text{soccer}) = 0.3 \).
     - Probability that a child does not play soccer: \( P(\text{not soccer}) = 1 - P(\text{soccer}) = 1 - 0.3 = 0.7 \).

3. **Complement Rule**
   - **Formula:** \( P(A') = 1 - P(A) \), where \( A' \) represents the complement of event \( A \).
   - **Application:** Use this rule to find the probability of an event not happening.

4. **Venn Diagram Representation**
   - **Sample Space:** Entire rectangle represents all possible outcomes.
   - **Event of Playing Soccer:** Circle inside the rectangle.
   - **Event of Not Playing Soccer:** Area outside the circle.

5. **Example: Flipping Three Coins**
   - **Objective:** Find the probability of not obtaining three heads.
   - **Calculation:**
     - Probability of three heads: \( P(\text{HHH}) = \frac{1}{8} \).
     - Probability of not three heads: \( P(\text{not HHH}) = 1 - \frac{1}{8} = \frac{7}{8} \).

6. **Example: Rolling a Die**
   - **Objective:** Find the probability of obtaining anything other than a 6.
   - **Calculation:**
     - Total outcomes: 6.
     - Probability of rolling a 6: \( P(6) = \frac{1}{6} \).
     - Probability of not rolling a 6: \( P(\text{not 6}) = 1 - \frac{1}{6} = \frac{5}{6} \).

# Sum of Probabilities (Disjoint Events)

1. **Sum of Probabilities for Disjoint Events**
   - **Definition:** If two events are disjoint (i.e., they cannot occur simultaneously), the probability of either event occurring is the sum of their individual probabilities.
   - **Formula:** If \( A \) and \( B \) are disjoint events, then \( P(A \cup B) = P(A) + P(B) \).

2. **Example: Kids Playing Sports**
   - **Scenario:** Kids can only play one sport (either soccer or basketball).
   - **Given Probabilities:**
     - Probability of playing soccer, \( P(\text{Soccer}) = 0.3 \)
     - Probability of playing basketball, \( P(\text{Basketball}) = 0.4 \)
   - **Calculation:**
     - Probability of playing soccer or basketball: \( P(\text{Soccer} \cup \text{Basketball}) = P(\text{Soccer}) + P(\text{Basketball}) = 0.3 + 0.4 = 0.7 \)

3. **Venn Diagram Representation**
   - **Union of Events:** The probability of either event happening (soccer or basketball) is represented by the union \( A \cup B \).

4. **Example: Rolling a Die**
   - **Objective:** Find the probability of rolling an even number or a five.
   - **Events:**
     - Event \( A \): Rolling an even number (2, 4, 6).
     - Event \( B \): Rolling a five.
   - **Calculation:**
     - Probability of an even number: \( P(A) = \frac{3}{6} = \frac{1}{2} \)
     - Probability of a five: \( P(B) = \frac{1}{6} \)
     - Probability of an even number or a five: \( P(A \cup B) = \frac{1}{2} + \frac{1}{6} = \frac{2}{3} \)

5. **Example: Rolling Two Dice**
   - **Objective:** Find the probability of obtaining a sum of 7 or 10.
   - **Events:**
     - Event \( A \): Sum is 7.
     - Event \( B \): Sum is 10.
   - **Calculation:**
     - Probability of sum 7: \( P(A) = \frac{6}{36} = \frac{1}{6} \)
     - Probability of sum 10: \( P(B) = \frac{3}{36} = \frac{1}{12} \)
     - Probability of sum 7 or sum 10: \( P(A \cup B) = \frac{1}{6} + \frac{1}{12} = \frac{1}{4} \)

6. **Example: Difference Between Dice Rolls**
   - **Objective:** Find the probability of a difference of 2 or 1.
   - **Events:**
     - Event \( A \): Difference is 2.
     - Event \( B \): Difference is 1.
   - **Calculation:**
     - Probability of difference 2: \( P(A) = \frac{8}{36} \)
     - Probability of difference 1: \( P(B) = \frac{10}{36} \)
     - Probability of difference 2 or 1: \( P(A \cup B) = \frac{8}{36} + \frac{10}{36} = \frac{18}{36} = \frac{1}{2} \)

# Sum of Probabilities (Joint Events)

1. **Non-Disjoint Events (Joint Events)**
   - **Definition:** When two events can occur simultaneously, they are not disjoint (also known as joint or non-mutually exclusive events).
   - **Problem:** Simply adding the probabilities of non-disjoint events can result in an overestimation because the intersection (overlap) of the events is counted twice.

2. **Inclusion-Exclusion Principle**
   - **Formula:** To calculate the probability of either event occurring (union of events), we use the formula:
     \[
     P(A \cup B) = P(A) + P(B) - P(A \cap B)
     \]
   - **Explanation:** 
     - \( P(A) \) and \( P(B) \) are the probabilities of events A and B, respectively.
     - \( P(A \cap B) \) is the probability of both events occurring (the intersection).
     - The term \( P(A \cap B) \) is subtracted because it is counted twice when adding \( P(A) \) and \( P(B) \).

3. **Example: Kids Playing Sports (Multiple Sports Allowed)**
   - **Scenario:** Kids can play both soccer and basketball.
   - **Given Probabilities:**
     - Probability of playing soccer, \( P(\text{Soccer}) = 0.6 \)
     - Probability of playing basketball, \( P(\text{Basketball}) = 0.5 \)
     - Probability of playing both, \( P(\text{Both}) = 0.3 \)
   - **Calculation:**
     - Probability of playing soccer or basketball:
     \[
     P(\text{Soccer} \cup \text{Basketball}) = P(\text{Soccer}) + P(\text{Basketball}) - P(\text{Both}) = 0.6 + 0.5 - 0.3 = 0.8
     \]

4. **Example: Rolling Two Dice (Sum or Difference)**
   - **Objective:** Find the probability of obtaining a sum of 7 or a difference of 1.
   - **Events:**
     - Event \( A \): Sum is 7.
     - Event \( B \): Difference is 1.
   - **Calculation:**
     - Probability of sum 7: \( P(A) = \frac{6}{36} = \frac{1}{6} \)
     - Probability of difference 1: \( P(B) = \frac{10}{36} = \frac{5}{18} \)
     - Probability of both sum 7 and difference 1: \( P(A \cap B) = \frac{2}{36} = \frac{1}{18} \)
     - Probability of sum 7 or difference 1:
     \[
     P(A \cup B) = \frac{1}{6} + \frac{5}{18} - \frac{1}{18} = \frac{7}{18}
     \]

5. **Key Concepts**
   - **Disjoint Events:** Events that cannot occur simultaneously. For these, the sum rule directly applies without any correction.
   - **Non-Disjoint Events:** Events that can occur together. The inclusion-exclusion principle must be used to avoid over-counting the intersection.

Understanding the distinction between disjoint and non-disjoint events is crucial in accurately calculating probabilities in real-world situations where events often overlap.

# Indepedence

1. **Definition of Independence**
   - **Independent Events:** Two events are independent if the occurrence of one event does not affect the probability of the occurrence of the other event. 
   - **Examples:**
     - **Coin Tossing:** The result of one coin toss does not influence the result of another.
     - **Chess Moves:** The moves in a game of chess are generally not independent, as each move is influenced by the previous ones.

2. **Importance in Probability and Machine Learning**
   - Assuming independence simplifies calculations and models, especially when dealing with large datasets or complex systems. However, it's crucial to correctly identify independent events to avoid incorrect conclusions.

3. **Calculating Probabilities with Independent Events**
   - **Product Rule:** The probability of both independent events \( A \) and \( B \) occurring is the product of their individual probabilities.
   \[
   P(A \cap B) = P(A) \times P(B)
   \]

4. **Examples of Independence**
   - **Randomly Split Students:** 
     - **Scenario 1:** 100 kids, 50 like soccer. Randomly split into two rooms of 50 each.
       - **Best Estimate:** 25 kids in each room like soccer.
     - **Scenario 2:** 100 kids, 40 like soccer. Rooms of 30 and 70 kids.
       - **Best Estimate:** 40% of 30 kids in room 1 like soccer, i.e., 12 kids.

5. **Probability Calculation for Multiple Events**
   - **Example:** Probability that a randomly chosen kid likes soccer and is in room 1.
     - Given: 
       - \( P(\text{Soccer}) = 0.4 \)
       - \( P(\text{Room 1}) = 0.3 \)
     - **Calculation:** 
     \[
     P(\text{Soccer} \cap \text{Room 1}) = P(\text{Soccer}) \times P(\text{Room 1}) = 0.4 \times 0.3 = 0.12
     \]

6. **Extended Product Rule**
   - **Application:** The product rule extends to more than two events if they are all independent.
   - **Examples:**
     - **Coin Tosses:** Probability of getting heads five times in a row.
       \[
       P(\text{5 Heads}) = \left(\frac{1}{2}\right)^5 = \frac{1}{32}
       \]
     - **Dice Rolls:** Probability of rolling two sixes with two dice.
       \[
       P(\text{Two Sixes}) = \left(\frac{1}{6}\right)^2 = \frac{1}{36}
       \]
     - **Rolling 10 Sixes with 10 Dice:** 
       \[
       P(\text{10 Sixes}) = \left(\frac{1}{6}\right)^{10}
       \]

Understanding the concept of independence is vital for correctly applying probability rules and avoiding common pitfalls in both theoretical and practical scenarios. The product rule provides a straightforward way to calculate the probability of multiple independent events occurring together.

# Birthday problem

1. **Problem Statement**
   - What is the probability that, in a group of \( n \) people, at least two people share the same birthday?

2. **Counterintuitive Nature**
   - Intuitively, it seems unlikely for two people to share the same birthday in a small group. However, the probability of shared birthdays increases rapidly with the size of the group.

3. **Calculating the Probability**
   - **Complementary Approach:** It's easier to first calculate the probability that no two people have the same birthday and then subtract this from 1 to get the probability that at least two people share a birthday.

4. **Mathematical Calculation**
   - **Single Person:** With one person, there are no other birthdays to compare against, so the probability of no shared birthday is \( 365/365 = 1 \).
   - **Two People:** The second person must have a birthday on a different day than the first, which has a probability of \( 364/365 \).
   - **Three People:** The third person must have a birthday on one of the remaining 363 days, giving a probability of \( 363/365 \).

   The probability that all three have different birthdays is:
   \[
   \frac{365}{365} \times \frac{364}{365} \times \frac{363}{365}
   \]

   - **General Formula for \( n \) People:**
   \[
   P(\text{No shared birthdays}) = \frac{365}{365} \times \frac{364}{365} \times \frac{363}{365} \times \dots \times \frac{365 - (n - 1)}{365}
   \]

   - **Example Calculation for 9 People:**
   \[
   P(\text{No shared birthdays}) = \frac{365 \times 364 \times 363 \times \dots \times 357}{365^9} \approx 0.905
   \]

   - **For 23 People:** The probability drops below 0.5, making it more likely that at least two people share a birthday.
   \[
   P(\text{No shared birthdays}) \approx 0.493
   \]

5. **Visualization**
   - The probability of no shared birthdays decreases as the number of people increases.
   - **Graph Interpretation:** The x-axis represents the number of people, and the y-axis represents the probability of no shared birthdays. The curve quickly drops below 0.5 around 23 people.

6. **Conclusion**
   - In a group of 23 people, there is a greater than 50% chance that at least two people share a birthday, which is a surprising result given the intuitive expectation that larger groups are required for such a coincidence.

# Conditional Probability - Part 1

1. **Concept of Conditional Probability**
   - Conditional probability involves calculating the probability of an event occurring given that another event has already occurred. It's denoted as \( P(A | B) \), which reads as "the probability of A given B."

2. **Example: Coin Tosses**
   - **Initial Scenario:** The probability of getting two heads when tossing two coins:
     - Sample Space: HH, HT, TH, TT
     - Probability of both heads: \( P(\text{HH}) = \frac{1}{4} \)

   - **Conditional Scenario:** Given the first coin is heads, calculate the probability that both coins are heads.
     - New Sample Space: HH, HT (the cases where the first coin is heads)
     - Probability: \( P(\text{HH} | \text{First coin is H}) = \frac{1}{2} \)

   - **Conditional Probability Denotation:** \( P(A | B) \)
     - \( P(\text{HH} | \text{First coin is H}) \) = Probability of both heads given the first coin is heads.

3. **Example: Dice Rolls**
   - **Independent Events:** The outcome of one die does not affect the other.
   - **Scenario:** What's the probability that the first die shows a 6 and the sum of two dice is 10?
     - Sample Space: 36 possible outcomes
     - Favorable Outcome: (6,4)
     - Probability: \( P(\text{First is 6 and sum is 10}) = \frac{1}{36} \)

   - **Conditional Probability Approach:** Calculate using the formula \( P(A \cap B) = P(A) \times P(B | A) \)
     - \( P(\text{First is 6}) = \frac{6}{36} = \frac{1}{6} \)
     - Given the first die is 6, the probability that the sum is 10:
       \[
       P(\text{Sum is 10} | \text{First is 6}) = \frac{1}{6}
       \]
     - Therefore, \( P(\text{First is 6 and sum is 10}) = \frac{1}{6} \times \frac{1}{6} = \frac{1}{36} \)

4. **General Product Rule**
   - The formula for calculating the probability of the intersection of two events:
     \[
     P(A \cap B) = P(A) \times P(B | A)
     \]
   - **Independent Events:** If A and B are independent, then \( P(B | A) = P(B) \), and the formula simplifies to \( P(A \cap B) = P(A) \times P(B) \).

5. **Further Examples:**
   - **Sum of Two Dice Equals 10**
     - Probability without condition: \( \frac{3}{36} = \frac{1}{12} \)
     - Given first die shows 6: \( P(\text{Sum is 10} | \text{First is 6}) = \frac{1}{6} \)
     - Given first die shows 1: \( P(\text{Sum is 10} | \text{First is 1}) = 0 \) (since the maximum sum can be 7)

### Key Takeaways
- Conditional probability adjusts the likelihood of an event based on new information.
- It requires redefining the sample space based on the given condition.
- The product rule helps calculate the probability of two events happening together, taking into account their dependence or independence.

# Conditional Probability - Part 2

1. **Conditional Probability Overview**:
   - Definition: Calculating the likelihood of an event occurring given that another event has already happened.
   - Example: Probability of it being humid today if it rained yesterday.

2. **Example with Coins**:
   - Four possible outcomes when two coins are tossed: HH, HT, TH, TT.
   - Probability of HH (both coins landing heads) is 1/4.
   - **Given Information Changes Probability**:
     - If the first coin is heads, new sample space: HH, HT (probability of HH given first is heads = 1/2).
     - If the first coin is tails, new sample space: TH, TT (probability of HH given first is tails = 0).

3. **Product Rule for Independent Events**:
   - For independent events A and B: \( P(A \cap B) = P(A) \cdot P(B) \).
   - **Example with Dice**:
     - Probability of rolling two dice with the first one showing six and the sum being 10 is 1/36.
     - The general product rule (for possibly dependent events): \( P(A \cap B) = P(A) \cdot P(B | A) \).

4. **School Example - Dependent Events**:
   - 100 kids, 50 play soccer, 50 don't.
   - Two rooms: Room 1 shows World Cup, Room 2 shows a non-soccer-related movie.
   - Kids who like soccer are likely to go to Room 1, making the events dependent.

5. **Another School Example**:
   - 100 kids, 40 play soccer.
   - 80% of soccer-playing kids wear running shoes.
   - Calculation: 40 kids play soccer, 32 (80%) wear running shoes.
   - Probability: \( P(\text{soccer}) = 0.4 \), \( P(\text{running shoes} | \text{soccer}) = 0.8 \).
   - \( P(\text{soccer} \cap \text{running shoes}) = 0.4 \times 0.8 = 0.32 \).

6. **Probability Tree**:
   - Two paths: Plays soccer or doesn't play soccer.
   - **Plays Soccer**:
     - 40% play soccer.
     - 80% of them wear running shoes.
   - **Doesn't Play Soccer**:
     - 60% don't play soccer.
     - 50% of them wear running shoes.

7. **Summarizing Cases**:
   - **Independent Events**: Randomly splitting kids into two rooms.
   - **Dependent Events**: Showing a soccer game in one room affects the choice.
   - Visual Representation: Independent events have intersecting lines; dependent events do not intersect.

# Bayes Theorem - Intiution

1. **Scenario**:
   - A rare disease is present.
   - You take a highly effective test and test positive.

2. **Objective**:
   - Calculate the probability of actually having the disease given a positive test result.

3. **Bayes Theorem**:
   - Used to calculate conditional probabilities.
   - Applicable in many fields, including spam recognition and speech detection.

4. **Population and Disease Prevalence**:
   - Population: 1 million people.
   - Disease affects 1 in every 10,000 people.
   - Sick individuals: 100.
   - Healthy individuals: 999,900.

5. **Test Accuracy**:
   - 99% accuracy means:
     - Among 100 sick people, 99 are correctly diagnosed as sick.
     - Among 100 healthy people, 99 are correctly diagnosed as healthy.
   - Misdiagnosis rates:
     - 1% of healthy people are incorrectly diagnosed as sick.
     - 1% of sick people are incorrectly diagnosed as healthy.

6. **Calculations**:
   - **Diagnosed Sick (Left Group)**:
     - Correctly diagnosed sick: 99.
     - Incorrectly diagnosed sick (healthy misdiagnosed): 9,999.
   - **Diagnosed Healthy (Right Group)**:
     - Correctly diagnosed healthy: 989,901.
     - Incorrectly diagnosed healthy (sick misdiagnosed): 1.

7. **Probability of Being Sick Given Positive Test**:
   - Only consider the "Diagnosed Sick" group.
   - Sick and diagnosed sick: 99.
   - Total diagnosed sick: 99 (sick) + 9999 (healthy) = 10,098.
   - Probability: \( \frac{99}{10,098} = 0.0098 \) or less than 1%.

8. **Bayesian Tree Representation**:
   - **Branches**:
     - Total population: 1 million.
     - Sick (100) and Healthy (999,900).
     - Further divided into:
       - Sick and diagnosed sick (99), sick and misdiagnosed healthy (1).
       - Healthy and misdiagnosed sick (9999), healthy and diagnosed healthy (989,901).

9. **Key Insight**:
   - Despite a positive test result, the probability of being actually sick is less than 1%.
   - This is due to the relatively low prevalence of the disease compared to the large number of healthy individuals, leading to a higher number of false positives.

10. **Conclusion**:
   - The example illustrates the importance of considering the base rate (prevalence) of a condition when interpreting test results, as demonstrated by Bayes theorem.


# Bayes Theorem - Mathematical Formula

To determine the probability of having a disease given a positive test result, we use Bayes' Theorem. Let's define the events:
- \( A \): The event that a person is sick.
- \( B \): The event that a person tests positive for the disease.

**Given Information**:
1. Probability of being sick (\( P(A) \)):
   - \( P(A) = \frac{1}{10,000} = 0.0001 \) (0.01%)
2. Probability of not being sick (\( P(\neg A) \)):
   - \( P(\neg A) = 1 - P(A) = 0.9999 \) (99.99%)
3. Probability of testing positive given sickness (\( P(B|A) \)):
   - \( P(B|A) = 0.99 \) (99%)
4. Probability of testing positive given not being sick (\( P(B|\neg A) \)):
   - \( P(B|\neg A) = 0.01 \) (1%)

**Objective**:
- Find \( P(A|B) \), the probability of being sick given a positive test result.

**Bayes' Theorem Formula**:
\[
P(A|B) = \frac{P(A) P(B|A)}{P(B)}
\]

To compute \( P(B) \), the total probability of testing positive, we consider both scenarios (sick and not sick):
\[
P(B) = P(B|A)P(A) + P(B|\neg A)P(\neg A)
\]

### Calculation Steps
1. **Calculate \( P(B) \)**:
   \[
   P(B) = (0.99 \times 0.0001) + (0.01 \times 0.9999)
   \]
   \[
   P(B) = 0.000099 + 0.009999
   \]
   \[
   P(B) = 0.010098
   \]

2. **Calculate \( P(A|B) \)**:
   \[
   P(A|B) = \frac{P(A)P(B|A)}{P(B)}
   \]
   \[
   P(A|B) = \frac{0.0001 \times 0.99}{0.010098}
   \]
   \[
   P(A|B) = \frac{0.000099}{0.010098}
   \]
   \[
   P(A|B) \approx 0.0098
   \]

### Conclusion
The probability of being sick given a positive test result is approximately 0.98%, despite the test's high accuracy. This low probability is primarily due to the rarity of the disease compared to the population size, causing the number of false positives to outweigh the true positives. This scenario exemplifies the importance of considering base rates in medical testing and probabilistic reasoning.

# Bayes Theorem - Spam Example

Let's analyze the problem using Bayes' Theorem to determine the probability that an email is spam given that it contains the word "lottery."

**Definitions and Notation:**
- Let \( A \) denote the event that an email is spam.
- Let \( B \) denote the event that an email contains the word "lottery."

**Given Information:**
1. Total emails: 100
2. Number of spam emails: 20
3. Number of emails containing "lottery": 24
4. Number of spam emails containing "lottery": 14
5. Number of non-spam (ham) emails containing "lottery": 10

**Required Probability:**
- We want to find \( P(A|B) \), the probability of an email being spam given that it contains the word "lottery."

### Using Bayes' Theorem

**Bayes' Theorem Formula:**
\[
P(A|B) = \frac{P(A)P(B|A)}{P(B)}
\]

**Calculations:**

1. **Prior Probability of Spam (\( P(A) \)):**
   \[
   P(A) = \frac{20}{100} = 0.2
   \]

2. **Prior Probability of Not Spam (\( P(\neg A) \)):**
   \[
   P(\neg A) = 1 - P(A) = 0.8
   \]

3. **Probability of "lottery" given Spam (\( P(B|A) \)):**
   \[
   P(B|A) = \frac{14}{20} = 0.7
   \]

4. **Probability of "lottery" given Not Spam (\( P(B|\neg A) \)):**
   \[
   P(B|\neg A) = \frac{10}{80} = 0.125
   \]

5. **Total Probability of "lottery" (\( P(B) \)):**
   \[
   P(B) = P(B|A)P(A) + P(B|\neg A)P(\neg A)
   \]
   \[
   P(B) = (0.7 \times 0.2) + (0.125 \times 0.8)
   \]
   \[
   P(B) = 0.14 + 0.1
   \]
   \[
   P(B) = 0.24
   \]

6. **Posterior Probability (\( P(A|B) \)):**
   \[
   P(A|B) = \frac{P(A)P(B|A)}{P(B)}
   \]
   \[
   P(A|B) = \frac{0.2 \times 0.7}{0.24}
   \]
   \[
   P(A|B) = \frac{0.14}{0.24}
   \]
   \[
   P(A|B) \approx 0.583
   \]

### Conclusion

The probability that an email is spam given that it contains the word "lottery" is approximately 0.583, or 58.3%. This means that if an email contains the word "lottery," there is a 58.3% chance that it is spam, according to this model and the given data.

# Bayes Theorem - Prior and Posterior

Bayes' Theorem allows us to update our beliefs about the probability of an event occurring based on new evidence or information. Here's a formal breakdown of the concepts of *prior*, *event*, and *posterior*, followed by some examples:

### Key Concepts

1. **Prior Probability (P(A)):**
   - This is the initial probability of an event occurring, based solely on general information available before considering any specific data. It represents our belief about the event before new evidence is introduced.

2. **Event (E):**
   - This represents new information or evidence that might affect our belief about the occurrence of the event A.

3. **Posterior Probability (P(A|E)):**
   - This is the updated probability of the event A occurring, given the new evidence or event E. It reflects our revised belief after taking the new information into account.

### Examples

1. **Spam Email Example:**
   - **Prior (P(A)):** The probability that an email is spam based on general data is 20%, as there are 20 spam emails out of 100 total emails.
   - **Event (E):** The email contains the word "lottery."
   - **Posterior (P(A|E)):** The probability that the email is spam given that it contains the word "lottery" is 58.3%. This posterior is calculated by considering only the emails that contain the word "lottery" and determining how many of them are spam.

2. **Medical Diagnosis Example:**
   - **Prior (P(A)):** The initial probability of being sick without any specific test result, which is typically a small percentage based on general population data.
   - **Event (E):** The individual tests positive for a disease.
   - **Posterior (P(A|E)):** The probability that the individual is actually sick given the positive test result. This is updated using the accuracy of the test and the prior probability of the disease.

3. **Dice Rolling Example:**
   - **Prior (P(A)):** The probability that the sum of two dice is 10, which is 3 out of 36 (since there are three ways to get a sum of 10: (4,6), (5,5), and (6,4)).
   - **Event (E):** The first die shows a six.
   - **Posterior (P(A|E)):** The probability that the sum is 10 given that the first die shows a six, which is now 1/6, as the only valid pair is (6,4).

4. **Coin Flip Example:**
   - **Prior (P(A)):** The probability that two coins both land on heads, which is 1/4, as there are four equally likely outcomes: (HH, HT, TH, TT).
   - **Event (E):** The first coin lands on heads.
   - **Posterior (P(A|E)):** The probability that both coins land on heads given that the first coin is heads is now 1/2, as the remaining possibilities are (HH, HT).

### Conclusion

The posterior probability always provides a more refined estimate than the prior probability because it incorporates additional information from the event. This refined estimate helps in making more accurate predictions or decisions based on the newly available data.

# Bayes Theorem - The Naieve Bayes Model

1. **Problem Setup:**
   - Data set: 100 emails, 20 are spam (20% probability).
   - Initial classifier: Assumes 20% chance of being spam.

2. **Adding Features:**
   - **Feature 1:** Word "lottery"
     - 14 out of 20 spam emails contain "lottery."
     - 10 out of 80 non-spam (ham) emails contain "lottery."

   - **Feature 2:** Word "winning"
     - 15 out of 20 spam emails contain "winning."
     - 8 out of 80 ham emails contain "winning."

3. **Calculating Probabilities:**
   - **P(spam | lottery):** Probability an email is spam given it contains "lottery."
     - Calculation: (Number of spam emails with "lottery") / (Total emails with "lottery")
     - Result: 14/24 = 0.583

   - **P(spam | winning):** Probability an email is spam given it contains "winning."
     - Calculation: (Number of spam emails with "winning") / (Total emails with "winning")

4. **Combining Features:**
   - **Problem with Multiple Words:** Direct calculation with 100 words (or more) can result in zero counts (0/0).
   - **Solution:** Use the naïve Bayes assumption.

5. **Naïve Bayes Assumption:**
   - Assumes independence between the features (words "lottery" and "winning").
   - **P(lottery, winning | spam):** Estimated by multiplying P(lottery | spam) and P(winning | spam).
   - **P(lottery, winning | ham):** Estimated similarly.

6. **Naïve Bayes Algorithm:**
   - **Calculation for Two Words:**
     - **Prior (P(spam)):** 0.2 (20/100 emails are spam).
     - **Prior (P(ham)):** 0.8 (80/100 emails are ham).

   - **P(lottery | spam):** 0.7 (14/20).
   - **P(lottery | ham):** 0.125 (10/80).

   - **P(winning | spam):** 0.75 (15/20).
   - **P(winning | ham):** 0.1 (8/80).

   - **Posterior (P(spam | lottery, winning)):** 
     - Calculation: 
       \[
       \frac{P(spam) \cdot P(lottery | spam) \cdot P(winning | spam)}{P(spam) \cdot P(lottery | spam) \cdot P(winning | spam) + P(ham) \cdot P(lottery | ham) \cdot P(winning | ham)}
       \]
     - Result: 0.913

7. **Conclusion:**
   - The naïve Bayes classifier efficiently combines multiple features to estimate the probability of an email being spam.
   - Despite the independence assumption being unrealistic, it often yields effective results.
   - Example result: 91.3% probability of being spam if the email contains both "lottery" and "winning."

# Probability in Machine Learning

1. **Relevance of Probabilities in Machine Learning:**
   - Machine learning often involves calculating the probability of an outcome given certain features.
   - This is known as conditional probability.

2. **Examples of Conditional Probabilities in Machine Learning:**
   - **Spam Detection:** Probability that an email is spam given features like words, recipients, attachments, etc.
   - **Sentiment Analysis:** Probability that a text is happy or sad based on the words it contains.
   - **Image Recognition:** Probability of a specific object (e.g., a cat) being present in an image given the pixel values.

3. **Naïve Bayes Classifier:**
   - Uses Bayes' theorem to calculate the probability of a class (e.g., spam) given an event (e.g., word presence).
   - The classifier calculates a posterior probability based on a prior probability and observed events.

4. **Pure Probabilities in Generative Machine Learning:**
   - Focus on maximizing the probability of a data sample belonging to a certain class or category.
   - Examples include generating realistic images or coherent text.

5. **Application of Bayes' Theorem in Classifiers:**
   - **Example:** For spam detection, start with a prior probability of spam.
   - Observe events (e.g., presence of specific words) and calculate the posterior probability.
   - Result: A refined probability that an email is spam given the observed features.

6. **Image Recognition:**
   - A classifier provides the probability of an object (e.g., a cat) in an image based on the pixel values.
   - The model outputs a probability score indicating the presence of the object.

7. **Medical Diagnosis:**
   - Use of demographics, symptoms, and metrics to calculate the probability of a patient's health status.

8. **Sentiment Analysis:**
   - A model calculates the probability that a given text is happy or sad based on the words used.

9. **Generative Models:**
   - **Face Generation:** Models like StyleGAN generate realistic human faces by maximizing the probability that the generated pixels represent a face.
   - The generated faces can be highly realistic, even fooling observers.

10. **Supervised Machine Learning:**
    - Focuses on answering specific questions about the data (e.g., does the image contain a cat? Is this sentence happy?).

11. **Generative Models and Conditional Probabilities:**
    - Aim to produce data samples (e.g., images) that maximize the probability of belonging to a certain class (e.g., human faces).