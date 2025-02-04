# autranz-speech_recognition ~ *SPEAK SEE*

<img src="static/images/AUTranz (1).png" alt="AUTRANZ logo" title="meju" >


## Introduction

## The project

[**AUTRANZ**]((<https://imejuart.pythonanywhere.com/>)
) was created for the purpose of helping people with hearing impairment, this is our way of making life easier for these categories of people, they can speak and see what they want to type.

Other features include: login and save your transcriptions for authenticated users, detect transcribed text language.

## The context

This project is our Portfolio project,concluding our foundation session at ALX SE. we are able to choose our team members or work alone if we wanted and pick what project we wanted, provided we have a working programm at the end of the three weeks of development.

## The Team

* **Omotolani Damilola [@Brownlolaoo]()
* **Augustus Ikwuegbuenyi[@Imejuart1]()
* **Frank Success [@froschi95]()

## Blog Posts

After developing the programm, we wrote a blog post to reflect on what we did so far.

## Tutorial

## Take a tour of the deployed version

-> [**AUTRANZ**](https://imejuart.pythonanywhere.com/)

## how to use AUTRANZ

Go to the website **AUTRANZ**

* Sign up
* Sign in
* Upload audio and transcribe

## Known bugs

* it does not understand some ethnical languages, so you would have check google for the language.
* It can't transcribe more than one minute and You have to convert it to .wav file.
* You have to upgrade your API to go higher than one minutes.

# Architecture

## overview

Autranz is a multi--page app, its coded mainly in python, we used Flask to take in an Audio file and create both a GET and POST request. we designed all the userinterface with figma, and used html and css for the frontend.

<img src="static/images/infra.png" alt="infra" title="meju" >

Here is a screenshort of how the post and get method works.

<img src="static/images/architecture.png" alt="AUTRANZ logo" title="meju" >



## list of components

These components make up what a user experiences when they check out **AUTRANZ**. Each component contains the code for a specific page of the app.

| component | Description |
|-----------|-------------|
| [Landing.html](./templates/Landing.html) | The landing page a user sees when they navigate to **AUTRANZ**. |
| [Login.html](./templates/Login.html)   | The login page. There's a link to go to the Signup page if a user hasn't signed up. |
| [Detect.html](./templates/detect.html) |page where users can detect various of languages. |
| [Transcribe.html](./templates/transcribe.html) | users can transcribe and save their transcriptions.
| [Signup.html](./templates/Signup.html) | Signup page for users who do not have an account. It asks for a valid email address and for them to make and confirm a password. |
| [Dashboard.html](./templates/dashboard.html) | The main page of **AUTRANZ** where users can see another user's can see list of their transcriptions, time , and date .' |
| [UserProfile.html](./templates/UserProfile.html) |  on this page the user can change their  information such as name, location, phoneno and so on. |

## mysql

We decided to go with MYSQL for our backend/database as it provides all the functionality we need to develop this project such as  user authentication and updating user info, Also for monitoring the number of users we have using the admin dashboard.
Users can also save and delete transcribed file.


## Related projects

* [AirBnB clone](https://github.com/Brownlolaoo/AirBnB_clone.git):a simple web app made in python,flask and jquery.

* [Simple Shell](https://github.com/Brownlolaoo/simple_shell.git):a command line interpreter that replicates the sh program.

# License

MIT License
