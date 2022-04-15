<h1> Butun sonlar to'plamini vector yordamida saralash (<span>o'sish tartibida </span>)</h1>

  <pre>
#include <bits/stdc++.h>
using namespace std;

int main()
{
	vector<int> v{ 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };

	sort(v.begin(), v.end());

	cout << "Sorted \n";
	for (auto x : v)
		cout << x << " ";

	return 0;
}
  
  </pre>
  
  
  <h1>Butun sonlar to'plamini vector yordamida saralash (<span>kamayish tartibida </span>)</h1>
  
  <pre>
    #include <bits/stdc++.h>
using namespace std;
 
int main()
{
    vector<int> v{ 1, 5, 8, 9, 6, 7, 3, 4, 2, 0 };
 
    sort(v.begin(), v.end(), greater<int>());
 
    cout << "Sorted \n";
    for (auto x : v)
        cout << x << " ";
 
    return 0;
}
    </pre>
