# Laporan Tugas 1: Versioning

## Oleh: Risda Rahmawati Harsono

### --- Skenario Fast-Forward ---

#### Membuat Sambungan Repositori
![Screenshot (3321)](https://github.com/user-attachments/assets/24eef52e-89f2-4703-b4a2-2a0b5bde897d)

#### Membuat Branch "ParentRisda" 
Di dalam branch ParentRisda terdapat file "HelloWorld.txt"
![Screenshot (3327)](https://github.com/user-attachments/assets/aacc0308-6240-4f13-9821-fec2e3872fcd)

#### Membuat Branch "ChildRisda"
Di dalam branch ChildRisda terdapat file "Halo_Child.txt"
![Screenshot (3324)](https://github.com/user-attachments/assets/6dddcd63-91a6-403f-9aed-9ce10ebe72da)

#### Merge - Fast Forward antara ParentRisda & ChildRisda
Disini terjadi skenario Fast Forward karena ada merge dari branch ChildRisda dan ParentRisda dimana ParentRisda tidak memiliki commit lain yang dilakukan di branch tersebut sebelum penggabungan.
![Screenshot (3325)](https://github.com/user-attachments/assets/f599cf63-3ae8-436c-a248-6e34123d86e1)

#### Mengirimkan hasil ke Main
![Screenshot (3326)](https://github.com/user-attachments/assets/405eaa48-ac61-43f6-9c88-c5d34bfeabb2)

#### Git Log
![image](https://github.com/user-attachments/assets/ed1fb832-b136-4cce-893d-adad61905b86)



### --- Three Way Merge & Solve Conflict ---

#### Melakukan perubahan pada file Halo_Child.txt di Branch ParentRisda
Kemudian perubahan di commit ke halaman github.
![Screenshot (3352)](https://github.com/user-attachments/assets/912548fc-a7e6-44a4-bb9c-b357067b958a)

#### Melakukan perubahan pada file Halo_Child.txt di Branch ChildRisda
Kemudian perubahan di commit ke halaman github.
![Screenshot (3353)](https://github.com/user-attachments/assets/79f51368-1f4a-4056-a36b-b604995f5ca4)
![Screenshot (3354)](https://github.com/user-attachments/assets/213bcbf4-edf7-4b20-8f21-6158fc774a53)

#### Mencoba proses MERGE antara ChildRisda & ParentRisda
Saat proses merge dilakukan, terjadi konflik dikarenakan ada perubahan di file Halo-CHild.txt baik pada ParentRisda maupun di ChildRisda, sehingga perlu diselesaikan.
![Screenshot (3356)](https://github.com/user-attachments/assets/6c00003d-546c-4bd6-a99c-3a6ad8eea807)


#### Resolve Konflik diantara dua Branch
Dilakukan penyelesaian konflik diantara dua Branch. Dilakukan resolve dengan merge melalui text editor, dan memperbaiki bagian yang diperlukan.
![Screenshot (3358)](https://github.com/user-attachments/assets/62028038-66e4-4a87-925e-7a2f7b015a9f)
![Screenshot (3359)](https://github.com/user-attachments/assets/134043ec-5b69-470f-a259-6429bfc613d8)

#### Commit file ke ParentRisda di Github setelah di Resolve
![Screenshot (3361)](https://github.com/user-attachments/assets/82f0a223-9d80-436e-82c7-94b45aa51beb)


#### Graph Proses Three Way Merge 
![Screenshot (3362)](https://github.com/user-attachments/assets/c7c2cd9f-c997-41a0-8e9e-a6870ec50ed5)



