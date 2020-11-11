//version = 4

strategy("Yaonology KDJ Indicators Tutorial", overlay=false, default_qty_type = strategy.percent_of_equity, default_qty_value = 100, currency = currency.USD, initial_capital = 10000, commission_type = strategy.commission.percent, commission_value = 0)

//Step Two: Parameter Setting

s = sar(0.02, 0.02, 0.2)                              //store the SAR value in a variable called s

//Step Three: Plotting

plot(s, style = plot.style_circles, linewidth = 2)    //plot the SAR indicator

//Step Four: Strategy Entry and Strategy Close

if crossover(close, s)
    strategy.entry("sar", long = true)
    
if crossunder(close, s)
    strategy.close("sar")
