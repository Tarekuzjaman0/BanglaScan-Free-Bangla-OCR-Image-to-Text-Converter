# BanglaScan - বাংলা OCR ওয়েব অ্যাপ

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

`BanglaScan` একটি আধুনিক এবং রেস্পন্সিভ ওয়েব অ্যাপ্লিকেশন যা ছবি থেকে বাংলা (Bengali) টেক্সট استخراج (OCR) করতে পারে। এটি সম্পূর্ণভাবে ব্রাউজারে চলে, কোনো সার্ভারের প্রয়োজন হয় না। এই প্রজেক্টটি Tesseract.js এর শক্তিকে একটি সুন্দর, গ্লাসিজম (Glassmorphism) ইউজার ইন্টারফেসের সাথে যুক্ত করে।

![BanglaScan Demo 1](https://github.com/Tarekuzjaman0/BanglaScan-Free-Bangla-OCR-Image-to-Text-Converter/raw/main/screenshot1.png)
![BanglaScan Demo 2](https://github.com/Tarekuzjaman0/BanglaScan-Free-Bangla-OCR-Image-to-Text-Converter/raw/main/screenshot2.png)

## ✨ ফিচারসমূহ

* **সম্পূর্ণ ক্লায়েন্ট-সাইড:** কোনো সার্ভার আপলোড নেই, সব প্রসেসিং ইউজারের ব্রাউজারেই হয়। এটি দ্রুত এবং সর্বোচ্চ গোপনীয়তা নিশ্চিত করে।
* **মাল্টি-ফাইল আপলোড:** একবারে একাধিক (৩০+) ইমেজ প্রসেস করার সুবিধা।
* **নির্ভুল বাংলা OCR:** লেটেস্ট [Tesseract.js](https://github.com/naptha/tesseract.js) ইঞ্জিন ব্যবহার করে ছবি থেকে বাংলা লেখা বের করা।
* **আধুনিক UI/UX:** সাদা গ্লাসিজম (White Glassmorphism) এবং মেটেরিয়াল ডিজাইনের সমন্বয়ে তৈরি ইউজার ইন্টারফেস।
* **সম্পূর্ণ রেস্পন্সিভ:** মোবাইল, ট্যাবলেট এবং ডেস্কটপ—সকল ডিভাইসে সুন্দরভাবে কাজ করে।
* **রিয়েল-টাইম স্ট্যাটাস:** প্রতিটি ফাইল প্রসেসিং এর লাইভ স্ট্যাটাস এবং প্রোগ্রেস দেখায়।

## 🛠️ ব্যবহৃত প্রযুক্তি

* **Frontend:** HTML5, CSS3
* **JavaScript:** Vanilla JavaScript (ES6+)
* **OCR Engine:** [Tesseract.js (v5)](https://github.com/naptha/tesseract.js)
* **Design & Icons:** Google Fonts (Roboto), Material Icons

## 🚀 কিভাবে চালাবেন

এই প্রজেক্টটি চালানোর জন্য কোনো জটিল ইনস্টলেশনের প্রয়োজন নেই।

### ১. লোকালভাবে (Offline)

1.  এই রিপোজিটরিটি ক্লোন (Clone) করুন:
    ```bash
    git clone [https://github.com/Tarekuzjaman0/BanglaScan-Free-Bangla-OCR-Image-to-Text-Converter.git](https://github.com/Tarekuzjaman0/BanglaScan-Free-Bangla-OCR-Image-to-Text-Converter.git)
    ```
2.  প্রোজেক্ট ফোল্ডারে যান:
    ```bash
    cd BanglaScan-Free-Bangla-OCR-Image-to-Text-Converter
    ```
3.  `pro_ocr.html` (বা আপনার দেওয়া নামটি) ফাইলটি সরাসরি যেকোনো আধুনিক ব্রাউজারে (যেমন: Chrome, Firefox) খুলুন।

### ২. GitHub Pages (লাইভ ডেমো)

আপনি খুব সহজেই এই প্রজেক্টটি GitHub Pages-এ বিনামূল্যে হোস্ট করতে পারেন:

1.  আপনার রিপোজিটরির **Settings**-এ যান।
2.  বাম পাশের মেনু থেকে **Pages**-এ ক্লিক করুন।
3.  **Source** হিসেবে 'Deploy from a branch' সিলেক্ট করুন।
4.  **Branch** হিসেবে `main` (বা `master`) সিলেক্ট করে `/root` ফোল্ডার রেখে **Save** করুন।
5.  কয়েক মিনিট পর আপনার প্রজেক্টটি একটি লাইভ URL-এ পাবলিশ হয়ে যাবে।

## 📄 লাইসেন্স

এই প্রজেক্টটি [MIT License](LICENSE)-এর অধীনে লাইসেন্সপ্রাপ্ত।

## 🙏 কৃতজ্ঞতা

* [Tesseract.js](https://github.com/naptha/tesseract.js) টিমের প্রতি, এমন একটি অসাধারণ ক্লায়েন্ট-সাইড OCR লাইব্রেরি তৈরির জন্য।
