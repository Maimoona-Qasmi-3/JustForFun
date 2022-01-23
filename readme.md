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
