#include <iostream>
using namespace std;
int main()
{
    // 1. Chú thích
    int a, b;

    // 2. Nhập / Xuất
    cout << "Nhap a va b: ";
    cin >> a >> b;

    // 3. Chuyen doi kieu du lieu
    double kq = static_cast<double>(a) / b;

    cout << "Ket qua = " << kq;

    return 0;
}
