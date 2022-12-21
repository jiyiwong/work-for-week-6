    float r;
    float g;
    float b;
    float a;
    float l;
    float x;
    float y;
    void setup() {
     size(500,500);
     background(0);
     smooth();
}
    void draw() { 
      
     rect(20,20,60,60);
     r = random(150);
     g = random(100);
     b = random(150);
     a = random(255);
     l = random(20);
     x = random(width);
     y = random(height);
     noStroke();
     fill(r,g,b,a);
     ellipse(x,y,l,l);
     
     

 if (mouseX < 80 && mouseX>20 && mouseY>20 && mouseY < 80) {
   fill(0);
  rect(x,y,l,l);
}
    }
void keyPressed() {
  if (key == 'x') {
    rect(x,y,random(1,100),50);
  }
}
