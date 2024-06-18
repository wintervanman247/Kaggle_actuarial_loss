# Kaggle_actuarial_loss
Description
The Actuaries Institute of Australia, Institute and Faculty of Actuaries and the Singapore Actuarial Society are delighted to host the Actuarial loss prediction competition 2020/21 to promote development of data analytics talent especially among actuaries. The challenge is to predict Workers Compensation claims using highly realistic synthetic data.

The data is fully synthetic and not specific to any legal jurisdiction or country. We are grateful to Colin Priest for building and supplying the dataset.

We invite the competitors to take claims inflation into account.

Upon completion of the competition we may get in touch with the winners for knowledge sharing opportunities within the actuarial community.

Evaluation
## Root Mean Squared Error (RMSE) Submissions are scored on the root mean squared error. RMSE is very common and is a suitable general-purpose error metric. Compared to the Mean Absolute Error, RMSE punishes large errors:
RMSE=1N∑1N(y(i)−y^(i))2−−−−−−−−−−−−−−−−⎷
where \\( \hat{y}(i) \\) the predicted value and \\( y(i) \\) is the original value. ## Submission File For every policy in the dataset, submission files should contain two columns: `ClaimNumber` and `UltimateIncurredClaimCost`. The file should contain a header and have the following format: ``` ClaimNumber,UltimateIncurredClaimCost WC8145235,1000.0 WC2005111,1000.0 WC6899143,1000.0 WC4785156,1000.0 WC8145238,1000.0 etc. ```
Timeline
The competition runs from 18 December 2020 to 11 April 2021 at 23:59 UTC*.

Original deadline was March 07 and was extended by 1 month.
Prizes
This competition has been made possible with the help of the following sponsors:   * 
* The Canadian Institute of Actuaries is the voice of the actuarial profession in Canada.

----------------------- Winners will be determined based on the leaderboard. Sponsors’ employees are not precluded from participating in the competition because the judging process is kept independent. Winners may be contacted for knowledge sharing opportunities, including writing a summary paper and participating in a webinar or panel discussions hosted by leading actuarial societies. You may wish to structure your summary paper based on the [Kaggle Winning Model Documentation Template](https://www.kaggle.com/WinningModelDocumentationGuidelines
Citation
Ali. (2020). Actuarial loss prediction. Kaggle. https://kaggle.com/competitions/actuarial-loss-estimation
