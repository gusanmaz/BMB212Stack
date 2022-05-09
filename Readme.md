Size hazir verilen Stack.java sinifina ait kodlar asagidaki gibidir.

```java
public class Stack {
    public char[] s;
    public int N;

    public Stack(int cap) {
        s = new char[cap];
    }

    public int size() {
        return N;
    }

    public boolean isEmpty(){
        return N == 0;
    }


    public void push(char item) {
        s[N++] = item;
    }

    public char pop() {
        return s[--N];
    }
    
    
    // Bu fonksiyon parametre olarak aldigi iki yiginin icerigi ayni ise true aksi halde false degerini dondurur.
    // Iki yiginda bos ise bu fonksiyon true degerini dondurur.
    // Iki yiginin da icerigi ayni fakat kapasiteleri farkli ise (s dizisinin eleman sayilari farkli ise) fonksiyon true degerini dondurur.
    // Fonksiyon taniminda (function signature) herhangi bir degisiklik yapmayiniz.
    
    public static boolean Equal(Stack s1, Stack s2){
        // Fonksiyon icini uygun sekilde doldurunuz.
    }
}
```

Size hazir verilen Main.java sinifina ait kodlar asagidaki gibidir.


```java
public class Main {
    public static void main(String args[]){
        // main fonksiyonun icini uygun sekilde doldurunuz.
    }
}
```

Yardimci Kod Ornegi: Asagidaki kod ornegi bir stringin karaketerlerini sirayla alt alta yazdirmaktadir. Kodun altinda kodun ciktisi da verilmistir.
Main altinda yazacaginiz kodda stringi olusturan karakterler uzerinde tek tek islem yapmak gerekebilecegi icin bu ornek kod size hazir verilmistir.

```java
public class Main {
    public static void main(String args[]){
        String s = "Bilgisayar";
        for (int i = 0; i < s.length(); i++){
            char c = s.charAt(i);
            System.out.println(c);
        }
    }
}
```

Kod Ciktisi:

```bash
B
i
l
g
i
s
a
y
a
r
```
