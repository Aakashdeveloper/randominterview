given a 1-indexed array of integres
that is already sorted in non -descresing
numbers be  numbers[index1] and numbers[index2] 
where 1<= index1< index2<= numbers.length

return the indices of two number index1 and index2 added by one as
an integre array [index1,index2] of length 2

example1
input [2,7,11,15]
target = 9
return [1,2]

example2
input [2,3,4]
target = 6
return [1,3]


function calc(job){
    var income = 5
    if(job){
        var income = 50
    }
    {
        var income = 500
    }
    {
        var income = 5000
    }
    return income
    
}

console.log(calc(true))


let arra [
    {user:'Sateesh", addess:"Hyd", count:10},
    {user:'Ranjith", addess:"Hyd", count:11},
    {user:'Mahes", addess:"Hyd",, count:12}
]


async function(req,res){
    try{
        const a = await someFunctin()
         const b = await someFunctin1()
         res.send('ok')
    }
    catch(error){
        res.error()
    }
}

python
find all duplicate in an array of integeres
every integer only appers once or twice
we need to find which apper twice
input > [4,3,2,7,8,2,3,1]
output > [2,3]

javascript 
given a number n write a function that return the total number of primes up to and including n
ex 
n = 5 and result should be 3
n = 0 and result should be 0
n = 100 and result should be 24


fetch data from url and display data in table in vuejs


display in angular tempalate variable fee
if there are less than two digit for integer part of the the percent you have to display leading zeros
if theere are ess than two decimal digit you have to display trallig zeros
if there are more than three decimal digits you need have round to the 3 digts


amount div
if there are less than 9 digit for the integer part of the amount you need to display leading zeros the number
have to be separated after every thrid digit with comma
if there are  less than 2 decimal digit you have to display
trailing zero and if there are more you have to round value to 2 decimal

public class A{
    private A instance
    private List<String> items;

    pubic void setList(String[] items) {
        this.items = items
    }

    public void getSize() {
        this.items.size()
    }

    public boolean isAvailable(string search){
        for(int item: items){
            if(item == search){
                return true
            }
        }
    }

    public statuc A getInsatnce(){
        if(instance ==null){
            return new A()
        }
        return instace
    }

    Sting toString(){
        return "text1"
    }
}

find the longest palindrome substring word
is banana javascript


start by creating a composable function. Start with useToggle


    <script>

    /*implement composable function that toggle the state 
        use useRef and state in vuejs*/
        function useToggle(){

        }

        const [state,toggle] = useToggle(false)
    </script>

   

    <tempalate>
    <p>State:{{state?'ON':'Off'}}</p>
    <p @click="toggle">
    toggle
    </p>
    <template>


var studs = [{
    name:'a',
    age:12,
    marks:70,
    roll:1
},
{
    name:'b',
    age:12,
    marks:35,
    roll:2
},
{
    name:'c',
    age:12,
    marks:3,
    roll:3
},
{
    name:'d',
    age:12,
    marks:45,
    roll:2
}]

we need to convert into object
where key will be roll and value is marks
if roll number is repeated add all marks for that roll number

javascript
given a tree we want the value of tree node associated with level 
return in which tree node is present
along with the level 

(function(){
    var a = b = 3
})()


console.log("b defined? "+(typeof b !== 'undefined'))

https://jsonplaceholder.typicode.com/posts
call api in angular service using observable

now in html give me submit button and show two way data binding

nodejs
create a POST  endpoint /maxProfit to find the max profite
that can be obtained  by buying or selling share
the endpoint accept a JSON body
with an array of n integres represent the price
of the stock on n consecutive day 

the endpoint shoukd return JSON
max Profit >ma xprofite obtained by buying and selling stocks
transction > array iof tuples represting the buy an sell days that leading
to the max profite
each tuple should contain two integeres represnt the zero-indexed day numbers

RequestBody
{
    "price":[7,1,5,3,6,5]
}

Response
{
    "maxProfit":7,
    "transction":[
        {
            buy:1,
            sell:5
        },
        {
            buy:3,
            sell:6
        }
    ]
}

golang 
write a code that concurrently fetches the page content
of the provided url and count the instance of the word "Oz"


task 1: Add a comment to the count function explaining what it does

var {
    url = [] string{
        "htt1",
        "htt2",
        "htt3",

    }
}

func main(){
    fmt.Println("done")
}

func count(url string)(int, error){
    res, err := http.Get(url)
    if err != nil{
        return 0, count
    }
    defer res.Body.Close()
    body := bufio.NewReder(res.Body)
    count :=0;
    for{
        m := pattern.FindRenderIndex(body)
    }
}


var myobj ={
    foo:'bar',
    
    func:function(){
        var self = this;
        console.log('outer func'+this.foo)
        console.log('outer func'+self.foo)
        (function(){
            console.log('inner func'+this.foo)
            console.log('inner func'+self.foo)
        }())
    }
   
}


this code cause stackOverflo if arrat
var list = readHugeList()
var nextListItem = function(){
    var item = list.pop()
    if(item){
        //process the list item
    nextListItem()
    }
}

javascript

given a linked list swap every two adjcent nodes and return
its head.
you may not modify the value in the list nodes, only nodes itself may be changes

example1
input 1->2->3->4

output 2->1->4->3


javascript
example Input 1(currencies and conversion rates)
USD, GBP, 0.69 (means USD=GBP*0.69)
GBP, JPY 140 (means GBP=JPY*140,0)

example Input 2(quires)
USD, GBP, 0.69
GBP, JPY -> USD = GBP*0.69= JPY*140.0*0.69=JPY*(140.0*0.69)= JPY*96.6 -> 96.6

write function that is able to calculat ethe conversion rat eof every query in input2
Like (USD,CNY)



javascript
return the string
input  > uoy-era-woh
output> How are you

sql

write a query the fetch the 2nd 
highest salaery from each dept

table sturtcure
dept id | dept | name | salary

python 
input = "bcabc"
output = "bca"
remove duplicate form string

simple login page with typescript

.class-a{
    color:green
}

.class-b.class-a{
    color:green
}

javascript

write a function 
    accept a string return a function that
        return the string that was passed in

html and css
build up a page layout 
header on top 
footer at always content
in between we have content
if content is large make is scrollable and
scrollbar should be between content 
do not scroll header and footer

javascript

function getData(number){
    var a = 0;
    let b = 0;
    const c = 0;
    if(number > 5){
        var a = 1;
        let b = 1;
        const c = 1;
    }

    return [a,b,c]
}
getData(7)


var x = 21;
var girl = function(){
    console.log(x);
    x = 20;
}
girl()


function sum(){
    var a = 3;
    return function(b){
        console.log(a+b)
    }
}

var fn = sum()
console.log(fn(2))

javascript
write function getTotal which will return sum of all argment
getTotal(2,3,4,5)(4,5,6)

javascript

setTimeout(() => {
    console.log('1');
},0)

new Promise((resolve) => {
    console.log('2')
    resolve()
}).then(() => {
    console.log('3')
})

console.log(4)

queueMicroTask(() => {
    console.log('5')
})

new Promise((resolve,reject)=>{
    reject("6")
}).catch(console.log)


write function in typescript
when we either pass string of number argumnet
if pass string as argument then it should return 
string or if we pass number as argumnent
then it shoudl return number


write function which will return most repeated number in an array with its count{5:4}
const input = [2,5,2,[5,4,[5,6[5,6]]]]
output :{5:4}

react
A list of color composed of "red" and "green" element
A "square" component that renders a square of a given color and executes a click method
implement a parent component named "app"
that:
1. Uses the given square component to render all squares from the
"colors" list
2. Exposes the following
- which clicking a green square => change current element
to "red" + add 1 new "green" element to the end of list
- when clicking a red square => delete current element

vuejs
we have 3 garage user have to choose 1 gaurage and each 
a has 10 charger
b has 7 charger
c has 4 charger
of them have charger. user request for queue for charger
and click in the application
and we have to return on which queue number 


javascript function 
to we have 3 garage user have to choose 1 gaurage and each 
a has 10 charger
b has 7 charger
c has 4 charger
of them have charger. user request for queue for charger
write a logic to select charger
user can choose more then 1 garage either
     A or B 
     B or c
     A or C

     React with typescript
create parent and child and in child component make input field
and get value in parent component


javascript
comapre two array and return first array element that
are not present in array2
let arr1 = [1,2,3,4,5]
let arr2 = [0,2,3,4,5]

output>1

const Mocha = require('Mocha')
const mocha = new Mocha()
const except = require('chai').expect
mocha.suite.emit('pre-require',this,'solution',mocha)


function countChange(change){
    return undefined
}

Question javasript
return the value of the changes describe in the object
where the key is the type of coin and the value is the
number of that type of coin
values for each coin in cents:
PENNY --> 1
NICKEL --> 5
DIME --> 10
QUARTER --> 25

describe('change counter',function(){
    if('sum the change value',function(){
        const change = {
            QUARTER:1,
            DIME:2,
            NICKEL:3,
            PENNY:7
        }
        expect(countChange(change)).to.equal(0.67)
    })
})

list = 1,2,3,4,5
print list[10:]

Javascript
return wether a game has been won based on this player location scores
** A player wins if they 
* Have no location worth negative points and
* Hava a total of least 1000 points OR a 
single location worth 400 points or more
** Example ** [300,100,500] ->True (400 points 
or more in one location) 
*[300,200,300,350] ->True (1000 points 
or more ) 
*[300,200,300,350, -50] ->False (location with negative points)
** @param {number[]} locationScores An integer array
of this player location scores
* @ return {boolean} weather or not player has won 


Take input form use an
input = {10,7,4,6,8,10,11}
they have common differenc of 2 
need to find the longest subarray

javascript
problem name is  walking robot

Run the code in the REPL to object
implement the walk method this method take in a string,
path, where each character in the string corresponding to  
a potential movement of the robot. The robot can move 
up,down,left and right represented by the character 'U', 'D', 'L' and 'R'
All other character can be ignored . Assume the robot intiail position
 is at (0,0). The output of this method is robot final x and y
 coordinates relative to the inital position

 need to pass test case
 it('go 3 times up', function(){
     var input = 'UUU'
     var result = walk(input)
     assert.deepEqual(result,[0,3],'')
 })

 given a list of student test scores, find the best avergae grade
 each student may have more than one test score in the list

 complete bestAverageGrade function
if gas one parameter, scores, which is an array of student test scores
each element in the array is a 2d array of the form [student name, test score]
test score may be +ve or -ve integeres

if you end up with an avg grade that is not an integer you should
use a floor function to return the largest integere less than or equal to the avg.
return 0 for an empty array

example 
input 
[
    ["A","87"],
    ["B","100"],
    ["C","64"],
    ["D","22"]

]

output is 87

golang 
input text = AABAACAADAABAABA
pattern : AABA

output : pattern found at 0, 9 and 12 index

React
implement a button that can be renedere from a 
configuration coming from the server.Assume there
is already a component that get the configuration
from the server

a> color
b> width and height
c> text label
d> onclick action call
* send Rest Service request with some data
* change color and label
* local log

create dummy object coming form api

add functionality to button so that i can drag and drop button 
any where and it shoudl stay there

golang 
func main(){
    42.toString()
    int.toString(42)
    strcov.IToa(42)
    fmt.Sprintf("%v",42)
}

golang
print number 100 to 1 in desceinding order
start from 0 but still want to print in descending order
func main(){
    
   
}


golang
fizbuzz
for 1 to 100
multiple of 3 print fiz
multiple of 5 print Buzz
multiple of 3 & 5 print fizzBuzz
func main(){
    
   
}


package main

import "fmt"

func main() {
    for i := 1; i <= 100; i++ {
        if i%3 == 0 && i%5 == 0 {
            fmt.Println("FizzBuzz")
        } else if i%3 == 0 {
            fmt.Println("Fizz")
        } else if i%5 == 0 {
            fmt.Println("Buzz")
        } else {
            fmt.Println(i)
        }
    }
}

this check is expensive can we minisise the checks


golang

type RunningAverage struct{

}

func main(){
    ra := RunningAverage{}
    println(ra.add(1))
    println(ra.add(2))
    println(ra.add(3))
    println(ra.add(78))
    println(ra.add(11))

}

write the add function to add elmenet inside and get avearge

/////////
golang

given a root of a binary tree and an integer targetsum
return all root-to-leaf paths where the sum of the node values in
the path equal target sum. Each path should be returned as a list of the node value
not node reference

a root to-leaf path is a path starting from the root and ending at any leaf node
A leaf is a node with no children

input : root = [5,4,8,11,null,13,4,7,2,null,null,5,1,] target sum = 22
output = [[5,4,11,2],[5,8,4,5]]


let say i  have the ability to fetch all music that a given customer
has listened to in the past 30 days and how many times they listened to each song
i'd like to build a playlist containig all the music that people at a party have listened
to sorted by the number of times each song has been played by the group collectivity
how would you store the playlist?
what code would you need to run to get the next song to play?


design a chat application
we can support talk to agent and person to person not group
agent
what design we can create, data model as well as api call


write python
conncet web service authenictate and get data
what module we need

sql query 
id A B C
1  1 2 3
2  4 5 6
3  7 8 9
3  10 11 12
4  13 14 15
4 16 14  15

identify rows with matching id, valB and ValC

go object with active as true from array in javascript

javascript combine the array and remove duplicate 
var employee = [
    {
        user:'binary',
        age:36,
        active:true
    },
    {
        user:'Fred',
        age:40,
        active:false
    },
    {
        user:'pebbles',
        age:10,
        active:true
    }
]

var user = [
    {
        user:'binary',
        age:36,
        active:true
    },
    {
        user:'mike',
        age:40,
        active:false
    },
    {
        user:'raplh',
        age:10,
        active:true
    }
]


var user = [
    {
        empid:7616,
        firstName:'abc'
        active:true
    },
    {
        user:'mike',
        age:40,
        active:false
    },
    {
        user:'raplh',
        age:10,
        active:true
    }
]


golang
function where read string as input
i want the dictory as output give count of char in that string


nodejs

right rotation
input arr[] = {1,2,3,4,5}
k =2
output4,5,1,2,3

golang
write fizz buzz from 1 to 15
divide by 3 i s fizz 
divide by 5 i s buzz 
divide by 2 & 5 i s fizzbuzz 



golang
accept sequence of whitespace sepearted word as input and
print the words after removing all duplicate word and sort them alphanumerically

input 
hello world and practice makes perfect and hello world
output

again and hello  makes perfect practice world


golang 
count the frequency of word in a text
"go is easy to learn go is fun go is powerful"

golang handle panic

package main

import "fmt"

func recoverFromPanic(){
    if  r:= recover(); r !=  nil{
        fmt.Println("Recoverd from panic:", r)
    }

}

func doSomething(){
    panic("panic")
}

func main(){
    doSomething()
    fmt.Println("Program Conyinue")
}

public class Account{
    private string id;
    private string id;
    private string id;
    private string id;
}


AEM call external service and need to unique account on basis filter on firstname lastname zipcode

golang
write a progran that accept a sentense can calculate the number and digitts

input = "Hello world! 123"
output
letter = 10
digit = 3


golang 
calcutae avg score of  a class indivial score are marked
TOM 90
Tim 85
Kumar 60
Anjana 98
Kathy 76


golang 
 implemnt sumofsquare which take an integer, c and 
 return the sum of all squares between 1 and c.
 you will need to use select statements, goroutine and channels


 enhcance the code with find the difference between
 the square of the sum and sum of square


 improve if else condition javascript
 return  whether a game has been won based on this player's
 location scores

 A play win if they 
 have no location worth nrgative point and
 have total of at aleast 1000 point or a single locaion worth 400
 point or more

 example [300,100,500] -> true(400 poins or more in on location)
 [300,200,300,350] -> true
 [300,300,300,350,-50] -> false

 funtion isGameWon(locationScore){
     let negativeScore = false;
     let singleLocation = false;
     let totalScore = 0
     for (let i =0;i<locationScores.length;i++){
         if(locationScores[i] < 0){
             negativeScore = true
         }
         if(locationScores[i] >=400){
             singleLocation = true
         }

         totalScore += locationScores[i]
     }

     if(negativeScore){
         return false;
     }else{
         if(singleLocation){
             return true
         }else{
             if(totalScore >= 1000){
                 return true;
             }else{
                 return false
             }
         }
     }
 }


 input : [10,7,4,6,8,10,11,12,13,14]
 find out longest subarray in array with common difference
 ouput = [4,6,8,10] and [10,11,12,13]

 in react write componrnt that input and return output

 golang 
 text : AABAACAADAABAABA
 pattern : AABA

 output pattern found at 0,9 and 12 index


 golang 
 you have a word in lowercase yourr task is to write thei word
 using fragment  you are given
 Ecach element of fragment can be used more than once
 but they cannot overlap
 it is guaranteed that it is always possible to write
 the word using given fragment


 what is the min number of element you have to use?
 return 0 if its not possible to build a word

 example 
 bu + ild + wo + rd  
 BuildWord("buildword", []string{"buil","dwor","bu","ild","wo","rd"}) = 4



 angular
 create a button on the page open pop up
 on the pop there will be checkboxes and 
 when selecting the check box we click save
 the value of checkbox will be passed to dummy api service 



 React logic

 when login state is true render user list component into child

 React counter program using userreducer with increment and decrement


 golang lru cache implement

 package main

 import (
     "container/list"
     "fmt"
 )

 type LRUCache struct{
     maxEntries int
     cache map[interface{}]*list.Element
     evicted chan interface{}
     list *list.List
 }

 type entry struct{
     key interface{}
     value interface{}
 }

 func NewLruCache(size int) *LRUCache{
     lru := &LRUCache{
        maxEntries:size
        cache: make(map[interface{}]*list.Element)
        evicted: make(chan interface{},1)
        list: list.New()
     }

     return lru
 }


 func (lru *LRUCache) EvictionChannel() <- chan interface{}{
     return lru.evicted
 }

 func(lru *LRUCache) Add(key,value interface{}){
     if elem, ok := lru.cache[key]; ok{
         lry.list.MoveToFront(elem)
         elem.Value.(*entry).value = value
         return
     }

     if lru.list.len() >= lru.maxEntries{
         elem := lru.list.Back()
         if elem != nil {
             lru.list.Remove(elem)
             delete(lru.cache, elem.Value.(*entry).key)
             select{
                 case lru.evicated <- elem.Value.(*entry).key
                 default:
             }
         }
     }

     newEntry := &entry{key,value}
     ele := lru.list.PushFront(newEntry)
     lru.cache[key] = ele
     
 }

 func(lru *LRUCache) Get(key interface{}) (interfaceP{,bool){
     if elem,ok := lru.cache[key];ok{
         lru.list.MoveToFront(elem)
         return elem.Value.(*entry).value,true
     }
    return nil,false
}


 func(lru *LRUCache) Len() int{
     return lru.list.Len()
 }


 type User struct{
     Name string
     IP string
     Location string
 }

 create a map with name as a key using struct

 ///////
 create have component that have text box

 on mount we will call the api and get the data.
 and when we type something in text box i will again call api 
 and display resut 

 for api call create custome hook and resume for both call



 ////////
 javascript 

 let person = {
     "name":"john",
     "address":{"street":1}
 }

 let person1 = person

 person1.address.street = "2"
 person1.name = "Amit"
 console.log(person)
 console.log(person1)

 python
 write code i have a word i have not extract first
 letter which is not repeated
 input = 'swiss'
 ouput = 'w'


 golang
number := [8]int{10,20,30,40,50,60}
slice from 4 to 8


golang
i have user struct

type User struct{
    Name string
    IP String
    Location string
}

create a map for the key is name


write replace only 3 line code
Main(){
    x := 5
    replace(&x,10)
    fmt.Println(x)
}

List = [1,1,'j',true]
Mutuable (can be changed)
Allow duplicate

tuple = (1,2,3,'dd',5)
Immutable(cannot be changed)


dictionaries
{
    "name":"john",
    "age":10
}
Mutuable
key must be unique

sets
{1,2,3}
> Mutuable
> No Duplicate value


golang
similuate race condition example code


golang
package main
import "fmt"

func main(){
   isSapce := func(ch byte)bool{
       switch(ch){
        case ' ' : //errro
        case '\t':
        return true
       }
       return false
       
   }


   fmt.Println(isSpace('\t'))
   fmt.Println(isSpace(' '))
}


import (
    "fmt"
    "time"
)

func main{
    data  :=  []string{"one","two","three"}

    for _,v  := range data{
        go func(){
            fmt.Println(v)
        }()
    }

    time.sleep(3* time.second)
}


golang
[]string["flower","flow","flight"]

output:"fl"

find larget prefix


golang 
simple code how to go rotuine work

golang write function 
    there is imteral api call and get the Response
    Make http request if respons is good display else add error handling


golang code to connect to database
just check if connection is succesful return nothing
    else error

golang function read json file and print filed nam and id


React 
create 2 component  address search
parent and child

when we type address give suggestion for address
select approprite address and console.log
take dummy data


golang 
we define a simple "Greeter"
service with "Sayhello"method
that take a "hellorequest"message
containing a name of return 
a "HelloRequest" message write a greeet mesaage

service Greeter{}


(function(){
    var a = b = 3
})();

console.log("a defined? "+(typeof a!== 'undefined'))
console.log("b defined? "+(typeof b!== 'undefined'))


with simple html and javascript without css like enter pin 
we need to hide input char as soon user type after 3 sec
when type next char all previous must be hidden



React
creat a responisve layout of 3 column with flex box

javascript

const trans = [{
    "category":"sports",
    "amount":50
},
{
    "category":"sports",
    "amount":100
},
{
    "category":"sports",
    "amount":-20
},
{
    "category":"travel",
    "amount":100
},
{
    "category":"dinning",
    "amount":150
},
{
    "category":"travel",
    "amount":120
}]

write one code which will return output like its is retrun highest amount from particular category
[
    {"sports":100},
    {"travel":120},
    {"dinning":150}
]

flat this array with one loop only
const arr1 = [1,2,3,4,[5,6,[7,8]],[9,10]]

function should take index of nested array 
add try catch also and optimised to use one loop
we can pass varaible like example pass 1
output should be

input 1 > 1
output > [1,2,3,4,5,6,7,8,[9,10]]

input 1 > 2
output > [1,2,3,4,[5,6,[7,8]],9,10]


React
useEffect()
useEffect(fn,[dep])


you are given an integer 'num' you can swap two digit at most once 
to get the max values number
retur  the max valueed number you can Get

example 1
input > 2736
output > 7236


example 2
input > 9973
output > 9973

example 3
input > 1993
output > 9913

//////

python
take 2 diff size of unsorted array containing 
duplicate elements then merge the array without duplication
    in a sorted manner

python 
code to check if two strings are anagram of each other?
listen-silent
hear-hire
bored-robed


react
this.setState({
    counter:this.state.counte+this.props.incremtn
})


const obj1 = {a:1,b:{c:2,d:3}}
const obj2 = {b:{c:4,e:5},f:6}

javascript
write function take array of integrager and return 
most frequent value in array 



const numbers = ['10','10','10'].map(parseInt)


const fn = () =>  console.log(this)

const fn1 = fn.bind({something:true})

.net 
you have tasked with migrating a substatial VB 6.0 application to VB .net how would you approch this migration to  ensure minimal disruption and maintain functionality

javascript
Promise.reject()
    .then(
        () =>  console.log(0),
        () =>  console.log(1)
    )
    .finally(() => console.log(2))
    .catch(() => console.log(3))
    .then(() => console.log(4))



function run(){
    console.log('Script start')

    setTimeout(function(){
        console.log('settimeout 1')
    },1)

    setTimeout(function(){
        console.log('settimeout 0')
    },0)

    
}


javascript
var a = 1
function b(){
    a = 10
    return;
    function a(){

    }
}
b()

console.log(a)


for(var i = 1;i<=5;i++){
    setTimeout(function(){console.log(i)},1000)
}


html and csss
have 4 box and align them on all 4 corner with flex in css

javascript
a = 10
console.log(a)
var a


function x(){
    for(var i=0;i<5;i++){
        setTimeout(function(){
            console.log(i)
        },1000)
    }

    console.log('123')
}

x()


React
fetch todo items from the given api
render the todo items on the page
update the server when a todo item is checked or unchecked


api document
https://jsonplaceholder.typicode.com

[GET]/todos?userId=1
retrive all todo items for user 1

[patch]/todos/<todoid>
update the todo item with the given id


html css
we have outer and inner div we need to design css for both
we need to have inner box smaller and placed in center of outer large box

we have 2 indepent component and need to share data from component 1 to compoent 2 using redux flow


nodejs
i have list of book in sql and you want a route for insert and update data


we have 1 node project and 4 database how can i make 4 db connection with app

need sql query
emp_master > emp_id, emp_name, manager_id
fetch hierarchy of manager both in upward and doward direaction based on empid

E1>M1>M2>M3>M4> CEO(upward)
E1<F1<F2<(downward)

java
> hiberante arch and how jpa help us in lazy loading
> implement the redis cache in springboot
> oauth in spring boot
> how to take care cache thread pool
> java if we have parallel stream explain machenism
java compiliable future work in


angular
create custome direactive to move mouse in downarad direaction


create post  /maxProfit to find the max profit that can be obtained by buying and selling a
single share of a given stock multiple times.
the endpoint should access a json body with an array of n integre represent the price of the stock on n
consecutive daya

output json should

maxprofit: an integer the mac profit that can be obtained bt buying and selling
transction: tuple represent the by ans sell in the day

ex
input {
    "price":[7,1,5,3,6,4]
}

Response
{
    "maxProfit":7,
    "transcition":[
        {
            "buy":1,
            "sell":5
        },
        {
            "buy"3,
            "sell":6
        }
    ]
}




python
use pytest to write unit test

import aiohttp

async def fetch_user_data(user_id):
    url = f"http:/testurl/{user_id}"
    async withaiohttp.ClientSession() as session:
        async with session.get(url) as response:
         response.rasie_for_status()
         return await response.json()

def fetch_user_posts(user_id):
    return [{"id":1,"title":"Post 1"},{"id":2,"title":"Post 2"}]

def get_user_with_post(user_id):
    user_data = fetch_user_data(user_id)
    user_posts = fetch_user_posts(use_id)
    return{
        'user':user_data,
        'posts':user_data
    }


golang
create function name reverseString
inout > "hello"
output> "olleh"

golang
write function to check if a number is prime 

input > isPrime(2)
output > true

input > isPrime(4)
output > false

golang
partitioning into min number of deci-binary numbers

A decimal number is called deci-binray of each of its digit is either 0 or 1 
without any leading zero. example 101 and 1100 are deci-binary and 112 and 3001 is not

example1
input n = "32"
output = 3
explaination 10+11+11 = 32


example2
input n = "82734"
output = 8

golang



[0 0 1 0
0 1 0 0
0 0 0 1
0 1 0 0]

generate 4*4 output sould be 1'once


golang
if we have input  as array of string we need to find the value is palindrome or not

input = ["kayak","deter","Abba","make","deified"]
output = [['kayak','Abba','deified'],['deter','make']]


javascript
implement a function for dashify
input > hello
output> h-e-l-l-o


javascript 
remove duplicate from the array
input = [2,1,2,3,1,2,3]
output = [1,2,3]

React
create a todo list in ui without any functionality
use data 

const data = [
    {
        id:1,
        text:'Docoto call',
        completed:true
    },
    {
        id:2,
        text:'Metthing call',
        completed:false
    },
    {
        id:3,
        text:'Scoor call',
        completed:false
    }
]


javascript

let x = {}
x.forEach((y) => {console.log(y)})


python
given a partically filled 9*9 2d 'array grid[9][9]  the goal is to assign digit to the empty cell
so that every row,column and subgrid of size 3*3 contains exactky one instance of the digit fron 1 to 9

goal is to create a fun will retur the sudoko filed out in 2D arrat


javascript
sample bank app like creat account and get user account details
if account id already ther then should say id already takem

golang
implement a simple linklist


React 
in social media we have like and disalike
we want counter value to increment and dectrmenent


React
create 2 input 
one static currency as US
and in second one user can enter and on basic of that it should conver


//html css
// you have 4 divs align then in one line with eqaul space between using flex box


//javascript

// given a linked list swap every two adjcent nodes and return
// its head.
// you may not modify the value in the list nodes, only nodes itself may be changes



//javascript do not use inbuilt
revert the string
input  > uoy-era-woh
output> How are you


//javascript
write function getTotal which will return sum of all argment
getTotal(2,3,4,5)(4,5,6)


python

write function fill_shape  to fill coloer
where parameter type of canvas is (canvas: List[List[int]],x;int,y:int)
similar to ms paint(fill the canavs from the point clicke up until the closet boundries)
white pixels are reoresented with 0, 
black pixels are reoresented with 1,
the coolor are represented by 2


python
list of integere and find the number apperining most

python 
design a class to calculate area of shape 
it can square, rect or circle

Javascript 
the code recusive code will cause a stack overflow of the array list is too large
how can you fix this still retain the recusive pattern

var list = readHugeList()
var nextListItem = function(){
    var item = list.pop()
    if(item){
        //process the list
        nextListItem()
    }
}




HTML 
>> 


CSS 
>> in which case we should use translate insted of absolute positing in css
>> How to make div in center 
.centered {
    margin-left: auto;
    margin-right: auto;
    width: 50%; /* or any width */
  }
>> z-index property and how does it work
>> how to adjust height of one div with respect to other 
>> Change sequence of div in CSS 
.box1 {
    order: 3;
  }
  
  .box2 {
    order: 1;
  }
  
  .box3 {
    order: 2;
  }
>> How do you combine multiple media query conditions?
>> Purpose of  and, not, and or not in Media querry
>> Breakpoints in media query
------------------------
javascript

Array Destructuring:
const arr = [1, 2, 3];
const [a, b, c] = arr;
console.log(a, b, c); // Output: 1 2 3

Object Destructuring:
const obj = { x: 1, y: 2 };
const { x, y } = obj;
console.log(x, y); // Output: 1 2

Output of 
const nested = { a: [1, 2], b: { c: 3 } };
const { a: [x, y], b: { c } } = nested;
console.log(x, y, c); // Output: 1 2 3



return the string
input  > uoy-era-woh
output> How are you

javascript
write function getTotal which will return sum of all argment
    getTotal(2,3,4,5)(4,5,6)


javascript
    comapre two array and return first array element that
    are not present in array2
    let arr1 = [1,2,3,4,5]
    let arr2 = [0,2,3,4,5]

>>    Find the Largest Number in an Array
function findLargestNumber(arr) {
    return Math.max(...arr);
  }
>> How we make sure if the function is called after set amount of time 
    function debounce(func, wait) {
        let timeout;
        return function(...args) {
          clearTimeout(timeout);
          timeout = setTimeout(() => func.apply(this, args), wait);
        };
      }
      
      const log = () => console.log('Debounced!');
      const debouncedLog = debounce(log, 2000);
      debouncedLog(); // Function will be 

>> debounce in javascript

map
filter
spread
let vs var vs const
--------------------
Node
Diff between put vs patch
Differen http status code
what is middleware and which middleware we use fo post call
How jwt work
diff between first and refresh token
>> difference between require and import in Node.js?
(coding)
i have list of book in sql/mongo and you want a route for insert and update data

-----------
How to create custome pipe
what to restrict user to user certain page in app
What are the subjects in angular
Use of mergeMap and concatMap 
>>are higher-order mapping operators that transform Observables, but they handle the emissions of inner Observables differently:


(coding)
https://jsonplaceholder.typicode.com/posts
call api in angular service using observable


python
def abc(x):
    x = 10

y = 5
abc(y)
print(f"y = {y}")



def abc(x):
    x += [10]

y = [5]
abc(y)
print(f"y = {y}")

def abc(x):
    x = [10]

y = [5]
abc(y)
print(f"y = {y}")



def abc(max):
      count = 1
      while count <= max:
        yield count
        count += 1
        
out = abc(5)
print(next(out))
print(next(out))
print(list(out))


a = [[1,2,3],[4,5,6],[7,8,9]]
out = [[row[i] for row in a] for i in range(len(a[0]))] 
print(out)


you are given an array customers where customers[i] = [arrrival,time]
arrival > is the time of the customer. The arrival times are sorted in non-decreasing order.
time > is the time needed to prepare the order of the ith customer

when a customer arrives he give the chef his order and the chef start preparing it once he is idle
the customer wait till the chef finesh preparing the oder
the ched does not prepare food for more than one xustomer at a time
the chef prepare food foe the custome rin order they input

retunr the avergae wiaiting time of all customer solution with 10^-5 from the actual answer are
considered acceptrd

ex1
input [[5,2],[5,4],[10,3],[20,1]]
output> 3.25000

ex2
input [[1,2],[2,5],[4,3]]
output> 5.0000



Javascript
var a = (function(x){
    delete x;
    return x;
}(0))

console.log(a)

//output> 0



/////
Caching

> What is the use of in-memory caching in application
> Implement a simple logic with nodejs+mongodb+redis for get api

graphql
> What is GraphQL, and how does it differ from REST?
> What is a GraphQL query, and how does it differ from a mutation?
> Can you explain the concept of "schema stitching" in GraphQL?

Jenkins
> how are you using jenkins in your app and what are the different stages you have
> Can you write simple jenkins file with pull, build and deploy stages

MySql
> Create a query in MySql for student and marks table  to find top five student on basis of marks
where both table have releation ship of rollNo
( if done above)
> Please save above output in view


Serverless Architecture
> What id a usecase of lambda in your application
> what are the limitation on lambda
> How you are exposing lambda function
    Ans > Api gateway

MongoDB
> How does mongodb scale the database 
ans > horizonatly
> What is the concept of sharing
> What happen if we have even number of shared in election when one shared down
ans > add arbitrary node
