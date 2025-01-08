# RISC-V Talent development program

the project is based on the RISC V talent development program.

<details>
  <summary> task 0- installation</summary>
</details>
<details>
  <summary>
    task 1 -Development of c program
  </summary>

  ### step 1: fire up the terminal 
  ```bash 
  vsduser@vsduser-VirtualBox:~$
  ```

  ### step 2: direction to home bash
  ```bash
  cd
  ```

  ### step 3: open leafpad bash
  ```bash
  leafpad sum1ton.c &
  ```

  ### step 4: write the code
  ```c
  #include<stdio.h>
  int main(){
    int sum = 0, n = 80, i;
    for(i=0; i<=n; i++){
        sum+=i;
        printf("The sum from 1 to 80: %d \n", sum);
    }
    return 0;
}
  ```

  ### step 5: compile and run the code
  ```bash
  gcc sum1ton.c
  ./a.out
  ```


  
</details>
