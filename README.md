# hw2
void setup() {
  //Set Windows size
  size(500,500); 

} 
  
  
void draw() {
  
  background(#0041FF);
  fill(#EA001B);
  noStroke();
  ellipse(302,435,70,70);
  fill(#ffffff);
  textSize(50);
  text("WALL E",138,450);
  fill(#939393);
  strokeWeight(5);
  stroke(#000000);
  rect(164,147,65,32);//gözün dışı için
  noStroke();
  fill(#000000);
  ellipse(198,163,26,26);//sol göz için
  rect(228,148,16,13);
  strokeWeight(5);
  
  stroke(#000000);
  strokeWeight(5);
  fill(#8d7a6f);
  ellipse(182,263,28,28);//el bolgesindeki daire
  ellipse(292,263,28,28);//el bolgesindeki daire
  fill(#939393);
  rect(244,147,65,32);//sağdaki göz ün kutusu
  fill(#000000);
  noStroke();
  ellipse(275,163,26,26);//sağdaki göz
  stroke(000000);
  fill(#F5DB72);
  rect(228,161,15,56);  
  rect(216,217,40,13);
  fill(#939393);
  rect(181,235,113,33);//üst gövde
  fill(#F5DB72);
  rect(181,265,113,78);//alt gövde
  fill(#E0CDB7);
  rect(181,250,21,12);//el
  rect(181,264,21,12);//el
  rect(272,250,21,12);
  rect(272,264,21,12);
  fill(#8d7a6f);
  //ayaktaki tekerlekler=
  rect(144,285,37,29);
  rect(144,313,37,29);
  rect(144,341,37,29);
  rect(294,283,37,29);
  rect(294,313,37,29);
  rect(294,341,37,29);

  
  
  
}
