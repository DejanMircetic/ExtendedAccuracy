# ExtendedAccuracy

This is a draft version of the new accuracy package. So far it is just extended version of Rob Hyndmans accuracy package, but in the future it will be different.

Some example how it works
library(forecast)

fit1 <- rwf(EuStockMarkets[1:200,1],h=100)

fit2 <- meanf(EuStockMarkets[1:200,1],h=100)

extended_accuracy(fit1)

extended_accuracy(fit2)

extended_accuracy(fit1,EuStockMarkets[201:300,1])

extended_accuracy(fit2,EuStockMarkets[201:300,1])

#Dalji koraci:
-Izuci strukturu kako je Hyndman pravio pakete
-Procitaj knjigu o paketima, kako bi do kraja skontao kako stvari funkcionisu oko pisanja prateceg materijala i dodavanja spoljnih paketa o kome kod u tvom paketu zavisi
-i jedostavno igraj se isprobavaj razlicite dizajne paketa, ali probaj da reprodukujes neke pakete u potpunosti

