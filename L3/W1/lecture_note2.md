# Random Variables

1. **Definition of Random Variables:**
   - Random variables differ from algebraic variables (e.g., x = 3) as they can take multiple values.
   - Example: Temperature and the number of heads in coin tosses are random variables.

2. **Example of a Random Variable:**
   - Flipping a coin:
     - Variable $X$ = Number of heads.
     - Possible values for $X$: 0 (tails) or 1 (heads).
     - Probability of $X = 1$ is 0.5.
     - Probability of $X = 0$ is also 0.5.

3. **Extended Example:**
   - For 10 coin tosses:
     - Possible values for $X$ range from 0 to 10 heads.
     - Probability calculations: Each scenario where heads and tails are independent has a probability of $\frac{1}{2^{10}}$.
     - For varying numbers of heads (e.g., $X = 9$ ), the probability is more complex.

4. **Experimentation Approach:**
   - Conduct an experiment repeatedly to estimate probabilities.
   - Example: Running the coin toss experiment 500 times to create a histogram.
   - Histogram reveals that extreme values (0 or 10 heads) are less probable, while central values (e.g., 5 heads) are more common.

5. **Importance of Random Variables:**
   - They allow modeling of entire experiments.
   - Useful in expressing problems in probability, such as counting heads or defective products.

6. **Types of Random Variables:**
   - **Discrete Random Variables:**
     - Take finite or countable values (e.g., number of heads, dice rolls).
   - **Continuous Random Variables:**
     - Take an infinite number of values within an interval (e.g., waiting time, height).

7. **Differences from Algebraic Variables:**
   - Deterministic Variables:
     - Have fixed outcomes ( e.g., $x = 2$, $f(x) = x^2$ ).
   - Random Variables:
     - Associated with uncertain outcomes and can take many values.

8. **Finite vs. Infinite Values:**
   - Discrete variables: Listable finite or countable values (e.g., 0, 1, 2, 3...).
   - Continuous variables: Values within an entire interval (e.g., time in minutes).

9. **Countable vs. Uncountable Values:**
   - Discrete variables may have an infinite range but are countable.
   - Continuous variables cover uncountable intervals.


# Probability Distributions (Discrete)

1. **Probability Distribution:**
   - Represents all possible outcomes of an experiment and their associated probabilities.
   - Example: Tossing three coins with the random variable being the number of heads.

2. **Example with Three Coin Tosses:**
   - **Possible Outcomes:**
     - No heads: 1 way.
     - One head: 3 ways (head could be on any one of the three coins).
     - Two heads: 3 ways (heads could be in any combination of two coins).
     - Three heads: 1 way.
   - **Total Possible Outcomes:** 8.
   - **Probabilities:**
     - P(X = 0) = 1/8
     - P(X = 1) = 3/8
     - P(X = 2) = 3/8
     - P(X = 3) = 1/8

3. **Histogram Representation:**
   - Shows the probability distribution for the number of heads in three coin tosses.
   - Higher likelihood for 1 or 2 heads due to more possible combinations.

4. **Example with Four Coin Tosses:**
   - **Possible Outcomes:**
     - All heads or all tails: 1 way each.
     - One head or one tail: 4 ways each.
     - Two heads and two tails: 6 ways.
   - **Total Possible Outcomes:** 16.
   - **Probabilities:**
     - P(X = 0) = 1/16
     - P(X = 1) = 4/16
     - P(X = 2) = 6/16
     - P(X = 3) = 4/16
     - P(X = 4) = 1/16

5. **Example with Five Coin Tosses:**
   - **Possible Outcomes:**
     - All heads or all tails: 1 way each.
     - One head: 5 ways.
     - Two or three heads: 10 ways each.
   - **Total Possible Outcomes:** 32.
   - **Probabilities:**
     - P(X = 0) = 1/32
     - P(X = 1) = 5/32
     - P(X = 2) = 10/32
     - P(X = 3) = 10/32
     - P(X = 4) = 5/32
     - P(X = 5) = 1/32

6. **Probability Mass Function (PMF):**
   - Represents the probability distribution for discrete random variables.
   - **Requirements:**
     - All values must be non-negative.
     - The sum of probabilities across all values must equal 1.
   - **Example for X3 (number of heads in 5 coin tosses):**
     - Probability for each possible value (0 through 5 heads).

7. **Binomial Distribution:**
   - A model that represents the probability distribution of the number of successes (heads) in a fixed number of independent trials (coin tosses).
   - Covers the scenarios described for different numbers of coin tosses.

# Binomial Distribution

The binomial distribution models the number of successes (e.g., heads in coin tosses) in a fixed number of independent trials, each with the same probability of success.

#### Key Concepts

1. **Binomial Distribution Basics:**
   - **Definition:** The distribution of the number of successes in $n$ independent Bernoulli trials, each with a probability $p$ of success.
   - **Histogram:** Shows the probabilities of obtaining different numbers of successes (e.g., heads) in $n$ trials.

2. **Example: Coin Tosses**
   - **Number of Trials (n):** 10 coin tosses.
   - **Possible Outcomes:** Number of heads can range from 0 to 10.
   - **Probability Mass Function (PMF):** The probability of getting exactly $k$ heads is given by:
     $$P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}$$
     Where:
     - \(\binom{n}{k}\) is the binomial coefficient.
     - \(p\) is the probability of getting heads.
     - \(n\) is the total number of coin tosses.

3. **Calculating Probabilities:**
   - **Example:** Probability of getting exactly 2 heads in 5 coin tosses:
     $$P(X = 2) = \binom{5}{2} \left(\frac{1}{2}\right)^2 \left(\frac{1}{2}\right)^{5-2}$$
     - \(\binom{5}{2} = \frac{5!}{2!(5-2)!} = 10\)
     - Probability = \(10 \cdot \left(\frac{1}{2}\right)^5 = \frac{10}{32} = 0.3125\)

4. **General Formula:**
   - **Binomial Coefficient:** Counts the number of ways to choose $k$ successes (heads) out of $n$ trials (coin tosses).
     $$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$
   - **PMF for General Case:**
     $$P(X = x) = \binom{n}{x} p^x (1-p)^{n-x}$$
     Where $X$ is the random variable representing the number of successes.

5. **Symmetry Property:**
   - When $p = 0.5$, the PMF is symmetrical around $n/2$, reflecting equal probabilities of success and failure.

6. **Example with Dice:**
   - **Number of Trials (n):** 5 dice rolls.
   - **Probability of Success (getting a 1):** $p = \frac{1}{6}$.
   - **Probability of getting exactly 3 ones:**
     $$P(X = 3) = \binom{5}{3} \left(\frac{1}{6}\right)^3 \left(\frac{5}{6}\right)^{5-3}$$

7. **Another Example:**
   - **Number of Trials (n):** 10 dice rolls.
   - **Probability of Success (getting a 1):** $p = \frac{1}{6}$.
   - **PMF Parameters:** $n = 10$, $p = \frac{1}{6}$.

The binomial distribution is a powerful tool for modeling scenarios with a fixed number of trials and a consistent probability of success, such as coin tosses or dice rolls.

# (Optional) Binomial Coefficient

The binomial coefficient and distribution are foundational concepts in probability theory and combinatorics, particularly useful in scenarios involving a fixed number of trials with two possible outcomes.

#### Binomial Coefficient

1. **Concept:**
   - **Definition:** The binomial coefficient $\binom{n}{k}$ represents the number of ways to choose $k$ elements from a set of $n$ elements without regard to order.
   - **Formula:**
     $$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$
     where $n!$ (n factorial) is the product of all positive integers up to $n$.

2. **Example Calculation:**
   - For $n = 5$ and $k = 2$:
     $$\binom{5}{2} = \frac{5!}{2!(5-2)!} = \frac{5 \times 4}{2 \times 1} = 10$$

#### Binomial Distribution

1. **Concept:**
   - **Definition:** The binomial distribution describes the probability of obtaining a certain number of successes in a fixed number of independent Bernoulli trials (e.g., coin tosses) with the same probability of success.

2. **Probability Mass Function (PMF):**
   - **Formula:**
     $$P(X = k) = \binom{n}{k} p^k (1-p)^{n-k}$$
     where:
     - $n$ = number of trials
     - $k$ = number of successes
     - $p$ = probability of success
     - $(1-p)$ = probability of failure

   - **Example Calculation:**
     - If $n = 5$, $p = 0.3$, and $k = 2$:
       $$  P(X = 2) = \binom{5}{2} (0.3)^2 (0.7)^{5-2}$$
       $$  = 10 \cdot (0.09) \cdot (0.343) = 0.3105$$

3. **Symmetry and Bias:**
   - **Symmetry:** When $p = 0.5$, the distribution is symmetrical.
   - **Bias:** When $p \neq 0.5$, the distribution is skewed. For example, if $p = 0.3$, the distribution will be skewed towards fewer successes.

4. **Plotting:**
   - The histogram of probabilities for different values of $k$ (number of successes) can be plotted to visualize the binomial distribution. For biased coins or dice, probabilities adjust according to the specific value of $p$.

#### Practical Applications

1. **Binomial Coefficient Use Cases:**
   - **Combinatorics:** Counting combinations in various scenarios.
   - **Probability:** Calculating the likelihood of specific outcomes in experiments.

2. **Binomial Distribution Use Cases:**
   - **Quality Control:** Determining the probability of defective items in a batch.
   - **Clinical Trials:** Estimating the number of patients who respond to a treatment out of a given number of trials.

In summary, the binomial coefficient helps in counting combinations, while the binomial distribution provides a way to calculate probabilities for outcomes in scenarios with fixed trials and consistent success probabilities.

# Bernoulli Distribution

The Bernoulli distribution is indeed fundamental in probability and statistics, especially as it forms the basis for more complex distributions like the binomial distribution. In the Bernoulli distribution:

- **Success** is defined by the probability $p$.
- **Failure** is defined by the probability $1 - p$.

For a Bernoulli random variable $X$, the probability mass function (PMF) is given by:
- $P(X = 1) = p$
- $P(X = 0) = 1 - p$

This makes it quite versatile for modeling binary outcomes across various contexts. If you have any specific questions or need examples, feel free to ask!

# Probability Distributions (Continuous)

### **Discrete Distributions:**

- **Nature:** Events are countable and can be listed.
- **Examples:** Coin tosses, number of people in a town.
- **Probability Mass Function (PMF):** The probability of each specific outcome. For example, the binomial distribution describes the probability of a certain number of successes in a fixed number of trials.

### **Continuous Distributions:**

- **Nature:** Events are not countable, and they form intervals. There are infinitely many possible outcomes within any interval.
- **Examples:** Waiting time on the phone, amount of rainfall.
- **Probability Density Function (PDF):** Describes the probability of the random variable falling within a particular range. The PDF itself does not give probabilities but rather the density of the probability. The actual probability is found by integrating the PDF over an interval.

### **Key Concepts:**

1. **Probability of Exact Values:** 
   - In discrete distributions, the probability of exact values is well-defined and positive.
   - In continuous distributions, the probability of the random variable taking any exact value is 0 because there are infinitely many possible values. Instead, we talk about the probability of the variable falling within a certain interval.

2. **Probability as Area:**
   - In discrete distributions, the probability mass function sums to 1 over all possible outcomes.
   - In continuous distributions, the probability density function integrates to 1 over the entire range of possible values. The area under the curve of the PDF represents probabilities.

3. **Approaching Continuous Distributions:**
   - To get a continuous distribution from a discrete one, we consider finer and finer intervals. As the interval width approaches zero, the discrete bars turn into a continuous curve, reflecting a smooth distribution.

# Probability Density Function

#### **Discrete vs. Continuous Distributions:**

- **Discrete Distributions:**
  - **Nature:** Listable outcomes, such as the number of heads in coin flips.
  - **Probability Mass Function (PMF):** Provides the probability of each specific outcome.
  - **Example:** Rolling a die and counting the number of times it lands on a specific face.

- **Continuous Distributions:**
  - **Nature:** Outcomes form an interval and are not listable. For example, the time a call lasts.
  - **Probability Density Function (PDF):** Describes the density of probabilities over intervals. The probability of any exact value is 0, but probabilities over intervals can be calculated by integrating the PDF.
  - **Example:** The time a phone call lasts, where we are interested in intervals like 2 to 3 minutes.

#### **Key Concepts for Continuous Distributions:**

1. **Probability Density Function (PDF):**
   - **Definition:** A function $f(x)$ that represents the density of the probability at each point $x$.
   - **Interpretation:** The height of the PDF at any point represents the relative likelihood of the random variable being near that point, but not the probability itself.
   - **Area Under the Curve:** To find the probability of the random variable falling within an interval, calculate the area under the PDF curve over that interval.

2. **Probability Calculations:**
   - **Exact Value:** The probability of the random variable taking any exact value is 0.
   - **Intervals:** To find the probability that the variable falls within an interval, integrate the PDF over that interval.
     - For example, if $f(x)$ is the PDF and we want the probability of $X$ falling between $a$ and $b$, compute $\int_{a}^{b} f(x) \, dx$.

3. **Requirements for a PDF:**
   - **Non-Negative:** $f(x) \geq 0$ for all $x$ in the real line.
   - **Normalization:** The total area under the curve must equal 1, representing the certainty that the variable will fall somewhere within its range. Mathematically, $\int_{-\infty}^{\infty} f(x) \, dx = 1$.

#### **Visualizing PDF and Probability:**

- **Uniform Distribution Example:** If the call center's call duration is equally likely between 0 and 5 minutes, the PDF is a horizontal line, and the probability of the call lasting between 2 and 3 minutes is the area under this line within that interval.
- **Variable Density:** In distributions where certain intervals are more probable (e.g., more likely to last between 1 and 2 minutes than 4 and 5), the PDF will have different heights for different intervals.

# Cumulative Distribution Function

#### **Concept Overview:**

- **Definition:** The Cumulative Distribution Function (CDF) provides the probability that a random variable $X$ is less than or equal to a certain value $x$. Mathematically, it's expressed as:
  $$F(x) = P(X \leq x)$$
  where $F(x)$ denotes the CDF of $X$ at $x$.

#### **Discrete vs. Continuous Distributions:**

- **Discrete Distributions:**
  - **CDF Representation:** The CDF for discrete distributions is a step function. It increases in discrete jumps corresponding to the probabilities of the specific outcomes.
  - **Example:** For a call center with call durations ranging from 0 to 5 minutes, the CDF starts at 0 and increases in steps corresponding to the probability of the call durations falling within certain intervals.

- **Continuous Distributions:**
  - **CDF Representation:** The CDF for continuous distributions is a smooth, non-decreasing function. It represents the accumulation of probability density over intervals.
  - **Example:** For a call duration that can vary continuously between 0 and 5 minutes, the CDF is a continuous curve that represents the probability of the call lasting up to any given point.

#### **Properties of the CDF:**

1. **Range:** The CDF values lie between 0 and 1.
   $$ 0 \leq F(x) \leq 1$$

2. **Endpoints:**
   - **Left Endpoint:** $F(x)$ approaches 0 as $x$ approaches negative infinity.
   - **Right Endpoint:** $F(x)$ approaches 1 as $x$ approaches positive infinity.

3. **Monotonicity:** The CDF is a non-decreasing function. It cannot decrease as $x$ increases.

#### **Relationships Between PDF and CDF:**

- **For Discrete Variables:**
  - **CDF Calculation:** Cumulative probabilities are computed by summing up the probabilities of outcomes up to a given point. For example, if the probability mass function (PMF) provides the probabilities for call durations in specific intervals, the CDF accumulates these probabilities.

- **For Continuous Variables:**
  - **CDF Calculation:** The CDF is computed by integrating the probability density function (PDF) from negative infinity to $x$. In other words:
    $$  F(x) = \int_{-\infty}^{x} f(t) \, dt$$
    where $f(t)$ is the PDF.

#### **Use Cases:**

- **PDF (Probability Density Function):**
  - Useful for finding probabilities over specific intervals by calculating the area under the curve.

- **CDF (Cumulative Distribution Function):**
  - Convenient for finding the probability that the random variable is less than or equal to a given value without needing to calculate areas directly.

### **Summary:**

- The **PDF** describes the density of probabilities over an interval and requires integration to find cumulative probabilities.
- The **CDF** provides the cumulative probability up to a certain value and is a smooth or step function depending on whether the variable is continuous or discrete.

Both functions are essential in probability theory and statistics for different types of calculations and analyses.

# Uniform Distribution

The uniform distribution is a fundamental continuous distribution where all values within a specified interval are equally likely to occur. Here's a breakdown of its characteristics, probability density function (PDF), and cumulative distribution function (CDF):

#### **1. Conceptual Understanding:**

- **Example:** Imagine waiting for a bus that arrives every 10 minutes, but you don't know exactly when. If you wait for a random time between 0 and 10 minutes, the time you wait is uniformly distributed over this interval. Every waiting time in this range is equally likely.

- **Support Call Center Example:** If a call center answers calls uniformly between 0 and 15 minutes, the waiting time is uniformly distributed over this interval. There's no preferred wait time; every time between 0 and 15 minutes is equally likely.

#### **2. Probability Density Function (PDF):**

- **Definition:** The PDF of a uniform distribution is constant over the interval \([a, b]\) and zero outside this interval. 

- **Formula:** 
  $$f(x) = \frac{1}{b - a}$$
  for $a \leq x \leq b$, and $f(x) = 0$ otherwise.

- **Explanation:** The height of the PDF is constant and equal to $\frac{1}{b - a}$, where $b - a$ is the length of the interval. This ensures that the total area under the PDF curve is 1.

- **Example for $a = 0$ and $b = 15$:**
  $$f(x) = \frac{1}{15 - 0} = \frac{1}{15} \approx 0.067$$

#### **3. Cumulative Distribution Function (CDF):**

- **Definition:** The CDF gives the probability that the random variable $X$ is less than or equal to a value $x$. 

- **Formula:**
  $$F(x) = \begin{cases}
  0 & \text{for } x < a \\
  \frac{x - a}{b - a} & \text{for } a \leq x \leq b \\
  1 & \text{for } x > b
  \end{cases}$$

- **Explanation:**
  - For $x < a$, the CDF is 0 because no probability is accumulated before $a$.
  - For $a \leq x \leq b$, the CDF is a linear function that increases from 0 to 1. It is calculated as the proportion of the interval \([a, x]\) relative to \([a, b]\).
  - For $x > b$, the CDF is 1 because all possible probability has been accumulated.

- **Example for $a = 0$ and $b = 1$:**
  $$F(x) = \begin{cases}
  0 & \text{for } x < 0 \\
  x & \text{for } 0 \leq x \leq 1 \\
  1 & \text{for } x > 1
  \end{cases}$$

#### **Graphical Representation:**

- **PDF:** A horizontal line from $a$ to $b$ at height $\frac{1}{b - a}$, with the line being zero outside this interval.
- **CDF:** 
  - A horizontal line at 0 for $x < a$.
  - A straight line with a slope of $\frac{1}{b - a}$ from $a$ to $b$.
  - A horizontal line at 1 for $x > b$.

### **Summary:**

- The uniform distribution is used to model scenarios where all outcomes within a certain interval are equally likely.
- Its PDF is a constant function over the interval and zero otherwise.
- Its CDF increases linearly within the interval and is flat outside the interval.

This simplicity makes the uniform distribution a good starting point for understanding continuous probability distributions.

# Normal Distribution

The normal distribution, also known as the Gaussian distribution, is one of the most widely used distributions in statistics, science, and machine learning. Here's a detailed breakdown of its properties, formulation, and applications:

#### **1. Intuitive Understanding:**

- **Bell Curve:** The normal distribution is often visualized as a bell-shaped curve. It becomes more apparent as the number of trials in an experiment increases (e.g., the binomial distribution approximates a normal distribution with a large number of trials).

- **Real-Life Example:** Many natural phenomena, such as human heights, weights, and IQ scores, follow a normal distribution. In machine learning, this distribution often models various types of data and noise.

#### **2. Probability Density Function (PDF):**

- **Formula:**
  $$f(x) = \frac{1}{\sigma \sqrt{2 \pi}} \exp \left(-\frac{(x - \mu)^2}{2 \sigma^2} \right)$$
  where:
  - $\mu$ is the mean (center of the distribution).
  - $\sigma$ is the standard deviation (spread or width of the distribution).
  - $\sigma^2$ is the variance (square of the standard deviation).

- **Characteristics:**
  - The PDF is symmetric around the mean $\mu$.
  - The height of the PDF at any point $x$ is determined by how far $x$ is from the mean relative to the standard deviation.

- **Standard Normal Distribution:** When $\mu = 0$ and $\sigma = 1$, the distribution is called the standard normal distribution. Its PDF simplifies to:
  $$f(x) = \frac{1}{\sqrt{2 \pi}} \exp \left(-\frac{x^2}{2} \right)$$

#### **3. Cumulative Distribution Function (CDF):**

- **Formula:** The CDF does not have a closed-form expression but is the integral of the PDF. It is computed using tables or software.

- **Characteristics:**
  - The CDF starts at 0 for $x \to -\infty$ and approaches 1 as $x \to +\infty$.
  - It represents the probability that a random variable $X$ will take a value less than or equal to $x$.

#### **4. Properties:**

- **Mean ( $\mu$ ):** The center of the distribution. The highest point on the curve is at $\mu$.

- **Standard Deviation ( $\sigma$ ):** Measures the spread of the distribution. A larger $\sigma$ results in a wider and flatter curve.

- **Variance ( $\sigma^2$ ):** The square of the standard deviation, providing another measure of spread.

- **Symmetry:** The distribution is symmetric around the mean $\mu$.

#### **5. Standardization:**

- **Purpose:** Standardization converts any normal distribution into a standard normal distribution (with $\mu = 0$ and $\sigma = 1$).

- **Transformation:**
  $$Z = \frac{X - \mu}{\sigma}$$
  where $Z$ follows a standard normal distribution.

- **Usefulness:** Standardizing allows for the comparison of different normal distributions and simplifies calculations.

#### **6. Applications:**

- **Natural Phenomena:** Height, weight, IQ, and many other biological and physical measurements are often normally distributed.

- **Machine Learning:** Many models assume normally distributed variables, especially in linear regression, and in algorithms that rely on Gaussian assumptions.

- **Statistical Inference:** The normal distribution is foundational in inferential statistics, used in hypothesis testing and confidence intervals.

#### **Summary:**

- **The Normal Distribution** is fundamental in statistics, characterized by its bell-shaped curve, mean $\mu$, and standard deviation $\sigma$.
- **PDF and CDF:** The PDF describes the likelihood of different outcomes, while the CDF provides the cumulative probability up to a point.
- **Standardization** is used to convert any normal distribution to the standard normal distribution for easier analysis and comparison.

Understanding the normal distribution and its properties is crucial for various applications in data analysis, statistics, and machine learning.

# (Optional) Chi-Squared Distribution

### Noise Power and Chi-Squared Distribution

In communications, understanding noise and its impact on transmitted signals is crucial for interpreting and improving signal reliability. The concept of noise power and its distribution is key to this understanding. Here's a detailed breakdown of the Chi-squared distribution and its relevance:

#### **1. Noise and Power:**

- **Noise in Communication:** When transmitting a message, noise can corrupt the signal. This noise, $Z$, can originate from various sources such as interference, obstructions, and environmental conditions.

- **Gaussian Noise:** The noise $Z$ is often assumed to follow a Gaussian distribution with mean $\mu = 0$ and variance $\sigma^2 = 1$ (standard normal distribution).

- **Noise Power:** The power of the noise, denoted as $W$, is given by the square of the noise:
  $$W = Z^2$$
  This power measure is crucial for assessing the impact of noise on the signal.

#### **2. Distribution of Noise Power (Chi-Squared Distribution):**

- **Chi-Squared Distribution:** The noise power $W$ follows a Chi-squared distribution. Specifically:
  $$W \sim \text{Chi-squared}(\text{df})$$
  where "df" stands for degrees of freedom.

- **Single Degree of Freedom:** For $Z$ following a standard normal distribution, $W = Z^2$ follows a Chi-squared distribution with 1 degree of freedom.

  - **PDF:** The probability density function (PDF) of a Chi-squared distribution with 1 degree of freedom is:
    $$f_W(w) = \frac{1}{\sqrt{2\pi w}} \exp \left(-\frac{w}{2} \right) \text{ for } w > 0$$
    This PDF shows a distribution that starts high for small values of $w$ and tapers off for larger values.

  - **CDF:** The cumulative distribution function (CDF) of the Chi-squared distribution can be obtained by integrating the PDF.

#### **3. Multiple Degrees of Freedom:**

- **Sum of Squared Normals:** If you have $K$ independent standard normal variables, $Z_1, Z_2, \ldots, Z_K$, the noise power over $K$ transmissions is given by:
  $$W = Z_1^2 + Z_2^2 + \cdots + Z_K^2$$
  This follows a Chi-squared distribution with $K$ degrees of freedom.

  - **Chi-Squared with $K$ Degrees of Freedom:** As $K$ increases, the Chi-squared distribution becomes more symmetric and its PDF becomes more spread out.

  - **PDF for $K$ Degrees of Freedom:**
    $$  f_W(w) = \frac{1}{2^{K/2} \Gamma(K/2)} w^{(K/2) - 1} \exp \left(-\frac{w}{2} \right)$$
    where $\Gamma$ is the gamma function.

  - **CDF for $K$ Degrees of Freedom:** Similar to the single degree of freedom case, the CDF is obtained by integrating the PDF.

#### **4. Key Characteristics:**

- **For Small $W$:** The PDF grows rapidly due to the concentration of probability around small values.
  
- **For Large $W$:** The PDF becomes flatter and more spread out.

- **Degrees of Freedom Impact:** More degrees of freedom lead to a more symmetric and spread-out Chi-squared distribution.

#### **Applications:**

- **Noise Analysis:** Understanding the distribution of noise power helps in assessing the quality of the communication channel and designing better systems to handle noise.

- **Statistical Testing:** The Chi-squared distribution is also used in hypothesis testing and goodness-of-fit tests, where it plays a role in evaluating how well observed data fits a theoretical model.

Understanding the Chi-squared distribution and its role in noise analysis helps in improving communication systems and interpreting noisy data accurately.

# Sampling from a Distribution

Sampling from a probability distribution is an essential technique in both probability and machine learning. It allows us to generate synthetic data that mirrors the characteristics of an original dataset when collecting more data is impractical or expensive. Here's a detailed explanation of how to sample from a distribution:

#### **1. Discrete Distribution Sampling**

Consider a discrete distribution with outcomes $\{a, b, c\}$ and corresponding probabilities $p(a), p(b), p(c)$. For example:

- **Probabilities:**
  - $p(a) = 0.3$
  - $p(b) = 0.5$
  - $p(c) = 0.2$

To sample from this distribution:

1. **Cumulative Distribution Function (CDF):**
   - Construct the CDF by stacking the probabilities:
     $$\text{CDF}(x) = 
     \begin{cases} 
     0 & \text{for } x < 0 \\
     0.3 & \text{for } 0 \leq x < 0.3 \\
     0.8 & \text{for } 0.3 \leq x < 0.8 \\
     1.0 & \text{for } x \geq 0.8
     \end{cases}$$

2. **Generate a Random Number:**
   - Draw a random number $r$ uniformly from the interval [0, 1].

3. **Determine the Interval:**
   - Find where $r$ falls within the CDF intervals to assign the outcome. For instance:
     - If $r \in [0, 0.3)$, the outcome is $a$.
     - If $r \in [0.3, 0.8)$, the outcome is $b$.
     - If $r \in [0.8, 1)$, the outcome is $c$.

#### **2. Continuous Distribution Sampling**

For continuous distributions, such as the Gaussian distribution, the process is similar but involves the CDF of the continuous distribution.

1. **Cumulative Distribution Function (CDF):**
   - The CDF $F(x)$ for a continuous distribution maps each value $x$ to a probability between 0 and 1.

2. **Generate a Random Number:**
   - Draw a random number $r$ uniformly from [0, 1].

3. **Use the Inverse CDF:**
   - To find the corresponding value $x$ from the continuous distribution, use the inverse CDF (also known as the quantile function):
     $$x = F^{-1}(r)$$
   - This process maps the uniform random number $r$ to a value in the distribution according to its CDF.

#### **Example: Gaussian Distribution**

To sample from a Gaussian distribution:

1. **CDF and Inverse CDF:**
   - Compute the CDF for the Gaussian distribution and then use the inverse CDF to get the sampled value.

2. **Uniform Sampling:**
   - Generate a uniform random number $r$ between 0 and 1.

3. **Find $x$ Using Inverse CDF:**
   - Compute $x = F^{-1}(r)$, where $F^{-1}$ is the inverse of the CDF of the Gaussian distribution.

#### **Applications in Machine Learning**

- **Synthetic Data Generation:** Sampling methods allow the creation of synthetic datasets to augment training data or simulate various scenarios.
- **Monte Carlo Methods:** Used in simulations and optimization problems to approximate solutions based on random sampling.
- **Simulation Studies:** Useful for studying the behavior of systems under various probabilistic scenarios.

### Summary

Sampling from a probability distribution involves generating random numbers and mapping them to the desired distribution using the CDF or its inverse. This technique is foundational for creating synthetic datasets and conducting simulations in various fields of study.