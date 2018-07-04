# Menggunakan_If-Else
[Exercises 3] Mengenal penggunaan Conditional if-else dalam JavaScript

var nama = "";
var peran = "";

if (nama == "" && peran =="") {
  console.log("Nama harus diisi!");
}

else if ( nama == "" && peran == "Ksatria") {
  console.log("Siapa nama mu wahai Ksatria ?");
}

else if ( nama == "" && peran == "Tabib") {
  console.log("Siapa nama mu wahai Tabib ?");
}


else if ( nama == "" && peran == "Penyihir") {
  console.log("Siapa nama mu wahai Penyihir ?");
}


else if ( nama === nama && peran == "") {
  console.log("Halo "+nama+" Pilih peran mu untuk memulai game!");
}


else if ( nama === nama && peran == "Ksatria") {
  console.log("Selamat datang di Dunia Proxytia,"+nama);
  console.log("Halo Ksatria "+nama+" kamu dapat menyerang dengan senjatamu!");
}

else if ( nama === nama && peran == "Tabib") {
  console.log("Selamat datang di Dunia Proxytia,"+nama);
  console.log("Halo Tabib "+nama+" kamu akan membantu temanmu yang terluka.");
}

else if ( nama === nama && peran == "Penyihir") {
  console.log("Selamat datang di Dunia Proxytia,"+nama);
  console.log("Halo Penyihir "+nama+" ciptakan keajaiban yang membantu kemenanganmu!");
}


