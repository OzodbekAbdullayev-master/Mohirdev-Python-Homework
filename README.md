# Mohirdev-Python-Homework
son = float(input("Juft son kiriting: "))
if son%2 == 0:
    print("Rahmat!")
else:
    print(("Bu son juft emas."))

yosh = int(input("Yoshingiz nechida?"))

if yosh<=4 or yosh>=60:
    narh = 0
elif yosh < 18:
    narh = 10000
else:
    narh = 20000
    print(f"Chipta {narh} so'm")

x = float(input("Birinchi sonni kiriting: "))
y = float(input("Ikkinchi sonni kiriting: "))
if x==y:
    print(f"{x}={y}")
elif x<y:
    print(f"{x}<{y}")
else:
    print(f"{x}>{y}")

mahsulotlar = ['un', "yog'", "sovun", 'tuxum', 'piyoz',
              'kartoshka', 'olma', 'banan', 'uzum', 'qovun']

savat =[]
for n in range(5):
    savat.append(input(f"Savatga {n+1}-mahsulotni qo'shing: "))

if savat:
    for mahsulot in savat:
        if mahsulot in mahsulotlar:
            print(f"Do'konimizda {mahsulot} bor")
        else:
            print(f"Do'konimizda {mahsulot} yo'q")
else: 
    print("Savatingiz bo'sh")      

mahsulotlar = ['un', "yog'", "sovun", 'tuxum', 'piyoz',
               'kartoshka', 'olma', 'banan', 'uzum', 'qovun']


savat = []
for n in range(5):
    savat.append(input(f"Savatga {n+1}-mahsulotni qo'shing: "))

bor_mahsulotlar = []
mavjud_emas = []
for mahsulot in savat:
    if mahsulot in mahsulotlar:
        bor_mahsulotlar.append(mahsulot)
    else:
        mavjud_emas.append(mahsulot)

if len(mavjud_emas) >= 1:
  for mahsulotlar in mavjud_emas:
    print(f"Do'konimizda quyidagi mahsulotlar yo'q: {mahsulotlar}")

else:
  print("Siz so'ragan barcha mahsulotlar do'konimizda bor")

users = ['alisher1983','aziza','yasmina','umar']

login = input("Yangi login tanlang: ")

if login in users:
    print('Login band, yangi login tanlang!')
else:
    print("Xush kelibsiz!")
          ****
