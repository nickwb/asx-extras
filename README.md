# asx-extras
Supplementary data relating to the ASX (Australian Securities Exchange)

## `hybrid_securities`
* Metastock compatible price history for (some) hybrid securities.
* Occassionally updated.
* Currently contains the following securities:
    * **CBAPC** - CommBank PERLS VI 
    * **CBAPD** - CommBank PERLS VII 
    * **CBAPE** - CommBank PERLS VIII 
    * **CBAPF** - CommBank PERLS IX 
    * **CNGHA** - Colonial Group Subordinated Notes 

## `trading_holidays`
* A list of days where the ASX did not (or will not) trade.
* Does not include weekends. Assume every Saturday and Sunday is also a non-trading day.
* Currently covers 1997-2037.
* No guarantee of accuracy! Some guesswork is involved for dates in the future, and I have had some difficulty confirming a few dates in the past. See `trading_holidays.todo` for more details.