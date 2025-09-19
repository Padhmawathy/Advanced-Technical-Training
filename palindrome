def palindrome(i,j):
	non_rev = str(i)
	for iteration in range(1,j+1):
		rev = non_rev[::-1]
		sum = int(non_rev) + int(rev)
		if str(sum) == str(sum[::-1]):
			return iteration
		non_rev = str(sum)
