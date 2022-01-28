//JAVASCRIPT
1.What are Data types?
Ans: String, Numbers and boolean
2.How to find the number of characters present in an alert or a prompt?
Ans: By using word.length().
3.How to take out a specific letter from the given word?
Ans: By using word.slice(0,0), in perenthesis we write first from where to start and after comma where to stop.(Note, In programming we always count from 0)
4.Function to make a name's fisrt letter capital and the rest small:
SOLUTION: var name = prompt("Write your name here:");
          var slicing = name.slice(0,1);
          var capital = slicing.toUpperCase();
          var restName = name.slice(1,name.length);
          var final = restName.toLowerCase();
          alert("Hi dear, " + capital + final):
5.Function to convert dog's age into human age:
SOLUTION: var dogAge=prompt("Write your dog's age down here:");
          var humanAge=(dogAge-2)*4+21;
          alert("If your dog was a human then it's age should be " + humanAge);
6.How many kinds of functions are there in Javscript?
Answer: There are three types of functions which are;
        1. Vanilla flavor: This function gives no output and takes no input. The simplest form.
        2. Chocolate flavor: This function only takes input but gives no output.
        3. Stawberry flavor: This is the hardest form of function which takes input and also gives output.
7.Function to buy some milk by giving and exchange of money:
SOLUTION: function getMilk(money){
          console.log("Leave House");
          console.log("Move Right");
          console.log("Move Right");
          console.log("Move Up");
          console.log("Move Up");
          console.log("Move Up");
          console.log("Move Up");
          console.log("Move Right");
          console.log("Move Right");
          var bottles = Math.floor(money / 1.5);
          console.log("Buy "+bottles+" bottles of Milk");
          console.log("Move Left");
          console.log("Move Left");
          console.log("Move Down");
          console.log("Move Down");
          console.log("Move Down");
          console.log("Move Down");
          console.log("Move Left");
          console.log("Move Left");
          console.log("Enter House");
          return money % 1.5;
           }
          getMilk(43.5);
8.Function to make a love calculator:
SOLUTION: prompt("Write you and your's name by seprating it with comma(,)")
          var random = Math.random();
          var whole = Math.round(random * 100)
          alert(whole);
          if(whole>=85){
          alert("Good Morning. Finally you are awake!");
          }else if (whole>=55){
          alert("Money in Friendship is just like oil in water. So be CAREFULL!!");
          }else{
          alert("Advice: 'Suicide is a permanent solution to a temporary problem'.");
          }
9.Function to make sure guest are invited or not:
SOLUTION: var entry = prompt("What is your name:");
          var guestList= ["Angela", "Jinnie", "Lester", "Selena", "Ketty"];
          if(guestList.includes(entry)){
              alert("Welcome Welcome!");
          }else{
              alert("Sorry!maybe next time");
          }
10.Last but not the least: Making a dice rolling webpage.
That dice rolling webpage is been uploaded in GitHub.
11.Making a live music band instruments.//
