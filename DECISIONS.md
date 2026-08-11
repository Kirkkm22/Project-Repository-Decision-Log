# Decision Log
## Assignment 2: Dataset (2026-16-07)
- Dataset: AirBnb from kaggle
- Our team choose the AirBnb because it contains a large amount of real world data with over 30 different variables and over 50,000 AirBnb properties.
- Main variable of interest: total_price because every other variable should influence the total price as well as providing a holistic view of the propertys value.
- Key decision: From this dataset we would be able to draw conclusions on why certain AirBnB properties are more valuable than others, or what feautrues contribute most to their price. From this we can learn aspects of a propterty that are most for AirBnB owners should invest in to maxmize revenues. On the converse we could also look at which types of properties often sit below the market average and we could use the findings from sucessful properties to influence those below.
- Cleaning done: Since the dataset contained
## Assignment 3: Descriptive Stats (2026-26-07)
- Most surprising pattern: The most suprising 
## Assignment 4: Probability (202X-26-07)
- Normal vs. empirical, and why: 
We found that total price 
## Assignment 5: Inference (2026-08-09)
- What we tested, alpha, conclusion: One sample test producces z = -0.615 and p =0.269 so at alpha we fail to reject Ho hence there is not enough evidence to show that the true average is below 370$ despit the sample mean sitting uder it. he sample mean distance to city center (3.19 miles) is close enough to the hypothesized 3.2 miles that we fail to reject H0 (p = 0.425 at α = 0.10), supporting the claim that the average distance to the city centre is equal to 3.2 miles. The 95% confidence interval for the proportion of private-room listings is 35.738% to 36.566%, a tight band given the very large sample, letting us say confidently that just over a third of listings citywide are private rooms.
Reaction : with n over 51,000, the standard errors are tiny, so results track the sample statistics closely and the price test result, where a below $370 sample mean still doesn't show a true sample mean of below $370, makes sense once you see how large the price standard deviation is (509.72, versus a mean of 368.62). The price variable is also extremely right-skewed, driven by a handful of extreme luxury listings. A business could use these findings to avoid overreacting to the sample mean and instead price near the low-$370s with confidence that the market hasn't shifted meaningfully below that level, use the confirmed 3.2-mile average distance as a benchmark when evaluating new listing locations, and treat the ~36% private-room share as a reliable baseline for inventory-mix or marketing decisions (e.g., how much to invest in growing entire-home vs. private-room supply).
Assumptions: independence is reasonable if listings were sampled without strong duplication/clustering by host or building, and the sample size (tens of thousands) easily satisfies the "n ≥ 30" rule and the CLT for the two z-tests and the proportion CI (np and n(1-p) are both far above 10), so non-normality of the underlying price distribution (heavily skewed) isn't a real concern here. The huge sample size effectively guarantees the sampling distribution of the mean/proportion is normal even though the raw price variable itself clearly isn't.

## Assignment 6: Regression (202X-YY-ZZ)
- First predictor removed and why: ____
- Multicollinearity handling: ___