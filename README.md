// Membuat larik satu dimensi dengan 5 elemen
int[] larik1 = new int[5];
// Mengisi nilai elemen larik satu dimensi
larik1[0] = 10;
larik1[1] = 20;
larik1[2] = 30;
larik1[3] = 40;
larik1[4] = 50;
// Menampilkan isi larik satu dimensi
System.out.println("Larik satu dimensi:");
for (int i = 0; i < larik1.length; i++) {
  System.out.println("larik1[" + i + "] = " + larik1[i]);
}

// Membuat larik dua dimensi dengan 3 baris dan 4 kolom
int[][] larik2 = new int[3][4];
// Mengisi nilai elemen larik dua dimensi
larik2[0][0] = 1;
larik2[0][1] = 2;
larik2[0][2] = 3;
larik2[0][3] = 4;
larik2[1][0] = 5;
larik2[1][1] = 6;
larik2[1][2] = 7;
larik2[1][3] = 8;
larik2[2][0] = 9;
larik2[2][1] = 10;
larik2[2][2] = 11;
larik2[2][3] = 12;
// Menampilkan isi larik dua dimensi
System.out.println("Larik dua dimensi:");
for (int i = 0; i < larik2.length; i++) {
  for (int j = 0; j < larik2[i].length; j++) {
    System.out.print("larik2[" + i + "][" + j + "] = " + larik2[i][j] + " ");
  }
  System.out.println();
}
