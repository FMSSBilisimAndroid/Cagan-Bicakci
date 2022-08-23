# DiceRoller
Simple Dice Roller App

## Namespace Nedir?

  XML için kullanılan namespace XML içerisinde benzersiz olarak isimlendirilmiş ögeler ve özellikler sağlamak için kullanılır. XML bir etiketleme dilidir aslında. Programcı etiketleri eklerken farklı kaynaklarda aynı isimde etiketler de olabilir. Aslında namespace tanımı yapmak bu aynı isimli etiketlerin çakışmasını engeller.
  
  Namespace tanımlaması yapılırken bir ön ek ve URL veya URI olarak namespace ismi verilir. URI ve URL kullanılmasını sebebi ise namespacelerin tek olmasını sağlamak içindir. Hangisinin kullanılacağı tercih sebebidir.
  
  ```
  xmlns:android="http://schemas.android.com/apk/res/android"
  xmlns:tools="http://schemas.android.com/tools"
  ```
  
  Buna basit bir örnek vermek gerekirse; RecycleView içerisinde bir ImageView ve TextView tasarladığımızı varsayalım. ImageView ve TextView için sırasıyla şu şekilde bir özellik eklediğimizi düşünelim; "android:text="@string/test", "android:src="@string/source". Burada gösterilecek image soruce ve texti uygulama çalışınca API'dan gelen verilerden aldığımızı varsayarsak Image ve Texti UI'da görüntülemek için uygulamayı çalıştırmamız gerekiyor. Fakat tools namespace'ini kullanarak "tools:src=some_src" "tools:text=some_text" şeklinde eklediğimiz zaman uygulamayı çalıştırmadan direkt olarak UI'daki değişiklikleri görebilir ve daha hızlı bir şekilde UI geliştirmelerimizi yapabiliriz.
  
  Sonuç olarak namespace UI üzerinde bir şeyi veya bir adresi göstermez. Burada kullanılan prefixler aynı isimdeki etiketlerin hangi namespace'e ait olduğunu gösterir ve kullanılan etikette göre o özelliği kullanmamızı sağlar ve özellikler arasında karışıklığın da önüne geçer.
  
  
