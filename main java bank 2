import java.io.*;

import static javax.security.auth.callback.ConfirmationCallback.OK;

class bank2 {

    public static void main (String args[]) {

        BufferedReader input=new BufferedReader (new InputStreamReader (System.in)); {

            int pin, option, saldo, proses, jum_transfer, no_rekening, penarikan; // Variabel
            saldo=2657892;
            no_rekening=43567890;
            jum_transfer= (int) 1000.000;
            penarikan= (int) 500.000;

            try {
                Object ATM;
                System.out.println ( “____ATM____“);
                System.out.println (” SELAMAT DATANG “);
                System.out.println (” BANK RYZEN CORPORATION “);
                System.out.println (” “);
                System.out.println (“_______“);
                System.out.println (“SILAHKAN INPUTKAN PIN ANDA”);
                System.out.print (“-> “);
                pin=Integer.parseInt(input.readLine()); // Inputan

                if (pin == 2412) // Kondisi If
                {

                    do { // Kondisi Do While
                        System.out.println (“\n_______“);
                        System.out.println (“MENU TRANSAKSI ANDA”);
                        System.out.println (“A/n RISS HAQIQI\n”);
                        System.out.println (“SILAHKAN PILIH OPTION”);

                        System.out.println (“-> 1. INFO SALDO”);
                        System.out.println (“-> 2. TRANSFER”);
                        System.out.println (“-> 3. PENARIKAN”);
                        System.out.println (“-> 4. TRANSAKSI LAIN”);
                        System.out.println (“-> 5. KELUAR”);
                        System.out.println (“________“);

                        System.out.print (“OPTION -> “);
                        option=Integer.parseInt(input.readLine());

                        switch (option) { // Perulangan Case
                            case 1:
                                System.out.println (“================================”);
                                System.out.println (“SALDO ANDA SAAT INI : “+saldo);
                                System.out.println (“================================”);
                                break;

                            case 2:

                                System.out.println (“=================================”);
                                System.out.println (“TRANSFER DANA KE BANK LAIN “);
                                System.out.println (“=================================”);

                                System.out.print( “Masukan No Rekening : ” );
                                no_rekening=Integer.parseInt(input.readLine());
                                System.out.print( “Masukan Jumlah Transfer : ” );
                                jum_transfer=Integer.parseInt(input.readLine());

                                for ( int i=0; i PIN MATCH : OK “);
                        }
else {
                            System.out.println (“> PIN NOT MATCH. Trasaksi Batal”);
                        }

                        if (jum_transfer SALDO : OK”);
                    }

else {
                    System.out.print (“–> SALDO TIDAK CUKUP UNTUK TRANSFER. Trasaksi Batal”);
                }

                    if (no_rekening == 43567890) { // Cek kevalidan No rekening
                        System.out.println (” -> No Rekening = “+no_rekening);
                        System.out.println (” -> a/n = TOTTO”);
                        System.out.println (” -> Jumlah Transfer = “+jum_transfer);
                        System.out.println (” TRANSAKSI BERHASIL !”); }

                    else {
                        System.out.println (“No Rekening tidak terdaftar. Transaksi BATAL”);
                    }

                    saldo=saldo-jum_transfer ;
                    break;

                    case 3:
                        System.out.println (“=================================”);
                        System.out.println (“PENARIKAN UANG “);
                        System.out.println (“=================================”);
                        System.out.print (“Masukan jumlah uang >> “);
                        penarikan=Integer.parseInt(input.readLine());
                        System.out.println (“Saldo Awal : “+saldo);
                        System.out.println (“Penarikan : “+penarikan);
                        saldo=saldo-penarikan;
                        System.out.println (“Saldo akhir : “+saldo);
                        for ( int i=0; i PIN MATCH “);
                }
                else {
                    System.out.println (“-> PIN NOT MATCH. Trasaksi Batal”);
                }


                if (penarikan >= (saldo-100.000))
                {
                    System.out.println (“-> SALDO TIDAK CUKUP : TRANSAKSI GAGAL !”);
                }

                else{
                    System.out.println (“TRANSAKSI BERHASIL”);
                }

                break;

                case 4:
                    System.out.println (“=================================”);
                    System.out.println (“RIWAYAT TRANSAKSI”);
                    System.out.println (“=================================”);
                    System.out.println (“Transksi Terakhir”);
                    System.out.println (“Penarikan Saldo :”+ penarikan);
                    System.out.println (“Trasfer Saldo :”+ jum_transfer);
                    System.out.println (“Saldo Akhir :”+ saldo);
                    break;

                default:
                    System.out.println (“TERIMA KASIH TELAH MENGGUNAKAN BANK RYZEN CORPORATION”);

            }
            System.out.println (“\nTEKAN 0 UNTUK KEMBALI KE MENU”);
            System.out.print (“->> “);
            proses=Integer.parseInt(input.readLine());
            ++proses;

        }

        while ( proses <= 1);
    }

else {
        System.out.println ("PIN ANDA SALAH ! ATM ANDA DIBLOKIR. \nHUBUNGI KANTOR CABANG TERDEKAT atau CALL 085642760001");
    }

}

catch (IOException e)
        {
        System.out.print("");
}

        catch (NumberFormatException e)
        {
        System.out.println("PIN ANDA BUKAN ANGKA !");
}
        }
        }
        }

