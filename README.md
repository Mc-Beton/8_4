# My first a bit upgraded, but still the same Site!:

Nothing much here, only learning the basics of creating a website in accordance to the Kodilla course.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Fisrt of all download or clone the files to Your pc.

### Prerequisites

Install flask, if You don't have it (yet, if You are here on GitHub i guess You already have it ;))

```
>pip install Flask
```

### Turn on Flask on cmd

In the app.py directory type in
```
>flask run
```
Thanks to that we can call out my website in a browser.

## Lets check it out!

### In a browser
Once flask is running on cmd, open any browser you usually use and type in:
```
localhost:5000/mypage/me
```
And there You go. Awesome, yeah? There is also another site, just type in:
```
localhost:5000/mypage/contact
```
Here You can "fake send" a message to me.

### What's going on behind the curtain (cmd)

As You can see, whenever you call out my site in a browser, or do sth on it, you check out what's going on in flask (cmd).
Once you called out my site by:
```
localhost:5000/mypage/me
```
You can see that flask received an information "GET".
In the second site "contact", You can "fakesend" me a message. Try it out.
Then in the cmd flask recevied your message as a "POST" method.

## But why again?

Just like in repo 8_1 these are my first steps in creating websites and try to understand the HTML Methods like GET and POST. It's almost a copy of repo 8_1, but it was needed for the corse.
I won't be doining anything more here, later I'll present more sites like this. Well, maybe more complex. ;)

## Authors
Filip Gabrys - Initial work With help from his mentor from the Kodilla course.
