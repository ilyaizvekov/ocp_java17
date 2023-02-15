# Контрольные вопросы

Ответы на контрольные вопросы главы можно найти в Приложении.

1. Какие из следующих методов являются допустимыми для точки входа, которые можно запустить из командной строки?
   (Выберите все, что подходит.)

```
A. private static void main(String[] args)
B. public static final main(String[] args)
C. public void main(String[] args)
D. public static final void main(String[] args)
E. public static void main(String[] args)
F. public static main(String[] args)
```
   
2. Какие варианты ответов представляют собой порядок, в котором следующие операторы могут быть собраны в программу, 
которая будет успешно скомпилирована? (Выберите все, что подходит.)
```
 X: class Rabbit {}
 Y: import java.util.*;
 Z: package animals;
```

```
A. X, Y, Z
B. Y, Z, X
C. Z, Y, X
D. Y, X
E. Z, X
F. X, Z
G. None of the above
```

3. Какие из следующих утверждений верны? (Выберите все, что подходит.)

```
public class Bunny {
   public static void main(String[] x) {
      Bunny bun = new Bunny();
} }
```

```
A. Bunny is a class.
B. bun is a class.
C. main is a class.
D. Bunny is a reference to an object.
E. bun is a reference to an object.
F. main is a reference to an object.
G. The main() method doesn’t run because the parameter name is incorrect.
```

4. Какие из следующих являются допустимыми идентификаторами Java? (Выберите все, что подходит.)

```
A. _
B. _helloWorld$
C. true
D. java.lang
E. Public
F. 1980_s
G. _Q2_
```

5. (Выберите все, что подходит.)

```
2: public class Bear {
3:    private Bear pandaBear;
4:    private void roar(Bear b) {
5:       System.out.println("Roar!");
6:       pandaBear = b;
7:    }
8:    public static void main(String[] args) {
9:       Bear brownBear = new Bear();
10:      Bear polarBear = new Bear();
11:      brownBear.roar(polarBear);
12:      polarBear = null;
13:      brownBear = null;
14:      System.gc(); } }
```

```
A. The object created on line 9 is eligible for garbage collection after line 13.
B. The object created on line 9 is eligible for garbage collection after line 14.
C. The object created on line 10 is eligible for garbage collection after line 12.
D. The object created on line 10 is eligible for garbage collection after line 13.
E. Garbage collection is guaranteed to run.
F. Garbage collection might or might not run.
G. The code does not compile.
```

6. Предполагая, что следующий класс компилируется, сколько переменных, определенных в классе или методе, находятся в 
области действия в строке, отмеченной в строке 14?

```
1: public class Camel {
2: { int hairs = 3_000_0; }
3: long water, air=2;
4: boolean twoHumps = true;
5: public void spit(float distance) {
6: var path = "";
7: { double teeth = 32 + distance++; }
8: while(water > 0) {
9: int age = twoHumps ? 1 : 2;
10: short i=-1;
11: for(i=0; i<10; i++) {
12: var Private = 2;
13: }
14: // SCOPE
15: }
16: }
17: }
```

```
A. 2
B. 3
C. 4
D. 5
E. 6
F. 7
G. None of the above
```



 