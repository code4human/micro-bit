[Introduction]
Microbit is a device for physical computing like Arduino, Raspberry Pi.
You can practice making codes on the website "makecode.microbit.org".
These codes are written easily for education.

[Explanation]
<microbit-traffic_light_STEP1.hex>
It's a code that prints traffic light, marking red light as 'O' and green light as 'X'. 

<microbit-traffic_light_STEP2.hex>
Traffic light of STEP1 is hard to cross at the crosswalk.
Therefore let the red light last for 2 seconds, and the green light flash repeatedly. 
 
<microbit-answer_robot_STEP1.hex>
Microbit has two buttons(A&B) on it.
On A pressed, it prints 'a'. On B pressed, 'b'.

<microbit-answer_robot_STEP2.hex>
In South Korea, there are famous idols : BTS and Seventeen. 
On A pressed, it prints 17. On B pressed, 'bts'.

<microbit-answer_robot_STEP3.hex>
Let the robot more friendly. You can make a question to the robot.
If you start, the robot print 'question'.
On A pressed, it prints 'yes'. On B pressed, 'no'.
On A and B pressed at the same time, it prints 'maybe'. 

<microbit-vending_machine.hex>
Let's imagine there is a vending machine with coke(no.1) and water(no.2).
If you start, the robot print 'drink'.
On A pressed, it prints 1. (So you can get a bottle of coke.)
On B pressed, it prints 2. (So you can get a bottle of water.)
On A and B pressed at the same time, it prints 1 or 2 randomly.

<microbit-angle.hex>
Microbit has a built-in tilt sensor. That's why you can estimate the angle with microbit.
On tilt left, it prints the negative number by the angle at which it is tilted.
On tilt right, the positive number.

<microbit-dice.hex>
It also supports shaking detection. 
On shake, it prints the random number 1 to 6.
You can play the board game with another person. 

<microbit-variable.hex>
We're gonna create a variable 'num'.
When you start, save 0 to the variable 'num'. And print 'num' to check the value.
On A pressed, 'num' will be changed by -1. And print 'num' to check the value.
On B pressed, 'num' will be changed by +1. And print 'num' to check the value.

<microbit-number_STEP1.hex>
With the variable 'num', you can judge the range of number.
The process of decreasing by -1 on A pressed is the same. However, let's add a condition.
If 'num' become less than -5, print string "small".

<microbit-number_STEP2.hex>
Similarly, on B pressed, if 'num' is more than 5, print string "big".

<microbit-rock.hex>
Using Microbit, you can make some games like rock-scissors-paper.
If you assign a number to each action, you can play the game.
Here we gave 0 to rock, 1 to paper, 2 to scissors.
When you start, print "game" and let the string last for 2 seconds.
On shake, let the variable 'num' store the random number 1 to 2.
If 'num' is 0, it shows the icon-rock. Else if 'num' is 1, then it shows the icon-paper.
And if 'num' are not 0 and 1('num'==2), it shows the icon-scissors. 
Let's shake!
