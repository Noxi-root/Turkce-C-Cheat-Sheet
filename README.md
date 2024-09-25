[![translate](https://img.shields.io/badge/For_English_CLICK_Here-English_Click_here?style=flat-square&logo=googletranslate&labelColor=white&color=blue)](https://github-com.translate.goog/Noxi-root/Turkce-C-Cheat-Sheet?_x_tr_sl=tr&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp)

>❓ Yardım almak için **__Discord__** üzerinden ulaşabilirsiniz: **n_oxxi**
<br></br>
>⭐ C'nin neredeyse tüm önemli konularını ele almaya çalıştım bu rehber size yardımcı olduysa bana destek olmak için `Star` butonuna tıklamanız yeterlidir.
<br></br>
>😊 Arkadaşlarınıza **__PAYLAŞMAKTAN__** çekinmeyin

---

<h1 align="center">C CheatSheet</h1>

Bu C CheatSheet sayfası, size C dilinin sözdiziminin hızlı bir tekrarını sağlamayı amaçlamaktadır. Sınavlarından hemen önce sözdiziminin hızlı bir şekilde tekrarına ihtiyaç duyan öğrenciler veya profesyonellerin C dili sözdizimine hızlıca bakmaları için faydalı olacaktır. Temel bilgilerle başlayalım ve C programlamanın daha karmaşık yönlerine doğru ilerleyelim.

### Index
* [Temeller](#temeller)
* [Kazan Plakası](#kazan-plakası-kodu)
* [printf](#printf-işlevi)
* [scanf](#tarama-işlevi-scanf)
* [Tek satır yorumu](#tek-satır-yorumu)
* [Çok satırlı yorum](#çok-satırlı-yorum)
* [Veri türleri](#veri-türleri)
* [Karakter türü (Character)](#karakter-türü-character)
* [Tamsayı türü (Integer)](#tamsayı-türü-integer)
* [Şamandıra tipi (float)](#şamandıra-tipi-float)
* [Çift tip (double)](#çift-tip-double)
* [Geçersiz tip (Void)](#geçersiz-tip-void)
* [Kaçış Dizileri](#kaçış-dizileri)
* [Alarm veya Bip](#alarm-veya-bip)
* [Geri Boşluk](#geri-boşluk)
* [Form feed](#form-feed)
* [Newline](#newline)
* [Taşıma iadesi (Carriage return)](#taşıma-iadesi-carriage-return)
* [Sekme (Tab)](#sekme-tab)
* [Ters Eğik Çizgi (Backslash)](#ters-eğik-çizgi-backslash)
* [Tek teklif (Single quote)](#tek-teklif-single-quote)
* [Soru işareti (Question mark)](#question-mark)
* [Sekizli No. (Octal No.)](#sekizli-no-octal-no)
* [Onaltılık No. (Hexadecimal No.)](#onaltılık-no-hexadecimal-no)
* [Null](#null)
* [if](#if)
* [if-else](#if-else)
* [if else-if](#if-else-if)
* [İç içe if-else](#iç-içe-if-else)
* [Switch Case](#switch-case)
* [while döngüsü (loop)](#while-döngüsü-loop)
* [do-while döngüsü](#do-while-döngüsü)
* [for döngüsü (loop)](#for-döngüsü-loop)
* [Mola (break)](#mola-break)
* [Devam (continue)](#continue-devam)
* [Function Definition](#işlev-tanımı-function-definition)
* [Function Call](#işlev-çağrısı-function-call)
* [return_type](#fonksiyonlarda-dönüş-tipi-return_type)
* [C fonksiyonlarında parametreler](#c-fonksiyonlarında-parametreler)
* [Pointers](#pointers-işaretçiler)
* [Pointer değişkeninin referansını alma](#işaretçi-pointer-değişkeninin-referansını-alma)
* [Diziler (Arrays)](#diziler-arrays)
* [Strings](#teller-strings)
* [gets ()](#gets)
* [puts ()](#puts)
* [fgets ()](#fgets)
* [String Functions](#dize-işlevleri-string-functions)
* [strlen ()](#strlen)
* [strcpy ()](#strcopy)
* [strcat ()](#strcat)
* [strcmp ()](#strcmp)
* [strlwr ()](#)
* [strupr ()](#strupr)
* [strrev ()](#strrev)
* [Yapı sözdizimi (Structure syntax)](#yapı-sözdizimi-structure-syntax)
* [typedef](#typdef-anahtar-sözcüğü)
* [FILE Pointer](#file-pointer)
* [Dosya açma](#dosya-açma)
* [fscanf ()](#fscanf)
* [fprintf ()](#fprintf)
* [fgetc ()](#fgetc)
* [fputc ()](#fputc)
* [Dosyayı kapatma](#dosyayı-kaptma)
* [malloc ()](#malloc)
* [calloc ()](#calloc)
* [Serbest Fonksiyon (free function)](#serbest-fonksiyon-free-function)
* [realloc ()](#realloc)

## Temeller
C programlama dilinden temel söz dizimi ve işlevler.

## Kazan plakası Kodu
```
#include<stdio.h> // başlık dosyaları
int main() // ana fonksiyon
{
    // kodunuz buraya
    return(0); // int main()'e değer döndürme
}
```
## printf işlevi
Çıktıyı ekranda göstermek için kullanılır
```
printf("Hello World!");
```
## tarama işlevi (scanf)
Kullanıcıdan girdi almak için kullanılır
```
scanf("biçim_belirleyicisi", &değişkenler)
```
Biz "adresi" temsil etmek için değişken adı ile ve kullanın. Sözdizimi şu şekilde çalışır:
```
int a;
scanf("%d",&a); // Klavye girişini adresli bir değişkende saklayın (a veya &a adresi)
printf("%d",a);
```
## Yorumlar
Yorum, derleyici tarafından yürütülmeyen bir koddur ve programcı, kodun işlevselliği hakkında okunabilirlik ve gelecekteki bakıma yardımcı olan açıklamalar veya hatırlatmalar sağlayarak kodlarına açıklama eklemek için kullanır.

## Tek satır yorumu
```
// Bu tek satırlık bir yorumdur
```
## Çok satırlı yorum
```
/* Bu bir
çok satırlı
yorumdur
*/
```
## Veri türleri
Veri türü, tamsayılar, kayan nokta sayıları, karakterler veya daha karmaşık yapılar gibi bir değişkende depolanabilecek veri türünü tanımlar. Verilerin program içinde nasıl saklandığını, yorumlandığını ve manipüle edildiğini belirler.

## Karakter türü (Character)
Genellikle tek bir sekizli (bir bayt) olarak temsil edilen karakter türü, tek tek karakterleri C programlama dilinde saklamak için kullanılır.
```
char değişken_adı;
```
C'deki bir karakter için biçim belirteci "% c" dir. Bir karakter yazdırmak için, bu belirteci printf işlev, sözdizimini takip ederek:
```
char x;
scanf(" %c",&x);
printf("karakter %c'dir",x)
```
## Tamsayı türü (Integer)
Ondalık olmayan sayısal değerleri saklamak için bir tamsayı türü kullanılır
```
int değişken_adı;
```
Bir tamsayının (integer) biçim belirteci "% d"
```
int a;
scanf("%d",&a);
printf("%d",a);
```
## Şamandıra tipi (float)
Ondalık sayısal değerleri saklamak için kayan nokta türü kullanılır
```
float değişken_adı;
```
float biçim belirteci "% f"
```
float b;
scanf("%f",&b);
printf("%f",b);
```
## Çift tip (double)
Çift hassasiyetli kayan nokta değerini saklamak için çift kullanırız.
```
double değişken_adı;
```
double biçim belirteci "% lf"
```
double ch;
scanf("%lf",&ch);
printf("%lf",ch);
```
## Geçersiz tip (Void)
C'deki boşluk türü, bir türün yokluğunu temsil eder. İşlev bildirimlerinde genellikle işlevin herhangi bir değer döndürmediğini belirtmek için kullanılır. Örneğin:
```
void myFunction() {
  // Fonksiyon kodu buraya
}
```
Bu bağlamda, void anahtar kelime şunu gösterir: myFunction bir değer döndürmez. Bir işlevin bağımsız değişken almadığını belirtmek için işlev parametreleri için de kullanılabilir

## Kaçış Dizileri
C'deki kaçış dizileri, ters eğik çizgi ile başlayan karakterlerin kombinasyonlarıdır ( \ ) ve doğrudan yazılamayan karakterleri temsil etmek için kullanılır. Bu diziler, dize değişmezleri veya karakter sabitleri içinde kullanıldığında özel bir şekilde yorumlanır.

Örneğin, kaçış sırası \n yeni satır karakterini temsil eder ve \t bir sekme karakterini temsil eder. İşte C dilinde kullanılan bazı kaçış sırası karakterleri.

## Alarm veya Bip
\a bip sesi çıkarır
```
#include<stdio.h>
int main()
{
    printf("\a"); // Bir bip sesi çıkarır
    return 0;
}
```
## Geri Boşluk
\ b bir geri boşluk ekler
```
#include<stdio.h>
int main()
{
    printf("Hello\bWorld"); // "HellWorld" şeklinde yazdırır
    return 0;
}
```
## Form feed
```
#include<stdio.h>
int main()
{
    printf("Page break here\fContinue text"); // Sayfa sonu oluşturabilir ancak her yerde desteklenmez
    return 0;
}
```
## Newline
Newline Karakteri
```
#include<stdio.h>
int main()
{
    printf("Line one\nLine two"); // İki satır yazdırır
    return 0;
}
```
## Taşıma iadesi (Carriage return)
Kaçış sırası ile temsil edilen satır başı \r C programlama dilinde, imleç konumunu geçerli satırın başına sıfırlayan bir kontrol karakteridir. Herhangi bir karakteri silmez, ancak imleci satırın başına taşır. Önce "Merhaba" dizesi yazdırılır, ardından satır başı imleci satırın başına geri taşır ve "Merhaba" üzerine yazılan "Dünya" yazdırılır.
```
#include<stdio.h>
int main()
{ 
    printf("Hello\rWorld"); // "World" çıktısı verir ancak davranış işletim sistemine bağlı olarak değişebilir
    return 0;
}
```
## Sekme (Tab)
Sekme alanı verir
```
#include<stdio.h>
int main()
{
    printf("Tabbed\ttext"); // Bir sekme boşluğu ekler
    return 0;
}
```
## Ters Eğik Çizgi (Backslash)
Ters eğik çizgi ekler
```
#include<stdio.h>
int main()
{
    printf("\\"); // Ters eğik çizgi yazdırır
    return 0;
}
```
## Tek teklif (Single quote)
Tek bir tırnak işareti ekler
```
#include<stdio.h>
int main()
{
    printf("\'"); // Tek bir tırnak işareti yazdırır
    return 0;
}
```
## Soru işareti (Question mark)
Bir soru işareti ekler
```
#include<stdio.h>
int main()
{
    printf("\?"); // Tek bir soru işareti yazdırır
    return 0;
}
```
## Sekizli No. (Octal No.)
Sekizli sayının değerini temsil eder
```
#include<stdio.h>
int main()
{
    printf("\101"); // Sekizli sistemde 101 olan 'A'yı yazdırır
    return 0;
}
```
## Onaltılık No. (Hexadecimal No.)
Onaltılık bir sayının değerini temsil eder
```
#include<stdio.h>
int main()
{
    printf("\x41"); // Onaltılık sistemde 41 olan 'A'yı yazdırır
    return 0;
}
```
## Null
Null karakteri genellikle bir dizeyi sonlandırmak için kullanılır
```
#include<stdio.h>
int main()
{
    printf("\0");
    char str[] = "Hello\0World"; // Boş karakter bir dizeyi sonlandırmak için kullanılır
    return 0;
}
```
## Şartlı Talimatlar (Conditional Instructions)
Koşullu ifadeler, bazı koşullara göre işlemleri gerçekleştirmek için kullanılır.

## if
```
if (/* durum */)
{
    /* kod */
}
```
## if-else 
```
if (/* durum */)
{
    /* kod */
}
else{
    /* kod */
}
```
## if else-if
```
if (durum) {
    // ifadeler;
}
else if (durum){
    // ifadeler;
}
else{
    // ifadeler
}
```
## iç içe if-else
```
if (/* durum */) {
    if (/* durum */) {
        /* kod */
    } else {
        /* kod */
    }
} else {
    /* kod */
}
```
## Switch Case
```
switch (ifade) {
    case sabit-ifade:
        ifade1;
        ifade2;
        break;
    case sabit-ifade:
        ifade;
        break;
    // ...
    default:
        ifade;
}
```
## Yinelemeli İfadeler (Iterative)
Yinelemeli ifadeler, programcıların herhangi bir kod satırı bloğunu tekrar tekrar yürütmelerini kolaylaştırır ve programcı tarafından eklenen koşullara göre kontrol edilebilir.

## while döngüsü (loop)
```
while (/* durum */)
{
    /* kod */
}
```
## do-while döngüsü
Çıkış kontrollü bir döngüdür. Bir farkla while döngüsüne çok benzer, yani do-while döngüsünün gövdesi, ifade yanlış olsa bile en az bir kez yürütülür
```
do
{
    /* kod */
} while (/* durum */);
```
## for döngüsü (loop)
İfadeleri veya programın bir bölümünü birkaç kez yinelemek için kullanılır. Dizi ve bağlantılı liste gibi veri yapılarını geçmek için sıklıkla kullanılır.
```
for (int i = 0; i < sayı; i++)
{
    /* kod */
}
```
## Mola (break)
Döngü içindeki anahtar sözcüğü kır, döngüyü sonlandırmak için kullanılır
```
#include <stdio.h>

int main() {
    for (int i = 0; i < 10; i++) {
        if (i == 5) {
            printf("Döngü şu anda bozuluyor i = 5\n");
            break; // i 5 olduğunda döngüden çık
        }
        printf("i = %d\n", i);
    }

    return 0;
}

```
Yukarıdaki kodun çıktısı:
```
i = 0
i = 1
i = 2
i = 3
i = 4
Döngü şu anda bozuluyor i = 5
```

## Continue (devam)
Devam anahtar sözcüğü döngünün geçerli yinelemesinin geri kalanını atlar ve döngünün başlangıç noktasına döner
```
#include <stdio.h>

int main() {
    for (int i = 1; i <= 10; i++) {
        if (i % 2 == 0) {
            continue; // Eğer i çift ise döngü gövdesinin geri kalanını atla
        }
        printf("%d ", i); // Tek sayıları yazdırır
    }
    return 0;
}

// Çıktı 1 3 5 7 9
```
## Functions & Recursion (Fonksiyonlar ve Özyineleme)
Fonksiyonlar, kapsamlı bir programı daha küçük parçalara bölmek için kullanılır. C programına yeniden kullanılabilirlik ve modülerlik sağlamak için birçok kez çağrılabilir.
## İşlev tanımı (Function Definition)
```
dönüş_tipi fonksiyon_adı(veri_tipi parametreler...){
//yürütülecek kod
}
```
## İşlev Çağrısı (Function Call)
```
fonksiyon_adı(parametreler...);
```
## fonksiyonlarda dönüş tipi (return_type)
İşlev döndürme ifadesi, belirtilen değeri veya veri öğesini arayan kişiye döndürür. Herhangi bir değer döndürmek istemiyorsak, işlev adını tanımlarken işlev adının önüne bir boşluk koyun.
```
dönüş_tipi fonksiyon_adı()
{
    return value;
}
```
## C fonksiyonlarında parametreler
Parametreler, tanımlarken ve çağırırken işlevin parantezinde geçirilen değerlerdir.
```
dönüş_tipi fonksiyon_adı(veri_tipi parametre...){ //parametrelerle fonksiyonları tanımlama
//yürütülecek kod
}
function_name(parametre...); //parametrelerle fonksiyonları çağırma
```
## Bir işlevi çağırmanın yolları
* Dönüş değeri ve parametrelerle
* Dönüş değeri ve parametrelerle
* Dönüş değeri ve parametresiz
* Dönüş değeri ve parametreler olmadan

## Recursion (Özyineleme)
Özyineleme, bir işlev küçük bir sorun üzerinde çalışmak için kendi bir kopyasını çağırdığında ortaya çıkar. Ve kendini çağıran işlev Özyinelemeli işlev olarak bilinir.
```
void recurse()
{
    ... .. ...
    recurse();
    ... .. ...
}
```
## Pointers (İşaretçiler)
İşaretçi, başka bir değişkenin adresini içeren bir değişkendir,

## Beyan (Declaration)
```
datatype *var_name;
```
İşaret değişkeninin adresini işaretçi değişkenine tahsis edebiliriz
```
#include <stdio.h>

int main() {
    int *ptr, x;
    x = 15;
    ptr = &x;

    // Bu, 15 değerini değil, x'in adresini yazdıracaktır
    printf("%p", ptr);

    return 0;
}
```
## İşaretçi (Pointer) değişkeninin referansını alma
```
#include <stdio.h>

int main() {
    int *ptr, x;
    x = 12;
    ptr = &x; // x'in adresini ptr'ye atayın
    printf("%d", *ptr); // x değerini yazdırmak için ptr'yi referanstan çıkarın

    return 0;
}
```
## Diziler (Arrays)
Dizi, aynı türdeki veri öğelerinin bir koleksiyonudur.

## Beyan (Declaration)
```
veri_tipi dizi_adı[dizi_boyutu];
```
örnek:
```
#include<stdio.h>                         
int main()                               
{
int arr[10];   
}
```
## Erişim öğesi (Accessing element)
```
veri_tipi değişken_adı = array[dizin];
```
## Teller (Strings)
Dize, null karakterle ('\ 0') sonlandırılmış 1-B karakter dizisidir.

## Beyan (Declaration)
```
char str_adı[boyutu];
```
## gets ()
Çok kelimeli bir dize girmenizi sağlar.
```
gets("string");
```
## puts ()
Dize çıktısını göstermek için kullanılır
```
puts("string");
```
## fgets ()
.gets() işlev güvensiz kabul edilir ve kullanımı daha iyidir fgets() yerine.
```
#include <stdio.h>

int main() {
    char str[50];
    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);
    printf("You entered: %s", str);
    return 0;
}
```
# Dize İşlevleri (String Functions)
## strlen ()
Dizenin uzunluğunu hesaplamak için kullanılır
```
strlen(string_adı);
```
## strcpy ()
İkinci dizenin içeriğini kendisine iletilen ilk dizeye kopyalamak için kullanılır
```
strcpy(hedef, kaynak);
```
## strcat ()
İki dizeyi birleştirmek için kullanılır
```
strcmp(birinci_string, ikinci_string);
```
## strcmp ()
İki dizeyi karşılaştırmak için kullanılır
```
strcmp(birinci_string, ikinci_string);
```
## strlwr ()
Dizelerin karakterlerini küçük harfe dönüştürmek için kullanılır
```
strlwr(string_adı);
```
## strupr ()
Dizelerin karakterlerini büyük harfe dönüştürmek için kullanılır
```
strupr(string_adı);
```
## strrev ()
Dizeyi tersine çevirmek için kullanılır
```
strrev(string_adı);
```
## Yapılar (Structures)
Yapı, tek bir ad altında farklı türlerde değişkenlerin bir koleksiyonudur. Yapıyı tanımlamak, yeni bir veri türü oluşturmak anlamına gelir.

## Yapı sözdizimi (Structure syntax)
```
struct structureName 
{
    dataType member1;
    dataType member2;
    ...
};
```
## typedef anahtar sözcüğü
typedef işlevi, kullanıcıların ilkel ve kullanıcı tanımlı veri türleri için alternatif adlar sağlamasına olanak tanır.
```
typedef struct structureName 
{
    dataType member1;
    dataType member2;
    ...
} new_name;
```
# Dosya İşleme (File Handling)

## DOSYA işaretçisi (FILE Pointer)
```
FILE *filePointer;
```
## Dosya açma
C'de bir dosya açmak için kullanılır.
```
filePointer = fopen(fileName.txt, w)
```
## fscanf ()
Bir dosyanın içeriğini okumak için kullanılır.
```
fscanf(FILE *stream, const char *format, ...)
```
## fprintf ()
Dosyaya içerik yazmak için kullanılır.
```
fprintf(FILE *fptr, const char *str, ...);
```
## fgetc ()
Okuma modunda açılan bir dosyadan bir karakter okur. Dosyanın sonuna ulaştığında EOF döndürür.
```
fgetc(FILE *pointer);
```
## fputc ()
Yazma modunda açılan bir dosyaya bir karakter yazar
```
fputc(char, FILE *pointer);
```
## Dosyayı kapatma
Dosyayı kapatır
```
fclose(filePointer);
```
# Dinamik Bellek Tahsisi
Yığından dinamik bellek ayırma için bir dizi işlev. Bu yöntemler, C programlarımızı daha verimli hale getiren dinamik belleği kullanmak için kullanılır

## malloc ()
'Bellek tahsisi' anlamına gelir ve verilen bayt miktarıyla bir bellek bloğu ayırır.
```
ptr = (castType*) malloc(size);
```
## calloc ()
'Sürekli tahsis' anlamına gelir ve verilen bayt miktarıyla n bellek bloğunu ayırır.
```
ptr = (castType*)calloc(n, size);
```
## Serbest Fonksiyon (free function)
Tahsis edilen belleği serbest bırakmak için kullanılır.
```
free(ptr);
```
## realloc ()
Ayrılan bellek yetersizse, verimlilik amacıyla bu işlevi kullanarak önceden ayrılmış belleğin boyutunu değiştirebiliriz
```
ptr = realloc(ptr, x);
```
