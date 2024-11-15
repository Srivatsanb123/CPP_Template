```cpp
#include <bits/stdc++.h>
using namespace std;

#define ll long long
#define pii pair<int, int>
#define pll pair<long long, long long>
#define vvi vector<vector<int>>
#define vvc vector<vector<char>>
#define vvs vector<vector<string>>
#define vvll vector<vector<long long>>
#define umi unordered_map<int, int>
#define umc unordered_map<char, int>
#define pb push_back
#define eb emplace_back
#define all(x) (x).begin(), (x).end()
#define rall(x) (x).rbegin(), (x).rend()
#define MOD 1000000007
#define INF 1e18
#define PI 3.1415926535897932384626433832795

// I/O macros
#define print(x) cout << (x) <<" "
#define input(x) cin >> (x)
#define yes() cout << "YES\n"
#define no() cout << "NO\n"

// Fast I/O
#define FAST_IO ios_base::sync_with_stdio(false); cin.tie(NULL);

// Utility function templates
template <class T>
void printmp(const vector<T> &v) { for (auto x : v) cout << x.f<<" "<<x.s << '\n'; }
template <class T>
void printv(const vector<T> &v) { for (auto x : v) cout << x << " "; cout << '\n'; }

// GCD and LCM
ll gcd(ll a, ll b) { return b == 0 ? a : gcd(b, a % b); }
ll lcm(ll a, ll b) { return (a / gcd(a, b)) * b; }

// Prime check function
bool isprime(ll a) {
    if (a <= 1) return false;
    for (int i = 2; i * i <= a; ++i)
        if (a % i == 0) return false;
    return true;
}

// Custom comparator (example usage in sort function)
struct custom_compare {
    bool operator()(const pii &a, const pii &b) const {
        return a.second < b.second;
    }
};

void solvet()
{
    int t;
    cin>>t;
    while(t--){
        //your code here
        
    }
}

void solve(){
    //your code here
    
}

int32_t main() {
    FAST_IO;
    solvet();
    return 0;
}
```
