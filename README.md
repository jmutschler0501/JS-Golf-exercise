# JS-Golf-exercise
JS Algorithms and Data Structures
This is my favorite exercise so far!  Moving along nicely!

var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
if (strokes == 1) {
  return names[0];}
if (strokes <= par - 2) {
  return names[1];}
if (strokes == par - 1) {
  return names[2];}
if (strokes == par) {
  return names[3];}
if (strokes == par + 1) {
  return names[4];}
if (strokes == par + 2) {
  return names[5];}
if (strokes >= + 3) {
  return names[6];


}

  return "Change Me";
  // Only change code above this line
}

golfScore(5, 4);
