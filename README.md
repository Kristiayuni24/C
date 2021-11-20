#include <iostream>
using namespace std;

int main() 
  {
	   
	   float angka, total = 0, rata;
	   int jumlahbilangan ;
	   
	   cout <<"------->>>> Sebuah Program untuk Menentukan Hasil Rata-rata <<<<--------" <<endl;
	   cout << endl;
	   cout <<"masukkan jumlah bilangan: "; cin>> jumlahbilangan;
	   cout << endl;
	   
	   for(int n=1; n<=jumlahbilangan; n++) 
     {
	   	cout <<"masukkan angka\t\t: "; cin>> angka;
	   	total = total + angka;
	   	
	   }
	    cout << endl;
	    cout << "total penjumlahan\t: " <<total <<endl;
	    rata = total / jumlahbilangan;
	    cout << "rata-rata\t\t: " <<rata;
	    cout << endl;
	    cout << "-------------->>>> Program Telah Selesai <<<<---------------" <<endl;
	   
	   return 0;
}
