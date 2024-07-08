### C# Sözdizimi: Temel Kavramlar

C# (C-sharp), Microsoft tarafından geliştirilen ve .NET platformunda çalışan modern, nesne yönelimli bir programlama dilidir. Güçlü tip güvenliği, basitlik ve performans odaklı bir yapıya sahiptir. Bu makalede, C# dilinin temel sözdizimini ve anahtar kavramlarını inceleyeceğiz.

#### 1. Namespace (Ad Alanı)
C# projelerinde, kodun daha düzenli ve yönetilebilir olmasını sağlamak için namespace (ad alanı) kullanılır. Namespace, sınıfları ve diğer türleri mantıksal gruplar halinde organize eder. Kullanımı şu şekildedir:
```csharp
namespace ProjeAdi
{
    class SinifAdi
    {
        // Sınıf üyeleri
    }
}
```

Örnek:
```csharp
namespace ArabaUygulamasi
{
    class Araba
    {
        public string renk;
        public int hiz;

        public void Hizlan()
        {
            hiz += 10;
        }
    }
}
```

#### 2. Değişken Tanımlama ve Veri Türleri
C# dilinde değişkenler belirli veri türlerine sahiptir ve bu türler derleme zamanında kontrol edilir. Temel veri türleri şunlardır:

- `int`: Tamsayılar için kullanılır. Örnek: `int sayi = 10;`
- `double`: Ondalıklı sayılar için kullanılır. Örnek: `double pi = 3.14;`
- `bool`: Mantıksal değerler için kullanılır (true veya false). Örnek: `bool dogruMu = true;`
- `char`: Tek bir karakter için kullanılır. Örnek: `char harf = 'A';`
- `string`: Metin verileri için kullanılır. Örnek: `string isim = "Ahmet";`

#### 3. Operatörler
C#’ta çeşitli operatörler bulunmaktadır:

- **Aritmetik Operatörler:** `+`, `-`, `*`, `/`, `%`
- **Karşılaştırma Operatörleri:** `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Mantıksal Operatörler:** `&&`, `||`, `!`
- **Atama Operatörleri:** `=`, `+=`, `-=`, `*=`, `/=`, `%=` 

#### 4. Kontrol Yapıları
C#’ta kontrol yapıları, kod akışını yönetmek için kullanılır. Ana kontrol yapıları şunlardır:

- `if` ve `else` ifadesi:
```csharp
if (kosul) {
    // Kosul doğruysa çalışır
} else {
    // Kosul yanlışsa çalışır
}
```

- `switch` ifadesi:
```csharp
switch (deger) {
    case 1:
        // 1 ise çalışır
        break;
    case 2:
        // 2 ise çalışır
        break;
    default:
        // Hiçbiri değilse çalışır
        break;
}
```

#### 5. Döngüler
Döngüler, belirli bir kod bloğunu tekrar tekrar çalıştırmak için kullanılır.

- `for` döngüsü:
```csharp
for (int i = 0; i < 10; i++) {
    Console.WriteLine(i);
}
```

- `while` döngüsü:
```csharp
int i = 0;
while (i < 10) {
    Console.WriteLine(i);
    i++;
}
```

- `do-while` döngüsü:
```csharp
int i = 0;
do {
    Console.WriteLine(i);
    i++;
} while (i < 10);
```

#### 6. Fonksiyonlar ve Metotlar
Fonksiyonlar, belirli bir işlemi gerçekleştiren ve gerektiğinde bir değer döndüren kod bloklarıdır. C#’ta fonksiyonlar şöyle tanımlanır:
```csharp
returnType FonksiyonAdi(parametreler) {
    // Fonksiyon gövdesi
    return deger;
}
```
Örnek:
```csharp
int Topla(int a, int b) {
    return a + b;
}
```

#### 7. Sınıflar ve Nesneler
C#, nesne yönelimli bir dil olduğundan, sınıflar ve nesneler temel yapı taşlarıdır. Sınıflar, veri ve metotları bir araya getiren yapılardır.
```csharp
class Araba {
    public string renk;
    public int hiz;

    public void Hizlan() {
        hiz += 10;
    }
}
```

Bu makalede, C# dilinin temel sözdizimini ve anahtar kavramlarını özetledik. Bu temel bilgiler, C# ile programlamaya başlamak için sağlam bir temel sağlar. Detaylı ve ileri düzey konular için daha kapsamlı kaynaklara başvurabilirsiniz.
