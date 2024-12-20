# Evaluating Player Return Rate

I was tasked with analyzing what percentage of players return to the game after registration. To accomplish this, I developed a function that calculates player **retention** by days relative to their registration date.

## What is Retention?

**Retention** is a metric that measures the proportion of users who return to the game within a certain number of days following their initial registration. This indicator helps us understand how engaging our product is and its ability to retain user interest.

### Example Calculation:
1. Day X: The app was installed by 25 new users.
2. Day X+1: On the next day, 9 out of these users returned to the app.
3. First-day Retention = (9 / 25) × 100% = 36%.

## Function Development

To calculate the Retention rate, I created a function called [`retention_per_day`](https://github.com/hellodiogenes/retention/blob/main/retention_function.ipynb) which performs cohort analysis based on four parameters:

1. **reg** – file containing user registration dates.
2. **auth** – file containing user authorization dates.
3. **start** – starting date for data collection.
4. **end** – ending date for data collection.

The function allows calculating Retention for any time period starting from the user's registration date.

## Technologies Used

For the implementation of this function, I used **Python** and modules **Pandas**, **Seaborn**, and **Matplotlib**.

## Results

[`retention_per_day`](https://github.com/hellodiogenes/retention/blob/main/retention_function.ipynb) functions was created.
