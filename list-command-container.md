`docker container ls -a` = Untuk melihat list container yang berjalan.

`docker container create --name namacontainer namaimage:tag` = Untuk membuat sebuah container.

`docker container start containerId/namacontainer` = Untuk menjalankan sebuah container. Note: kita bisa menggunakan container id nya atau nama containernya langsung. Kita bisa menjalankan 2 container dengan satu sumber image dan port yang sama secara bersamaan asal namanya berbeda.

`docker container stop containerId/namacontainer` = Untuk menghentikan jalannya sebuah container.

`docker container rm containerId/namacontainer` = Untuk menghapus sebuah container yang ditentukan.

`docker container logs -f containerId/namacontainer` = Untuk melihat log container.
