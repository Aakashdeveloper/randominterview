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
>> What is the novalidate attribute used for in HTML forms
>> Regex to accept only numbers 
^\d+$
>> How can you enhance the accessibility of application 
>> Difference in async and defer attributes are used in the <script> tag.
async: Downloads the script asynchronously and executes it as soon as it is ready, without blocking the HTML parsing.
defer: Downloads the script asynchronously but defers execution until after the HTML parsing is complete.
>> Block VS Inline 
>> How we can allow user to open default mail 
<a href="mailto:example@example.com">Send Email</a>
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
>> Purpose of  and, not,   and or not in Media querry
>> Breakpoints in media query
>> Flex Container with Equal-Width Children
.container {
    display: flex;
}
.item {
    flex: 1; /* Equal width for all items */
    padding: 10px;
    background-color: lightcoral;
}
>> Reorder Flex Items
>> CSS to add background to even rows in list 
li:nth-child(even) {
    background-color: #f0f0f0;
}
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
     // Output: 1 2 3



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

>> What are some common RxJS operators?
map: Transforms emitted values.
filter: Filters emitted values based on a condition.
mergeMap / flatMap: Projects each value to an Observable and merges the results.
concatMap: Projects each value to an Observable and concatenates the results.
switchMap: Projects each value to an Observable and switches to the latest one.
debounceTime: Emits a value from the source Observable only after a specified delay.
distinctUntilChanged: Emits only distinct values based on a comparison function.
take: Emits only the first N values from the source Observable.

>> Purpose of combineLatest work?
>> How can you handle errors in RxJS?
>> Different type of subjects 
(coding)
https://jsonplaceholder.typicode.com/posts
call api in angular service using observable

>> How can we create custom themes in angular 
>> Purpose of snacbar in angular material

ES6  
>>How generator function works
>> Promise.all and Promise.race

SpringBoot 
How does Spring Boot handle dependency injection?
Explain the role of Spring Security in a Spring Boot application and 
how to configure basic authentication, JWT-based authentication, or OAuth2.
Discuss how Spring Boot supports databases with Spring Data JPA, Hibernate, and auto-configuration for different data sources.
Explain how to use @Scheduled annotations to schedule tasks in Spring Boot 
How to optimize the performance of a Spring Boot application?
lazy loading, proper caching mechanisms (e.g., @Cacheable), connection pooling, and profiling.
Explain how to design microservices using Spring Boot, 
including service registration and discovery with Eureka, API 
Gateway with Zuul or Spring Cloud Gateway, 
and inter-service communication using Feign.
What is the difference between @RequestMapping and @GetMapping or @PostMapping?
How does Spring Boot integrate with message brokers like Kafka or RabbitMQ?
Explain how Spring Boot can connect to message brokers, 
set up listeners, and handle asynchronous communication with messaging systems like Kafka or RabbitMQ.
How would you implement a custom filter or interceptor in Spring Boot?
Filter interface or interceptors using HandlerInterceptor and configure them in the Spring Boot application.

Java 8
>>What is the difference between map() and flatMap() in Java 8 Streams?
>> How can we implement map() and flatMap()
List<String> words = Arrays.asList("hello", "world");
List<Integer> wordLengths = words.stream()
                                 .map(String::length)
                                 .collect(Collectors.toList());
 map() transforms each element of the stream, whereas 
flatMap() is used when the transformation results in a stream of elements (i.e., flattening a stream of streams into a single stream). 
>> How can you make a class immutable in Java?
Use final for the class and its fields, ensure fields are initialized only once (in the constructor), and do not provide setters.
     Additionally, return deep copies of mutable objects when necessary.
>>How do you convert a List to a Stream in Java 8?
For example, List<String> list = Arrays.asList("a", "b", "c"); list.stream().
>> What is the @FunctionalInterface annotation used for?
it has exactly one abstract method and can be used with lambda expressions.
>> How can we imporve the efficiency of stream
Lazy Evaluation: Intermediate operations (like map or filter) are not executed until a terminal operation (like collect or forEach) is called.
Parallel Streams: Stream operations can be easily run in parallel with the parallelStream() method, improving performance for large datasets.

>> Steps to integrate oAuth in Java


microservice
>> How we manage communication between microservices?
Synchronous Communication: Typically achieved using REST, gRPC, or GraphQL for real-time data exchange.
Asynchronous Communication: Message brokers like Kafka, RabbitMQ, or ActiveMQ are used for event-driven architecture, where services communicate using events and messages.
Service Mesh: Tools like Istio or Linkerd help manage service-to-service communication by providing traffic routing, load balancing, and retries.
API Gateway: A gateway acts as a single entry point for client requests and routes them to the appropriate services.
>>. What are the common strategies for inter-service communication in microservices?
Direct Communication:
REST: Typically used for synchronous HTTP-based communication.
gRPC: A high-performance RPC framework that uses protocol buffers for data serialization and supports synchronous communication with better performance.
Message Brokers:
Asynchronous Communication: Kafka, RabbitMQ, or ActiveMQ are used to enable services to communicate asynchronously by sending messages to a broker.
Event-Driven Architecture: Microservices publish events to an event bus or a message broker, and other services subscribe to these events.
Service Mesh: Service meshes like Istio or Linkerd provide advanced communication capabilities such as traffic routing, observability, and fault tolerance without changing the application code.

SQL :
>> write a query to find the second highest salary in a table?
SELECT salary FROM Employees
ORDER BY salary DESC
LIMIT 1 OFFSET 1;
>> Delete duplicate rows while keeping the one with the lowest id
WITH CTE AS (
    SELECT *, ROW_NUMBER() OVER (PARTITION BY column1, column2 ORDER BY id) AS rn
    FROM my_table
)
DELETE FROM my_table
WHERE id IN (SELECT id FROM CTE WHERE rn > 1);
>> Find employees whose salary is above the average salary in their department:
SELECT employee_id, salary 
FROM Employees e
WHERE salary > (SELECT AVG(salary) 
                FROM Employees 
                WHERE department_id = e.department_id);

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
> difference between in-memory and distributed caching 
>> How does Redis handle persistence?
>> How to monitor and manage Redis performance
>> How does Memcached handle data expiration and eviction?
Explain the two main persistence mechanisms: 
RDB (Redis Database Backup) and AOF (Append-Only File), and their trade-offs.

graphql
> What is GraphQL, and how does it differ from REST?
> What is a GraphQL query, and how does it differ from a mutation?
> Can you explain the concept of "schema stitching" in GraphQL?
>> Role of introspection in GraphQL
> Given a GraphQL query, write the resolver function for fetching data from a database.
> Implement a pagination solution for a list of items using cursor-based pagination in GraphQL.
> How do you handle file uploads in GraphQL?
> How do you implement caching in a GraphQL server?


Jenkins
> how are you using jenkins in your app and what are the different stages you have
> Can you write simple jenkins file with pull, build and deploy stages

MySql
> Create a query in MySql for student and marks table  to find top five student on basis of marks
where both table have releation ship of rollNo
( if done above)
> Please save above output in view
> Write a SQL command to update data through a view and handle any potential issues with view updates.
>> Provide the SQL command for updating data and discuss any limitations or requirements.
>> What is a materialized view, and how does it differ from a regular view?


Serverless Architecture
> What id a usecase of lambda in your application
> what are the limitation on lambda
> How you are exposing lambda function
    Ans > Api gateway
> What are the common triggers for serverless functions?
> How do you handle authentication and authorization in a serverless environment?
    xplain methods such as API Gateway authorizers, OAuth, JWT tokens, and integrations with identity providers.
> How do you handle versioning and rollback in serverless functions?
     such as using AWS Lambda versions and aliases, 
     strategies for rolling back to previous versions if needed.


MongoDB
> How does mongodb scale the database 
ans > horizonatly
> What is the concept of sharding
> What happen if we have even number of Replica in election when one Replica down
ans > add arbitrary node
> How do you insert a document into a MongoDB collection?
> How do you perform aggregation in MongoDB?
    Discuss using the aggregate method and 
    common stages like $match, $group, $sort, and $project:
> How do you perform text search in MongoDB?
    db.myCollection.createIndex({ description: 'text' });
   db.myCollection.find({ $text: { $search: 'keyword' } });
> best practices for managing MongoDB performance and reliability?
     monitoring with tools such as MongoDB Atlas, 
     sharding for large datasets, 
     indexing for query optimization
     backups for data recovery.


React >>
>> manage state in a React application
Local Component State: Using useState or this.state in class components.
Context API: For global state management.
State Management Libraries: Such as Redux or Zustand for more complex state nee
>> How do you optimize performance in React applications?
    Memoization: Using React.memo and useMemo to prevent unnecessary re-renders.
Code Splitting: Lazy loading components with React.lazy and Suspense.
Avoiding Inline Functions: Creating functions outside of render methods to prevent re-creation on each render.
Virtualization: Using libraries like react-window or react-virtualized for rendering large lists efficiently.


golang
step1
4,7,12,19,28,.......200
(generate this screen in golang)

step2
generate square for odd number

step3
add the square to the mat and calculate the total area occuiped

all three step should have parallel and in finally 


package main

type ( 
    Shape interface {
    getArea() float64
    }

    Square struct{
        side float64
    }

    Mat struct{
        shapes []Shape
    }

    tPlaceCh chan Shape


)

func (s *Square) getArea() float64{
    return s.side * s.side
}

func (m  *Mat) getAreaOccupied() (result float64){
    for _, shape := range m.shapes{
        result += shape.getArea()
    }
    return
}

func (m *Mat) place(shape Shape){
    m.shapes = append(m.shapes, shape)
}


nodejs
const qs = require('querystring').parse('foo=bar&abc=xyz&abc=123')

how can we access value 123

option 
1) qs['abc']['abc']
2) qs[0]['abc']
3) qs['abc'][1]
4) qs['abc']  > correct

mongodb
what is the principle implication of using bulk write operation in MongoDb
1) decreasing performance
2) Increased throughput  >> correct
3) Increased data quality
4) increases network traffic

nodejs execute event loop starting from newwst first

microservice nodejs
what happen to deployed microservice when you use the 'service instance per container' deployment pattern

1) they become isolated
2) they share resource
3) they become difficult to scale up or down
4) they are inrestricted in terms of cpu/memory consumption

nodejs
which npm command prints all local packages that need updating
ans > npm outdated

nodejs
how can you modify node's global module search path
ans> set NODE_PATH=C:\path\to\your\global\modules

Javascript
similar strings
two strings are said to be similiar if they are composed of the same character
example "abaca" and "cba" are similiar since both of them composed of character 
'a','b','c'
but 'abaca' and 'bcd' are not similiar

given an array of string words of length n, find the number of pairs of string that are 
similiar

example
n =3 , words=['xyz','foo','of']
answer = 1

create function countSimilarPairs(word){

}


golang
implement function to merge two sorted link list as
new sorted linklist


golang
we need to refeactor large if statement
using polyomormisum


golang
we need to start http server and define handler and respond with myname


golang
we need to print number from 1 to 10
one go routine will print odd and one even
and print output in correct order

goalng
given three array soretd in non-decreasing order
print all comman element in these array

input 
arr1[]= {1,5,10,20,40,80}
arr2[] = {6,7,20,80,100}
arr3[] = {3,4,15,20,70,80,120}
output = 20 ,80

python 

React
Cretae todoList user able to add edit and complete and

React
the application has 2 component
file > contains input box and filelist component
fillist > display the list of files and filders an let user add 
more files

intial Data:
{
    name:src,
    isOpen:true,
    files:[
        {
            "name":"App.js"
        },
        {
            name:"component",
            "isOpen":false,
            "files":[{name:"File.js"}]
        }
    ]
}

requirent
1) inital component should display file folder structure
accorsing to the given intial data

2) there should be + button at the end of every folder
3) clicking a folder shoudl toggle its expansion and chnage the + sign to - sign
on expansion and vice versa
4) clicking a file should do nothing if it does not contain file or a folder
5) Double -clicking a files should make it a folder
6)clicking + button 
a) should take afile name from the input box, add it to the require folder and reset
the input box
b) shoudl if thr input box is empty display an alert saying " Please enter file name"


Note: Each item in the list is <li> tag with two items <button> which conatin a <span>
for display + and - and a <ul> for displaying its sub file/folder if any


JavaScript
function test(){
    var a = 'a'
    (function(){
        console.log(a)
        return;
        var a = 'b'
    })()
}

{
    company:'HCL',
    address:"Noida",
    "techno":{
        "ui":"opo",
        "java":"asd",
        "subtechno":{
            html:"abc",
            css:"frv"
        }
    }
}

output{
    company:'HCL',
    address:"Noida",
    "techno_ui":"opo",
    "techno_java":"asd"
    "techno_subtechno_html":"abc",
    "techno_subtechno_css":"frv"
}


golang
ping pong app with go routine and gochannel

golang we have connection pool for db clinet
once we get request we fetch client from pool fetch and response
design code for this create dummy client
intilize quantity and max quantiy
if no client available go to max and if go max close


array return most repeated item in an array
const nested = [2,'A',2,['A',4,['A',6,['A',8]]]]


React
A list of clor composed of red and green elements
A "square" component that render a square of a given clor and 
execute a click method

implenment a parent component named "App"  that:
1. Uses the give square component  to render all square from the "color" list
2. Expose the following functionallity
a> Click green => change current element to "red" + add 1 "new "green"
element at the end of the list
b> click red > delete current elemement

react
react component implemnt counyer

golang
implement a procedure and consure using gochannle 
producer should generate sires of integr and consumner should
recive from channel and double the integer and return and
shut down the system gracefully

python 
write function that recive 2 interga return true f those are equal
else false

list at least 5 non-trivial test case they have to be postivr and negative

python 
write a script that gets a urls as argument
makes a ping to the host and append the result to a file


javascript
we have array of object on basis of index user provide
we need to pick value without iteration


javascript
use Destructuring
we have key value pair 
try to retrive data from a map structure from a particular index


we have endpoint
write react component and list down the title on order list
https://jsonplaceholder.typicode.com/posts?_limit=10

golang 
 
https://gist.githubusercontent.com/pyPRO2019/dc44ae45f7cfe2f2a34fec30db4678eb/raw/df247df4e11260c669f986d0de589a90459d7e7b/students_data.csv
read data nd find uniqure recored

you are workinh on an edu game platform where iser can access and play edu game to 
learn various subject. 

Req
1)user should have profile with the basic info like usernmae and email
2)game have various ataribute including title, subject and dicciculty level
3) user can play multiple games and their progres should be tracked for each game
separatley
4) the progress should include info like score achieved and the data of the last playthourgh
5) user should earn achievment in games based on their in-game actions and perfomance . the 
achievemnt info includes the achcievemnt name in addition to the date

Task1
design a complerhsive database schema to represent these entires
(user game, progress and achievment) and establish the necesasry relation
between them

task2 sql query
the edu game platforn has gained popularity ans there is a need to 
showcase the top- performing
user in each subject based on their overal achievment

the challenge is ti retireve a list of user who have achieved the highest total score in 
each subject create a query that return a list containing rhe top-performaing
user in each subject for each subject includes user basic info(usernmae, email)
and total score achieved



task3
y
pagination bug fix:
onserve that there is a bug in pagination where despoite having 16 items 
in the list only3 pages are displayed (assume 5 per page) identify and retify
the bug to ensure that the pagination display the correct number of pages

function cretapAgination(){
    const totalpage = Math.floor(subjectData.length/itemsPerPage)
    const paginationContainer = docuemnt.getElementById('pagination')
    paginationContainer.innerJTML = ''

    for(let i = 1; i<=totalpages;i++){
        const pageLink = document.createElement('li')
        pageLink.classList.add('page-item')
        pageLink.innerHtml = '<a class="page-link" href="#">${i}<a/>'

        pageLink.addEventLisetner('click',()=>{
            displaySubjects(i)
            window.scrollTo(0,0)
        })
        paginationContainer.appendChild(pageLink)

    }
}

 
javascript 
create pareant and child component 
and share data between them using context api

react
test case for counter finction

vue3
'use strict'
console.log(b)
var b = 10

for(var i = 0;i <5;i++){
    setTimeout(() => {
        console.log(i)
    },1000)
}

react

javascript 
debounce


javascript 
palindrome code

give a json aaray of onkevt return all object that have key
value that matches  a condition
1. build an executable that excetur this list and return all object whose 
birthdate contains 1990
2. if necessary extend method to 
return all objects who meets additional criterta favorite color = blue
const data = [{
    name:'Anne',
    birthdate:'01/01/1990',
    favcolor:'blue'
}
]

css
what is height of element have content 10px border 1px padding 5px and margin 10px

javascript
write code which handle this senario
1> sum(1,2,3,.....n)

2>sum(1)(2)(3)......(n)

react 
make react component
call api with async and await
jsonsplaceholder.typicode.com/users

react native
> how to implment custome animation for user interface transition react native
> to handle third party with react native
> react-native how can we ensure react native app is aceesibiliy to disable perosn
> react-native how to configure to access local db like SQL lite for offline data
> react-native major the perforamce of app
> react-native add feature like accesing camre
> react native approch navigation


python 


angular reactive form
design angular folder
with field
1> appname
2> app description
3> Redirect uri
4> Gender and it have male and female

and register button only enable when all value added

sudoku grid validation suggest best algo with step
determine if a 9*9 sudoku board is valid.
Only filled cell need to be validated according to following rules:
1.Each row must contain the digit 1-9 without repetition
2.Each column must contain the digit 1-9 without repetition
3.Eaxh of the nine 3*3 sub-boxes of the grid must contain the
digits 1-9 without repetition

note
sudoku board could be valid but is not necessarily solvable
> only filled cell need to be validated according to the 
mention rule

suggest best algo with step
given an m * n matrix board wher each cell is a batteship 'X' or empty '.'
return the numbe of batteship on board

1>batteship can only be placed horizontally or vertically on board
2>in other word they can be made of the shape 1* k (1 row and k columns)
or k *1(k rows and 1 column) where k can be of any size
3> at least one horizontal or vertical cell separateds bewteen two batteship
(ie there are no adjuxt battleship)


golang 
get a integer as input and write goroutine, channel
to find sum of cubes

exmple if input is 3
then ouput is 36

python
dict
stocks={
    "apple":252.12,
    "microsoft":198.11,
    "intuit":672.08,
    "databrick":112.78,
    "yahoo":8.96,
    "blackberry":1.2,
}

find the top 3 company and return there name and value


python output
def calc(x,y,/, ope='add'):
 if ope == 'add':
  return x+y
 elif ope == 'sub':
 return x-y
 elif ope == 'mul':
  return x*y
  elif ope == 'divide':
  return x/y
else:
    raise ValueError('invalid operation')

result = calc(x=7,y=2,ope='mul')

python
can you simple class which has class method and instance method


javascript
const getUser = () => {
    return new Promise(resolve => {
        resolve(
            [
                {id:1,name:'Jack'},
                {id:2,name:'John'},
                {id:3,name:'Mike'}
            ]
        )
    })
}

const getUserStatuse = () => {
    return new Promise(resolve => {
        resolve(
            [
                {id:1,isActive:true},
                {id:2,isActive:true},
                {id:3,isActive:false}
            ]
        )
    })
}

map both of them on basis of id


javascript
setTimeOut(() => {
    console.log(1)
},0)

console.log(3)

Promise.resolve(4).then(console.log)

new Promise((resolve,reject) => {
    console.log(5)
    reject(6)
}).catch(error => {
    console.log(error)
})

typescript
any vs unkown

angular
directive vs component


test case jest handle userinput and make backend call

const searchInput = document.querySelector('#search-input')

fromEvent(searchInput, 'keyup').pipe(
    /* Write code here*/
).subscribe()


ios

func divideLoot(
    people:Int,
    fairly:Bool) -> string{
        var output;
        string = "we're going to split.....\n"
        if fairly{
            output += "Everyone get 1/\"

        }
        return output
    }
    print(divideLoot(people:5, fairly))
)

sql query
what is having and where clause

const arr= [
    {name:'Alex',age:25},
    {name:'Bob',age:30},
    {name:'Alex',age:25},
]

groupedBy(arr,age)

output
{
25:[
    {name:'Alex',age:25},
    {name:'Alex',age:25},
],
30:[{name:'Bob',age:30}]
 }


 javascript
 const arr = [1,4,2,10,15]
 create function to find larget element in array
find nth larget 


javascript
string is palindrome code if we have remove 1 or less char

example
//"abcbda" -> true
//"desbacbe" -> false
//dabcba"> true
//"asdfghj"> false

javascript 
on the basis of output understand the function and write

    input = "this is a test sentence"
    output:[t,h,i,s,i,s,a,t,e,s,t,s,e,n,t,e,n,c,e]

    input = "thiis iss a teest seentennce"
    output:[i,s,e,e,n]


    input = "thiiis iss a teeest seentennncce"
    output:[i,e,n]

    we have 3 component compa,b,c, we need where c is actual view component I what design where compA render insider component b
    will render 3 time im component A use children porps


JavaScript
write function take an array and revere the array and return new array


React
we have 2 category  closet and Suitcase
closet have few item display in terms of card
Suitcase have few item

every item have move button on click of that
if item in closet will move to Suitcase div
and vice versa

golang
 we need to attempt the sorta list of flight based on their price
 from high to low
 20,30,50,100
 you will implement the sortByPrice function that take in a slice of
    type flight and return the sorted list of flight
    in order to help you see what is going you hav been provided a very quick
    prtint flight function which you can use to print the fligh out



        javascript
const people : Person[]= [
    {name:'abc', age:30},
    {name:'def', age:25},
    {name:'pqe', age:35}
]

react
given  react component that display a list of a 
grocery item each wit a name cost and quantity complete the following task:
1) implement the logic for button that increaase and decrease the quantity of each item
2) Dipaky the total cost of all items based on their quantity and const
3) Add a input field for the user to set their budget when total cost
exceed the budget log the amount by which the total cost exceed the busget


css
make a red circle red backgroudn in center of page or div

given a collection of candidate numbers (candidates) 
and a target number (target)
wriet a function combinationSum2 to find all unique
    combination of candiates where choosen number
    sum to target. Each number in candiates may only be used 
    once in the combination

    input combinationSum2([10,1,2,7,6,5], 9)
    output [[1,2,5],[1,7],[2,6]]


var x = 0;
for (let i =0;i<5;i++){
    setTimeout(() => {
        x++;
        console.log(x)

    },1000)
}
console.log(x)


let obj1 = {key:"value"};
let obj2 = obj1
let obj3 = obj2

obj1.key = 'new Value'
obj2 = {key: "another value"}

console.log(obj1.key, obj2.key, obj3.key)


python
function to add 2 nuber


python 
check palindorm
given sting s conating just the characters '(',')','{','}','[',']' 

input is valid if
1) open barcket must be cloase by the same type of brakcet
2) open bracket must be closed in the correct order
3) Every close brakcet has ca cooresponding opne bracket of the same type



tableA: Device_id, device_status= connect,not conncetc,device_type= samsung , motorola

SQL
tableB: device_id, snapshot_date, record_status = 'Update','Delete',"Insert"

write query to find count of record for snapshot date on basis of record status 



SQL
tableB: device_id, snapshot_date, record_status = 'Update','Delete',"Insert"
write query to delete  2 record and keep 1


create a single todo app using reactjs
Same data local state management
each todo item will have description , due date,
status, completed/cancelled date, 
handle form validation for required field 
order the todo item based on due date in increasing order
wen and item marked as completeded or cancelled move them to
bottom of the page of todo List
Apply appropitae styling to the page using css 

React (typescrit) pool manager

design pool manger app that allow users to 
vote one of the two option and view the winner
the app should be built using React + typescript
App the 3 comoponnent pollmanager , vote and results

vote component
> display text of ecah option
> procide a vote burron fro each option
> disable vote button for each option whne the winner is declared

Result component
> display the result text based on the 
> if no vote cast show empty
> if same number of vote show tie 
> if one has extr then sow leaser is leading by vote diff

view winner
> if no vote cast button disabled
> clicking winner button 
display resukt text "it is a tie" if same number of vote
if one has extr then sow leaser is leading by vote diff
    disable the view winner button 
    disable votr button for each option

poll manager
>>display poll Question
> manage state of the poll incduing vote and winner status
> pass the relevent data and function to the vote and result component



in vote component
interface VoteProps{
        options: PollOption[];
        onVote:(optionId: number) =>void;
        viewwinner: boolea
    }

export interface PollOption{
        id:number
        text:string;
        votes:number
    }


export interface Poll{
        question:string
       options:PollOption
    }




python
given two nodes on atree find the first ancestor they have in
common Nodes have pointers to  their parent and their childern


python
we have a game in which consecuitve duplicates pieces of the same type
cancel each other  out and remaining pieces slide in until no more pieces can be removed

Give a board resprestn by string return the final state of the board after playing the game

input = "abbba"
output:"" ("abbba" => "aa" => "")

input = "ab"
output = "ab"

golang
package main

import {
    "log"
    "net/http"
}

implement 
//get /rules (list all rules)
//post (/rules) (insert a single rule)

type FirewallRue struct{
    VMID uint64 `json:"vm_id"`
    Direaction string `json:"direaction"`
    Source string `json:"Source"`
    Destination string `json:"Destination"`
    Protcol string `json:"Protcol"`
    Port int `json:"Port"`
}

func main(){
    database := make(map[unint64]* FirewallRue)
    database[1] = &FirewallRule{VMID:1}

    r: http.NewServeMux()

    r.HandleFunc("GET"){

    }
}

s:= &http.Server{
    Addr: ":3000",
    Handler: r
}


function fn(){...}
    // functional component
    function form(){
        // call fn whrn form unmount
    }


    output

    const olObj = {
        contant:{
            email:"old_email"
        }
    }

    const newObj = {
        ...oldObj
    }

    console.log(oldObj.contact.email)
    console.log(newObj.contact.email)


    output
    javascriot
    how do you promidify th delay function ?
        it should print 

    const delay = () => setTimeOut(() => {
        console.log('timeout')
    })

    async function main(){
        console.log('start')

        await delay;

        console.log('finish')
    }

    main()

    it should print start,timeout, finish and make sure it run asynchronously


    jacascript
    what is missing
    what do you need to define name and age when intasniting the person class?

        class Person{
            name = "",
            age = 0
        }


        const John = new Person('a',10)


given this array of users can you implement the getActiveUserWithCat return active use with cat


input=[
    {name:"a",isActive:false,hasTrue:true},
    {name:"b",isActive:true,hasTrue:true},
    {name:"c",isActive:true,hasTrue:false},
    {name:"d",isActive:true,hasTrue:true}
]

golang
there are 2 golang routine one is producer
other is consumer once it recive it will send acknolwdgement and then 
    producer will send new mesaage
    in case of 10 sec delay in acknolwdgement it will end bot goroutine


output of javascript code

const makeMap = () => {
    const parks = new Map()
    parkse.set("uinversla",{name:"USF",age:30});
    parks.set("disney",{name:"magic",age:40})
    parks.set("uinversla",{name:"IOA",age:50})

    console.log(JSON.stringify(parks))
}



function sumArray(array:number[]){
    let sum = 0;
    for(let i = 1 ; i<array.length;i++){
        sum +=array[i]
    }
return sum
}


javascript
implement a function to find the sum of number without any loop
    arr = [1,2,3,4,5]


    javascript
    "A"-1
    2+"-2"+"2"
    "Hello"-"World"+78
    
React creates simple component 
counter for increase and decearese and dipslay ouput

there is a sitting length N made only od letter 'a'
whenever there are two identical adjust letter like 'aa' 
yjey can be transformed into single letter that is the next 
letter of the alpjabet.
like 'aa' transfomeed to 'b' and 'ee' will transformed to 'f'
and 'zz' cannot be further transfomred

what is thw alpjabet larget string that can be obtained from the intial
string?


function soluiton (N)

    example
    N = 11 function should retirn 'dba';
        'aaaaaaaaaaa' => 'bbbbba' => 'ccba' => 'dba'





const sumOFNums = numbeersArr.reduce((acc,num) => {
    return acc+num
})

console.log(sumOFNums) //15

Question implement a polyFill name "myreduce: that replicate the same behavioyr as "reduce"

Array.prototype.myreduce = function(cb,initialVal){
    const array = this
}


const numberArr = [1,2,3,4,5]
const sumOFNums = numbeersArr.myreduce((acc,num) => {
    return acc+num
})

console.log(sumOFNums) //15




 
implemnation of stack operation like push pop empty, peek, and swap use javascript and html
with the given template

push > insert an element to the top of stack
pop > remove the top most element
empty > retyr true if the stack is empty ,false otherwise
peek> returns the value of the topmost item
swap> the two topmost element of the stack can are swapped


stack can hold 5 value at max
textbox should accept any type of value

<button type="submit" id="pushbutton">Push</button>
<button type="submit" id="popbutton">Push</button>
<button type="submit" id="emptybutton">Push</button>
<button type="submit" id="peekbutton">Push</button>
<button type="submit" id="swapbutton">Push</button>

do not add on click


    after adding value add in the table
<table>
    <tr><td class="stack-item" id="5" data-testid="5"></td></tr>
    <tr><td class="stack-item" id="4" data-testid="4"></td></tr>
    <tr><td class="stack-item" id="3" data-testid="3"></td></tr>
    <tr><td class="stack-item" id="2" data-testid="2"></td></tr>
    <tr><td class="stack-item" id="1" data-testid="1"></td></tr>
</table>

golang
i have varibale its a string type store message size is %d
var msg = "Size:%d MB"
in println pass data like 30 mb and format response

golang
i have map that cotains string string like username pranit
i want to check map have username key exist

golang
i want to create method either accept integer or float method name is "Add"
if i pass integer it return type should integer
if i float integer it return type should float

team has created rest end point and consume the rest end point call api

golang 
we have array of 10 mobile numbar in api
but we got more than 300 number in array we ned to process
but downstram accept only 10 and they alos applied rate limiting of calling 5 time

we have 6 to 7 lambda function making http call to fetch the lambda
All the api we are calling need to pass token 
for diff env ,
we have diff diff value for token generation
we creeated diff config file now everything working fine for qa env we need to change config
and config file shipped with lambda how to manage env with lambda


react

ui button if we click on button it should giev call to backend api and retrerve the data
frm the backend and display on ui

fins the second larget or smallest number in the array


write python function

    example1
    input: digits = "23" 
    output: ["ad","ae","af","bd","be","bf","cd","ce","cf"]

    example2
    input: digits = "" 
    output: []

    example2
    input: digits = "2" 
    output: ["a","b","c"]

    return all combination of charcter like mobile key pad
    where
    1 have nothing
    2 have abc
    3 have def
    4 have ghi
    and so on
    and 0 have nothing






update object 2 with all filed of object 2

const obj1: any = {
    field1:"test",
    field2:"tes1",
}
    

const obj2: any = {
    id:"1a"
}

const park = {
    id:2,
    name: "a",
    loc:{
        city:"a",
        state:"b"
    }
}

const {name,state} = park
console.log(name)
console.log(state)


export class ExampleCass{
    public async queryAll(reqs: ExampleRequest[]):Promise<boolean>{
        let results: boolean[] = []
        const promise = reqs.map(async(req:ExampleRequest) =>  Database.query(request));
        try{
            results = await Promise.all(promises)
        }catch(err){
            logger.warn(error)
        }
        return OtherService.sendResult(results)
    }
}


export class ExampleCass{
    private constantProperty: string;
    public constructor(constProp: string){
        this.constantProperty = constProp
    }
}


class PersonClas{
    public firstName:string;
    public lastName:string;

    public get fullName(){
        return this.firstName + this.lastName
    }
}

class person : PersonClas = {
    firstName :"a",
    lastName:"b"

}

logger.info(person.fullName)



api.data.gov.sg/v1/environment/air/temperature

display 
device id
name 

in react after calling the api


javascript
const obj = {a:1, b:{c:2}};

Object.freeze(obj)
{a: 1, b: {…}}
obj.a = 2
2
obj.b.c = 3
3
console.log(obj)

javascript 
create sum function that can take any paramater and it can be any number
sum(1,2,4)(8,9)(7,11)()
and this can be any number of argument


javascript
we have arra of object of student data
of same clss but different section
return all with just section a


golang 
codr to find hight comman factor of any number

javascript

if(!A){
    console.log("A")
}else if(!B){
    console.log("B")
}else{
    console.log("error")
}

input = {
    error="hi"
}


python
given an array of intergs nums sorted in non-decreasing order
find the starting and ending position of a given target value

if target is not found in the array return [-1,-1]

example
input = [5,7,7,8,8,10]
target = 8
output = 3,4


React 
Recreate the traffic light using css and html
make it so ecah "light" is clickable
when clicked it should it should set the circle to the correct color
the other two into the "off state" color


php
What are constructors and destructors in PHP?
Explain the concepts of visibility (public, protected, and private) in PHP.
How can you secure a PHP application against XSS (Cross-Site Scripting)?
How do you create and retrieve session variables?
Explain autoloading in PHP. How does the spl_autoload_register() function work?
Diff between put vs patch
How does PHP handle caching, and what caching techniques can be used?

Coding>  Find Duplicate Elements in an Array
> Sort an Array Without Using Built-in Sort Functions


Larvel
> What is the purpose of phpunit.xml in Laravel?
> What is the Event and Listener system in Laravel, and how is it used?
> How does authentication work in Laravel?
> What is Auth::attempt() in Laravel, and how is it used?
> What is the difference between can() and gate() for authorization in Laravel?
> What is Laravel Sanctum, and how does it handle API token authentication?
>> How we can setup event broadcasting in Larvel

sql

write a query the fetch the 2nd 
highest salaery from each dept
MySql
> Create a query in MySql for student and marks table  to find top five student on basis of marks
where both table have releation ship of rollNo
( if done above)
> Please save above output in view
> Write a SQL command to update data through a view and handle any potential issues with view updates.
>> Provide the SQL command for updating data and discuss any limitations or requirements.
>> What is a materialized view, and how does it differ from a regular view?


React
> create 2 component 
one parent component
second child component
share data between parent and child


golang
for the following code can you write a program for the client side?


package main


golang in 5 producer producing 5 number one by one and consumer
is responsible for consume number
> it should work in producer 1 producer will produce and consumer will consume
then next producer will produce 1 number and consumer will consume
    and so on
    so all producer 1 by 1 produce number 1
    
golang
to implement stack interfcae which folowing method:
pop(), push(), peek(), isEmpty(), max()


golang
you were hired as a consultant for best blog<sup>TM<sup>
company need help with findihing the implentation of RestApi 

first 
we need to implement empty methods in 'commentRepository' and 'Post Repository'.
the structs resprest an in memory storag
for out entitess you will find stubd of the methods in the repository/respositiry.go file


react
create tic tac toe game
creae a stateful custome hook exeuted bases on a data change

python
we have a catalog of song title(and their length) that we play a local radio
We asked to play two of the song in row they must add up exactly seven min long

exampe:
song_times_1 = [
    ('abc',"8:05"),
    ('def',"2:27"),
    ('ghi',"3:41"),
    ('jkl',"2:49"),
    ('mno',"3:19"),
    ('pqr',"3:18"),
    ('st1',"10:26"),
    ('lkh',"4:55"),
]
output ['ghi','mno']


python 
find the longest chaining of song  and make sure no song should not repeate
return the starting till longest chain with matching word, starting song is provided as input
song_times_1 = [
    'd b r',
    'r o d',
    't m t t r',
    'dreams',
    'blues hand me down',
    'forever young',
    'American dreams',
    'all my love',
    'contaloop',
    'Take it all',
    'love is forever',
    'Young American',
    'Dreamship',
    'Every breath you take'


]

output = 
song1_1 =  'Every breath you take'

output
chaining song = [ 'Every breath you take','Take it all','all my love','love is forever','forever young',
'Young American','American dreams','dreams',]
    

python
write function that simulate communication between 2 microservice
    one generate user id and other use thate id for search

javascript
async function async1(){
    console.log("1")

}



ios filter movies
need to build a small part of ios app print out log items
the swift function logdumpGetUnique has a small set of itemstored in a string.
    Each log item is separeted by a semicolon
    your goal is to return a new tring with the following requirnemnt:


1> Remove log items that are duplicate based on username
2> Form each log item remove id= Num propoerty and value.

for item that are duplicate based on the username keep
the first one that appers on the list and remove the subsequent one


example Iput
name = Dan B, username=db, email=db@gmail.com, id=123;
name = hannaa, username=hsmith, email=hsm@gmail.com, id=33;
name = Dan Brick, username=db, email=db@gmail.com, id=663

output
name = Dan B, username=db, email=db@gmail.com;
name = hannaa, username=hsmith, email=hsm@gmail.com;


ios 
need to build a small part of ios app that need to implment a simple 
key-value type of a cache in swift you need to implement a cache class that functions
add,get and size

the add function take 2 param  a key and value and adds the pair to the local cache
when an item is added to the cache this function should return the string "added" and if the item alreday existed
    in the cache theis function should
        return the string "overeritten

        the get function attemp to returive an item from the cache
        based on the key parameter oassed in if the item exist in the cache
        retur the value ,otherwise return string "miss"

        the size function will return numner of item in the cache]



            <script>
               function mul(a,b){
                   return a*b;
               }
               function div(a,b){
                   return a/b;
               }
               document.writeln(mul(5,7).toString());
               document.writeln("<br>");
               document.writeln(typeof mul(5,7).toString());
               document.writeln("<br>");
               document.writeln(div.toString());
               document.writeln("<br>");
               document.writeln(typeof div.toString());

            </script>
            <button onClick='setName()'>SetName </button>
            <p id="name"></p>


            var num=10;
            function fun(){
                num=100;
                return;
                function num(){}
            }
            fun();
            console.log(num);




            golang
using jin framwork write api which are reading and saving book information
2 api

for num = "1432219" and k = 3
output = "1219"

react with typescript wit prime react

we have api
https://jsonplaceholder.typicode.com/users
imtergate into react app and return tabel format showing
id, name , username, email and address
and address should be like
street,suite,city and zipcode

and use Prime React for table

react with typescript wit prime react
implement user auth- keep username as user and password as pass
provide login and logout button

> desigb a multi-page application with appropriate routing
> creagt at least two main route
> a public route accessible to all user (eg homepage)
> A private route accessible only to authenticated users
creata route gaird that prevete unauthorixed access ro private route
ensure that only authenticated user can access certain part of the application


python
avergae-waiting-time

there is a restaurnat with s single chef you are give an array customer,where customers[i]= [arrival,time]
arrival >is the arival time to ith customer. the arrival time are sorted in non-descreaing order
time > is the neede to prepare the order of the ith customer
when a customer arrives, he give the chef his order and the chef start prepaing it once he is idle
the customer waits till chef preparing his order the chedf does not prepare the  food for more than one customer
at a a time
the chef prpeare food fr cutsomer in the order they were given in the input

retun the avergae waiting time of all customers solution within 10^-5 f0r the actual ansewer considered

inpur = [[1,2],[2,5],[4,3]]
output = 5.00000


javascript

i have array from -infinity to +inifinty find second largest number in array


how to call api in reactjs


golang

write code we recicev string
1> ({})
2> (({{}}))
3> [{}{}{}]

validate formate barakcet should be sequnetically close
if correct return true else false

    package main

    import (
        "fmt"
    )

    func main(){
        var slice = [5]int{1,2,3,4,5}
        var newSlice []int
        newSlice = slice[0:2]
        newSlice = append(newSlice,6)
        fmt.Println(newSlice)
        fmt.Println(slice)
    }
    

    golang write code
    given 1->2->3->4->5
    and n = 2

    output = 1->2->3->5

    input is list n i number
    we need to remove the node from the end of the list



python
let asume on one of the s3 loaction we have file (partfile)
we have 2 file part1 and part2  to convert into text and make one and copy in different locatin


python
Given a string of sorted integers sepearted by space indentify wheters a target is present in array or not 
Input

javascript
can filter array based on function

    javascript

    implement json.stringify function mannuly without inbuit


python List Comprehension
num_list = [1,2,3,4,5,6]
return new list with even number


python

what is missing  the claas

class Person:
 def __init__(name)
        name="a"
def print_name():
 print(name)


javascript  
cosnole.log(x)
let x = 40

javascript
const a = {val:45}
const b = a 
b.val = 90
console.log(b)
console.log(a)

javascript
function abc(){
    let x =20;
}

const newFun =abc()
console.log(newFun(45))
we can only modify function abc() and output shoudbe 65



write sql query to find all products that have
never been order from the products and order_items tables


html css
draw on circle and inside that make one more

python
check weather string is palindrome


datascience


python
python create 2 sets of values for the analysis
set1=[3,-5,-.5,2,7]
set2=[2.5,0,2,8,10]
using these 2 set of values set1 is predicted value
and set2 is actual value
find root mean square without any libraray


now in
set1=[3,-.5,2,7]
set2=[2.5,0,2,8]


python
write function one aws log need to fetch from cloud and show time 


javascript
we are giveb an array of object represting studenst tst score each with a name 
and score property

we need function in javascript
1> an array if name of student who score above 80
> an aray of object whee each object conatins the student name and a boolena indicating of they passed (score >=65)
3> the average scroe of all student


javascript
write a function to return a promise the function should take 
a number as an argument when the number is even the promise should return a number that is
2 times the original number. when the number is odd it should throw error

javascript

using the function form above question write a second function that takes as an array an argument and calls second
function for each number in the array the function should return the new number
when an error occur the number shoud be set to -1

const input = processNumber([1,2,3,4])
console.log(result) /[-1,4,-1,8]


nodejs
how to approch api
> create new user save field like name and able upload image with s3




this.setState({counte: this.state.counter+this.props.value})


python code
theather booking system
50 seats in theater 
10 in row

i want book seat in row 1 
2, 6

and thn row 2 
seat 3,7

show row in table format



javascript 
var a = [12,234,23,12,431]



make counter component in reatc

write a function to merge two array ad result should be sorted array without inbuili


next js and typescript
create a form that allow files upload
submitting the form should upload to : `/api/upload/
after upload something about the  file in message

the endpoint should be responsble for:
processing the uploaded input according to the algo
returning the result

finally shoe the rsult on the UI


typescript
import type {Equal, except} form '@total-typeScript/helpers'

// ennsure routes can only have the 'component' property
// ensure the component value of a route cannot be changes after creation

const routes = {
    "/":{
        component:'Home'
    },
    "/about":{
        component:'About',
        search:'?foo=bar'
    }
}

@ts-expect-error
routes['/'].component = 'About'
    



type tests = [
    Excpet<Equal<(typeof routes)['/']['component'],'Home'>>
]

make a screen with tiles with text and checkbox 
for web show 6 box in row
for tab 4 in one row and all in next
for mobile one under anothe use flex box


javascript
take a paragah as an input, ans count word from it


system design question
design system for sending notification (system design question)

what is the seocnd aregument foe setState useful for?
> to replace the state completely insted of the deafult merge action
> to invoke code afte the setState opertaion done
> th access the pervios state before the setstate operation


what instance property can be used ti access the property of a class component?
1> this.properties
2> this.props
3> this.attribute
4> this.attrs

what are the 2 object that act as the input of a class-based component?

what advantage does the react devloper tools for chrome offer?
1> it shows the attribute of html element in a side pane.2
2> when clicking on an html element it shows the corresponding jsx
3> it visualizes the jsx tree hierarchy

what could be a reason to use flux?
1> root component get too bloated with mainting state
2> there are more than 10 component in the application
3> the application is menet to be used as acloud application
4> the application is very simple in nature


what is react approch to separation of concern?
1> the code defining the ui in a componet is always separated from the rest of 
the logic in the component
2> with react html is written in component so that here strict separation between js 
code and browser
3> what displayed in the browser is only refelection of the state
ofthe application

can a child component subscribe to the extranl state that its parent
is also subscribe to?
1> yes, but only if it was wrappped component
2> yes , any class component can subscribe to the external state

how can we solve the problem when both a server and a client-renedered
app need to use async data?
1> by mistake the ajax call before the first reactDOM.render call on the clinet
2> by mistake the server-rendered app manully invoke the componentDidMount method
3> by using an iniatl data concept that can be controlled on both server and client

what is the reason behind the advice against using a contextApi?
1> it requires the use of external packages ans state containers
2> it makes the application use more memeory
3> it a global concept that complicates responsibilities and testing
4> it makes the code less readable

how do you call a function that return another function
    1> functionName().()
    2> functionName(())
    3>functionName(() => ())
    4>functionName()()

java 
invoke restful service and url is abc.com
call a service abc 

javascript
write function which accept an array
    [1,2,3,1,2]
    as input

convert each array element into a key of a new object
start with empty object
key must be unique

input > [1,2,3,1,2]
output
{
    1:"Hello",
    2:"Hello",
    3:"Hello"
}


input must have same width as button


<div class="container">
<h1 class="heading">Please login</h1>
<div>
    <label class="label-for-input margin-bottom-5">Username</label>
    <input class="input-field margin-bottom-5" type="text">
</div>
<div>
    <button type="button" class="login-button">Login </button>
</div>
</div>

.container{
    width:50%;
    height:30%;
    background-color: grey;
    color: white;
    position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
   } 
   .heading{
    text-align: center;
   }
   .label-for-input{
    display: block;
    font-size:30px;
   }
   .input-field{
    width: 100%;
    height: 20px;
    border-color:black;
   }
   .login-button{
    width: 100%;
    background-color: yellow;
    font-size:30px;
     border-color:black;
   }
   .margin-bottom-5{
    margin-bottom:15px;
   }


React
design a small app in react with functional component
it have ine input box that shold accept user age shoud accept number
then there should be a button on click 
> if age is greather then 18 the display message > eliglible for driving
> if age is smaller then 18 the display message > not eliglible for driving

nodejs
create a url shrotner service similiar to bitly
service should allow user to access long url when shorten url is accessed



nodejs

using aws servies help me create serverless image processing pipeline
the pipeline should automatically resized image uploaded images

and in another bucket uploade resign images


javascript
count character in string and list

complet following code on hashing

var a = 10
var b = 2;
var c = 'USD'
var cardNum = 1454112114114111;

const module = (modulename) =>{
    if(modulename != 'instalment')
    {
        return false
    }else{
        return modulename
    }
}

const password = ( ) =>{
    const buf = Buffer.___('pass','asci')
    const pass = ___.tostring('hex')
}


write  a ts function called addElement that takes
    an array of numbers and a number
    it should return a new array with the number appended
to the end without modifying the original array

write  a typesscript function
caled mapArray that takes an array of number
and a function as arg. the function should
    aply the given function to each  element of the Array
        and return a new array with the resukt

form the below ser how would i extarct the strret,city ,state 
and bot  hobbies in one line using both object desstrutuing
and array desstrutuing

const user = {
    name:'a',
    age:10,
    addreess:{
        street:"b",
        city:"c",
        state:'e'
    },
    hobbies:['f','g']
}

write a tyoescript function safeParseJson that take a JSON string
    inout and safely parse it.
    if parsig fails it should return null insted of throwring error

    write a tyoescript function fetchUrlIsInParallel
        that fetches data from all the urls in parallel using axios
        if all request succeed return the result . if any request 
        fails log the error and return an empty array


how would you optimise the below .filter  and .map calls?

const users = [
    {id:1,name:"a", role:"aa"},
    {id:2,name:"b", role:"bb"},
    {id:3,name:"c", role:"cc"},
    {id:4,name:"d", role:"dd"}
]
const adminNames = users.filter(user => user.role === "admin")
.map(user => user.json)

console.log(adminNames)

how would i optimise the below function using a hshmap
plesee return an object insted of the map


interface Intallation {
    carId:string,
    partId:string
}

const intallations: Intallation[]{
    {cardId:"a",partId:"aa"},
    {cardId:"b",partId:"bb"},
    {cardId:"c",partId:"cc"},
    {cardId:"d",partId:"dd"}
}

function countParts(intallations:Intallation[]):{[key:string]:value}{
    const partCount = new Map<string, number>()
    intallations.forEach(intallation => {
        if(!partCount[intallation.carId]){
            partCount[intallation.carId] = 0
        }
        partCount[intallation.carId]++;
    })

    return partCount

}


javascript
how would you write function called encode messgae that takes a string 
    and return it with consective identical characters respresented as the count followed
    by the the character?

ex 
input "aaaabbe" 
output > "4aaaa2bb1e"

input "zzzqqrrrr"
output = "3zzz2qq4rrrr"


///////////////
which of the following statement are true for nodejs?

> Nodejs is a framework
> Nodejs is a javascript runtime env
> Nodejs is a programming languages
> Nodejs is a superset of javascript


what does the term "non-blocking" means in the context of nodejs
> function return immediatly and execute the task in the background
> function block other function for execution
> function pause execution until their return value is computed
> function immediatly return without a value


when working with async/await which statment would be used to pause the
execution of an async function until a promise is resolved or rejected>
>delay
>pause
>hold
>await


which of the following is true about the async keyword in nodejs?
> it makes a function return a promise
> it always makes a function execute asynchronously
> it allow the await keyword to be used within the function
> it stop the event loop until the function completes

if a promise neither resolve nor rejected, it is said to be in which state?
> completed
> pending
> nullified
> void


what happens in the event loop when there's no more work to schedule?
> it exits immediatly
> it goes into a infinite loop
> it wait for more tasks before proceeding
> it throws an error

what are there result of awaiting reject promise in an async function without a try/catch
block?

> it throws an error
> it return the rejected value
> it return a undefined value
> the function continue exeution without any issue


which command is used to execute custome script defined
in the package.json file  nodejs

what would you use to get the list of verison of a 
packages available on npm

> npm list [package]
> npm show [package]
> npm view [package] version

which of the following os the correct way to do a named export of function named 
myfunc in nodejs?

> export myfunction
> exports = myfunction
> module.exports.myFunction = myFunction
> module.exports - myFunction

suppose you have the following code file named
calc.js
how would you import the add function in another file
> const {add} = require('calc')
> const add = require('./calc')
> import {add} from './calc'
> import add from './calc'

how would you import only specific function from a module that has
multiple named exports

in the es6 if a module named './math.js' has a default export of a 
function named calc, how would you import it into your code?
> require('./math.js').default
> import {calc} from './math.js'
> import calculate from './math.js'
> import * as calculate from './math.js'

in nodejs which method is recommended for handling exception in async/await code?
> using try/catch blocks
> async.catch()
> using error-first callback
> .on('error')

Output
const promise = new Promise((res,rej) => {
    throw new Error("Error Occured")
})
promise.then(() => {
    console.log("Success")
}).catch(() => {
    console.log("Failure")
})

what is the nvm command for switcing between nodejs versions


nodejs which file extension does eslint check by default without any configuration
> .mjs
> .es6
> .es
> .js

in jest testing in nodejs what function is used to group releated tests

to automatically generate api docuemntation for your nodejs app
which tool might you employe?
> expressDoc
> nodeDocApi
> ApiDoc
> swagger

-----------------
angular
how do you specify where your routed components will appear in your application?
> they always apper just inside the <body> tah of your index.html
> use *ngSwitch to display the appropriate component based on the url
> use the <router-view> Component
> use the <router-outlet> Component

what is the @viewChild decorator used for?
> to get a handle on a DOM node decorated with a ref tag(#ref)
> to add metaData for the children of a view
> to make custom * directives
> none of above


where should you sort and filter data?
> in your component
> in a pipe
> in a filter
> in a directive

what specifically does angular mointor when it determines whether or not
to fire ngOnChanges()?
> Reference changes
> Component changes
> function changes
> Event Changes

ngrx ngrx-data, obervable, store and other state managmenet solutions
all created a single --------- that can be used throughout an application
> immutable structure
> code technique
> store
> manifest

what design pattern can be used to help with component communication
in an angular application
> abstract factory or factory method pattern
> top to bottom pattern
> object communication pattern
> mediator or observer pattern


ngrx is a state mangement solution that can be defined as:
> component+service
> redux +RxJS
> container + presentation
> event Bus + observable service

what items are stored in the "core" folder?
> component object resource entity items
> object that will be created multiple times
> singleton object(service, single use component etc)
> items that are "shared" in the application


function calls made from a template can be replaced with ----- in many cases?
> component
> services
> properties
> pipes

what rxjs operators can be used to change from one observable to another?
> changeMap()
> switchMap()
> forkJoin()
> SiwtchObservable()

in what order do interceptor execute?
> reverse alphabetical order by class name
> the order is indeterminate
> the order in which they were provided in a module
> the calling controller determines the order

-----------------
postgres

if you want to retrun aall rows from two or more tables that meet the join condition
which type of join would you use?
> left
> full
> right
> inner


postgre
we have 2 table 
cutomsers with custid and name
orders with order_id cust_id and amount

you write a query to join these table which return the result 

result > custid name order id

which join we should use


postgre
assume that you write a query that returj the following result
> Result
   Cust_name
   Shannon
   Olivia
   James
   Heath
   Brenna
   ALec
   Alec
   
whcih sql clause did you most likely use to select your result?

> order by cust_name Desc
> order by cust_name
> order by cust_name Asc
> Group by cust_name

SQL
assume that a company has a table in its database that stores order
information including the amount of the order:
  order_id cust_id amount
  9020      109     36.80
  9022      105     28.22
  9024      109     23.20
  9025      103     47.00

you write a query to sum up which return the following results:
select SUM(amount) FROM orders; >135.22

what is the function used in this query called in sql


what is primary character that makes a database releational?
> data stored in the datvase are of similar length
> users from accorss the org can acess the data in multiple tables
> data stored in the databse address a common subject
> keys join releted data accrooss multiple tables


what is one of the primary advantages of postgresSql?
> it is developed by corporate sponsors
> it is installed on most computers
> it is open source and freely available
> it offers its iwn set of proprietary standards

Assume that company has an inv_table table that contains a 
listing of all products that they sell along with their prices

this table contains five records:
product  cost
ref      1500
oven     850
ref      950
micro    125
dish     600

consider code 
SELCT DISTINCT product from inv_table
 which of the following is true about the result of this query?

> the result will return five row of data

> the result will return one row of data

> the result will return four row of data

> the result will include two columns


sql
consider the code below:
SELECT (3+8+9+Null);
What would the output of this code return?

> Null
> this code would return on error
> 20
> 3,8,9,Null

what are some mandatory elements for creating a function in postgresql?
> Create function statement, function name, zero or more arguments  and return type
> language specification ,function statement, sql statements and return type
> Create function statement,name, one or more argument and return type
> function name,body, argument list and default aregument values

what is one difference between output argument and returing a table from a function?
> output argument cannot be array types but table columns can
> output argument must be assigned to varaible, but tabkes can be handled as a row set
> output argument may have many values, but a table may have one value per row
> output argument will only receive one value, whereas a table may have many rows

when you execute a query in pl/pgsql that return a result what should you provide?
> a query to hold the result
> a destination for result
> result from queries are automatically returned to the function caller
> the PERFORM statment to supress result

what is one way to migitate SQL injection in dynamic quires?
> using a parameterized query
> a call to the format() function specifying %L for sql identifiers
> call the pg_prepare() function before execution
> Always execute dynamic queries with the perform statment

when creating function what are some factors that can cause your 
code to fail or produce erroneous results
> missing error handling, transactions, schemas
> false assumptions, env setting, database object changes
> using schemas error handling database object changes
>env setting, using cursoers, function overloading

when a polymorphic function is called in postgresql what does the databse 
look at to determine the funcyion to call?

> the types of the arguments supplied in the function call
> the schema where the function resides . if ambiguos then the return type os also checked
> the return type
> the types of the inpit parameters and return type

-------------------
Does mongodb support sql
> no because mongodb has no join capability
> no, standards-based sql does not support document

how does mongodb ensure high availability?
>  by supporting shared storage
> by using a dynamo ring
> by sharding data over multiple nodes
> by replicating data on multiple database server

how is data queried from mngodb?
> by using sql
> by making api call through a language specific driver
> by using MQL
> by making rest request

can mangodb use multiple indesx on an instances for one find operations?
> yes but only with expressibe query
> yes but only for sorting result after filtering
> yes but only for $or clauses

what would be a reason for using a projection on a query?
> reduce the amount of data that must be transmitted by mongodb
> dynamicaly redact fields according to the contents of the document
> reduce the amount of data that must be read by mongodb
> reduce the amount of data which must be transmitted and read by monfodb

givem the array {hrs:[2,3,5,7,11]} what syntax would reference the array element with value 7?
> hrs:3
> hrs:{$eq:7}
>hrs:3
> hrs[3]


$each, $sort and $slice are used in conjunction with what operator to mange atomic
array updates?

when desiging a componend index what field should  come first?
> the lowest cardinality exact match
> any field you are quering with s sin clause
> the field being used to sort
> the most selective exact match

which of the following is NOT a mechanism mongodb provides to reduce index
RAm usage?
> hashed indexes
> fitered indexes
> prefix compression
> bitmap indexes

when does an index become a multikey index mongodb?
> when any value it indexes is an array
> when it indexes all fields in an object
> when it contains multiple fields
> when it no longer contains unique values

what is NOT a type of index supported by mongodb?
> compound
> bloomfilter
> sparse
> wildcard

the mongodb profiler should be used with care because
> profiling data can quicly fill up availabile disk space
> disabling the proflier requires a restart of the database
> it will log every single operation by default
>it adds significnt overhead to normal performance

what does command db.setProfilingLevl(1,5) do?
> enables the profiler to log the 5 slowest operations
> enables the profiler to store only slow quired slower than 1 millisecond
> enables the profiler to store only slow quired slower than 5 millisecond
> turns on the profiler and logs all operations every 5 second

in mongodb $unwind for document {x:0, scores:[1,2,3,6,7,6]}
how many document will the $unwind stage created

which of these $group accumulators os optimized to work with pre-sorted data?
> $sum
> $max
> $first 
> $addToSet

which of these statements is correct?
> a document within an aggregation stage can be more than 16mb but the
returned document should be 16mb or less
> an aggregation is like a stored procedure

which stage will stream document to the next stage in the pipeline
 rather than blocking mongodb?

> $set
> $sortByCount
> $bucket
> $group

a major drawback of relational databses is having to plan downtime and perform
a schem migration when new fields are added to a table? how to fix in mongo

> subset pattern
> bucket pattern
> schema version pattern
> dcument verisom pattern

which of the following is a schema design antipattern?
> precomputing data on write rather than on read
> sperating data that is frequently access together
> enforcing schema validation after data structure has become more grid
> using data subset to reduxe the size of the normal working ste

it is much more efficient to compute a summary of measures such a avg
and max or min values when you write a mongo document. which combination of mongodb
pattern support this?

> computed and bucket pattern
> computed and attribute patterns
> overspill and attribute patterns
> subset and document version patters

which is one disadvatnge of using hashed sharding?
> it return unpredictable results during balacncing rounds
> you cannot perform range search when using it
> it can require significantly more RAM and disk 10 then other sharding options
> it results in an unevn distribution of operations across servers

mongodb 
what write concern should be used in an app to ensure data is not lost during a 
failover

when might a primary node read data from a secondary?
> immediatly after wining an election
> when perfoming a backup
> primary nodes will never read from secondary nodes
> when a query is perfromed for majortiy-commited data

what features of sharding enables specific data to remain in defined geographic location

which is true about shared key?
> the value of the shard key in a document cannot be changed
> you must apply the shared key when performing an upsert
> shared key can only be strings or numbers
> the shared key is required in every query against the shared collection

when does it make sense to read from a secondary node in a replica set?
> when your index is larger than the RAM
> when primary node is unable to handle the load
> when your query is ad-hoc and has no good index
> when you need data that has been commited to more than just the primary node

which three of the following are the reason why the PSA topology is noy recoomand
for production system? SLECT 3 coorect answer?
> a system with arbiters can be highly available or guarantee durability but not both
> the write concren "majority" can cause performace issue if a secondary is unavailble
> this deployment provides only one complete copy of data
> it limit the amount of cpu and RAM that can be allocated to prmary node


which one is coorect
what threats does encryption-at-rest protect against?
> accidentally sharing the database file with samba on win server
> theft of data by cloud provider admin
> theft of mongodump backup tape
> an  intruder getting rot access to the database server


cloud
what is redundancy in cloud storage?
> duplicate of critical component or system to ensure continous operation in the Event
of a Failure
> unnecessary investment in duplicate system and config
> preparing for and recovering from a catastrophic event such as natural disaster
> strategy that ensure a system s continuosly available to users with minimal downtime

which of the following features of RPO ? (select all that apply)
> max age of files that must be recovered from the previous backups to ensure business operations
> Amount of time that can pass before the outage impedes services
> amount of data lost in an outage
> time taken to get all the system up and running again

match the nines of uptime  guaranteed by the provider with the respective availability
and downtime

three nine

what is the cloud networking?
> connecting all the systems within an organization to a pulic,private and hybrd cloud
> controlling the traffic on the website by using multiple servers
> connecting to a virtual machine by running linux securely
> creating virtual network with the help of software

how does SDN support cloud networking?(select all that apply)
> Security: SDN can make your network more secure
> network Virtualization
> scalability
> automation


what is cloud storage?
> technology that eneables storing data and files on the internet
> technology that allows you to progammatically create content
> technology that eliminates the need for storage
> > technology that make storing data in hard disk faster


which strategy allow enterrprises to downsize applications that are no longer
useful in production
> refactor
> rehost
> retire
> repurchase

which strategy is considrerd the most future -proof migration approch
> refactor
> rehost
> retire
> repurchase

which strategy involves swapping interally admin system for third-party managed services
available from the cloud provider
> refactor
> rehost
> retire
> repurchase

what are the various cloud storage types based on how data is stored and retrieved?(select all that apply)
> warm storage
> block storage
> object storage
> file storage

match the storage categories with the respective performance
a> Hot storage
b> warm storage
c> cold storage

1> cheap and deep
2> capacity optimized
3> high performace

what are some benefits of migrating to the cloud?(select all that apply)
> reliability
> scalability
> cost optimise
> collaboration

which definition best descibes platform as a service (PAAS)?
> A complete cloud env that includes  everything developers need to build,
run and manage applicaations - from servers and operating systems to all 
the networking, storage middleware tools and more.
> a cloud service delivery model in which businesses are proided with all the
req resources to power compute, networking storage,networking and other service
> a software licensing and delivery model in which software is licensed on a 
subscription basis and is centerally hosted


match the migration strategy with the function
a> refactor
b> retain
c> rehost
d> replatform
e> repurchase
f> relocate

1> lift an reshape
2> lift and shift
3> hypervisor lift and shift
4> Drop and shop
5> rearchitect
6> revisit

what is the core objective of finops?
> to focus solely on it infra without considring financial implications
> to create a budget that is fixed and unchangeable throughout the year
> to bring accountability and visibility to cloud costs
> to elemeniate all cloud spending entirely

how is finops best defined?
> a collobration of operating model and tech that combines finanacil best parices with 
tech to optimize cloud cost
> a collobration of finance and operations professionals that combine their 
joint expertise in developing cloud based business solutions
> a collobration of  finance professionals that drive a business to find way to make
the job of finance professional more efficent

why is it difficult to track cost for multicloud?
> it's not well understood
> it is a less complex cloud deployment
> it uses aws
>  it is a more complex cloud deployment


what is the core objective in cloud spending optimization?
> to minimize cloud cost while ensuring optimal perfomace and resource
utilization
> to elimiates all cloud spending entirely
> to maximize cloud servicr usage without regard to costs

what is included in a finops playbook?
> all of these asnswers
>tools
> processes
> skills


oss2 platform
where do you get base images from?
> download from the internet
> artifactory submissions repository
> nexus
> artifactory base-images repository


what is the function of jfrog artifactory?
> All of the below asnswers
> for npm,mvn, build dependencies
> to store the docker image
> to store the helm chart

in this oss2.0 building block, developers can consume and interact with our product and services from their 
development pipeline
> presistent storage
> security scanning
> container networking
> platform api

to create an ubuntu base layer within a docker image, we run this command:
> FROM base_images/mmcos/ubuntu
> FROM base_images/mmc/red_hat
> FROM base_images/nnc/ubuntu
> FROM base_images/mmcos/red_hat

when selecting a base image for your containers, we recommand:
> Red hat base images - because we are more familiar with them
> Gnome- to ensure desktop compatibility
> finding something on the internet
> ubuntu base images - becuase they are lightweight and secure


command to build dockerfile
> $docker build <path to docker file>
> $docker build to <path to docker file>
> $docker build in <path to docker file>
> none of above


with _____ out nodes can host pods across multiple application hosting tiers,
maximinzing resource ussage.
> the self service portal
> software-defined container networking policies
> software-defined storage
> an enterprise secrets mangmenet solutions


true or false
all docker images are made up of layers and every docjer image uses a base image


why is it necesasry to have an image managment solution in place?
> to ensure that only approved secured images can run on the platform
> it is not necesasry
> to create high resolution images
> to create a secure netowrk connection

how can you best determine wheather network policies are the cause of a failed connection in 
or out of a pid in oss2.0 kubernates?
> directly contact a member of the platform team for assistance
> visit the calico dashboard in datadog and filter by your cluster and namespace
> raise a change order
> ask for help in the teams issue channel

which command is used to create a new layer a docker image containing the application code?

what is the purpose of the dockerignore file?
> to manage docker network inside your deployment
> to optimize the image by excluding files and directories that you dont need
> to manage docker image lifecyles
> to manage docker containers sequentially

what does the COPY instruction do in a Dockerfile?
> the COPY command allows you to copy a file or folder from your host system into the docker image
> the COPY command create a copy of your image
> the COPY command makes a copy of your Dockerfile
> the COPY command create a copy of your running container

information such as API token and certificates are taken care by the ______ solution in platform
> self service portal
> conatiner networking
> security scanning
< secrets managment


what are the web app offered by camunda?
> cockpit, tasklist, admin
> cockpit, userlist , groups
> cockpit, usersetting, admin
> none of above

with camunda cockpit you can monitor _______
> Group
> users
> workflow and processes
> none of above


php laravl
design api endpoint to fetch the user countries based on  ORM
we have usertable and country 

how we define route, controller 
need sudo code


react  we have 2 array extract only the 'id' value
let arrOne = [{id:1,name:'a'},{id:2,name:'a'},{id:3,name:'a'},{id:4,name:'a'}]


in arrOne add value at index number 1 one value and print final array


write a react component to fetch and render name,gender using api
https://randomuser.me/api

sql
write a sql query to fetch the 7th and 8th student based on marks from student table

javascript
pick second larget value from array without inbuilt 

in complex 
the company is mifrating large monolthic app to microservice service app
how to design this with share state managemnet 



implmentining component libraray
task is to implement shared component library with angular
how would we arch this libraray with resuablity


base on secure lamadba function with securing secrets
to enhance secuirty we need to avoid hardcoding
we need to design this in secure form and how lambda will access values

building realtime chat application with app sync aws
taks is to development chat with app sense and graphql
design arch of this app and how we will manage real time updates and offline senarios 

monitiring and observability
with microfront with angular and node
design arch with aws 

angular
create a custome that take string as input and revert the string
and add that pipe in component

const str = "axids=gam=y-ETroKRJE&dv360-eS1UaD&ysdsp=y-3Xi&tbla=y-zR3R;
table_id-df6;weathergeo=%222%7Click;cmp=t=123455"

write the function to extact value of cmp from string
console.log(extractValue(str,'cmp'))

modifiy code
now we have something like array of values
const [cmp, tble_id] = // should get output
console.log(cmp, tble_id) and this should happen in parallel


python
we have csv file 
id name and sale column
write code to calcute total sales grouped by name and save in new csv file


let say we need to design a page student progress card
and api return data for marks we need to show the total % of marks for student
in order to delop in angular

javascript
let a = [...[..."..."]].length


const product = [
    {id:1,name:'aa',price:12.99 and many more},
    {id:2,name:'bb',price:12.99 and many more}
    {id:3,name:'aa',price:12.99 and many more}

]

remove all product with name "aa" and update all product name "bb" to "cc"


cretea a custome hook called 'useWindowsize' that display the current width and height of browser window
const App = () = {
    const size = useWindowSize()

    return(
        {
            size.width
        }/ {
            size.height
        }
    )
}

the width and height can be derviedc using width= window.innerWidth, height = window.innerHeight


golang 
what will be output

package main

import(
    "fmt"
    "time"
)


func main(){
    go helw()
    time.Sleep(1 * time.Second)
    goby()
}

func helw(){
    fmt.Println("HW")
}

func goby(){
    fmt.Println("GB")
}

golang goroutine


golang
var intSlide = []int{91,42,23,14,15,76,87,19,95}
implmenet two channel and two groutine to find the odd and even number

outpu will be
ODD 91
ODD 23
Even 42 and so on

javascript 
code tht reads and process the "enenrgyConsumption" dataset below
1> write a function to calacualte the total consumption for each region 
    (like [{regaion:A, cosumpution: 123},{regaion:B, cosumpution: 345})
2> write a function identify the region with highest enery consumption
3> optimized code the efficienctly handle the datatest imagine you have milion of record_status

const dataset = [
    {"region":"Region A","energy_consumitption":100}
    {"region":"Region B","energy_consumitption":34}
    {"region":"Region A","energy_consumitption":45}
    {"region":"Region C","energy_consumitption":33}
    {"region":"Region C","energy_consumitption":56}

]

javascript
take 2 different size of unsorted array containing duplicate Elements
then merge the array without duplicate in a sorted manner


sql
we have 3 main information portfolia management 
email, assest and investement
we have to enter in the company
there are set of assets for DL and 

investement dont direactly invest into DL but they invest in funds
set of funds get invested like A and B and c
we can say DL 1 funded A and B , DL2 invested in fund C and B and so on 
there are many to many releationship

can we think how model will made for database


angular
we have obe address list compoent and other is address component
we have to use addresslist component use address component

javascriot what will be the output
var a = [1,2,3,4,5]

for (var i = 0; i<a.length;i++){
    setTimeout(function(){
        console.log(i)
    },1000)
}

swift 
we have high order function so implement filter function


    react code
there should be state with default value
on click on button it should incemrent
but in console.log it should print old and new value both


react
we have array of 20 record and display in table 
and on each page we should only 5 record and we have prev and next button
on first page prev shoud not be disable and on last next should be 

golang
write 1 function to find out prime number upto n numbers


golang
creata a function that accept any number of pre-sorted integers slices and return a single
    sorted integre slice containing all of the elementts of the input slice
    any packages in go standard libraray

    input
    {3,9},{},{0,5,8,} and {2,6,7,8}

    output
    {0,2,3,5,5,6,7,8,8,9}

golang
we have 2 variable a as 1 and b 2 swap in single line

i have employee table each emp is connected to department
table have name id and location 
get all the emp whose location is abc and department is abc

golang
abcdeabcdabcaba=>
e>1
d>2
c>3
b>4
a>5

from string return the count of character
and we have just same char in whole string should throw error
like just aa > throw error
bb => thro error
abcc
a> 1
b>1
c>2

mongodb we have 2 records with case insentive data how to search both in mongodb    query

  {
    "name": "John"
  },
  {
    "name": "john"
  }


golang
we are given a list of valid pins ["1234","0001","6789"]
we are also given the input string fron a pin pad
the input string contains the numbers [0-9] and can conatins backspace char respresent by '#'
write a function to checky string is a valid pin number.
input 
"1234" > true
"0000" > false
"1233##4"> true is reolved to "1234"
"02#0011#" > true is resolved to "0001"


time and space complixity

codw with swift
find thrid, second and first form array of integere without sorting


node

typescript

what all things authenticion in angular
restapi authenticion code jwt

golang
in microservice
service a communicate with b service
and how would we gracefully handle take of downtime if go down


golang 
where we can mutex

golang 


golang
write program to demonstrate how to handle
fan-in and fan-out conncurencu pattern
use goroutineq and channel to process multiple job and aggregate result 

javascript
export fuction isArray(value){
    
}

golang
you are given 9*9 sudouo board.
A sudouo board. is valid f the following rules are followed:
> each row much contains the digit 1-9 without duplicate .
Each column must conatins the digiti 1-9 without dupicate
each of the nine 3*3 sub boxe of the grid must contain the digit 1-9 without duplicate
retrun true if the sudouo board is valid otherwise return false
Note a board does not need to be full or solvable to be valid
input 
board = {{"1","2",".",".","3",".",".",".","."}, so on }

javascript
find 2nd largest number form array


create a form 
email  and password
and submit in state
use hooks and moodren way use ref


javascript
write function which will take 2 aregument
    one is array of integer and second is sum 
    we need to return all comibination that will form sum


javascript
i have array of number not sorted but move even to left and odd to write


golang

func main(){
    slice := []int{1,2,3}

    updateArray := Update(slice)
    println(updateArray)
}

func Update(num []int) []int{
    nums[1] = 4
    nums = append(nums,5)
    return nums
}


func main(){
    go hellowWorld()
    time.Sleep(1 * time.Second)
    goodbye()
}

func hellowWorld(){
    fmt.Println("hii")
}

func goodbye(){
    fmt.Println("bie")
}


golang
given an array [5,2,6,1] print the indexex of the elem that will add up to the sum of given number

Ex given number 3
output index 1,3

application for allow user to book calender where user can set like this week only 30 min you can book
how do we design this app



sample code for gorotuine to show both unbuffer and buffer channel

golang

this is kafka event data
exampleData.json
[
    {
        "eventId":"1234-5678-9012-3456",
        "payment":{
            "paymentId":1,
            "amount":100,
            "currenncy":"USD",
            "payer":"Abc",
            "reciver":"ZYX"

        }
    },
    {
        "eventId":"1234-5678-9012-3456",
        "payment":{
            "paymentId":2,
            "amount":130,
            "currenncy":"USD",
            "payer":"giu",
            "reciver":"ZdgYX"

        }
    }
]

main.go

package main


func main(){
    var(
        ctx
        db
        handler
        logger
    )

    event := events.Event{
        eventId:"1",
        payementId:"1",
        amount:130,
        currenncy:"USD",
        payer:"giu",
        reciver:"ZdgYX"
    }
}

handler.go

package event

type PaymentEventHanlder struct{
    DB database.Database
}

func NewPayment(db database.Database){

}

type EventPaymanet Struct{

}


type Event Struct{
    
}


func (p PaymentEventHanlder) processEvent(ctx context.Context, e Event)error{
    //implement here

}


database.go

package database

import (
    "context",
    "error",
    "time"
)

type Database interface{
    savePayment(ctx, payment) error
    GetPayment(ctx, id) (*Payment,error)
}

type DB struct{
    cache map[string]Payment
}

func NewDatabase() Database{
    retrun &DB{
        cache:Map[string]Payemnt{}
    }
}

type Payment struct{

}


// need to implment 
func (d *DB) savePayment(ctx,payment) error{

}

form react app call api https://jsonplaceholder.typicode.com/todos
display only userid and title and only disply where completed: true



there is a restaurnat with a single chef you are given an array customers where customers[i] = [arrival,time]
arrival is the arrival time of the ith customer the arrival time are sorted in non-descesing order
time is the needed to prepare the order of the ith customer

when a customer arrives he gives the chef his order and the chef start preparing it once he is idle
the customer wait tiill the chef finsish prepating his order.
the chef does not prepare fodd for more than one customer at a time
the chef peraores food for customers in the order they given in the Input
return the avh waiting time of all customers 
solution within 10^-5 from the actual answer are cinsidered accepted

input customers = [[1,2],[2,5],[4,3]]
output > 5.00000

input customers = [[5,2],[5,4],[10,3],[20,1]]
output > 3.25000


javascript
write custome logic to flatten nested array


golang
create a function that accept any number of presorted integer Slice and return 
a singe sorted integer cintaiing all the element of the input slice

javascript
there are 2 word s1 and s2 we need to check are they anagram of each other
all value will be lower case and no special char


javascript
given two string s and p return an array of all the start indices of p's
anagrams in s. You may return the answer in any order

example
input: s = "cbaebabacd", p ="abc"
outpu= [0,6]

input: s = "abab", p ="ab"
outpu= [0,1,2]

python 
you are given an non empty array we have every element twice only 1 element coming once
find that

javascript
we have to gatther matirx aroud which user using which pages in website
we need to save log timeStamp, custionId, loginId
for everyday we have new file


we need to read 2 log file we need to find loyal customer
criteirs 
> both day they visited website
> visit 2 unique pages


write function to return log of day1 and  day2 and return list of loyal customer


javascriot
write function to find the longest consective seques from the array
input [9,5,6,3,4,7,8,2,11]
output should be 8


input [10,20,30,40]
output should be 1


angular
write service to fetch data from api


golang concurenncy  lets say we have 3 system a,b,c and c is very slow just accept 16 trans whereas 
a and b is very highthough a is upstream and b is interface to c how to implement


golang
lets say we have slice of integres
write the gorotuine to sum of the values

golang

find longest palindrome
substring 
given a string s find and return the longest palindorm substring in s 
you may assume that max length of s is 1000
input : "ababd"
output: "aba"
input :"asdfsda"
output: "a"



golang
you are given a array A containing N integers
a pair of elements A[i] and A[j] is said to be similar if both the given
consitions are satisisfuy
1> i!= j
2> A[i] = A[j]+1

you have to find the count of differetn pairs of similar element in the array

2pairs (A[i],A[j]) &(A[k],A[i]) are said to be different if (i!=k) Or (j!=i)

input {1,5,6,2,5}
output = 3 pairs

use 
func similiarElements(N int, A []int)int{}


search and sort : concertQueue

n people each with a differe heigh attedn a concert 
they all are standing
due to the hright of the poeple standing before then some face issue
find the number of people with a height greater then those standing behind them

fun concerrQueue(N int,A[1000]int) int{}

input 
5
5 4 3 1 2

output
0,1,2,3,3

postgress can you write custome function to find non null records like we have 3 row we have id and rest is value ,  id  value1 value2 value3

id  value1 value2 value3
1   null    "data" "data"
2   "value"  null   "value"
3   null     null   null


ouput shouuld
row1 value1
row2  value2
row3  value1

solution arch need to find th method and task for solution planning which method and task role he can use
> ADM for servce delivery
> ADM for servce package development
> ADM for solution planning for Si 
> ADM for application Modertnization


Primart purpose of calcuating the estimate at completion
> to Evaluate the prosjct schedule
> to forcast the total cost of the projact at completion
>to measure cost efficiency
>to determine the amount of work completed

What is the signifcance of the contract and MSA in the IPC co-create processs
> it outline the deployment approch and estimate for the project
> it require an understaing of components like scope deliverable and commerical terms
> it provides insight into the key martics for predictable goverance
> it define the overall delivery strategy

A project manager is planning a communication strategy what is the primary goal of the strategy
> to reduce project documentation
> to avoid conflcit within the team
> to ensure timely and effective info dissemantation
> to min Communication with stakeholder

which of the following best describe "KISS" princeple

in the SOLID principle which principle suggest that a class should only have one reason to change

what is the primary purpose of axure RP within the AIDT framework

what does the averge Daily rate principle represent

you can share myWorkspace presenatation only with your teamin ARC
> true
> false

what is a core focus of agile leadership


what  does agile leadership prioritize when it comes to product delivery
> Minimizing the number of featre n each release
> Ensuring long-term planning
> delivering working software frequently
> delivering complerhsive docuemnt

which itil framework component focus on defining and managing the entire lifecycle of it service
from planning through to delivery and support
> service transition
> service design
> service strategy


we have table A total rows 10 and table B total row 6 it has common 3 rows from table A.
write all joins and output

python
we are number integer we have to flip


python 
write async function get queu as input and every second it should return 10 message to queue

golang


python
maximize bankruptcy
> you will reveice a list as input conataining the stock values arrange
in order from the date of their intro to the last value the values are integeres

you must return the maximal loss p expressed -ve if there is a loss otherwise 0

ythe list cann be significatn size(upto 100000 elemets)
ecah value is an inegetr between 0 to 2^31

example 
input = (3,2,4,2,1,5)
output = -3


golang

input is array of string and output is grouped of input
input = ["eat","tea","tan","ate","nat","bat","teae"]
output = [["bat"],["nat","tan"],["ate","eat","tea","teae"]]

golang

st region sku ams emea apj unit
0   ams   101 10  20    7   1
1   emea  101 15  23    8   2
2   apj   101 11  12    9   3
3   ams   102 55  65    45  2


output
st region sku dollarvalue unit total
0   ams   101   10         1    10
1   ams   102   55         1    110
2   emaa  101   23         2    46
3   apj   101   9          1    27



javascript
you are given a non-negative integer N your task is to write a program
that can print the number of prime numbers less than N.

input:
the input contains an integrs N represting the non-negative integers

output:
print the number of prime numbers less than N


input : 10
output :4

implement method name solve

javascript
Design a data structure that follows the constraints of a Least Recently Used(RLU) cache

RLU cache should support
intialize the LRU cache with a positive capacity 
no keys shoud present in the cache initilly

int get(int key): Return the value of the key if it exist, otherwise return -1
void put(int key, int value): update the value of the key if the key exists
otherwise add the key-value pair to the cache
if number of key exceed the capacity from its operation evict the least recently used key

input
2
6
GET, 2 PUT, 1,100 PUT,2,125 PUT,3,150,GET,1 GET 3

output
-1 -1 150

javascript
not increasing not decreasing
you are given an array consisting of distinct integrs Print the
min number of elements to be removed such that no three consective
elemement in the array are either increasing of decearesing

input
5
1 2 4 1 2 

output 
2

javascript
little brother factoral challange
 your 10 year old brother 
 he mad a list of factorials of numbers from m to n 
 now your brother wants challenge you
 you must write a progam to find all the numbers(if any)
 whose factorial start with an evne number.

input  1 to 10
output 2 3 4 8

input 5 to 7
output 0


given a string find substring base on
The susbtring must be the longest one of all the possibel substring in the given string
there should not be any repeated char in the substring(case senstive)
if there is nore than one substring sataisfy the above two condition then print
    the substring which occur first

if there is not substring all the aformentoned condition then print -1

input > "character"
output > "racte"

python function to calcuate cost of the pizza

thin curst > 8
cheese >2

small > 0.75
medium > 1.0
large> 1.25

small thin curst cheese ($8 + $2)*.75


javascript
input  = ['A','B','C',1,2,3,'4','5',6,'@','~']
 
* split the string, integer and special chart into new array
make sure 4 and 5 which is a string should br in integer array list and connver it to integer

follow -up
integer = [1,2,3,4,5,6]
split it to 2 array with random element and sum each array


golang
write function take an slice in array of integere and we need to return most frequent accuroance number


python
write iterater class 


angular
implmenent route gaurd that prevent access to the /admin route unless user is authenitcated


typescript
what is interface and create and demontracte


typescript
concept of async and await with code example

typeScript
async fetchAllData(){
    const data1 = await fetchData();
    const data2 = await fetchData();
    return [data1,data2]
}

javascript

kth non repeating character
given a string str of length n(1<=n<=10^6) and a number k, the task is to find the kth non-repeating char in the string

inpit = "geeksforgeeks, k"= 3
output = r

input = "geeksforgeeks, k"= 2
output = o


write  code for toggle border color in angular for div

component used to show list of latest update to users
in component h1 element and toggle the visisbility og th div with id"upgarede-list"
bt clicking h1 element the dv element sgould be visiabel at start 

the counter compoennt implement  a counter it consis of a button to increment
the count and a label displaying the current value it can be used within another component template
fins the app component so that it incluses the counter compoenent within its template and 
set the counter count value to the appcomponent variable counterState.
when counter count variable incresed the appcomonent counter state should refelt the chnages


complete function generateNewFolderName that recievs an array of folder names and return a generate unique folder name using
    following rules
    1> if there is no fikder with name "New Folder" in the array then "New Folder" os returned
    2> if there is a folder with name "New Folder" and there is no folder with name "New Folder (2)"
    the "New Folder (2)" is returned ("New Folder (1)" is never used)
    3> the N value of "New Folder (N)" should increment by 1 until a unique folder name is found


    func main(){
        rand.seed(time.Now())

        wg := &sync.WaitGroup{}

        numbers := make(chan int)

        for i := 0; i<5;i++{
            wg.Add(1)
            go generateNumber(wg, numbers)
        }

        go func(){
            for{
                number, ok := <-numbers
                if !ok{
                    break
                }
                fmt.Println(numbers)
            }
        }()

        wg.Wait()
    }


    golang https://go.dev/play/p/p23ZbmWUMke



react with typeScript

design poll manager app that allow user to vote for one
of two options and view the winner

the app have three component
pollmanager
vote
result

the vote component
> display text of each option
> provide a "Vote" button for each option to cast a vote
> disable the "vote" button for each option when the winner is declared

result component
display the current leader or tie status
> display the result text based on the condifiton
a> if no vote gave been cast the result text should be empty ""
b> if the sam number of vote have been cast for both options the result text should be "it is a tie"
c> if one option has more vote than the other , the result stext should be "(Leader) is leading by (Vote_difference) vote(s)"

view component
> if no vote have been cast the button should be disable
> clikcing on "view winner" button 
a> display the result text:"its a tie" if the sae number of vote
have been cast for both
b> display the result text:"{Leader} won by (Vote_difference) vote(s) if one option has more votes than the other "
c> disable the "view winner" button
d> disable the "vote button"for each options

poll manager component
> display poll question
> manage the state of the poll incuding votes and winner status
> pass the relevent data and function to the vote and result component


    in result component
    interface ResultsProps{
        poll:Poll;
        viewWinner:boolea,
        setViewWinner:(viewWinner:boolean)=> void;
        totalVotes:number;
    }


we have types folder with file Poll.ts
export interface PollOption{
    id: number;
    text:string;
    votes: number;
}

export interface Poll{
    question: string;
    options: PollOption[]
}

export const pollData:Poll = {
    question:"Who is abc",
    options:[
        {id:1,text:"A",votes:0},
        {id:2,text:"B",votes:0}
    ]
}

interface of Vote component
interface VoteProps {
    options: PollOption[];
    onVote: (index: number) => void;
    viewWinne: boolean;
  }
  


  write react comonent which take file form user like upload file form local machine and upload to server
  (file will be huge)


  python complete the function
opmize datatabase query times
there are n host serveres where the throughput of the ith host server is given by the host_thorughput[i].

these host server are grouped into cluster size of three the throughput of the cluster denotes as custer_throughput
is defined as the median of the host_thorghput value of the threee server in the cluster
Each host server can be part of at most one cluster and some server may remian unsued

th total syste through called syste_throughput is the sum of the throughput
of all the cluster formed the task is to find the max possile system_throughput

n= 8
host_thorghput = [4,4,5,6,4,4,5,6]
output 11

function name is 
    
def getMaxThruughtput(host_throughput):


the median of a cluster of three host servers is throughput of the 2nd server when the thre throughput are sorte in eitger
ascending or desceinding order

angular
displayColumns: string[] = ['name','age','city']

in table add button to sort on basis of name and use material Ui comonenent


[5,6,7,8]
[x:x**2 for x in my_list if x%2 != 0]



let a;
var b;
console.log(a)
console.log(b)

create an observable that will prit sequence
[2,3,4,6,8,..100]


const studentData = [
    {name:a, marks:[{m:80},{p:90},{c:40}]}
    {name:b, marks:[{m:100},{p:50},{c:70}]}
    {name:c, marks:[{m:65},{p:80},{c:70}]}
]

write code to get the topper for each subject
if more than one topper make it as an array

componant Address

export class Adress{
    street:String;
    city:string;
}

@Component({
    selectpr:'app-address',
    temp;ate `<p>{{addrss.street}}</p>`
})

export class AddressComponent


AddressListComponent{
    @Input()adddress:Address[] = [{street:'a'}]
    Construcotor
}





var a = [1,2,3,4,5]
for(var i = 0; i<a.length;i++){
    setTimeout(function(){
        console.log(i)
    },1000)
}
