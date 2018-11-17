# Abstract Factory Design Pattern Benefits

(What is)
- This factory class returns different subclasses based on the input provided and factory class uses if-else or switch statement to achieve this. 
- In the Abstract Factory Pattern, we get rid of if-else block and have a factory class for each-sub class. Then an Abstract Factory class that will return the sub-classes based on the input factory class.
- It seems confusing but once you see the implementation, it's really easy to grasp and understand the minor difference between Factory and Abstract Factory Pattern.

(Benefits)
- Abstract Factory design pattern provides approach to code for interface rather than implementation.
- Abstract Factory pattern is "factory of factories" and can be easily extended to accomodate more products, for example we can add another sub-class Laptop and a factory LaptopFactory
- Abstract Factory pattern is robust and avoid conditional logic of Factory pattern

(Example in JDK)
- javax.xml.parsers.DocumentBuilderFactory#newInstance()
- javax.xml.transform.TransformerFactory#newInstance()
- javax.xml.xpath.XPathFactory#newInstance()
