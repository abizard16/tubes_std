#include "relasi.h"

int main()
{
    ListAtlet LA;
    ListPertandingan LP;
    ListRelasi LR;

    createListAtlet(LA);
    createListPertandingan(LP);
    createListRelasi(LR);
    int opsi;
    cout << "SELAMAT DATANG DI APLIKASI PERTANDINGAN" << endl;
    cout << "1. Input Data Atlet" << endl;
    cout << "2. Input Data Pertandingan" << endl;
    cout << "3. Show Data Atlet" << endl;
    cout << "4. Show Data Pertandingan" << endl;
    cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
    cout << "6. Show Relasi" << endl;
    cout << "7. Delete Data Belakang Atlet" << endl;
    cout << "8. Delete Data Belakang Pertandingan" << endl;
    cout << "9. Exit" << endl;
    cout << "Masukan Opsi : ";
    cin >> opsi;

    while(opsi != 9){
        if(opsi == 1){
            int jumlah;
            infoTypeAtlet data;
            cout << "Masukan Jumlah Pemain : ";
            cin >> jumlah;
            for(int i = 0; i < jumlah;i++){
                cout << "Masukan Nama Pemain : ";
                cin >> data.nama;
                cout << "Masukan Usia Pemain : ";
                cin >> data.usia;
                cout << "Masukan Negara Pemain : ";
                cin >> data.negara;
                cout << "Masukan Posisi Pemain : ";
                cin >> data.posisi;
                cout << "Masukan Tinggi Pemain : ";
                cin >> data.tinggi;
                insertFirstAtlet(LA,newElmAtlet(data));
                cout << endl;
            }
            cout << "Data Berhasil dimasukan";
            cout << endl;
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi ==2){
            infoTypePertandingan dataPertandingan;
            int jumlah;
            cout << "Masukan Jumlah Pertandingan : ";
            cin >> jumlah;
            for(int i = 0;i < jumlah;i++){
                cout << "Masukan Nama Pertandingan : ";
                cin >> dataPertandingan.nama;
                cout << "Masukan Juara Pertandingan : ";
                cin >> dataPertandingan.juara;
                cout << "Masukan Jumlah Shoot Pertandingan : ";
                cin >> dataPertandingan.shoot;
                cout << "Masukan Goal Pertandingan : ";
                cin >> dataPertandingan.gol;
                insertFirstPertandingan(LP,newElmPertandingan(dataPertandingan));
                cout << endl;
            }
            cout << "Data Berhasil dimasukan";
            cout << endl;
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi == 3){
            cout << "Data Atlet diantaranya adalah :" << endl;
            showDataAtlet(LA);
            cout << endl;
            cout << "Data Berhasil dimasukan";
            cout << endl;
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi == 4){
            cout << "Data Pertandingan diantaranya adalah :" << endl;
            showDataPertandingan(LP);
            cout << endl;
            cout << "Data Berhasil dimasukan";
            cout << endl;
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi == 5){
            string namaPemain,namaPertandingan;
            cout << "Masukan Nama Pemain : ";
            cin >> namaPemain;
            cout << "Hubungan Dengan Pertandingan : ";
            cin >> namaPertandingan;
            KoneksiTandingPemain(LR,LP,LA,namaPertandingan,namaPemain);
            cout << endl;
            cout << "Data Berhasil dihubungkan";
            cout << endl;
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi == 6){
            cout << "Data Pertandingan dengan Pemainnya diantaranya adalah :" << endl;
            showRelasi(LR);
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else if(opsi ==7){
            string konfirmasi;
            adrAtlet p;
            cout << "Konfirmasi Delete Last Atlet (y/n) : ";
            cin >> konfirmasi;
            if(konfirmasi == "y"){
                deleteLastAtlet(LA,p);
                cout << "Data Berhasil Dihapus" << endl;
                showDataAtlet(LA);
            }else{
                cout << "Data Batal Dihapus" << endl;
            }
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }else{
            string konfirmasi;
            adrPertandingan p;
            cout << "Konfirmasi Delete Last Pertandingan (y/n) : ";
            cin >> konfirmasi;
            if(konfirmasi == "y"){
                deleteLastPertandingan(LP,p);
                cout << "Data Berhasil Dihapus" << endl;
                showDataPertandingan(LP);
            }else{
                cout << "Data Batal Dihapus" << endl;
            }
            cout << "1. Input Data Atlet" << endl;
            cout << "2. Input Data Pertandingan" << endl;
            cout << "3. Show Data Atlet" << endl;
            cout << "4. Show Data Pertandingan" << endl;
            cout << "5. Relasikan Pertandingan dengan Atlet" << endl;
            cout << "6. Show Relasi" << endl;
            cout << "7. Delete Data Belakang Atlet" << endl;
            cout << "8. Delete Data Belakang Pertandingan" << endl;
            cout << "9. Exit" << endl;
            cout << "Masukan Opsi : ";
            cin >> opsi;
        }

    }

    return 0;
}
