# Build instructions
Here you will find instructions on how to properly configure your preferred Linux-based OS distribution (or Distro for short) to compile OpenBangla Keyboard.
The next subchapters document how to manually compile OpenBangla Keyboard from source, alongside an automated buildscript called make-pkgs.

এখানে আপনি ওপেনবাংলা কিবোর্ড সোর্স থেকে কম্পাইল করার জন্য আপনার পছন্দসই লিনাক্স-ভিত্তিক অপারেটিং সিস্টেম ডিস্ট্রিবিউশনকে (অথবা সংক্ষেপে ডিস্ট্রোকে) সঠিকভাবে কনফিগার করার দিকনির্দেশনা পাবেন।
পরবর্তী সাবচ্যাপ্টারগুলোতে ওপেনবাংলা কিবোর্ডকে সোর্স থেকে ম্যানুয়ালি কম্পাইল করার পদ্ধতি এবং একইসাথে স্বয়ংক্রিয়ভাবে কম্পাইল করার জন্য "make-pkgs" নামক একটি স্বয়ংক্রিয় বিল্ডস্ক্রিপ্ট এর ব্যবহারপ্রনালি অন্তর্ভুক্ত করা হয়েছে।

## Build requirements of OpenBangla Keyboard
**(ওপেনবাংলা কিবোর্ড কম্পাইল করার জন্য যা প্রয়োজন)**

- GNU GCC, G++ compiler or Clang
- Rust 1.34.0 or later
- GNU Make or Ninja and Meson
- CMake
- Qt 5.5 or later
- iBus development library
- fcitx development library
- Zstandard compression library (zstd)