# 🎬 React Native Film Rehberi (Movie App)

Bu proje, React Native temellerini ve API entegrasyonunu öğrenmek/pekiştirmek amacıyla geliştirilmiş, tek ekranlı durum yönetimi (state management) ile çalışan bir mobil sinema uygulamasıdır. Veriler [The Movie Database (TMDB) API](https://www.themoviedb.org/) üzerinden anlık olarak çekilmektedir.

## ✨ Özellikler

*   **Popüler Filmler:** Uygulama açıldığında TMDB veritabanındaki en popüler filmler listelenir.
*   **Arama Motoru:** Üst kısımdaki arama çubuğu ile tüm filmler veritabanında Türkçe olarak aranabilir.
*   **Detay Ekranı:** Harici bir navigasyon kütüphanesi kullanılmadan, tamamen `useState` mantığı ile sayfalar arası geçiş sağlanır. Filmin afişi, puanı, vizyon tarihi ve Türkçe özeti görüntülenebilir.
*   **Platform Bağımsız:** Expo sayesinde hem iOS hem de Android cihazlarda sorunsuz çalışır.

## 🛠️ Kullanılan Teknolojiler

*   **React Native & Expo:** Hızlı mobil geliştirme arayüzü.
*   **JavaScript (ES6+):** Temel programlama dili.
*   **Fetch API:** Sunucu istekleri ve JSON veri işleme.
*   **React Hooks:** `useState` ve `useEffect` ile hafıza/yaşam döngüsü yönetimi.

## 🚀 Nasıl Çalıştırılır?

Bu projeyi bilgisayarına hiçbir şey kurmadan doğrudan tarayıcı üzerinden test edebilirsin:

1. Kodu kopyala.
2. [Expo Snack](https://snack.expo.dev/)'e git.
3. `App.js` içine yapıştır ve sağdaki panelden önizlemeyi başlat!

> **Not:** Uygulamanın çalışması için kod içindeki `API_KEY` değişkenine kendi TMDB API anahtarınızı girmeniz gerekmektedir.
