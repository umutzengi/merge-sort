<h1>Merge Sort Projesi</h1>

<h2>[16, 21, 11, 8, 12, 22] dizisinin Merge Sort'a göre adımları;</h2>

1.Öncelikle diziyi tek eleman kalıncaya kadar ikili parçalara ayıracağız.
<ul>
<li>[16, 21, 11] --- [8, 12, 22]</li>
<li>[16] --- [21, 11] --- [8] --- [12, 22]</li>
<li>[16] --- [21] --- [11] --- [8] --- [12] --- [22]</li>
</ul>
  
2.Şimdi birleştirme işlemine sayısal değeri küçük olan elemanla başlayacağız;
<ul>
<li>[16] --- [11, 21] --- [8] --- [12, 22]</li>
<li>[11, 16, 21] --- [8, 12, 22]</li>
<li>[8, 11, 12, 16, 21, 22]</li>
</ul>

<h2>Big O gösterimi;</h2>

<li>Diziyi parçalara ayırırken sürekli 2'ye böldüğümüz için; 2^x = n => logn,</li>
<li>Birleştirme yaparken ise elemanların birbirlerine göre karşılaştırmasını yapmanın maliyeti n - 1 => n,</li>
<li>Bütun bu işlemlerin BigO gösterimi: O(n * logn)</li>
