# AB-Testing-FreeShippingBar

Test Duration: 2019/06/14 - 2019/7/12

Device: Desktop

Hypotheses (metric growth estimation based on past test library):

1) Adding a Free Shipping Bar under the checkout button will increase the overall add-to-cart rate by 0.5%

2) Adding a Free Shipping Bar under the checkout button will increase the overall checkout rate by 0.35%

3) Adding a Free Shipping Bar under the checkout button will increase revenue by 0.25%

We suggest NOT rolling out the variation group - adding a free shipping bar under the checkout button. Because 
a) overall add-to-cart rate doesn’t have statistically significant improvement at both session-level and customer level, 
b) overall conversion rate doesn’t have statistically significant improvement at both session-level and customer level, 
c) revenue doesn’t have a statistically significant improvement in the variation group.
Although the free shipping bar seems to encourage our existing customers to convert faster, it didn’t increase the shopping frequency nor did it increase our revenue. On the other hand, it would discourage new customers from purchasing when they see the minimum threshold is beyond reach. Certain product categories (dress, skirt) are easier to reach the free shipping threshold. Therefore more likely for customers to convert, while other categories may have a negative effect.


