# xumoyun333
print("Ikkita a va b sonlardan kattasini topish dasturi")
a=None
b=None
try:
    a = int(input("a="))
except:
    print("a sonini kititishda xatolik yuz berdi")
    a=0
try:
    b = int(input("b="))
except:
    print("b sonini kiritishda xatolik yuz berdi")
    b=0
if a>b:
   print("A katta B dan a=",a)
else:
   print("B katta A dan b=",b)
print("Dastur tugadi")
