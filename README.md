# RPS Challenge

![Image of the game UI](cover.gif)

About
-------

This is a Ruby + Sinatra implementation of the "Rock, Paper Scissors" game created in a very much test-driven manner. You choose your signs while the computer makes its choice randomly. Try your luck, beat the allmighty!

You can play the game on Heroku:
https://sasso-carta-forbici.herokuapp.com


How to install
----

Download or clone this repository to your computer.
Open your terminal and navigate to the folder with the game (rps-challenge). Run `bundle install` to install the required dependencies.


Run tests
----
```
$ rspec
```

How to play
----

Open your terminal and navigate to the folder with the game (rps-challenge). Type in the following command and hit enter:

```
$ ruby app.rb
```
You should see something like this:
```
Thin web server (v1.7.2 codename Bachmanity)
Maximum connections set to 1024
Listening on localhost:4567, CTRL+C to stop
```

Now open your web browser, copy-paste the game address `localhost:4567` from the code above into the address line and hit enter. Enjoy!
