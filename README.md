# Shakib — Personal Portfolio

সাধারণ পার্সোনাল পোর্টফোলিও ওয়েবসাইট — 3D অ্যানিমেশনসহ।
GitHub Pages দিয়ে ফ্রিতে লাইভ করা যাবে।

## ফাইলে যা আছে
- `index.html` — পুরো ওয়েবসাইট (একটাই ফাইল, CSS + JS ভেতরে আছে)
- `README.md` — এই নির্দেশনা

## 3D অ্যানিমেশন
- Hero-তে Three.js দিয়ে ঘূর্ণায়মান 3D Torus Knot + ভাসমান কণা (মাউস নাড়ালে ক্যামেরা ঘোরে)
- CSS 3D ঘূর্ণায়মান কিউব (S / 🔧 / 💧)
- প্রজেক্ট কার্ডে মাউস নাড়ালে 3D Tilt এফেক্ট
- স্ক্রল করলে সেকশনগুলো ভেসে ওঠে

ইন্টারনেট না থাকলে Three.js অংশটা শুধু বন্ধ থাকবে, বাকি সাইট আর CSS 3D ঠিকঠাক চলবে।

## GitHub-এ আপলোড করে ফ্রিতে লাইভ করার ধাপ (মোবাইল দিয়েই হবে)

### ১. GitHub অ্যাকাউন্ট খোলো
- github.com-এ যাও, Sign up করো (ইমেইল + পাসওয়ার্ড দিলেই হবে)

### ২. নতুন Repository বানাও
- উপরে **+** → **New repository**
- Repository name: `shakib-portfolio` (যেকোনো নাম চলবে)
- **Public** সিলেক্ট করো
- **Create repository**-এ ট্যাপ করো

### ৩. ফাইল আপলোড করো
- রিপোজিটরির ভেতরে **Add file → Upload files**
- এই ZIP থেকে `index.html` ফাইলটা আপলোড করো
- নিচে **Commit changes**-এ ট্যাপ করো

### ৪. GitHub Pages চালু করো
- রিপোজিটরির **Settings** → বামে **Pages**
- **Build and deployment → Source:** `Deploy from a branch`
- **Branch:** `main` আর ফোল্ডার `/ (root)` রেখে **Save** করো
- ১-২ মিনিট অপেক্ষা করো

### ৫. লাইভ লিংক পাবে
তোমার সাইট এই ঠিকানায় লাইভ হবে:
`https://তোমার-username.github.io/shakib-portfolio/`

যেমন username `shakib` হলে:
`https://shakib.github.io/shakib-portfolio/`

## নিজের তথ্য বদলাতে চাইলে
`index.html` ফাইলটা খুলে শুধু এই জায়গাগুলো বদলাও:
- নাম, পেশা, About লেখা
- স্কিল আর প্রজেক্টের লেখা
- Instagram লিংক: `https://www.instagram.com/sh.akib.71`
- ছবি যোগ করতে চাইলে `<img src="photo.jpg">` ব্যবহার করো, আর `photo.jpg` ফাইলটাও একই রিপোজিটরিতে আপলোড করো

## নোট
- এটা সম্পূর্ণ ফ্রি, কোনো টাকা লাগবে না।
- ফাইল বদলালে GitHub-এ আবার আপলোড করলেই লাইভ সাইট আপডেট হয়ে যাবে (১-২ মিনিট লাগে)।
