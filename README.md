# Dart_file
Dart Summery

☛ Programming Language
=======================

1-Sentence
2-Syntax   ① Data Type  --- ②Data Address Name  --- ③Data of a value


✎ int x = 1;
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Start
=========

void main() {
  print("Hello World !");
}

✽ Any code in Dart Must Run Main Function()  ☜

To Print value Write print();

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ variables
============

1- num ☞ للعد الصحيح والعدد الكسري 
2- int ☞ للعدد  الصحيح فقط
3- double ☞ للعدد العشري 
4- String ☞ للنصوص 
5-bool ☞ صح ام خطأ!
....... etc etc etc

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Update Value Of variables
============================                                 
void main() {                                                    
  int x = 10;
  int y = 20;
  int z = x + y;
  print(z);
}

✔️Print Value Of z = 30 

_____________________________________


void main() {
  int x = 10;
  int y = 20;
  x = 30;
  int z = x + y;
  print(z);
}
✔️Print Value Of z = 50        🔴Becaues He Update The Value Of Variable x form 10 to 30 



------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Initialize vs Declare
=========================

int x ;   ☞ Declare      بتعرف  القيمة اللي موجودة من حيث النوع واسم المتغير   

int y = 10;  ☞ Initialize     بتعرف القيمة اللي موجودة وتحط ليها قيمة ابتدائية   

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ double & bus game
======================

int + int = int 
double +double = double
int + double = double


void main() {
  int x;
  x = 5; //in first value of x = 5;

  x = x + 2; // add second step add 2 
  x = x - 2; // min 2 

  x = x + 1;  // add third step add 1
  x = x - 3;  // min 3
  print(x); // print value of x  = 3
}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Strng
========

✿       تكون للكلمات والنصنوص والحروف     

void main() {
  String fname = 'Waled';
  String lname = 'Saied';
  String char = 'M';
  print(fname + ' ' + lname); // first way
  print('$fname  $lname');  // second way
  print(char);
}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Boolean
============

void main() {
  int x = 6;
  int y = 3;

  bool num = x > y;
  print(num);
}

// output true 🔴Becaues check num of x is greater than y and print (true or false) after check

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ List
========

♣ List<> namelist = [];

void main() {
  List<int> x = [1, 2, 3, 4, 5];
  print(x[0]); // print first element in list 1
  
}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Map
======== 

Key - Value 

♣Map<datatype of key, datatype of value> dataName  = {
  ' ': ' ',
  ' ': ' ',
}

void main() {
  Map<String, String> data = {
    'name': 'waled',
    'phone': '123456879',
    'city': 'Alex',
  };

  print(data);  // print all data in map
  print(data['name']); // print data field in name 
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ var & dynamic
=================


 ✵ var بياخد نوع الداتا اللي بيتحط فيه القيمة بتاعىة المتغير   

✵  dynamic بياحد نوع اي  قيمة تتحط وممكن ستم التعدسل علس المتغير حتي لو كان نوع غير اللي اتحط في الاول 


void main() {
  var x;
  x = 5;
 // x ='data';
  print(x);                            بياخد قيمة int اللي اتحطت في الاول
}



void main() {
  dynamic x;
  x = 5;
  x = 'Mario';                   Any Data
  print(x);
}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ final & const
=================


⇞ final ♙ run time             اقدر احط فيها قيمة جاية من الداتا بيز Not Allowed To Declare variables
⇞ const ♙ compile time         لو الداتا بتاعتي ثوابت زي ال Pi = 3.14 او او

fianl name = 'maria';
const pi = 3.14;
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Arthimetic Operators
=======================
☃ + add
☃ - subtract
☃ * multiply
☃ / divide 
☃ % remainder
☃ ~/ divide return integer result 
☃ ++ increment
☃ -- decrement

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Relational Operators
=======================

✂ > Greater than
✂ < Less than
✂ >= Greater than or Equal
✂ <= Less than or Equal
✂ == Equal
✂ != Not Equal

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Type Test Operators
=======================

♢ is
♢ is!


void main() {
  int x = 5;
  double y = 7.9;

  bool s = x is int;
  print(s);          // return true check the value
}



void main() {
  int x = 5;
  double y = 7.9;

  bool s = y is int;
  print(s);          // return true check the value
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Bitwise Operators
=======================
☂ Control by Binary Code (transfer numbers)

☂ And &
☂ or |
☂ xop ^
☂ not ~
☂ left shift <<   يزود صفر من اليمين
☂ right shift >>  يزود صفر من الشمال 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Assignment Operators
=======================

↬ +=
↬ -=
↬ *=
↬ /=
↬ ??=
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Logical Operators
=====================
 
∎ And &&    ☣All true
∎ or ||     ☣ one true
∎ Not !     ☣oppisite


------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ IF Statement
===============
✘if
✘else
✘else IF


void main() {
  int x = 5;
  int y = 10;

  if (x > y) {
    print('$x is greater than $y');
  } else {
    print('$x is less than $y');
  }
}

🔴print last message Becaues x is less than y 



void main() {
  int x = 10;
  int y = 10;

  if (x > y) {
    print('$x is greater than $y');
  } else if (x == y) {
    print('$x is equal than $y');
  } else {
    print('$x is less than $y');
  }
}

🔴print message Equal Becaues x is equal than y 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ inline if
=============
void main() {
  int x = 2;
  int y = 4;
 if x  > y ? '$x is greater than $y' : '$y is greater than $x';
}


۵ ---? --:--
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ if null
==========


void main() {
  var a = null;
  var b = 12;

  var result = a ??= b;
  print(a);
  print(result);
}

print 
12
12 
🔴Becaues ??= equal var of a = b

void main() {
  var a = null;
  var b = 12;

  var result = a ?? b;
  print(a);
  print(result);
}

print
null
12
🔴Becaues ?? condition print value of a null and result 12
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Switch Case
===============

🔴 Logic

switch(variable_expression) { 
   case constant_expr1: { 
      // statements; 
   } 
   break; 
  
   case constant_expr2: { 
      //statements; 
   } 
   break; 
      
   default: { 
      //statements;  
   }
   break; 
} 
_________________________________________________________

void main() {
  var grade = "A";
  switch (grade) {
    case "A":
      {
        print("Excellent");
      }
      break;

    case "B":
      {
        print("Good");
      }
      break;

    case "C":
      {
        print("Fair");
      }
      break;

    case "D":
      {
        print("Poor");
      }
      break;

    default:
      {
        print("Invalid choice");
      }
      break;
  }
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Function (Method) ♚
=======================

♚ Parameters ⌨ inputs
♚ return Type ⌨ outputs ✃ Type    **    ✃ void


void main() {
  printNames();
}

void printNames() {
  print('My Name is');
  print('Waled Saied');
}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Parameters & return type ♚
==============================
void main() {
  print(addition(8, 4));
}

int addition(int x, int y) {
  int z = x + y;
  return z;
}

₰ Parameters in Function x, y are put in main Function With Calling Function
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Optional named parameters ♚
===============================

void main() {
  print(addition(8, 4, 1, 2, 3));
}

int addition({int a, int b, int first, int second, int tnird}) {
  return a * b;
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Loops ☣
===========

♝ for

void main() {
  for (int x = 1; x <= 10; x++) {
    print(x);
  }
}
₯ print x form 1 to 10

_________________________________________________________
void main() {
  List<String> names = [
    'ali',
    'ahmed',
    'mohamed',
    'mahmoud',
  ];

  for (int i = 0; i <= names.length; i++) {
    print(names[i]);
  }
}

₯ print List of names
_________________________________________________________

void main() {
  List<String> names = [
    'ali',
    'ahmed',
    'mohamed',
    'marwan',
  ];
  names.forEach((String element) {
    print(element);
  });
}

₯ print List of names by forEach
_________________________________________________________

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Object Oriented Programming
===============================

☛ Classes & Objects
===================== ♜ any class Contain Attributes(variables) and Methods
♛ class (Cars)
♛ object (brands)


void main() {
  Cars civic = new Cars();
  civic.carName();
}

class Cars {
  String? brand;
  String? model;
  String? color;

  void carName() {
    print('Honda');
  }
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Constructors
===============

≛ Setter (Set Data)
≛ Getter (Fetch & Get Data)

⍟ this refer to the class 

void main() {
  Cars crolla = new Cars();
  crolla.setBrand('Corolla');
  String brand1 = crolla.getBrand();
  print(brand1);

  Cars lada = new Cars();
  lada.setBrand('Lada');
  String brand2 = lada.getBrand();
  print(brand2);
}

class Cars {
  late String brand;
  late String model;
  late String color;

  void setBrand(String brand) {
    this.brand = brand;
  }

  String getBrand() {
    return brand;
  }
}

_________________________________________________________


void main() {
  Cars Lanous = Cars(
    brand: 'Lanous',
    model: 'Daiwoo lanous 2009',
    color: 'Blue',
  );

  print(Lanous.brand);
  print(Lanous.model);
  print(Lanous.color);
}

class Cars {
  String? brand;
  String? model;
  String? color;

  Cars({required String brand, required String model, required String color}) {
    this.brand = brand;
    this.model = model;
    this.color = color;
  }
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Special Constructors
=======================
void main() {
  Cars Lanous = Cars(
    brand: 'Mazeratie',
    model: 'Kllio 2021',
    color: 'red',
  );

  print(Lanous.brand);
  print(Lanous.model);
  print(Lanous.color);
}

class Cars {
  final String? brand;
  final String? model;
  final String? color;

  Cars({this.brand, this.model, this.color}) {}
}


🔴 كدا قدرت استدعي الميثود بتاعتي مرة واحدة بس فوووق ومقددرش اعدل عليها عكس الطريقة اللي فوق بتخليني اعدل علي الداتا بتاعتي 

☊ Fianl فيها ميزة اللي هي تخليني احط الداتا مرة واحدة بس وخلاص مبتتغيرش + لما بعرفها لازم تاخد قيمة متقبلش تعريف بسسس ي نجم 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Static
=========

⬤ ⬤ ⬤ ⬤   باختصار كداااا بتخليني اقدر اكسس علي الحاجة بتاعتي (Access)
من خلال اسم الكلاس بتاعتي من غير ما احتاج اعمل اوبجكت 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Inhertiance
==============

مثلا حاجة زي الشكل الشكل دا لية اية لية خواص زي اي طول عرض خواص تانية نيجي نعمل مثلا دايرة او مستطيل او مربع يقوم الشكل دا يورث الخواص اللي موجودة في الشكل الكبير

Shape ===> Parent   (SuperClass)
Circule ===> Child (SubClass)

class Human{
   void walk(){
      print("Humans walk!");
   }
}

// inherting the parent class i.e Human
class Person extends Human{
   void speak(){
      print("That person can speak");
   }
}

void main(){
   Person p = new Person();
   p.speak();
   p.walk(); // invoking the parent class method
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Override
===========
اخلي الميثود دايما تعمل حاجة فوق اللي بتعملها * * * *

☛ Abstract
===========

هو كلاس مبقدرش اخد منو اوبجكت 🔴 
لازم يتعملها Override🔴


abstract class Person {
//declaring abstract method

  void displayInfo(); //abstract method

}

class Boy extends Person {
// Overriding method
  void displayInfo() {
    print("My name is Waled");
  }
}

class Girl extends Person {
// Overriding method
  void displayInfo() {
    print("My name is Malek");
  }
}

void main() {
  Boy b = new Boy(); // Creating Object of Boy class
  Girl g = new Girl(); // Creating Object of Girl class

  b.displayInfo();
  g.displayInfo();
}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
