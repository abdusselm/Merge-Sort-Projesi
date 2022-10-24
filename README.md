# Merge-Sort-Projes
[Patika.Dev](https://www.patika.dev)
Bu Repostory'de Verilen Bir Dizinin Merge-Sort Algoritmasına Göre Aşamaları Gösterilmektedir

## Soru - 1
**[16,21,11,8,12,22]**
Yukarıda ki dizinin Merge-Sort Türüne Göre Aşamalarını Yazınız 

**1.Aşama (Parçalama Aşaması)**
Bu aşamada verilen dizi en az iki veya daha az sayıda kalacak şekilde sürekli bölünür.

1.[16,21,11]|[8,12,22]
2.[16,21],[11],[8,12],[22]

Dizinin parçalama işlemi bittikten sonra ikili veya birli gruplar kendi içlerinde kıyas edilirler ve dizi bölündüğü gibi
kendi içinde tekrar sıralanarak birleştirilir.

**2.Aşama (Birleştirme Aşaması)**

1.[11,16,21], [8,12,22]
2.[8,11,12,16,21,22]

## Soru - 2
**Big - O Gösterimini Yazınız**

Dizimizde n adet sayıda değişken olduğundan 2 lik tabanda
2ˣ=n olduğundan, yani algoritmanız n sayıda girdiyi 2ˣ=n kadar dolaşacağından
ama verilerin gruplu olarak birleştirilme aşamasında ilgili dizi de n kadar dolaşılacağından
bu algoritmanın Big O Notation'ı O(nlogn)'dir.