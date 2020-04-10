## Question List ##

1.] Output of below code .

```java

public class Main {
    public static void main(String []arg){
        System.out.println(print(1));
    }
    
    static Exception print(int i){
        if (i>0){
            return new Exception();
        }
        else{
            throw new RuntimeException();
        }
    }
}

```

  1. ***"java.lang.Exception"***
  2. It will show a stack trace with a runtime exception.
  3. It will not compile.
  4. It will run and throw an exception.
	
2.] Which code would you use to tell of "schwiffy" is of type String?

  1. "schwiffy".getType().equals("String")
  2. **"schwiffy".getClass().getSimpleName() == "String"**
  3. "schwiffy" instanceof String
  4. "schwiffy".getType() == String
	
3.] Given the string "strawberries" saved in a variable cal fruit, what would fruit.substring(2,5) return?

  1. awb
  2. **raw**
  3. rawb
  4. traw
	
4.] What will this program print out to the console when executed?

```java
public class Main {
    public static void main(String []arg){
        LinkedList<Integer> list = new LinkedList();
        list.add(5);
        list.add(1);
        list.add(10);
        System.out.println(list);               
    }  
}
```

  1. [10, 5, 1]
  2. [10, 1, 5]
  3. **[5, 1, 10]**
  4. [1, 5, 10]
	
5.] How do yu write a foreach loop that will iterate over ArrayList<Pencil> pencilCase?

  1. for (int i=0; i<pencilCase.size(); i++){}
  2. for (pencilCase.next()) {}
  3. Iterator iterator = pencilCase.iterator()
	 for (iterator.next())
  4. **for (Pencil pencil: pencilCase) {}**
	
6.] What is the output of this code?	

```java
public class Main {
    public static void main(String []arg){
        String message = "Hello world!";
        String newMessage = message.substring(6, 12)+message.substring(12, 6);
        System.out.println(newMessage);                
    }   
}
```
  1. The code does not compile.
  2. "world!!world"
  3. "world!world!"
  4. **A runtime exception is thrown**
	
7.] Give this code, which command will output "2"?

```java
public class Main {
    public static void main(String []arg){
        System.out.println(arg[2]);                
    }   
}
```

  1. java Main 1 "2" "3 4" 5
  2. **java Main 1 "2" "2" 5**
  3. java Mian.class 1 "2" 2 5
  4. java main 1 2 "3 4" 5
	
8.] What does this code print?

```java
System.out.println("apple".compareTo("banana"));
```

  1. 0
  2. **a negative number**
  3. a positive number
  4. false
	
9.] What can you use to create new instances in Java?

  1. another instance
  2. private method
  3. **constructor**
  4. field
	
10.] What is the output of this code?

```java
public class Main {
    public static void main(String []arg){
        int a =123451234512345;
        System.out.println(a);                
    }   
}
```

  1. '123451234512345'
  2. '12345100000'
  3. **Nothing--this will not compile.**
  4. a negative integer number
	
11.] The runtime system start your program by calling which function first?

  1. print
  2. iterative
  3. hello
  4. **main**
	
12.] How can you achieve runtime polymorphism in Java?

  1. **method overriding**
  2. method overloading
  3. method calling
  4. method overrunning
	
13.] Which for loop is invalid?

  1. for(int x=1; x<-10; x++){}
  2. for(i=3; i<=3; i++){}
  3. for(;;){}
  4. **for(int i; i==2; i++){}**
	
14.] What letters will print when this code is run ?

```java
public class Main {
    public static void main(String []arg){
        try{
            System.out.println("A");
            bedMethod();
            System.out.println("B");
        }
        catch(Exception ex){
            System.out.println("C");
        }finally{
            System.out.println("D");
        }                
    }  
    public static void bedMethod() {
        throw new Error(); //To change body of generated methods, choose Tools | Templates.
    }
}
```
 
  1. A,C and D
  2. C and D
  3. **A and D**
  4. A, B, and D
  
15.] Which is the most up-to-date way to instantiate the current date?

  1. **LocalDate.now()**
  2. Calender.getInstance().getTime()
  3. new SimpleDateFormat("yyyy-MM-dd").format(new Date())
  4. new Date(System.currentTimeMillis())
