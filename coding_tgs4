import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
pengunjung = pd.read_csv("Pengunjung_Mall.csv")    #membaca file csv dengan nama menggunakan library pandas dan menyimpannya dalam variabel pengunjung
print(pengunjung.head())

#Preprocessing yaitu mengubah nama kolom agar lebih seragam. Lalu kolom gender adalah kolom kategorik, maka kita akan mengubah data tersebut menjadi data numerik.
# ubah nama kolom
df = pengunjung.rename(columns={'Gender': 'gender', 'Usia': 'Usia',
                        'Pendapatan_Tahunan_Ribuan_USD': 'Pendapatan_Tahunan_Ribuan_USD',
                        'Pengeluaran_USD': 'Pengeluaran_USD'})
