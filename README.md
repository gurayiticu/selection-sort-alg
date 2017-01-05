+# selection-sort-algoritmas
 +public static void selec_sort(int[] dizi, int n){
 +int temp;
 +int enKucuk;
 +for(int i=0;i<n-1;i++){
 +enKucuk=i;
 +for(int j=i; j<n;j++){
 +if(dizi[j]<dizi[enKucuk]){
 +enKucuk=j;
 +}
 +}
 +temp=dizi[i];
 +dizi[i]=dizi[enKucuk];
 +dizi[enKucuk]=temp;
 +}
 +}
 +}
 +}
