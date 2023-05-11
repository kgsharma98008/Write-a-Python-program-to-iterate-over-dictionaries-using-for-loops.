# Write-a-Python-program-to-iterate-over-dictionaries-using-for-loops.

my_dict = {"apple": 1, "banana": 2, "cherry": 3}
# iterate over keys
print("Iterating over keys:")
for key in my_dict:
 print(key)
# iterate over values
print("\nIterating over values:")
for value in my_dict.values():
 print(value)
# iterate over items (key-value pairs)
print("\nIterating over items:")
for key, value in my_dict.items():
 print(key, value)
