#include <iostream>
using namespace std;

int main (){
    int jumlahSiswa, nilai;
    
    cout << "Masukkan jumlah siswa:";
    cin >> jumlahSiswa;
    
    for(int i = 1; i <= jumlahSiswa; i++){
        cout << "\nMasukkan nilai siswa ke-"<<i<<":";
        cin >> nilai;
        //percabangan 
        if (nilai>=75){
            cout << "Hasil: Lulus" << endl;
        } else {
            cout << "Hasil Tidak Lulus " << endl; 
        }
        }
    cout << "\nProgram selesai."<<endl;
    return 0;
}
