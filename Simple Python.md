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

# Check memory

```
import sys

variable = 30
print(sys.getsizeof(variable)) # 24

```

# Check byte size

```
def byte_size(string):
	return(len(string.encode('utf-8')))

byte_size(':)') # 4
byte_size('Hello World') # 11

```

# Print string for n times

```
n = 2;
s = "Programming";

print(s * n); # ProgrammingProgramming

```

# Cap first letter

```
s = "programming is awesome"

print(s.title()) #Programming Is Awesome

```

# Chunk

```
from math import ceil

def chunk(1st, size);
	return list(
		map(

			lambda x: 1st[x * size: x * size + size], list(range(0, ceil(len(1st) / size )))

		)

	)

chunk ([1,2,3,4,5],2) # [[1,2],[3,4],5]

```

# Compact - remove bool value items

```

def compact(1st):
	return list(filter(bool, 1st))

compact([0, 1, False, 2, '', 3, 'a', 's', 34]) # [1, 2, 3, 'a', 's', 34 ]

```

# Transposed













