# Emoji-matching-game-

Emoji matching game  in js 

- Methods involved :
  - Flip the card 
  - Success event
  - Failure event
  - Resetting the event 
  - Shuffling the cards
  
- To Access the card :
  - Use query selector 
  - data-image attribute is used in  Images 
  - data-set.image is used in javascript to access the images 
  
- To flip the card : 
  - Add Event Listener 

- To keep track of the cards 
  - Use 3 variables 
  - isflipped = false 
  - firstcard= null or undefined 
  - secondcard 
  - Since the default value is null or undefined , it need not be undefined 
  
- ```javascript 
  function flip()
    this.classList.add("flip")
    if(isflipped==false)
      Switch on the isflipped flag as true 
  ```
- ```javascript 
  function reset():
  // reset all flag values 
    var isflipped = false;
    var firstcard;
    var secondcard;
  ```
- ```javascript 
  function success():
    removeEventlistener(firstcard && secondcard);
    reset();
    // stop flipping the card and turn it open 
    ```
- ```javascript 
  function failure():
   if (failed):
    // do reverse of flip function
     settimeout(()=>{
     this.classList.remove("flip")
     ,1000})
    // to hold on things for a minute
  ```
- 
```javascript 
  function shuffle(){
  var index= math.random()*16;
  card.style.order=index;
```

<img src="Screenshot (736).png">

https://suprajaarthi.github.io/Emoji-matching-game-/
