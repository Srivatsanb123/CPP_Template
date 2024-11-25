```cpp
#include <bits/stdc++.h>
using namespace std;

#define ll long long
#define ull unsigned long long
#define pi pair<int, int>
#define pll pair<long long, long long>
#define vi vector<int>
#define vc vector<char>
#define vs vector<string>
#define vll vector<ll>
#define all(x) (x).begin(), (x).end()
#define rall(x) (x).rbegin(), (x).rend()
#define MOD 1000000007
#define INF 1e18
#define PI 3.1415926535897932384626433832795
#define yes cout << "YES\n"
#define no cout << "NO\n"
#define pb push_back
#define eb emplace_back
#define FAST_IO                                                                \
  ios_base::sync_with_stdio(false);                                            \
  cin.tie(NULL);
template <typename T1, typename T2> using ump = std::unordered_map<T1, T2>;
template <typename T> using pq = std::priority_queue<T>;
template <typename T1, typename T2> void printmp(unordered_map<T1, T2> &mp) {
  for (auto x : mp)
    cout << x.first << " " << x.second << '\n';
}
template <class T> void printv(vector<T> &v) {
  for (auto x : v)
    cout << x << " ";
  cout << '\n';
}
template <class T> void inputv(vector<T> &v, int n) {
  v.resize(n);
  for (int i = 0; i < n; ++i)
    cin >> v[i];
}

void solvet();
void solve();

int32_t main() {
  FAST_IO;
#ifdef SB
  freopen("input.txt", "r", stdin);
  freopen("output.txt", "w", stdout);
  auto _clock_start = chrono::high_resolution_clock::now();
#endif
// solve();
// solvet();
#ifdef SB
  cout << "---------------------\nExecuted in "
       << chrono::duration_cast<chrono::milliseconds>(
              chrono::high_resolution_clock::now() - _clock_start)
              .count()
       << "ms." << endl;
#endif
}

void solvet() {
  int T;
  cin >> T;
  while (T--) {
    solve();
  }
}

void solve() {}
```
