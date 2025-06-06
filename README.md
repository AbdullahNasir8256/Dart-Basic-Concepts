# Dart-Basic-Concepts

void main() {
//  Q.1: Create two integer variables length and breadth and assign values then check if they are square values or rectangle values.
// ie: if both values are equal then it's square otherwise rectangle ?

int length = 9;
int breadth = 9;

if (length == breadth) {
(print('its square value'));
} else {
(print('its rectangular value'));
}

// Q.2: Take two variables and store age then using if/else condition to determine oldest and youngest among them ?

int personeOne = 46;
int personeTwo = 78;

if (personeOne > personeTwo) {
return print("personeOne is older than personetwo");
} else {
return print('personeOne is younger than personeTwo');
}

// Q.3: A student will not be allowed to sit in exam if his/her attendance is less than 75%. Create integer variables ?

int numberOfClasses = 16;
int numberOfClassesHeld = 10;
num percentage = (numberOfClassesHeld / numberOfClasses) * 100;

if (percentage == 75) {
print('you are eligible for exam');
} else {
print(
'you are not eligible for exam -------your percentage is $percentage%');
}

//   Q.4: Create integer variable assign any year to it and check if a year is leap year or not ?

int year = 2004;
if (year % 4 == 0) {
print('its a leap year');
} else {
print('its not a leap year');
}

// Q.5  Write a program to read temperature in centigrade and display a suitable message according to temperature:

num temp = 35;

if (temp == 0) {
print('cold weather');
} else if (temp <= 0 || temp >= 20) {
print('normal weather');
} else if (temp <= 20 || temp >= 40) {
print('hot weather');
}

// Q.6: Write a program to check whether an alphabet is a vowel or consonant.

String isVovel = "a";

if (isVovel=="a" ||
isVovel=="e" ||
isVovel== "i" ||
isVovel=="o" ||
isVovel=="u"
) {print('word is a vovel : $isVovel');
} else {print('a word is a consonant' );
}

// Q7: Create a marksheet using operators of at least 5 subjects and output should have Student Name,
//     Student Roll Number, Class, Percentage, Grade Obtained etc ?

int math = 70;
int physics = 65;
int chemistry = 90;
int english = 85;
int urdu = 75;
int totalMarks = 500;

String name = "name : zain ali";
String Class = "class : pre engineering part2";
String rollnum = "rollumber : 808";

int percentage = math + physics + chemistry + english + urdu;

print(percentage * 100 / totalMarks);

print(name);
print(Class);
print(rollnum);

if (percentage >= 90) {
print('A+ grade');
} else if (percentage >= 80) {
print('A grade');
} else if (percentage >= 70) {
print('B grade');
} else if (percentage >= 60) {
print('C grade');
} else {
print('F grade');
}
