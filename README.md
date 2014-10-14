#Stocktile wearable

![stockwearable](https://github.com/ssegma/longhorn/blob/wear/stockwearable.jpg)

Expend original Stocktile function to a wearable device, and send out stock change notification to wearable when it changes over certain limits.

# How it works.

1. Use yahoo YQL service to get quotes
https://developer.yahoo.com/yql/console/?q=desc%20maps.map&env=store://datatables.org/alltableswithkeys#h=select+*+from+yahoo.finance.quotes+where+symbol+in+(%22FB%22%2C%22GOOG%22%2C%22BRCM%22)

2. Parse JSON down to stock entities,.

3. Display them..
4. Send it out to Wearable


#Longhorn
Longhorn is the code name of [Stocktile](https://play.google.com/store/apps/details?id=com.svpino.longhorn), an Android application to follow stock tickers from different markets around the world.



##Requirements
This project now comes in [Android studio](https://developer.android.com/sdk/installing/studio.html).


##License
This code is published using the Apache License Version 2.0. For more information, visit the [Apache License](http://www.apache.org/licenses/LICENSE-2.0) page.
