# 1.-konversi-dolar-ke-rupiah
#include <stdio.h> 
#define kurs 15171.00 
//konstanta tetap  
int main (){     
float dollar=0;     
printf("****PROGRAM KONVERSI DOLLAR KE RUPIAH****\n");     
printf("Jumlah Dollar : $");     scanf("%f",&amp;dollar);     printf("=========================================\n");      
float rupiah= dollar*kurs;     printf("Hasil Konversi Ke Rupiah : Rp %.2f",rupiah);     
return 0; }
