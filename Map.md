- syntax of map
map<key, value> mp;
map<datatype, datatype> mp;
map<int, int> mp;

- each key should be unique.

- usual workflow(mostly used to count frequency)
  for(for int i=0;i<nums.size();i++)
  {
      mp[s[i]]++;
      //s[i] is element, mp[s[i]]++ increment & stores the frequency of unique element.
  }

- to make pair in maps, use
  mp.insert(make_pair(10, 20));
  mp.insert(make_pair(20, 30));

to get the first and second value, use
for(auto it=mp.begin(); it!=mp.end() it++)
{
    cout<<(*it).first<<" "<<(*it).second<<endl;
}
