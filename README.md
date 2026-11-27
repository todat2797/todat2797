#include <iostream>
using namespace std;

int x = 10;  // Biến toàn cục

struct SinhVien
{
    int tuoi;
    void xuat();
};

void SinhVien::xuat()
{
    cout << "Tuoi: " << tuoi << endl;
}

int main()
{
    int x = 20;  // Có thể khai báo sau câu lệnh

    cout << "x cuc bo = " << x << endl;
    cout << "x toan cuc = " << ::x << endl;

    SinhVien sv;
    sv.tuoi = 18;
    sv.xuat();

    return 0;
}
