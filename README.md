// TASK 1 lav en bruger på Github

//////////////////////////////////////////////////////////////////////////////////////////////////////////

// TASK 2
String teacherName = "Tess Løvgreen"; // Tekst
int wholeNumber = 365; // Hele tal
String cityName = "København"; // Tekst
boolean hasPiaADog = true; // Har Pia en hund?
boolean doesThis_addUp = false; // giver 60*24 = 1439?
double decimalNumbers = 22.12; // Tal som er i decimal, double bruges oftere for decimaltal
char letter = 'S'; // Bogstaver, enkle anførselstegn er korrekt her
float score = 2.2 + 33; // en score
int minInADay = 60*24; // minutter på et døgn

///////////////////////////////////////////////////////////////////////////////////////////////////////////

// TASK 3
//3.A -  start en ny processing i sketch og kald den Task3

///////////////////////////////////////////////////////////////////////////////////////////////////////////

//3.B - I det globale scope, erklær en variabel af typen (string) med navnet (adress).

void setup(){
String address; // Denne variabel er deklareret udenfor.

void setup(){
  size(400, 400); // størrelsen på vinduet
  background(255); // 255 = hvid farve
  address = "Din adresse her"; // Adresse variable 
}

void draw() {
  fill(0); // 0 = sort farve
  text(address, 40, 40); //eksempel
}
////////////////////////////////////////////////////////////////////////////////////////////////////////////

//3.C -  tilføj erklæring af en varibel som gemmer summen af to heltal. Find selv på passende navn og datatype


int number1 = 10; // Det første heltal
int number2 = 10; // Det andet heltal
int sum; // Variabel til at gemme summen af de to heltal

void setup(){
  size(400, 400); // størrelsen på vinduet
  background(255); // 255 = hvid farve
  sum = number1 + number2; // Beregner summen af number1 og number2 og gemmer resultatet i sum
  println("Summen af de to heltal er: " + sum); // Udskriver summen til konsollen
}

void draw(){
  // Draw funktionen er tom, da vi kun fokuserer på at udskrive summen i setup()
}

////////////////////////////////////////////////////////////////////////////////////////////////////////////

//3.D - gør det samme med en variabel som gemmer resultatet af en division.

int dividend = 20; // Dividenden (det tal der skal divideres)
int divisor = 3; // Divisoren (det tal, der divideres med)
float divisionResult; // Variabel til at gemme resultatet af divisionen

void setup() {
  size(400, 400); // Størrelsen på vinduet
  background(255); // 255 = hvid farve
  divisionResult = float(dividend) / divisor; // Udfører divisionen og gemmer resultatet i divisionResult
  println("Resultatet af divisionen er: " + divisionResult); // Udskriver resultatet.
}

void draw() {
  // Draw funktionen er tom, da vi kun fokuserer på at udskrive resultatet af divisionen i setup()
}

///////////////////////////////////////////////////////////////////////////////////////////////////////////

3.E - Gør det samme med en variabel som gemmer en besked til brugeren.



