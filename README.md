# Restaurant Sales Report

Hangi zaman da hangi yemek daha çok satılıyor.
satışlar sabah mı akşam mı
nakit mi kredi kartı mı

1. Satış miktarı tahmin etme. (Quantity)

# Amaç
Amacımız, veri kümemizde bulunan çeşitli bilgileri kullanarak "quantity" (miktar) sütunundaki değerleri tahmin etmek için bir yöntem geliştirmektir. Bu tahminleme süreci, sipariş tarihi, ürün adı, ürün tipi, fiyatı, işlem tipi gibi diğer sütunlardaki verilerin analizine dayanacaktır.

Öncelikle, makine öğrenimi modeli oluşturarak ve bu modeli eğiterek geçmiş verilerden öğrenmeyi planlıyoruz. Bu model, geçmiş alışveriş verilerinden elde ettiği bilgilerle yeni siparişlerin "quantity" değerlerini tahmin etme yeteneğine sahip olacak şekilde tasarlanacaktır.

Ayrıca, elde edilen modeli kullanarak, müşteri profillerini anlamak ve yeni müşteri siparişlerinin olası miktarlarını tahmin etmek istiyoruz. Örneğin, geçmiş alışveriş alışkanlıklarına dayanarak, belirli müşteri gruplarının muhtemel sipariş miktarlarını tahmin edebiliriz.

Bu çalışma aynı zamanda, işletmenin operasyonel süreçlerini iyileştirmek ve müşteri memnuniyetini artırmak için değerli içgörüler sunmayı hedeflemektedir. Veri analizi ve makine öğrenimi tekniklerini kullanarak, veri kümemizdeki bilgileri derinlemesine inceleyerek işletme performansını optimize etmeyi ve müşteri hizmetlerini iyileştirmeyi amaçlıyoruz.

## Sütunlar

- order_id: a unique identifier for each order.
- date: date of the transaction.
- item_name: name of the food.
- item_type: category of item (Fastfood or Beverages).
- item_price: price of the item for 1 quantity.
- Quantity: how much quantity the customer orders.
- transaction_amount: the total amount paid by customers.
- transaction_type: payment method (cash, online, others).
- received_by: gender of the person handling the transaction.
- time_of_sale: different times of the day (Morning, Evening, Afternoon, Night, Midnight).

