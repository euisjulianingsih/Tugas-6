#Boyband
##cpp
```
#include <iostream>
using namespace std;

// Deklarasi kelas
class Boyband {
public:
    // Public member data
    string nama;
    int members;
    string genre;

    // Public method untuk menampilkan informasi
    void informasi() {
        cout << "Nama: " << nama << endl;
        cout << "Members: " << members << endl;
        cout << "Genre: " << genre << endl;
        cout << "Debut year: " << getDebutYear() << endl;
    }

    // Public method untuk mengatur tahun debut
    void setDebutYear(string debutyear) {
        this->debutyear = debutyear;
    }

private:
    // Private member data
    string debutyear;

    // Private method untuk mendapatkan tahun debut
    string getDebutYear() {
        return debutyear;
    }
};

int main() {
    // Membuat objek dari kelas boyband
    Boyband P1;

    // Memberi nilai atribut objek
    P1.nama = "John";
    P1.members = 5;    P1.genre = "Pop";
    P1.setDebutYear("2020");

    // Memanggil metode untuk menampilkan informasi
    P1.informasi();

    return 0;
}

```
##RuningHasilCapture

<img width="232" alt="output boyband" src="https://github.com/euisjulianingsih/Tugas-6/assets/156889234/a3530d90-c618-4480-9458-94dc18d6b299">
