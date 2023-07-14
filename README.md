Analisis MMPBSA dan MMGBSA menggunakan gmx_MMPBSA hasil MD kompleks protein-ligand, Sistem memiliki 2 ligand.

1. Buat direktori kerja.
2. Tempatkan direktori-direktori kompleks hasil simulasi Gromacs ke dalam direktori kerja. Dalam setiap direktori merupakan 1 kompleks dengan segala file input-output simulasi gromacs, mulai dari preparasi sampai produksi.
3. Tempatkan file eksekusi (gmxana2_lig2.sh).
4. Pada Terminal Linux, jalankan perintah berikut: chmod a+x gmxana2_lig2.sh
5. Eksekusi analisis dengan perintah: ./gmxana1_lig2.sh
6. File output dalam bentuk rmsd ligand, rmsd protein, rmsf, sasa dan gyration dalam format .xvg tersimpan pada setiap direktori kompleks.
7. Output akan ditempatkan pada setiap kompleks dalam direktori PB (untuk MMPBSA) dan GB (untuk MMGBSA).   
