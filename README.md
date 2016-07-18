:sparkles: [one of my 100 projects](https://github.com/dotsara/100-projects) :sparkles:

# Score bugs

I watch a _lot_ of sportsball on tv. And few+ years ago, [I started cataloging](http://tumbly.dotsara.com/tagged/football) the different [score bugs](https://en.wikipedia.org/wiki/Score_bug)--the on-screen graphic giving you game details--for football games. Mostly because at the time some of them were _rubbish_ (I'm glaring at you, baby NFL Network).

It won't surprise you to know that once I paid closer attention to score bugs in football, I paid closer attention to them in every other sport I watch, too. Y'all, some of them are real bad. But! some of them are wonderfully thoughful, too. Par example: the bug for Wimbledon matches. :heart_eyes:

![Wimbledon 2016 Ladies' Championship](research/wimbledon_2016_women-championship.png)

You know: who's playing, who's serving, the current game's score, the outcome of previous sets (or games if you're in the first set).

It's so good!

My goal is to fiddle around with how _I_ think the best score bug should look for `#{sport}`. 

## (American) Football :football: 

Whether I'm watching at home or at a bar, there's information about the game I want at a glance:
* teams
* score
* possession
* game progress (quarter, time left)
* field position

The one that really gets me is how most of the network score bugs will show field position _until the play begins_ and then you are out of luck until the play is done and the score bug gets an update. Psh, that's too long to wait. And it's longer if there's a penalty. Boo.

```
            2ND 14:38

• PITTSBURGH       10
  ---

  BALTIMORE         3
  ---

  3RD & 4  -   OWN 45

```
