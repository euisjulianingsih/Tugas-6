# Robot
##cpp
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class Robot {
public:
    // Public member data
    string nama;
    int umur;

    // Metode untuk menampilkan informasi
    void perkenalandiri() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "MBTI: " << mbti << endl;
    }

    // Public method untuk mengatur MBTI
    void setMBTI(string mbti) {
        this->mbti = mbti;
    }

private:
    // Private member data
    string mbti;
};

int main() {
    // Membuat objek dari kelas robot
    Robot r1;
    Robot r2;

    // Memberi nilai atribut objek (menggunakan metode setMBTI untuk mengatur MBTI)
    r1.nama = "John";
    r1.umur = 30;
    r1.setMBTI("ISTJ");

    r2.nama = "jaehyun";
    r2.umur = 30;
    r2.setMBTI("ISTJ");

    // Memanggil metode untuk menampilkan informasi
    r1.perkenalandiri();
    r2.perkenalandiri();

    return 0;
}
```

##RuningHasilCapture
<img width="325" alt="output robot" src="https://github.com/euisjulianingsih/Tugas-6/assets/156889234/f7493553-8980-4585-a036-1737697cf3ff">


