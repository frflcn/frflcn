- 👋 Hi, I'm Trevor. I'm a self employed Uber Driver with a degree in physics looking for a job in software engineering.

I'm adept at solving complex mathematical problems and have tremendous problem solving skills.

I currently am proficient in Python, C++, and SQL.

I've programmed my very own working Android App in Java.

I've solved numerous mathematical and computational problems on the fun website, projecteuler.net, mainly in python but also in C++.

I on the occasion have used SQL to help me with my end of the year finances. 

I'm also in the process of learning javascript.



The Android App
I was in personal need of an app that would set alarms everyday according to when the sun reaches 30 degrees in the sky and when it sets.
Something that changes daily and according to your place on the Earth, so personally setting a new alarm everyday would be tedious and mildy annoying.
I tried to find an app that would do this for me, but was unable to do so, so I set out to design it myself.

I knew a little bit of Java from years ago, when my brother decided it would be a good idea if I knew Java. With the little Java I knew and the absolultely nil I knew about Android
programming, I set out to design the app. With lots of reading online docs and YouTube videos explaining Android, I finally came up with a working model.
It worked it was there bare minimum that I personally needed but not what an app with this purpose should have. So I added more and more functionality to get the app to where it is today.

The app uses:
Google Play services, to determine the user's current location.
A calculation from NOAA to calculate when the sun will set and be at 30 degrees in the sky.
Android's AlarmClockManager to set the Alarms.

I also learned how to use Google API's and API keys, to use Google map features in the app.



Project Euler

Project Euler is both a fun and challenging website that is designed to test both your mathematical and programming skills at the same time.
If you lack in either, the problems here will be out of reach.
Project Euler has plentitude of problems ranging from Extraordinaly Easy to Absolulety Insane, with a tendency to lean towards Absolutely Insane.
Nonetheless I Enjoy challenging myself with these problems from time to time.

One of the most enjoyable solves I had was problem number 70, which goes as follows:


Euler's Totient function, φ(n) [sometimes called the phi function], is used to determine the number of positive numbers less than or equal to n which are relatively prime to n. For example, as 1, 2, 4, 5, 7, and 8, are all less than nine and relatively prime to nine, φ(9)=6.
The number 1 is considered to be relatively prime to every positive number, so φ(1)=1.

Interestingly, φ(87109)=79180, and it can be seen that 87109 is a permutation of 79180.

Find the value of n, 1 < n < 10^7, for which φ(n) is a permutation of n and the ratio n/φ(n) produces a minimum.


A relatively simple problem to understand with a seemingly simple solution for a computer to solve:
Just loop through all the numbers of n up to 10^7, then loop through all the numbers less than n and see if it's relatively prime to n.
Count all the relatively prime integers and find φ(n).
See if φ(n) is a permutation of n.
Then find the minimum n/φ(n) where φ(n) is a permutation of n.

The problem is that this solution will take about 5000 millenia for the computer to run through all the numbers.




