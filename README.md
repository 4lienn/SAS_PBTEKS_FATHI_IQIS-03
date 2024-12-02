Apa itu import java.util.Scanner?

Bayangkan kamu sedang membangun sebuah rumah. Untuk membangun rumah, kamu membutuhkan berbagai macam bahan bangunan seperti kayu, semen, paku, dan lain-lain. Nah, dalam pemrograman, kita juga membutuhkan "bahan-bahan" tertentu untuk membangun program kita.

import java.util.Scanner adalah seperti kita mengambil sebuah kotak berisi alat-alat khusus yang bernama Scanner. Kotak ini berisi berbagai macam alat yang berguna untuk membaca input dari pengguna, misalnya ketika kita ingin program kita meminta pengguna untuk memasukkan angka atau kata.

Mengapa Kita Membutuhkan Scanner?

Agar program kita bisa berinteraksi dengan pengguna, kita perlu cara untuk mengambil data yang dimasukkan pengguna. Scanner inilah yang memungkinkan kita untuk "mendengarkan" input dari pengguna, seperti ketika pengguna mengetik di keyboard.

Contoh Sederhana:

Java
import java.util.Scanner;

public class ContohScanner {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);   


        System.out.print("Masukkan nama Anda: ");
        String nama = input.nextLine();

        System.out.println("Halo,   
 " + nama + "!");
    }
}
Gunakan kode dengan hati-hati.

Penjelasan Kode:

import java.util.Scanner;: Ini adalah bagian di mana kita mengambil kotak alat Scanner.
Scanner input = new Scanner(System.in);: Kita membuat sebuah objek bernama input dari kelas Scanner. Objek ini akan digunakan untuk membaca input dari keyboard (ditunjukkan oleh System.in).
System.out.print("Masukkan nama Anda: ");: Kita menampilkan pesan di layar untuk meminta pengguna memasukkan nama.
String nama = input.nextLine();: Kita menggunakan metode nextLine() dari objek input untuk membaca seluruh baris yang diketik pengguna dan menyimpannya dalam variabel nama.
System.out.println("Halo, " + nama + "!");: Kita menampilkan pesan selamat datang dengan menggunakan nama yang telah dimasukkan pengguna.
Jadi, intinya:

import java.util.Scanner adalah cara kita untuk menggunakan alat-alat yang ada di kelas Scanner agar program kita bisa berinteraksi dengan pengguna dan menerima input dari mereka.