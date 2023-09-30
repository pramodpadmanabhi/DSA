*** Count Factors of given number
* Code
  ** int countFactors(int N){
      int countFactors = 0;
      for(int i =1;i<=sqrt(N);i++){
        if(N%==0){
          if(i == N/i){
              countFactors++;
          }else{
              countFactors+=2;
          }
        }
      }
  return countFactors;
  }
