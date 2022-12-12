# Flatdango code challenge

# Description
This code challenge is about a mini-web application called Flatdange which allows the user to purchase movie tickets from the Flatiron movie theater.The user should be able to see a list of film titles on the left menu and the details of the first film on a card at the center of the page. When the user clicks on a film title, they should be able to see the films details displayed.There is also a buy ticket button on the card bottom that allows the user to purchase a movie ticket.

# Installation
To be able to run this program on your computer:

Open the terminal on your computer.

Clone the repo from github using:

    git clone https://github.com/JacobMuchori/flatdango-wk3-code-challenge.git

Change directory into the repo folder:

    cd flatdango-wk3-code-challenge

Open it in ``Visual Studio Code``:
  code .

## Running the application
To run the application:

- First run:

        json-server --watch db.json 
    
    
This ensures our db.json file is running in the backend.

- Open a new terminal:

        google-chrome index.html 
    
This enables us to run our html file in the browser.


# Project set up
Once the index.html file is running in the browser, you should be directed to a window which is displaying the mini-web application.In the mini-web application,there is a title showing the movie theater and a subtitle explaining the mini-web apps main function.We also have a left side bar that contains the title of the films that are available and a card displaying the details of our first film by default. Upon clicking of a specific film title, you should see a card display showing the details of the film title selected. The card shows the title of the film, its poster image, movie description, the movies runtime and showtime and the available tickets for purchasing. There is also a buy ticket button at the bottom of the card, which when pressed, you should see the available tickets number decrease, meaning that the user has purchased a ticket.

# Details of Author
 This challenge was contributed by:
- [Jacob Muchori Kinyua](https://github.com/JacobMuchori)

# License
-[ISC]