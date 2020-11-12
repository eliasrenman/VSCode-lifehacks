# VSCode lifehacks

Here is a compiled list of small or big lifehacks that I've come across when using VSCode, Primarily developing in Javascript / Typescript.

## Convert Json to Javascript object with search replace
I for one do not like having my keys defined with in quotes in javascript, but sometimes you copy paste a JSON object into your code and need to manually remove the quotes.
Heres were a small search replace will help you.

Simply input the following in the search bar and enable regular expressions.
```
"(.*)":
```
And in the replace box write
```
$1:
```
![image](https://i.imgur.com/61Qv2xh.png)
And like magic this:
![image](https://i.imgur.com/O076s6H.png)
Will turn into this:
![image](https://i.imgur.com/cjrYlSN.png)
