# java-interview-questions
Java Interview Questions
(Sunflower)
1. What is Hibernate and its advantages.
2. How to implement OneToMany using JPA.
3. What are various Fetch Types.
4. How to create list of 1 to 100 integers.
5. Collect even number from 1 to 100 in set using stream api.
6. Explain different implementation of spring data jpa
7. How do you optmized database using spring data jpa
8. What is spring security
9. How to limit api request to 100/day for particular API.g
10. How to add functionaly to show pages on role basis.
11. (Airtel R1)
12. Design Patterns 
13. Factory design pattern https://medium.com/nerd-for-tech/understanding-factory-method-design-pattern-4d7ba8f0dfc4
14. Singleton Design Pattern 
14.JWT token
15.Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.
16.Reverse Integer input= 123 output= 321
17. Difference Between REST and SOAP APIs
    (Airtel R2)
19. Publisher -> can publish single or multiple topic, Subscriber can subscribe and read multiple topic, if all subscriber read all topic topic will be deleted (Can be solved using observer design pattern).
20. thread locking and  than how to prevent it.
(Google)
21. parse csv using java.
22. what is marker interface.
23. explain micro service architecture, explain how request comes to micro service.

24. what is indexing
25.comparator comparable 
26. how to define beans in spring boot
27. HashCode of 2 differnt autowired same bean in springboot
if beans are get at two deferent loactions what will be there hashcode
28 removing from enhanced for loop, difference in list iterartor and iterator 
29 hashcode of set  if 2 same objects are added in set what will be its size 
30 curdrepository and jparesposity defeince in them 
31 diff in @enity and @table 
32 how to define thread using runnable lambda expression
33 Convert list in to map asked in 2 interviewsa
 34 try {
}catch(Exception e)
{
}catch(Arthiemetic e)
{
}
which one will execute

35 Relation of TCP, UDP and http 
36 why executor 
37 whY websockets are needed 
38 difference between abstract design pattern and factory design pattern.
39 Java 8 features
40 list set differencence 
41 string immutable
42 String s1=new ("Helo"),String s2=new ("Helo") what will be in scp and heap 
43 synchronized 
44 factorial program 
45 valid paranthesis
46  return query pararms as map :- url = http://xyz.com?a=3&b=4&c=4


public Map<String,String> ConvertQueryParam(String str)
{

int index=str.indexOf("?");
str=str.substring(index,str.length());
   String[] queryParams= str.trim().split("&");

Map<String,String> map=new HashMap<>();

for(int i=0;i<queryParams.length();i++)
{
String[] keyValuePair=queryParams.split("=");
   map.put(keyValuePair[0],keyValuePair[1]);
}

return map;

47 
Patients
patientId, diet_id , allergry_id  
SELECT * FROM Patients RIGHT JOIN  PatientInfo  on Patients.patientId=PatientInfo.Id  where patientId IS NULL;


PatientInfo
Id , Name, Address ,


Patient info which are not there in Patients. using sq


48 Why sockets are used 
49 how sockets are used to create tcp connection



Clear Trail Technology
1. What is the difference between monolithic and microservice architecture and how does it affect the product?
2. What is the difference between TCP and UDP?
3. In map, for example, we have key values and we need to find what are the, like, in the values there are repeating characters. First question, we need to remove the key which has repeating characters. Second question, we need to find the value which has the most repeating character and its count.
4. We have one table, employee table. In the employee table, we have employee name and department and ID. For example, and the values are one row is Lavina department. And we have also a role as well. So Lavina with role as software developer with ID 1 and our second value is Sagar with ID 2 and a role as a DevOps engineer. We need an output as Lavina with software engineer, Lavina with DevOps, Sagar with software engineer and Sagar with DevOps. How can we print a value like this using SQL?
5. What is Concurrent Modification Exception and how to solve in map?
6. We are creating 12 threads with on a core CPU of 4. Will this work? If yes, how it will work? And who handles threads, JVM or CPU?
7. If you were given a chance to learn a new technology, how would you like do it? Like what do you follow directly jumping into the uh what we say, documents or what will you do? And second question is, if you are given low time for learning new thing and doing it, how will you do it? And you are given to learn new thing with a signed junior, how will you do it?
   
    
