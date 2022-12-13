# selection-short-project
Selection_Short_Project

1-[22,27,16,2,18,6] -> Insertion Sort

  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2-Big-O gösterimini yazınız.

3-Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

  Average case: Aradığımız sayının ortada olması
  Worst case: Aradığımız sayının sonda olması
  Best case: Aradığımız sayının dizinin en başında olması.

4-[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

CEVAPLAR

1- Dizinin içerisinde en küçük eleman bulunur ve ilk sıradaki eleman ile yer değiştirilir. -> [2,27,16,22,18,6]
   Sonra dizi index değeri 1 artırılarak (yani 2.elemana geçerek) ikinci en küküç değer bulunur ve o index değerindeki sayı ile yer değiştirilir. -> [2,6,16,22,18,27]
   3.adımda zaten en küçük durum olduğu için dizi değişmez. -> [2,6,16,22,18,27]
   Sonraki adımda tekrar aynı iterasyonu uyguluyoruz. -> [2,6,16,18,22,27]
   Önceki adımdaki uygulamadan sonra diğer elemanların sıralaması uygun olduğu için dizinin son halini bulmuş oluyoruz.

2- Big-O=(n^2)

3- 18 elemanı dizinin orta sıralarında bulunduğu için "Average case" kapsamındadır.

4- Selection Sort en küçük elemanın sıraya yerleştirilmesi esasına dayanmaktadır.

   -> [2,3,5,8,7,9,4,15,6]
   -> [2,3,4,8,7,9,5,15,6]
   -> [2,3,4,5,7,9,8,15,6]
   -> [2,3,4,5,6,9,8,15,7]
   
