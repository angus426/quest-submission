# Chapter 2 - Day 2
## 1.Explain why we wouldn't call changeGreeting in a script
Because we call this function on the transaction to modify all things on the blockchain.
## 2.What does the AuthAccount mean in the prepare phase of the transaction?
It means who sign this transaction.
## 3.What is the difference between the prepare phase and the execute phase in the transaction?
We need the prepare function than put all things that we want to excute inside it.
## Contract
```
pub contract HelloWorld {
    
    pub var myNumber: Int

    pub fun updateMyNumber(newNumber: Int){
    self.myNumber = newNumber
    }   
    init(){
        self.myNumber=0
    }
}
```
## Transaction
```
import HelloWorld from 0x01
transaction(userInput: Int){
prepare(signer: AuthAccount){
}
execute{
HelloWorld.updateMyNumber(newNumber: userInput)
 }
}
```
## Script
```
import HelloWorld from 0x01

pub fun main():Int {
  return HelloWorld.myNumber
  }
  
```
## Result
```
16:46:40 
Script 
Result
{"type":"Int","value":"0"}
16:47:00 
Script 
Result
{"type":"Int","value":"46"}
```
