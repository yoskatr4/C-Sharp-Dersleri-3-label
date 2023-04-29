# C-Sharp-Dersleri-3-label
C Sharp Dersleri 3 (Label)

## Label Nedir
Kullanıcıya form üzerinde bilgi vermek için kullanılır. Bu nesneye kullanıcı tarafından bilgi girmek dışında
text kutusuna çok benzer.
• Text özelliği ile içindeki bilgilerin yerleşimi TextAlignözelliği ile belirlenebilir.

• Image özelliği ile Label içerisinde resim gösterilebilir.

• ImageAlign özelliği ile resmin yerleşmini belirleyebilirsiniz.

• ImageList ve ImageIndex özellikleri ilede resim gösterilebilir.

• Bu kontrolün önemli özelliklerinden biri AutoSizeözelliğidir. Bu özellik normelde false dir.

• Transbaran özelliğini kullanmak için BackColor veColor.Transparent değerlerini
kullanabilirsiniz.

## UseMnemonic
Bu özellik Label içinde bulunabilecek & karakterinin nasıl davranacağını belirler. Normalde bu özellik
true dur. Ve Text özelliğinde & karakterinden sonraki karakteri kısa yol tuşu yapar. Alt-E gibi.

## Bazı Label Özellikleri :
#### BackColor : Tahmin edebileceğiniz gibi Label’ın arka plan rengini ayarlar.

#### BorderStyle : Label’ın kenarlarının nasıl olacağını belirler.

#### Font : Font’unu ayarlamamıza yarar. Boyut,yazı tipi gibi özellikleri barındırır.

#### Text : Label’da ne yazacağını ayarlayan özelliktir.

#### TextAlign : Label’da yazan yazının nerede duracağına karar verir.

#### Örnek:  TextAlign = Left ,top,right gibi..

#### (Name) : Label’ın kod tarafında hangi isimle adlandırılacağını, çağırılacağını belirler.

#### Default olarak Form’a eklediğiniz kaçıncı label ise “label””kaçıncı label” şeklinde gelir.

#### Örnek: Biz ikinci bir label eklersek name i ‘label2’ olacaktır

#### AutoSize : Label’ın boyutunu ayarlamak için kullanılır.Bu özellik True olur ise; 

#### Label’ı tek boyutta kullanırız. Yani satır sonunda bir alt satıra geçip devam etmez, sürekli sağa doğru yazmaya devam eder. False yaparsak serbestlik kazanırız.
