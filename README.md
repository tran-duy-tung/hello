p = input()
i = 0
kq = ''
while i < len(p):
    t = '0'
    while int(t) < 97 or int(t) > 122:
        t = t+p[i]
        i += 1
    kq = kq+chr(int(t))
print(kq)    

