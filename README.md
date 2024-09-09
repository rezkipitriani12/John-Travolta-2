def hitung_tabungan(gaji, pengeluaran=600000):
    # Menentukan apakah bisa menabung
    if gaji > pengeluaran:
        tabungan = gaji - pengeluaran
        return f"Bisa menabung. Jumlah tabungan: Rp {tabungan}"
    elif gaji == pengeluaran:
        return "Tidak bisa menabung."
    else:
        return "Cari tambahan, gaji kurang."

# Input gaji Mr. John (Masukkan nilai gaji yang didapat dari program pertama atau secara manual)
gaji_mingguan = 870000  # Sesuaikan dengan hasil dari program pertama atau input manual

# Input pengeluaran mingguan Mr. John
pengeluaran_mingguan = 600000

# Hitung apakah bisa menabung
status_tabungan = hitung_tabungan(gaji_mingguan, pengeluaran_mingguan)

# Output hasil
print(status_tabungan)
