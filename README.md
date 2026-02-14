[main.py.txt](https://github.com/user-attachments/files/25312903/main.py.txt)# Betik-Diller-2.Hafta
![screenshot png](https://github.com/user-attachments/assets/26a8ebf2-5010-488d-9688-5cdd9b6f7403)
[Uploading maiimport random  # Ayberk Korkmaz

fb_sayac = 0
gs_sayac = 0
ber_sayac = 0

for i in range(40000):
    z1 = random.randint(1, 6)
    z2 = random.randint(1, 6)

    if z1 % 2 == 0 and z2 % 2 == 0:
        fb_sayac += 1
        print("FB")

    elif z1 % 2 == 1 and z2 % 2 == 1:
        gs_sayac += 1
        print("GS")

    else:
        ber_sayac += 1

toplam = fb_sayac + gs_sayac + ber_sayac

print("FB oran:", fb_sayac / toplam)
print("GS oran:", gs_sayac / toplam)
print("Beraberlik oran:", ber_sayac / toplam)
n.py.txt…]()

