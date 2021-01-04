# ExtendedAccuracy

This is a draft version of the new accuracy package. So far it is just extended version of Rob Hyndmans accuracy package, but in the future it will be different.

Some example how it works

fit1 <- rwf(EuStockMarkets[1:200,1],h=100)
fit2 <- meanf(EuStockMarkets[1:200,1],h=100)
extended_accuracy(fit1)
extended_accuracy(fit2)
extended_accuracy(fit1,EuStockMarkets[201:300,1])
extended_accuracy(fit2,EuStockMarkets[201:300,1])
