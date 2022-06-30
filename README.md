# quest-submission
# Chapter 2 - Day 1
## Contract
```
pub contract JacobTucker {
    pub let is : String
    init(){
    self.is="the best"
    }
```
## Script
```
import HelloWorld from 0x03

pub fun main(): String {
    return HelloWorld.greeting
}
```
## Result
16:24:39 
New Script 
Result
{"type":"String","value":"the best"}
# Chapter 2 - Day 2
1.Explain why we wouldn't call changeGreeting in a script
Ans:Because we call this function on the transaction to modify all things on the blockchain.
2.What does the AuthAccount mean in the prepare phase of the transaction?
Ans:It means who sign this transaction.
3.What is the difference between the prepare phase and the execute phase in the transaction?
Ans:We need the prepare function than put all things that we want to excute inside it.
