# Algorithm :: recursive Algorithm
 
- 순환( recursive )
    자기자신을 호출하는 것    
    
      3! = 3*2*1  
      n! = n(n-1)

      int fact(int n)
      {
          if(n<=1) // 탈출조건;  
          return n*fact(n-1) //  지속;    
      }

- recursion 의 장단점 

      장점 :  코드가 짧다.  
              이해가 쉽다.
      단점 :  메모리를 많이 차지함.
              시간이 많이 걸린다.
            
