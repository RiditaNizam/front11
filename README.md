public int[] front11(int[] a, int[] b) {
  int[] answerArray = new int[0];
  int[] answerArray1 = new int[1];
  int[] answerArray2 = new int[2];
  
  
  if(a.length == 0 && b.length == 0){
  	return answerArray;
  }
  
  else if(a.length == 0){
  	answerArray1[0] = b[0];
    return answerArray1;
  }
  
  else if(b.length == 0){
  	answerArray1[0] = a[0];
    return answerArray1;
  }
  
  else{
  	answerArray2[0] = a[0];
    answerArray2[1] = b[0];
    return answerArray2;
  }
}
