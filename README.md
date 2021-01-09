## Remove-empty-strings-from-the-list-of-strings
## Sample code to check the empty strings from the list
```sh
list1 = ["Mike", "", "Emma", "Kelly", "", "Brad"]
resList = list(filter(None, list1))
print(resList)
```
## Example Output
["Mike", "Emma", "Kelly", "Brad"]
