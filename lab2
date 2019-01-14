//: Playground - noun: a place where people can play

import UIKit

//Ex 1

func oldMcDonald(_ animal:String,_ sound:String)->String{
    let txt = "Old McDonald had a farm. Eyi Eyi oh.\n" +
    "And on his farm he had a \(animal). Eyi Eyi oh.\n" +
    "With a \(sound) \(sound) here, and a \(sound) \(sound) there.\n" +
    "Here \(sound) , there \(sound), everywhere a \(sound) \(sound).\n" +
    "Old McDonald had a farm. Eyi Eyi oh."
    
    //print(txt)
    //print()
    return txt
}

print(oldMcDonald("lamb","baa"))
print(oldMcDonald("dog","woof"))
print(oldMcDonald("cat","meow"))

//End Ex 1

//Ex 2

func xor(a:Bool, b:Bool)->Bool{
    //(true, false)->true
    //(false, true)->true
    //(false, false)->false
    //(true, true)->false
    
    return (a != b)
}

print("xor(true, true) =" ,xor(a:true,b:true))



func implication(a:Bool, b:Bool)->Bool{
    //(true, false)->false
    //(false, true)->true
    //(false, false)->true
    //(true, true->true
    return !a || b
}
print("implication(true, true) =" ,implication(a:true,b:true))
print("implication(true, false) =" ,implication(a:true,b:false))
print("implication(false, false) =" ,implication(a:false,b:false))
print("implication(false, true) =" ,implication(a:false,b:true))

//End Ex 2

//Ex 3

func factorial(n:Int)->Int{
    
    var f = 1
    var i = 1
//    while i<=n {
//        f*i
//        i+=1
//    }
    
    for i in 1...n{
        f*=i
    }
    return f;
    
}
factorial(n: 4)

func isPrime(n:Int)->Bool{
    //if n is prime it divides (n-1)!+1
    var t = factorial(n: n-1)+1
    
    return (t % n) == 0 //is prime
    
}

isPrime(n: 12)
isPrime(n: 13)






