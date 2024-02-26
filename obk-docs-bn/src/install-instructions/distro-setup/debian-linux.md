# Debian GNU/Linux
এই অংশে পাঠক Debian GNU/Linux ডিস্ট্রোতে iBus এবং fcitx IM কনফিগার করার দিকনির্দেশনা পাবেন।
**(`কোডব্লক` এর মধ্যকার লেখা টার্মিনালে রান করার কমান্ড নির্দেশ করে।)**

## iBus ইন্সটল
নিম্নে উল্লেখিত দিকনির্দেশনা অনুসরণ করার মাধ্যমে পাঠক iBus কনফিগার করতে পারবেন।

- প্রয়োজনীয় প্যাকেজ ইন্সটল করা।

```
sudo apt install --install-recommends ibus
```

- iBus কার্যকর আছে কি না তা নিশ্চিত করা।

```
ibus-setup
```

## fcitx ইন্সটল
নিম্নে উল্লেখিত দিকনির্দেশনা অনুসরণ করার মাধ্যমে পাঠক fcitx কনফিগার করতে পারবেন।

- প্রয়োজনীয় প্যাকেজ ইন্সটল করা।

```
sudo apt --install-recommends fcitx5
```

- fcitx কার্যকর আছে কি না তা নিশ্চিত করা।

```
fcitx5-configtool
```
## Debian GNU/Linux এর ভার্সন খুঁজে বের করা 
নিচের কমান্ডটি টার্মিনালে রান করুন: 
```
lsb_release -a
```
আউটপুটটি এমন হবে: 
```
No LSB modules are available.
Distributor ID:	Debian
Description:	Debian GNU/Linux 12 (version_name)
Release:	version_number
Codename:	version_name 
```
এখানে ```version_name``` ও ```version_number``` হবে যথাক্রমে আপনার Debian ইন্সটলেশনের ভার্সনের নাম ও নাম্বার।    

## ওপেনবাংলা কিবোর্ড এর প্যাকেজ ডাউনলোড ও ইন্সটল করা  
[এখান](https://github.com/OpenBangla/OpenBangla-Keyboard/releases) থেকে আপনার ডিস্ট্রোর ভার্সন নাম ও নাম্বার অনুযায়ী ওপেনবাংলা কিবোর্ডের প্যাকেজ টি ডাউনলোড করুন।
উদাহরণস্বরূপ আপনার Debian ভার্সন যদি হয় 12 তবে আপনি ডাউনলোড করবেন ```OpenBangla-Keyboard_2.0.0-debian12.deb``` নামের প্যাকেজটি।  

প্যাকেজটি সহজে ইন্সটল করার জন্য ```gdebi``` ব্যবহার করতে পারেন। টার্মিনালে রান করুন:  
```
sudo apt install gdebi
```
এবার File Manager এ ডাউনলোড করা প্যাকেজটি খুঁজে বের করুন। এরপর, পাকেজটি রাইট ক্লিক করে "Open with GDebi Package Installer" সিলেক্ট করুন। 
এরপর Gdebi ওপেন হলে "Install Package" ক্লিক করুন।   
<screenshot> 

আপনার কম্পিউটারে এখন ওপেনবাংলা কিবোর্ড ইন্সটল হয়ে গিয়েছে। পরবর্তী নির্দেশনার জন্য DE-ভিত্তিক সেটআপ অংশটি দেখুন।   
