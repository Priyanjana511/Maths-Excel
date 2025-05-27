# Maths-Excel
 # 1. Plotting and fitting of Binomial distribution and graphical representation of probabilities.
# Binomial Distribution
 The binomial distribution is a discrete probability distribution. It describes the outcome of binary scenarios, e.g. toss of a coin.
 # Binomial Distribution Formula
 <img width="178" alt="image" src="https://github.com/user-attachments/assets/be0f602a-d28b-4d89-b089-cea40718ab22" />
  Mean(µ=np)
 Variance(σ²=npq) 
Implementation in Excel:
 =BINOM.DIST(number_s, trials, probability_s, cumulative)
 Where: 
number_s: number of successes. 
trials: total number of trials. 
probability_s: probability of success on each trial. cumulative: TRUE
 returns the cumulative probability; FALSE returns the exact probability
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EXOiGejS3v5PgdwgVgnJMXABThXQ0V14P-D311He_iYtsA?e=6U74Ux

# 2. Plotting and fitting of Multinomial distribution and graphical representation of probabilities.
# Multinomial Distribution
The multinomial distribution is a multivariate generalization of the binomial distribution. Consider a trial that results in exactly one of some
 fixed finite number k of possible outcomes, with probabilities, p p , p(so that p ≥ 0 for i = 1 ,..., k and Σi=1kpi=1), and there are n independent trials.
 Then let the random variables X indicate the number of times outcome number i was observed over the n trials. Then X=( X , X ,...,X ) follows a
 multinomial distribution with parameters n and p, where p=( p , p ,...,p )
 # Multinomial Distribution Formula
 <img width="346" alt="image" src="https://github.com/user-attachments/assets/5b30f6e2-a92c-4b95-8075-84cb62bb62dc" />
When X=( x_{1}, x_{2} ,...,x k ) follows a multinomial distribution with the PMF given above, X_{i} follows a binomial distribution with n trials
and success probability pi
 how to implement in excel
 Multinomial MULTINOMIAL(X1,X2,X3)
 Probability = MULTINOMIAL PRODUCT(p1^X1,p2^X2,p3^X3)
 https://1drv.ms/x/c/ff30b5fe74a8fe1a/EQYEnI3nw5dDtAr11LD1tzYBEyo8LllM7doTxpjpI7dLDg?e=cuAODB
 
 # 3. Plotting and fitting of Poisson distribution and graphical representation of probabilities.
 # Poisson Distribution
 The Poisson distribution is a type of discrete probability distribution that determines the likelihood of an event occurring a specific number of times
 (k) within a designated time or space interval. This distribution is characterized by a single parameter, λ (lambda), representing the average
 number of occurrences of the event.
 # Poisson Distribution Formula
 <img width="181" alt="image" src="https://github.com/user-attachments/assets/3f7894f5-0729-43ce-bcf3-d3204bd6eb46" />
 how to implement in excel
 POISSON.DIST(number_s,average,cumulative)
 POISSON.DIST(k, λ ,FALSE)
 https://1drv.ms/x/c/ff30b5fe74a8fe1a/EbbT6XO4m8lEuz7AmrFK6OIBx0exi0aDJfEyBH200ZREJw?e=t9b93K
 
 # 4. Plotting and fitting of Geometric distribution and graphical representation of probabilities.
 # Geometric Distribution
 A geometric distribution is a discrete probability distribution that indicates the likelihood of achieving one's first success after a series of
 failures. The number of attempts in a geometric distribution can go on indefinitely until the first success is achieved. Geometric distributions are probability distributions that are based on three key assumptions. The trials that are being undertaken are self-contained. Each trial may only have one of two outcomes: success or failure. For each trial, the success probability, represented by p, is the same.
#  Geometric Distribution formula
<img width="173" alt="image" src="https://github.com/user-attachments/assets/6c8fc402-51fb-4a5f-be07-69352c9946e6" />
 how to implement in excel
 Probability = (1-p)^k*p
 https://1drv.ms/x/c/ff30b5fe74a8fe1a/Ed1OGvnF6idAhZyyTLh_huMBkd2b9vtVq0wGsi-RwP4ZuA?e=mtKk2i
 #  5. Plotting and fitting of Uniform distribution and graphical representation of probabilities.
 # Uniform distribution Formula
A uniform distribution is a distribution that has constant probability due to equally likely occurring events. It is also known as rectangular distribution (continuous uniform distribution). It has two parameters a and b: a = minimum and maximum. The distribution is written as U(a, b) b = A uniform distribution is a type of probability distribution where every possible outcome has an equal probability of occurring. This means that all values within a given range are equally likely to be observed.
# Uniform Distribution Formula
<img width="394" alt="image" src="https://github.com/user-attachments/assets/d023bcda-f4f8-46fb-97b2-eca791c71602" />
how to implement in excel
 P = (x - x ) / (b - a)
 https://1drv.ms/x/c/ff30b5fe74a8fe1a/EQ7x_Jgb2u5BrYoDYNVQ7LEBycseN6-6J4G72lMIR8X4cw?e=AU7Ieb
 # 6. Plotting and fitting of Exponential distribution and graphical representation of probabilities.
# Exponential Distribution
 If the probability of the event happening in a given interval is proportional to the length of the interval, then the Random Variable has an exponential distribution. The
 support (set of values the Random Variable can take) of an Exponential Random Variable is the set of all positive real numbers.
# Exponential Formula
<img width="207" alt="image" src="https://github.com/user-attachments/assets/b6fcc469-5c6a-48bd-8f3a-a0a849819235" />
 Here is the rate parameter and its effects on the density function. e is a constant roughly equal to 2.718
 How to Implement in excel
 EXPON.DIST(X,lambda,cumulative)
 EXPON.DIST (X,lambda, FALSE)
https://1drv.ms/x/c/ff30b5fe74a8fe1a/ERyGWN6cp0FHshI7mz9vh5sB4hAme3QeJ2xwG0sDFQid4A?e=iTH7PD
# 7. Plotting and fitting of Normal distribution and graphical representation of probabilities.
# Normal Distribution
We define Normal Distribution as the probability density function of any continuous random variable for any given system. Now for defining Normal Distribution suppose we take f(x) as the probability density function for any random variable X
# Normal Distribution Formula
<img width="244" alt="image" src="https://github.com/user-attachments/assets/5744bbb6-e713-46ae-8bd4-c2857d2882dd" />
how to implement in excel
 1. Input your data set into an Excel spreadsheet 
2. Find the mean of your data set
 =AVERAGE(cell range)
 "cell range" is a required component and the range of cells where your data exists, such as cells A1 through A64. 
. 3. Find the standard deviation of your data set 
=STDEV(cell range) 
4. Select a value for the distribution
 5. Type the NORM.DIST function and fill 
NORM.DIST(x, mean, standard deviation cumulative)
 NORM.DIST(x, mean, standard deviation, FALSE)
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EfWr_MigrwdNouqIw1_Qjc8BfQG63V4aLAm1DB-VBR27cw?e=JlSCet
# 8.Calculation of Cumulative Distribution Functions for Exponential and Normal Distributions
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EfI5_ks-vT9AjZHh9Jiyun4B0b1on5Nykbg6yy2ea9AGHA?e=PbRlKO
# 9. Given data from two distributions, find the distance between the distributions.
#  Euclidean distance
 Euclidean distance is the distance between two real distinct value.It is calculate by the square root of the sum of the squared difference elements in two vectors
<img width="292" alt="image" src="https://github.com/user-attachments/assets/6e2f1f5b-7e08-418d-a994-c84eb19ce1e2" />
 how to implement in excel
 = SORT(SUM X MYZ(array_X, array_Y))
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EbgF17d5mNRJlwvHYB-0WTkBHInRJGoK_-RnKyErphEMKg?e=mjOE6h
# 10. Application problems based on the Binomial distribution.
 Ques: Antibiotics occasionally cause nausea as a side effect. A major drug company has developed a new antibiotic called Phe-Mycin. The company claims that, at most, 10 percent of all patients treated with Phe-Mycin would experience nausea as a side effect of taking the drug. Suppose that we randomly select n = 4 patients and treat them with Phe-Mycin. Each patient will either experience nausea (which we arbitrarily call a success) or will not experience nausea (a failure). We will assume that p, the true probability that a patient will experience nausea as a side effect, is.10, the maximum value of p claimed by the drug company. Furthermore, it is reasonable to assume that patients' reactions to the drug would be independent of each other. Let x denote the number of patients among the four who will experience nausea as a side effect. It follows that x is a binomial random variable, which can take on any of the potential values 0, 1, 2, 3, or 4. That is, anywhere between none of the patients and all four of the patients could potentially experience nausea as a side effectSuppose that we wish to investigate whether p, the probability that a patient will experience nausea as a side effect of taking Phe-Mycin, is greater than. 10, the maximum value of p claimed by the drug company. This assessment will be made by assuming, for the sake of argument, that p equals .10, and by using sample information to weigh the evidence against this assumption and in favor of the conclusion that p is greater than.10. Suppose that when a sample of n=4 randomly selected patients is treated with Phe Mycin, three of the four patients experience nausea. Because the fraction of patients in the sample that experience nausea is 3/4.75, which is far greater than .10, we have some evidence contradicting the assumption that p equals.10
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EbK17Rl7__RGu-0e7TFJhO4BpK95P_1KS4K7XshiBAqZ7w?e=eGps8T
# 11. Application problems based on the Poisson distribution.
 Ques: In a cafe, the customer arrives at a mean rate of 2 per min. Find the probability of arrival of 5 customers in 1 minute using the Poisson distribution formula.
 https://1drv.ms/x/c/ff30b5fe74a8fe1a/Ee3Q8Zh6Z6pHrXRjRJ_wedEB3OM3yw_4QC_5exHWl6w_AA?e=WAO9hD
# 12. Application problems based on the Normal distribution.
Ques:: According to the website of the American Association for Justice, ^11 Stella Liebeck of Albuquerque, New Mexico, was severely burned by McDonald's coffee in February 1992. Liebeck, who received third-degree bums over 6 percent of her body, was awarded $160,000 in compensatory damages and $480,000 in punitive damages. A post-verdict investigation revealed that the coffee temperature at the local Albuquerque McDonald's had dropped from about 185 degree F before the trial to about 158 degree after the trial. This case concerns coffee temperatures at a fast-food restaurant. Because of the possibility of future litigation and to possibly improve the coffee's taste, the restaurant wishes to study the temperature of the coffee it serves. To do this, the restaurant personnel measure the temperature of the coffee being dispensed (in degrees Fahrenheit) at a randomly selected time during each of the 24 half-hour periods from 8 a.m. to 7:30 p.m on a given day. This is then repeated on a second day, giving the
 48 coffee temperatures in excel.
https://1drv.ms/x/c/ff30b5fe74a8fe1a/Eb9FJz7twIpDjT3gviUTuqUBG6cTpp-UMkLf6EdPX-uGsQ?e=UjVpQl
# 13. Presentation of bivariate data through scatter-plot diagrams and calculations of covariance.
 Bivariate Data/ Bivariate Analysis
 Bivariate analysis is one of the statistical analysis where two variables are observed. One variable here is dependent while the other is independent. These variables are usually denoted by X and Y. So, here we analyse the changes occurred between the two variables and to what extent
 how to implement in excel
 = COVARIANCE.P(array1,array2)
 The COVARIANCE.P function used the following arguments array 1, this is
 range or array of integer value.
# Pearson Correlation Coefficient formula
<img width="326" alt="image" src="https://github.com/user-attachments/assets/bf9181ad-a74a-4341-928b-ef28311aa374" />
 CORRELATION in excel and COVARIANCE in excel 
= CORREL(hours,score)
 = COVARIANCE.P(hours, score)
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EeosKuDIqGhFncVNmv6YTFsB5_Vxs5btnT-pPXoBJfgEgQ?e=ZXE3uR
# 14. Calculation of Karl Pearson's correlation coefficients.
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EWlbr47WdrVMjAdO1LGhTwIBZFbDicb7peIdPiz0ZfWXuw?e=39g2kX
#  15. To find the correlation coefficient for a bivariate frequency distribution.
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EVnLxgJnNudHuefpwJ_kDr8B-E2KvU6u5EOlImp4G2nbMg?e=TFTZhK
# 16. Generating Random numbers from discrete (Bernoulli, Binomial, Poisson) distributions.
 How to implement in excel
 = BINOM.INV (1,P, RAND()) will generate 1 or 0 with chance of 1 being P random number
https://1drv.ms/x/c/ff30b5fe74a8fe1a/ESp6cQFs5ZpPlKrnBLqWXBwBQgmxEvccMYUSqeQOYd6UXQ?e=eRUDNa
# 17. Generating Random numbers from continuous (Uniform, Normal) distributions.
 = NORMINV(RAND(),B2,C2)
 Where this RAND() function create your probability. B2 provides you mean,
 C2 refers your standand deviation.
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EZAzWsQcD3dHpSuIyA9ISBgB3G_NxXI9mmtx1aL5ffI8gw?e=4B82bA
#  18. Find the entropy from the given data set.
 The entropy of a random variable is the average level of information, surprise, or uncertainly inherent to the variable's possible outcomes. Given a discrete random random variable X which takes value in the alphabet x and distributed according to the P: x [0, 1] The entropy is H[X]
<img width="226" alt="image" src="https://github.com/user-attachments/assets/23b7208c-8f49-4c06-94b3-35fe823718ae" />
 The choice of base for log varies for different applications.
 Base 2 gives the unit of bits while base e gives natural units.
 Base o gives the units of H(X)
 An equivalent definition of entropy is the expected value of the self
 information of a variable.
https://1drv.ms/x/c/ff30b5fe74a8fe1a/EQtFVSHPV-ZOnN_JmiKglKwBPK0DUTXmlgWekRucsj5ajQ?e=eG6dbf
