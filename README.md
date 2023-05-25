# Write-a-Python-program-that-accepts-a-word-from-the-user-and-reverse-it.
1)#a = "".join(reversed(x))
q = "name is deekshith"
a = "".join(reversed(q))
print(a)
2)
q[::-1]
3)
def reverse_string(q):
    q2 = ""
    for i in q:
        q2 = i + q2
    return q2


