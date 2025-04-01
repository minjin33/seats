#include <iostream>
using namespace std;

int main()
{
    int seats1[5][4] = {0};
    cout << "1 2     3 4 (1호차)" << '\n';
    cout << "------------" << '\n';
    for (int i=0; i<5; i++) {
        
        for (int j=0; j<4; j++) {
            
            if (j==2) {
                
                cout << "    ";
                
            }
            
            cout << seats1[i][j] << " ";
            
        }
        
        cout << '\n';
    }
    cout << "------------" << '\n';
}
