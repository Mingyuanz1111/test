# THIS IS NEW README FILE
HAHAHAHAHA

code test:
```c++
#include <bits/stdc++.h>
#define pii pair<int,int>
#define f first
#define s second
#define INF (int)1e9
typedef long long ll;
using namespace std;
int main(){
    int n;
    pii tar;
    cin >> tar.f >> tar.s >> n;
    pii a[n];
    for(int i=0; i<n; i++) cin >> a[i].f >> a[i].s;
    sort(a,a+n);
    for(int l=0; l<n; l++){
        int r=upper_bound(a+l,a+n,{x-3*a[l].f,INF})-a-1;
        if(r-l<3) break;
        for(int i=r; i>l && (ll)3*a[i]>=x-a[l].f; i--){
            int p=l+1,q=i-1;
            while(p<q){
                if(a[p]].f+a[q]].f>x-a[l]].f-a[i]].f) q--;
                else if(a[p]].f+a[q]].f<x-a[l]].f-a[i]].f) p++;
                else{
                    if(){
                        cout << inp[l].s << " " << inp[p].s << " " << inp[q].s << " " << inp[i].s;
                        return 0;
                    }

                }
            }
        }
    }
    cout << "IMPOSSIBLE";
    return 0;
}
```
