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
