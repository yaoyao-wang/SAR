## 1. What is the SAR?

### SAR Formula
SAR(Tn)=SAR(Tn-1)+AF(Tn)*[EP(Tn-1)-SAR(Tn-1)]


The SAR indicator, developed by J. Welles Wilder Jr., is used by traders to determine trend direction and potential reversals in price.
The technical indicator uses a trailing stop and reverse method called "SAR," or stop and reverse, to identify suitable exit and entry points. 
Each day’s SAR value is calculated based on previous day’s SAR value, a preset acceleration factor, and the day’s extreme price.
We set acceleration factor by ourselves. The most popular initial factor is 0.02, and the most popular maximum is 0.2
When we observe a change in extreme price, we increase the factor by a preset amount, which is 0.02 by default, until the factor reaches the maximum value we give it, which is 0.2 in this case.
In other words, if we see there’s a persisting price trend, we keep increasing the acceleration factor until it reaches maximum or the trend stops.
On the other hand, extreme price is either the day’s highest or lowest price. If we observe a bullish price trend, we use highest price as extreme price; if we see a bearish one, we use lowest price.
After determining the day’s acceleration factor and extreme price, we can calculate the day’s SAR value by adding previous day’s SAR value to the product of the day’s acceleration factor and the difference between the day’s extreme price and previous day’s SAR value.
As we can see, SAR is closely connected to the price trend, as it affects both acceleration factor and extreme price.
The parabolic SAR indicator appears on a chart as a series of dots, either above or below an asset's price, depending on the direction the price is moving.
A dot is placed below the price when it is trending upward, and above the price when it is trending downward.
