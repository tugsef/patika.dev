# INSERTION SORT PROJESİ

- **Aşamalar**

 **Not:Elemanların seçildiğini belirtmek için "| |" işareti kullanılmıştır.**
 
Endeks başlangıcı 1 'dir.  

**1.Adım**  (n)  [|22|,27,16,|2|,18,6] En küçük eleman bulunur.İlk endeksteki elemanla yer değiştirir.                           
				
**2.Adım**  (n-1) [2,|27|,16,22,18,|6|] 22  ile 2 yer değiştirdi. İlk endeks elemanı seçildi.ikinci  endeks için diğer elemanlar
arasından en küçüğü seçilir. Yer değiştirir.                                                

**3.Adım**  (n-2) [2,6,16,|22|,|18|,27] 27 ile 6 yer değiştirdi.İkinci endeks elemanı seçildi.Üçüncü endek elemanı için diğer
elemanlar arasından en küçüğü seçilir. Yer değiştirir. Üçüncü indeks elemanı diğer kalan     
elemanlardan küçük olduğundan geçildi.Dördüncü  endeks için diğer elemanlar
arasından en küçüğü seçilir					                         

**4.Adım**  (n-3) [2,6,16,22,18,27]22 ile 18 yer değiştirdi. 5 endeks elemanıda diğer elemana göre küçük olduğundan          
sıralanma tamamlanmış oldu.

- **Big-O Notation Gösterimi**

n + (n-1) + (n – 2) + ....... +1 ->Birden n kadar olan sayıların toplamını veririr.

n ( n +1 ) / 2  (n^2 + n )/2 Big – O Notation gösterimi domine eden -> n^2

Worst Case gösterimi  o(n^2) -> Quadratic

- **Time Complexity**

18 sayısı sonda olmadığı için Worst case değildir.
18 sayısı başta olmadığı için Best case değildir.
18 sayısı başta ve sonda olmadığı için Average case kapsamına girer.

> PROJE [Patika.dev Veri Yapıları ve Algoritmalar][(https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje) dersi kapsamında tarafımdan hazırlanmıştır.
