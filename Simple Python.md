# Duplicate item

```
def all_unique(1st):
	return len(1st) == len(set(1st))

x = [1,1,2,2,3,2,3,4,5,6]
y = [1,2,3,4,5]
all_unique(x) #False
all_unique(y) #True

```

# Check same items in string

```

from collections import Counter

def anagram(first, second):
	reture Counter(first) == Counter(second)

anagram("abcd3", "3acdb") # Ture

```