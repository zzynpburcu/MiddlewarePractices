# Middleware Kavramı


Middleware yani ara katman client tarafından bir request gönderildiğinde request'e karşılık response dönene kadar geçen sürede yapılması gereken işlemler için process'in arasına girmeyi sağlayan yapılardır. Request ve response arasına girip işlem yapmamıza olanak sağlamasının yanında, bu aralığa çoklu işlemler de dahil edebiliriz. Bu işlemlerin hangi sırayla yapılacağını da belirleyebiliriz.



## .Net5'de Middleware Yapısı
.Net5 içerisindeki middleware'ler Startup sınıfı içerisinden Configure metodu içinde saklanır. Middleware'lerin çalışacağı pipeline ı bu metot içerisinde belirleriz.
