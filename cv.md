# Nefontov Dmitriy
----
## Contacts
* **Phone:** +7(921) 441-82-99
* **Email:** Nefontov@gmail.com
* **Discord:** [TheShumniy](https://discordapp.com/users/424598991058239488/)

----
## Objective
* Learning something new.
* Learning the JavaScript programming language
* Becoming a web developer

----
## Skills
* C++ Basic
* Java Basic
* Visual Studio 2022, IntelliJ IDEA
* Git, GitHub

----
## Education
**University:** Saint-Petersburg State Marine Technical University, Automation engineer

----
## Code example
**Project Casino** 

***this project is a mini casino game.***
* *You have $1000*
* *Need to place bets*
* *After the bet is made, the program randomly decides whether the bet has won or lost.* 
* *The game goes up to $0*.

***After all, casinos always lose!*** 
``` 
//Code in Java

import java.util.Random;
import java.util.Scanner;

public class Casino {
    public static void main(String[] args) {
        int money = 1000;
        if (money>0){
        do {
            System.out.println("У вас :"+money+"$");
            System.out.println("Делайте ставку");
            Scanner IN = new Scanner(System.in);
            int a = IN.nextInt();
            if(a>0&&a<=money){
                int b = (int)(Math.random()*10);
                if(b>=5){
                    money -= a;
                    if(money<=0){
                        System.out.println("Вы проиграли!");
                        System.out.println("У вас не осталось денег, проваливайте от сюда!!!");
                    }else {
                        System.out.println("Вы проиграли, попробуйте еще раз");
                    }
                }else {
                    money+=a;
                    System.out.println("Вы выйграли, попробуйте еще раз");
                }

            }else {
                System.out.println("У вас нет столько денег, поробуйте поставить другую сумму");
            }

        }while (money>0);
        }
    }
}
```
----
## Experience
I work as a marin automation engineer.

I have no experience of working in IT.

----
## English
A1 (beginner)