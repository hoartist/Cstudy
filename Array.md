## Array(배열)

- C++ 에서 사이즈 구하기
<br>
int arr[]={1,2,3,4,5,6,7};
<br>
int n=sizeof(arr)/sizeof(arr[0]);//7
<br>
<br>
- basic rotation algorithm
<br>
void leftRotatebyOne(int arr[],int n){
<br>
int temp=arr[0],i;
<br>
for(i=0;i<n-1;i++){
<br>
arr[i]=arr[i+1];
<br>
}
<br>
arr[i]=temp;
<br>
}
