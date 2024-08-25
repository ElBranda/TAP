#include <bits/stdc++.h>

using namespace std;

int main() {
    int n;
    vector<int> d,md;
    
    cin >> n;
    
    for (int i = n-1; i >= 2; i--) {
        bool f=false;
        
        if (n%i==0) {
            for (int j = 0; j < d.size(); j++) {
                if (d[j]%i==0) {
                    f=true;
                    break;
                }
            }
            
            if (!f) d.push_back(i);
        }
    }
    
    if (d.size()==0) {
        std::cout << "1\n1 1\n";
    } else {
        std::cout << d.size() << "\n";
        for (int i = 0; i < d.size(); i++) {
            std::cout << 1 << " " << d[i] << "\n";
        }
    }
    
    return 0;
}
