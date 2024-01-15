# Fedora Linux
এই অংশে পাঠক Fedora Linux ডিস্ট্রোতে iBus এবং fcitx IM কনফিগার করার দিকনির্দেশনা পাবেন।
**(`কোডব্লক` এর মধ্যকার লেখা টার্মিনালে রান করার কমান্ড নির্দেশ করে।)**

## iBus ইন্সটল
নিম্নে উল্লেখিত দিকনির্দেশনা অনুসরণ করার মাধ্যমে পাঠক iBus কনফিগার করতে পারবেন।

- প্রয়োজনীয় প্যাকেজ ইন্সটল করা।

```
sudo dnf install ibus ibus-gtk\* ibus-qt\* ibus-wayland\* --exclude=\*devel
```

- iBus কার্যকর আছে তা নিশ্চিত করা।

```
ibus-setup
```

## fcitx ইন্সটল
নিম্নে উল্লেখিত দিকনির্দেশনা অনুসরণ করার মাধ্যমে পাঠক fcitx কনফিগার করতে পারবেন।

- প্রয়োজনীয় প্যাকেজ ইন্সটল করা।

```
sudo dnf install fcitx fcitx-configtool fcitx-gtk\* fcitx-qt\* --exclude=\*devel
```

- iBus কার্যকর আছে তা নিশ্চিত করা।

```
fcitx5-configtool
```