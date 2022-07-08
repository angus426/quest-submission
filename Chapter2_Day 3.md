# Quests
## 1.In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.
```
  pub fun main(){
  var favouritePeople:[String]=["Jason","Mike","Andre"]
  log(favouritePeople[0])
  }
```
## Result
22:01:11 Script "Jason"

22:01:11 Script Result{"type":"Void"}
## 2.In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!
```
 pub fun main():UInt64{
 let websites: {String: UInt64} = {"Facebook": 4,"Instagram": 3, "Twitter": 1, "YouTube": 2, "Reddit": 5,"LinkedIn": 6}
 return websites["Instagram"]!
 }
```
## 3.Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).


