# Android-Advanced-Concepts

#Databinding Vs Kotlin Synthetic(KTX)

Kotlin Synthetic (KTX) can be used to avoid findViewById()  for smaller projects. It is very easy to use and really helpful in some situations.
But it is not a recommended best practice(by google) . Also you will miss a lot of advantages provided by data binding for larger complex projects. If you are planning to build an industrial level Android application with a proper architectural design, I highly recommend you to use data binding.
Some other benefits of Data binding.

1) Update the values automatically.(doesn’t have to keep track of all the ways a value can be updated)
2) More readable code
3) More maintainable code
4) Faster development times
5) Faster execution times
6) Well suited for MVVM and MVI architectures.
7) Errors can be found during the compile time.
8) No limitations comparing with Kotlin synthetic





