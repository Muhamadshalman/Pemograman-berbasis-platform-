# GENERIC-COLLECTION

Untuk pertanyaan pertama, kita perlu membuat kelas `Mahasiswa` sebagai kelas generik. Berikut adalah implementasinya:

```java
public class Mahasiswaku {

    public static void main(String[] args) {

        Mahasiswa<String, String, Integer> m = new Mahasiswa<>();

        m.setNim("20220040156");
        m.setName("MUHAMAD ALIF ALFARIZ");
        m.setClas(22);

        System.out.println(m.getNim());
        System.out.println(m.getName());
        System.out.println(m.getClas());

    }
}

class Mahasiswa<N, S, C> {
    private N nim;
    private S name;
    private C clas;

    public void setNim(N nim) {
        this.nim = nim;
    }

    public N getNim() {
        return nim;
    }

    public void setName(S name) {
        this.name = name;
    }

    public S getName() {
        return name;
    }

    public void setClas(C clas) {
        this.clas = clas;
    }

    public C getClas() {
        return clas;
    }
}



```

Untuk pertanyaan kedua, berikut adalah program menggunakan `ArrayList` dan `ArrayDeque`:

```java
import java.util.ArrayList;
import java.util.ArrayDeque;

public class Main {
    public static void main(String[] args) {
        // Contoh penggunaan ArrayList
        ArrayList<String> arrayList = new ArrayList<>();
        arrayList.add("Item 1");
        arrayList.add("Item 2");
        arrayList.add("Item 3");

        System.out.println("Isi ArrayList:");
        for (String item : arrayList) {
            System.out.println(item);
        }

        // Contoh penggunaan ArrayDeque
        ArrayDeque<Integer> arrayDeque = new ArrayDeque<>();
        arrayDeque.addFirst(1);
        arrayDeque.addLast(2);
        arrayDeque.addLast(3);

        System.out.println("\nIsi ArrayDeque:");
        for (int item : arrayDeque) {
            System.out.println(item);
        }
    }
}
```

Dalam contoh yang diatas, kita menggunakan `ArrayList` untuk menyimpan objek-objek bertipe `String`, dan `ArrayDeque` untuk menyimpan objek-objek bertipe `Integer`. Kedua kelas tersebut adalah implementasi dari antarmuka `List` dan `Deque` di dalam Java Collections Framework.
