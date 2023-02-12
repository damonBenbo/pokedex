# pokedex

![pokedex](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjyBCSPs4MgvFtCY8T-roDTxd1rvErY540uA&usqp=CAU)

---

## Goal
---
My goal in making this is to create an interactive pokedex, much like the one used in the games and shows where the user can look up and browse through a database of pokemon with their information and a picture displayed for it.

This site is going to be geared towards all of the *Ash Ketchums* out there who are a aiming to be the very best that ever was.

---

## Database

---

I plan on using a database and API that has all the information about the pokemon that will be in the pokedex, [pokeapi](https://pokeapi.co) . This contains a lot of information about all the pokemon and uses postgresql for its database and what I will also be using to wrangle all the info needed for displaying.

The database schema I’ll be aiming to use is leveraging the postgresql that it currently uses. The schema is going to look something like this:

![image](https://user-images.githubusercontent.com/115174854/218297215-f0777066-319e-42c0-8d20-23da96a6c0c6.png)

---

## Functionality

---

The app will have the ability to search pokemon by name/number so users can pull up a specific pokemon that they might be looking for information on. I also am aiming to add  next/previous buttons to browse through each pokemon if a user just wants to look through.

The user flow will look something like this:
1. User navigates to site to references or look up pokemon
2. User can use interactive pokedex to either next/previous with buttons or use the search bar to look up a specific pokemon
3. User can reference information about selected pokemon and find any details they may need to know and scroll through data.
4. **Rinse and repeat**, User can continue process until they have found all the data they have needed for any pokemon

---

## Stretch Goals:

---

After finishing the fundamental aspects of the app I hope to implement 3D models into it for where the pictures will be currently going, or allow for toggling between for user preference.

I would also like to add the ability to add a toggle to show the “shiny” variants of the pokemon and genders if possible.

