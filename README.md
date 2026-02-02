At first, I just wanted to make a starry sky. 
But then I discovered the comet emoji—and some code that lets emojis follow the mouse’s X and Y coordinates.
And that’s when an evil idea popped into my head… 
```
function setup() {
  createCanvas(600, 400);
}
function draw() {
  background(0, 100, 400);
  //star in the sky
  textSize(30)
  text("✨", 20, 100) //star1
  textSize(30)
  text("✨", 400, 50) //star2
    textSize(50)
  text("✨", 450, 100) //star3
  textSize(20)
  text("✨", 130, 150) //star4
  textSize(80)
  text("☄️", 260, 180) //star5
  
  //earth on bottom half
   stroke(0);//black outline
  strokeWeight(1);//outline thickness
  fill("#75501A");
  rect(0, 250, 600, 200);
  
  textSize(80)
  text("🦖", mouseX, mouseY) //
}
