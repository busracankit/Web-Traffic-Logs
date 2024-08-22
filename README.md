Web Trafik Loglarına Dayalı Yapay Zeka Destekli Soru-Cevap Sistemi
Bu proje, web trafik loglarını kullanarak bir yapay zeka destekli soru-cevap (Q&A) sistemi geliştirmeyi amaçlamaktadır. Sistem, web sunucusundan gelen günlük kayıtlarını analiz ederek doğal dildeki kullanıcılardan gelen sorulara doğru cevaplar vermeyi hedefler.

Özellikler
Veri Hazırlığı: Faker kütüphanesi ile sahte log verileri oluşturulur.
Veri Analizi: Log verileri pandas kullanılarak işlenir ve temizlenir.
Vektörleme: TF-IDF ve FAISS kullanılarak log kayıtları vektörlere dönüştürülür.
RAG Modeli: T5 modelini kullanarak kullanıcı sorularına uygun cevaplar oluşturulur.
Test ve Değerlendirme: Performans değerlendirmesi ve doğruluk analizi yapılır.
Kurulum ve Kullanım
Gereken kütüphaneleri yükleyin: pip install faker pandas scikit-learn faiss-cpu transformers torch.
Web trafik loglarını oluşturun ve işleyin.
Modeli eğitin ve yanıtları değerlendirin.
Zorluklar ve İyileştirmeler
Veri hazırlığı, performans sorunları ve model entegrasyonu gibi zorluklarla karşılaşıldı. Yanıt kalitesini artırmak için algoritma ve veri analizinde iyileştirmeler yapılması önerilmektedir.
