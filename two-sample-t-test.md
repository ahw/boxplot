# Independent Samples t-Test

> While the single sample t-test is easiest to understand, it is rarely used in practice. That's because researchers don't often have a population mean to compare against an observed sample mean. A more common situation is to compare two different samples of subjects in order to decide if they come from the same population.
> For these comparisons, the null hypothesis is that the two samples can be treated as members of the same population for the variable of interest. This hypothesis is often stated as **m<sub>1</sub> - m<sub>2</sub> equals zero**, where m<sub>1</sub> refers to the mean of the first sample, and m<sub>2</sub> refers to the mean of the second sample. The alternative hypothesis states that the two samples come from different populations for the variable of interest. The alternative hypothesis and can be stated as
> - m<sub>1</sub> - m<sub>2</sub> is not equal to zero (for the two-tailed test) or
> - m<sub>1</sub> - m<sub>2</sub> is greater than zero (for the one-tailed test) or
> - m<sub>1</sub> - m<sub>2</sub> is less than zero (for the one-tailed test in the other direction).
>
> The graphic below shows the logic of creating the sampling distribution for two independent samples. The top of the graphic shows the population frequency distribution for two populations that are differentiated by the independent variable. For each of these two populations we select sample sizes, referred to as n1 and n2. Then a sampling distribution of the mean is generated for each population. To create a single sampling distribution, known as the sampling distribution of the differences between the means, all possible deviations between population 1 means and population 2 means are computed. These deviations are then plotted. The bottom of the graphic shows the sampling distribution of the differences between the means.
> ![Difference in samples](http://simon.cs.vt.edu/SoSci/converted/T-Dist/t-distribution.gif)
>
> It is important to recognize the the mean for the sampling distribution of the mean is zero when the null hypothesis is true. That's because both populations have the same mean, which also means that both sampling distributions will have the same mean, therefore, the average deviation between the means will be zero. Remember that hypothesis testing always uses the sampling distribution associated with the assumption that the null hypothesis is true.
>
> As the single sample t-test, the sampling distribution for the difference between the means is also a t-distribution. Further, the standard deviation (i.e., the standard error) of the sampling distribution of the difference between the means must be estimated because the decision to reject the null hypothesis is based on how many standard error units the observed difference in the sample means is from zero. Fortunately, this standard error can be estimated. Because we are now dealing with two samples this standard error is now called the standard error of the difference instead of the standard error of the mean.
>
> #### Standard Error of the Difference
> ![Standard error of the difference](http://simon.cs.vt.edu/SoSci/converted/T-Dist/stdErrDiff.gif)
>
> While this formula is complex, closer examination shows that the standard error of the difference is simply a function of the sample size of the two groups (i.e. n<sub>1</sub> and n<sub>2</sub>) and the variance on the dependent variable within the two groups (i.e., s<sub>1</sub><sup>2</sup> and s<sub>2</sub><sup>2</sup>). The computation of the observed independent samples t-value is also more complicated because of using two samples.
>
> #### Observed independent samples t-value
> ![Observed independent samples t-value](http://simon.cs.vt.edu/SoSci/converted/T-Dist/tScoreDiffNull.gif)

Source: http://simon.cs.vt.edu/SoSci/converted/T-Dist/