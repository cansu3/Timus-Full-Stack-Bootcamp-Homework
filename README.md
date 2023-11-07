# Timus-Full-Stack-Bootcamp-Homework
## Javascript Array Methods

1. **concat()**: Mevcut bir diziye başka bir dizi veya değerler ekler ve yeni bir dizi oluşturur.
2. **copyWithin()**: Dizinin belirli bir bölümünü, belirli bir konumdan başlayarak belirli bir konuma yapıştırır.
3. **entries()**: Dizinin her anahtar/değer çiftini içeren bir dizi döndürür.
4. **every()**: Tüm dizi öğelerinin belirli bir koşulu sağlayıp sağlamadığını kontrol eder.
5. **fill()**: Dizinin belirli bir kısmını belirtilen bir değerle doldurur.
6. **filter()**: Belirtilen bir test fonksiyonuna göre dizi öğelerini filtreler ve yeni bir dizi oluşturur.
7. **find()**: Belirli bir test fonksiyonuna göre dizideki ilk uygun öğeyi bulur ve döndürür.
8. **findIndex()**: Belirli bir test fonksiyonuna göre dizideki ilk uygun öğenin dizinini döndürür.
9. **flat()**: Tüm alt dizileri belirtilen bir derinlikte düzleştirir.
10. **flatMap()**: Dizi öğelerini belirli bir işlevle haritalandırır ve ardından sonuç dizisini belirli bir derinlikte düzleştirir.
11. **forEach()**: Dizi öğeleri üzerinde bir fonksiyon uygular.
12. **from()**: Bir nesneyi diziye dönüştürür.
13. **includes()**: Belirli bir değerin dizide bulunup bulunmadığını kontrol eder.
14. **indexOf()**: Belirli bir öğenin dizideki ilk konumunu döndürür.
15. **join()**: Tüm dizi öğelerini birleştirerek bir dize oluşturur.
16. **keys()**: Dizinin anahtarlarını içeren bir dizi döndürür.
17. **lastIndexOf()**: Belirli bir öğenin dizideki son konumunu döndürür.
18. **map()**: Dizi öğelerini belirli bir işlevle haritalandırır ve sonuçları içeren yeni bir dizi oluşturur.
19. **pop()**: Dizinin son öğesini kaldırır.
20. **push()**: Dizinin sonuna bir veya daha fazla öğe ekler ve yeni uzunluğu döndürür.
21. **reduce()**: Dizi öğelerini birbirine toplar veya birleştirir.
22. **reduceRight()**: Dizi öğelerini sağdan sola doğru birleştirir.
23. **reverse()**: Dizinin öğelerini tersine çevirir.
24. **shift()**: Dizinin ilk öğesini kaldırır ve kaldırılan öğeyi döndürür.
25. **slice()**: Belirli bir bölümü kopyalar ve yeni bir dizi olarak döndürür.
26. **some()**: En az bir dizi öğesinin belirli bir koşulu sağlayıp sağlamadığını kontrol eder.
28. **sort()**: Diziyi belirli bir sıraya göre sıralar.
29. **splice()**: Dizideki bir bölümü kaldırır, değiştirir veya yeni öğeler ekler.
30. **toLocaleString()**: Diziyi temsil eden bir yerel dizeyi döndürür.
31. **toString()**: Diziyi bir dizeye dönüştürür.
32. **unshift()**: Dizinin başına bir veya daha fazla öğe ekler ve yeni uzunluğu döndürür.
33. **values()**: Dizinin değerlerini içeren bir dizi döndürür.

## Do/Do While Farkı
do while döngüsü ve while döngüsü, JavaScript'te döngü oluşturmak için kullanılan iki farklı döngü türüdür.

while döngüsü, koşul doğru olduğu sürece bir kod bloğunu yürütür.
do while döngüsü ise koşulun doğru olup olmadığını kontrol etmeden önce kod bloğunu en az bir kez yürütür ve ardından koşulu kontrol eder.
    
## For/For Each Farkı
JavaScript'te, `for` ve `forEach` döngüleri, bir dizi veya bir nesne üzerinde işlem yapmak için kullanılan farklı döngü türleridir. İşlevsellikleri ve kullanım amaçları açısından bazı farklılıklar bulunmaktadır:

1. `for` döngüsü: Genellikle bir dizi veya nesne üzerinde belirli bir sayıda tekrarlamak istediğinizde kullanılır. Döngü başlangıç koşulunu, döngünün devam etme koşulunu ve her adımda gerçekleştirilecek olan işlemi manuel olarak belirtmenizi sağlar.

```javascript
for (let i = 0; i < array.length; i++) {
  console.log(array[i]);
}
```

2. `forEach` döngüsü: Bir dizi veya bir nesne üzerinde her öğe için belirli bir işlem yapmak istediğinizde kullanılır. `forEach` yöntemi, dizideki her öğe için belirtilen bir işlevi çağırır. Bu yöntem, döngü değişkenini ve döngü koşullarını manuel olarak belirtme gereksinimini ortadan kaldırır.

```javascript
array.forEach(function(element) {
  console.log(element);
});
```

Temel fark, `for` döngüsünün daha fazla esneklik sağlaması ve her türlü döngü senaryosunu kapsayabilmesidir. Diğer yandan, `forEach` döngüsü daha basit bir sözdizimi sunar ve döngü değişkenini ve döngü koşullarını belirtme gereksinimini ortadan kaldırır. Ayrıca, `forEach` döngüsü, dizi üzerinde işlem yapmak için daha temiz bir yaklaşım sunabilir.

