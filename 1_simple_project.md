# It Program will to do numbers *SUM*, *Difference*, *product*

Basically it program take input numbers like first input 4 and second input 5 then it program automatically will to do  *sum*, *difference* *product*

first will do **sum**
first will do **difference**
first will do **product**

it's simple program 

```python
def main():

  user_input1 = int(input())
  user_input2 = int(input())
  total = user_input1 + user_input2
  print(f"Tow number sum is complete= {total}")


  
  user_input1 = int(input())
  user_input2 = int(input())
  total = user_input1 - user_input2
  print(f"The difference of the two numbers is complete= {total}")

  user_input1 = int(input())
  user_input2 = int(input())
  total = user_input1 * user_input2
  print(f"The product of the two numbers is complete. {total}")

main()
```