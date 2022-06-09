# 2913874040
My first GitHub repo

Student: Chen, Liyang
Number: 218523683
Source: https://github.com/clycly-ai/2913874040
Date: 2022.6.9

This README is used to outline Assessment 3 of SLE712.

Part 1
Question 1 and 2
The basic idea of these two questions is to build a table after downloading statistics from the Internet and add other information as needed or requested.
The specific steps have been presented in Rstudio. To create a table, you need to add data. For example, the average value is calculated first and then inserted into the table. Additionally, both the original form and the form with new information added need to be retained.

Questions 3 to 5
The steps for these three questions have been implemented within Rstudio. The requirements of these three problems are the common key information extraction and calculation in statistical information processing, and the requirements are very clear.

Questions 6 to 9
These four questions are about another common situation in statistics, the analysis of long-term statistics and trends. The problems therefore involve the computation of data from different periods and the creation of boxplots.

Question 6 uses Download.file to download the data to establish data induction, and questions 7 and 9 need to calculate the tree growth data of different locations and years based on the data of question 6. For example, the result of question 7 is that the tree data in the northeast has an average of 5.292 (M_NE_2005, 2005) and 54.228 (M_NE_2020, 2020). The standard deviation is 0.9140 (SD_NE_2005, 2005) and 25.2279 (SD_NE_2020, 2020).

The relevant data for the Southwest are averages:
2005 (M_SW_2005): 4.862 and 2020 (M_SW_2020): 45.596

Standard deviation:
2005 (SD_SW_2005): 1.1475 and 2020 (SD_SW_2020): 17.8735

From the data trend, the data values ​​of the trees in the southwest are higher, indicating that the trees here are growing better.

Question 8 Build a boxplot based on the original data from Question 6. The box plot is built using boxpolt according to the two tree planting places, and finally the "col =" command is added at the end of the command to match the pictures with different colors to distinguish them.

Question 10
The question asks to use the t.test command with the wilcox.test command to calculate the P value.

Part 2
Question 1
The key to this problem lies in the induction of gene information. After downloading separately using the download.file command, according to the discussion in the Internet Rstudio community, library("R.utils") and library("seqinr") are relatively simple methods. Thus this problem adopts this method.

The calculation result is that the sequence fragment values of E. coli and Weltevreden are both 3462.

Question 2-1
The completed set of problem 1 can be directly used in this problem to calculate the code length of two bacteria. Detailed programming calculation steps already exist in Rstudio.

The encoding length of E. coli (Lenth_Ecoli in R) is 3978528, and the encoding length of Weltevreden (Lenth_W in R) is 4278831.
Comparing the data of the two, the length of Weltevreden is obviously longer. Therefore, Weltevreden can carry more information than E. coli, and Weltevreden may have more gene expression and biological traits than E. coli.

Question 2-2
boxplot(Lenth_Ecoli,ylab="sequence length (bp)")
M_E <- mean(Lenth_Ecoli)
M_ME <- median(Lenth_Ecoli)
This problem requires building a boxplot for each of the two bacteria and calculating the mean and median.
This problem is not complicated. Use the boxplot command to create a box plot, and use the mean and median commands to calculate the mean and median respectively.

result:
The boxplots of the two bacteria have been drawn in Rstudio.

The mean (M_E) for E. coli was 938.5534 and the median (M_ME) was 831.
Weltevreden's mean (W_E) was 915.06223 and the median (M_ME) was 786.

Questions 3-5
This part could not be completed because I was scheduled for an unexpected business trip on May 29, 2022. The original plan was to return to complete the remaining issues after completing the business trip and hand them in on June 3, but the delay in the work caused the remaining issues to eventually not be completed, and the submission was also delayed.
