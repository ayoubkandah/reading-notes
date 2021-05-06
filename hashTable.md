Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.


Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a hash. A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

Since we are able to hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.

The element is stored in the hash table where it can be quickly retrieved using hashed key.

hash = hashfunc(key)
index = hash % array_size


String                                Hash function                               Index
abcdef       (971 + 982 + 993 + 1004 + 1015 + 1026)%2069       38
bcdefa       (981 + 992 + 1003 + 1014 + 1025 + 976)%2069       23
cdefab       (991 + 1002 + 1013 + 1024 + 975 + 986)%2069       14
defabc       (1001 + 1012 + 1023 + 974 + 985 + 996)%2069       11



void insert(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc(s);
        //Search for an unused slot and if the index will exceed the hashTableSize then roll back
        while(hashTable[index] != "")
            index = (index + 1) % hashTableSize;
        hashTable[index] = s;
    }

void search(string s)
    {
        //Compute the index using the hash function
        int index = hashFunc(s);
         //Search for an unused slot and if the index will exceed the hashTableSize then roll back
        while(hashTable[index] != s and hashTable[index] != "")
            index = (index + 1) % hashTableSize;
        //Check if the element is present in the hash table
        if(hashTable[index] == s)
            cout << s << " is found!" << endl;
        else
            cout << s << " is not found!" << endl;
    }
