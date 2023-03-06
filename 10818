#include <iostream>

int main() {
    int cnt;
    int* p;

    std::cin >> cnt;

    p = new int[cnt];

    for (int i = 0; i < cnt; i++) {
        std::cin >> p[i];
    }


    int min = p[0];
    int max = p[0];

    for (int i = 0; i < cnt; i++) {
        if (min > p[i]) min = p[i];
        if (max < p[i]) max = p[i];
    }
    std::cout << min << ' ' << max;

    return 0;
}
