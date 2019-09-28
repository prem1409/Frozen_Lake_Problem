# Frozen_Lake_Problem
It is really cold in Edmonton out here. But noone can stop your zeal for playing. You along with your three friends have gone on a vacation to Bamph for a trip and you end up near Lake Louise. You guys decide to play frisbee in team of two each. The competition is pretty tough and both the teams are close to victory <br/>
With you at the throwing end you decide to throw frisbee really hard so that your team wins. And... There goes your throw and your team wins.You start celebrating but unfortunately you realise that with your throw you ended up throwing the frisbee into the lake. <br/>
The water in the lake is mostly frozen, but there are some holes where the ice is melted. In any case you want to get the frisbee. Since your rival team is sledging that you won by luck and they want a rematch. You want to show them who the real boss is <br/>
Incase if you step on the melted ice you fall into ice cold freezing water. Also the ice is slippery so you don't always tend to move in the direction you intend to.< br/>
This is how the environment looks like
```
        SFFF
        FHFH
        FFFH
        HFFG
S : S is your starting point and you know its safe to step on it
F : F is your frozen ice point. Here the ice is frozen so you can safely step on it
H : H is your hole. Here is where the problem arises. If you step on this you are doomed
G : G is where your final goal or frisbee is located
```

Now you have different conditions when your one attempt would end
```
1. If you reach your end goal.
2. If you fall into one of the holes.
3. You dont reach the goal or fall into the lake within 100 steps of your starting move.
```
You will recieve a reward of 1 when you reach your goal that is in case 1 in other two cases you will recieve a reward of zero

-------------------------------------------------------------------
## Prerequisites
This is a Python 3.x project. Please install requirements.txt using 
```
pip install -r requirements.txt
```
