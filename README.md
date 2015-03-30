# Caitlyn

#include <iostream>

using namespace std;

int main()
{
    if (fopen("auction.in", "r")) {
        freopen("auction.in", "r", stdin);
        freopen("auction.out", "w", stdout);
    }

    int n;
    int m;
    cin>>n;
    cin>>m;
    int pay[m];

    for(int i=0; i<m; i++){
        cin >> pay[i];
    }

    for(int i=0; i<m; i++){
        pay[i]*i
    }
}
