# Jan 23 Class Notes

Open Circuit vs Short Circuit

Insert Image

Some Stores:

- Forraker - have to know what you want
- HobbbytownUSA - motors
- HarborFreight - tools, smalle electronics, wire strippers 18-24 gauge

(Our wires, 22 gauge)

## Deadlines for the Midterm

- Wednesday 1/25 > sketches for Midterm
- Wed. March 8 > presentation
- Project updates and documentation in blog
- How I got from point A to point B and everythign in between including failures.
- See the logic behind choices.
- START EARLY. Do NOT be afraid to restart.

*Useful website: Draw.io*
(but probably easier to just draw circuit by hand)

## Storing Data

bit: 1 or 0

8 bits = 1 byte

Range of a byte (0-255), so 256 possible choices including zero.
Binary can be all zeros or all ones.

binary base 2
decimal base 10
(Insert Image/ Table for Binary vs Decimal)

### Data Types

bool - true or false
byte - unsigned (0 - 255)
char - signed byte (-127 - 127)
word - (0 - ~64k)
int - signed word (~ -32k - ~32k)
unsigned long - (0 - 4 mil)
float - (decimal place)
*unsigned means: no +/-*

rolling over: ex) byte > more than 255

4 bits - nibble
8 bits - byte
16 bits - word
32 bits - long
32 bits - float (decimal place)
64 bits - double long
*avoid floating point math if we can, hardware doesn't do division*

data type        name         value
ex) byte      sensorValue      =0;

## Variables

void setup() {
}

Some functions need parameters.
Parenthesis signal a function.
No parenthesis signal a variable.
Can't write code without variables.
Have to define functions and variables BEFORE using them.

rnd = random()
gives us a random, # and stores it in rnd
void: function isn't returning anything.
map: scales one range to another.

### Conditional

(insert image of conditional function)

## Blink Without Delay

unsigned long timestamp = 0;
two equal signs > compare

int LEDState = LOW;
const long interval = 1000

void setup() {
} pinMode(LEDBUILTIN, OUTPUT);

unsignedlongcurrentimestamp= millis();

if currenttimstamp - previoustimestamp > = () {
}

if (LEDState == LOW) {

} (LEDState = HIGH);
} else {LEDState = LOW;

} previoustimestamp = currenttimestamp

digitalwrite (LEDBUILTIN, LEDState)
