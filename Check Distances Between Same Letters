class Solution {
public:
    bool checkDistances(string s, vector<int>& distance) {
       map<char , vector<int>>m;
       for(int i=0;i<s.size();i++)
         m[s[i]].push_back(i);

      vector<int>v;
      int j = 0;
      for(auto it : m)
      {
        auto i = it.second[1] - it.second[0] -1;
        if( i != distance[it.first - 'a'])
          return false;
      }
      return true;
    }
};
