# ALGO8.TUGAS4

## CODING PROGRAM LENGKAP

    #include<stdio.h>
    #include<conio.h>


    void fungsi_by_value(int a){
    a = a * 3;
    printf("A by value adalah = %d alamatnya adalah %p\n",a,&a);

    }
    int main (){
     int a=5;
    printf("A main adalah = %d alamatnya adalah %p\n",a);

    fungsi_by_value(5*a+1);
    getch();
    }



## HASIL PROGRAM
![img](https://github.com/dindapuspitadewi/ALGO8.TUGAS4/blob/master/4.jpg?raw=true)

