
 public class StringManipulation {
public static void main(String[] args) {
// 1. String literal
String str1 = "Java Programming";
// 2. new String() constructor
String str2 = new String("Java Programming");
// 3. Character array
char[] charArray = {'J', 'a', 'v', 'a', ' ', 'P', 'r', 'o', 'g', 'r', 'a', 'm', 'm', 'i', 'n', 'g'};
String str3 = new String(charArray);
// Compare using == (checks reference) and .equals() (checks content)
System.out.println("str1 == str2 : " + (str1 == str2)); // false - different objects
System.out.println("str1.equals(str2) : " + str1.equals(str2)); // true - same content
System.out.println("str1 == str3 : " + (str1 == str3)); // false
System.out.println("str1.equals(str3) : " + str1.equals(str3)); // true
// Escape sequences
String quote = "Programming Quote:\n\"Code is poetry\" - Unknown\nPath:
C:\\Java\\Projects";
System.out.println("\n" + quote);
}
}

