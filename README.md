# hello-world
learn to make repository
Q2.
Byteland has NN cities (numbered from 11 to NN) and N−1N−1 bidirectional roads. It is guaranteed that there is a route from any city to any other city.
Jeanie is a postal worker who must deliver KK letters to various cities in Byteland. She can start and end her delivery route in any city. Given the destination cities for KK letters and the definition of each road in Byteland, find and print the minimum distance Jeanie must travel to deliver all KK letters.
Note: The letters can be delivered in any order.
Input Format
The first line contains two space-separated integers, NN (the number of cities) and KK (the number of letters), respectively. The second line contains KK space-separated integers describing the delivery city for each letter. Each line ii of the N−1N−1 subsequent lines contains 33 space-separated integers describing a road as ui vi diui vi di, where didi is the distance (length) of the bidirectional road between cities uiuiand vivi.
Constraints
 2≤K≤N≤1052≤K≤N≤105
 1≤di≤1031≤di≤103
 Byteland is a weighted undirected acyclic graph.Byteland is a weighted undirected acyclic graph.
Output Format
Print the minimum distance Jeanie must travel to deliver all KK letters.
Sample Input
5 3
1 3 4
1 2 1
2 3 2
2 4 2
3 5 3
Sample Output
6
Explanation
Jeanie has 33 letters she must deliver to cities 11, 33, and 44 in the following map of Byteland
One of Jeanie's optimal routes is 32→21→11→22→432→21→11→22→4, for a total distanced traveled of 2+1+1+2=62+1+1+2=6. Thus, we print 66 on a new line.

Sample Problem 3
Chris Gayle has a legacy of hitting sixes in his innings. He loves to hit sixes. Now in a particular match, he already know that he will face total of (N + 1) balls which means that he will get out on (N + 1)th ball. So he has decided to hit sixes in each of the initial N balls. He will require some power Pi to hit a six on ith ball. He can only hit a six on any ball if he has power greater than the required power. He has M amount of power initially. He can play initial N balls in any order and by hitting six on ith ball, he will gain Gi power but he will not loose that Pi power. Now you are required to output "YES" or "NO" to answer that if he can hit N sixes or not.
 First line will contain T (No. of test cases).
 First line of each test case will contain two space separated integers : N and M
 Next each N lines will contain two space separated integers denoting Gi and Pi
Output
 For every test case, print the required answer in a new line.
Constraints
 1 ≤ T ≤ 10
 1 ≤ N ≤ 104
 1 ≤ M, Gi and Pi ≤ 109
Sample Input
1
2 7
3 6
2 4
Sample Output
YES
