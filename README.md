# SQL

1>stp_wq:
![image](https://user-images.githubusercontent.com/77121389/158655066-cedabb36-1ff3-414c-be29-7c6e6c5919b6.png)


2>Regex implementation:AUS_ID

1>	Bill_list.description will always contain the AUS treaty id in it (got it Confirmed from Dannielle) .
2>	The Treaty Id always  follows a particular pattern (based on Karu’s input)

I am using Regular expression to match the pattern  ,which is:
  REGEXP_SUBSTR(b.descrip,'\w{2}-\w+\-\w\-\w+\-\w\-\d{2}(\-\d{2})?')as Aus_Treaty_ID.
  
  
  3>Td'ed policy-used automatic ppulation using tricks in excel and coded the following  excel logic in SQL using Lead and Lag function in SQL
  
  ![image](https://user-images.githubusercontent.com/77121389/158657676-0f8179a5-6406-4335-b5cf-706ed512aa01.png)

