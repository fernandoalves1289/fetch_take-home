Hello team,

In the last few days I had the opportunity to deepdive into some tables of our datalake. And I found some insights that could drive some successfull actions, but also with some critical data issues that should be solved for us to have a better understanding of our user.

Analyzing the consumer behavior of our platform, we have some insights that could drive some actions:

In the chart below, we see the top 5 brands with most value spent in purchases registered in our platform:

![image](https://github.com/user-attachments/assets/0eb4e3a1-d76d-4475-b282-7b87e371b9e2)

As you can see, we have the CVS products (their own store brand) far ahead in the leadership. I was wondering if we could evolve in our partnership with them. Even CVS being long-time partners of ours, we could offer them to double the points given to the users for all CVS owb-brand products. This would require some studies for efficiency and profitability, but sound a good idea that could be a win-win for us of for them.

Another study I did here is to determine who are our power users. I used some concepts of CRM to gather three different KPI's that could explain how an user is dedicated to our platform: recency (time since last purchase), frequency (how many times the user purchased with us) and value (the total value the user spent with us). With these three measure altogehther, we can determine our power users. With cutoffs I determined myself (but we can do other exercises to gather more or less users depending or the actions we do with them), I got to a number of 33 power users. We can see below the matrix showing their KPI's on these RFV values. To show our gratitude to these users, we could send some gift to all of them, and most import, counting on them to be our "influencers", so they could express their enchantment with our gift and we could use repost their publications on our socials.

![image](https://github.com/user-attachments/assets/869f42fe-e790-4015-94a1-3d243400adc4)

And finally, going deeper in our business, I checked our growth year by year considering the total news users we have registered in each one of them. It's important to say that we could gather these numbers considering other factors, like calculate real active members or check deeper KPIs, especially those related to P&L, to check the business effectiveness. But considering the total users, we have a scenario of decrease in new members in 2023 compared to 2022. And when we project the final numbers of 2024 (I only had data until september) we see another decrease. Please, let me know if the business is more directed to retain and engage the existent members in these two years. If not, it's a pain points for us to resolve together.

![image](https://github.com/user-attachments/assets/39356dcf-7c1c-42b3-889b-f209e7cb0471)

And now really to wrap up (sorry guys, the e-mail got a little long), I'd like to highlight some serious issues we have with our database concerning our transactional, user and product data. Even with these issues, I think the results I gathered have a good level of reliability, but I found some issues that we could act to refine an improve as soon as we can:
- A lot of our products are registered in our database without barcode number approximately 30% of them. This is the field connected to the transactions table for a posterior analysis of our top brands that determine our marketing and sales strategies. With these issues on the barcode information, we may be missing great opportunities for the sales and marketing team.
- Our transactions table is facing duplicated information. By some error in the migration of the infos of number of prodicts on the shopping cart and the values of sales, we have two lines for each purchase in our tables. Depending on how our data analytics team is performing the analysis, we may be reporting double the real number of transactions we have.

I also discovered inumerous other issues on our database that makes our analysis harder and longer and on which I'm available to do a call to explain them better. With these issues, the team need to correct the information for the analysis instead of doing the analysis itself and avoiding the team to generate deeper insights for the business. The addressing of these corrections should be prioritized.

Thanks for the attention and I keep available for questions or for a call to discuss any point of this e-mail.

Best regards,
Fernando Alves
