---
github: "true"
---

### 

#### کیان:

بچه‌ها، یکی بهم میگه اصل KISS یعنی چی؟ 😅 یه جا خوندم "Keep It Simple, Stupid"، ولی گیج شدم!

#### پیمان:

کیان جان، نترس! اون "Stupid" توهین نیست، بیشتر یه شوخیه برای این‌که یادت بمونه ساده نگه داشتن چیزها بهتره. 😄

#### ماهان:

آره دقیقاً! بذار برات یه داستان بگم. فرض کن می‌خوای یه دوچرخه بسازی. 🚲

#### کیان:

خب، دارم گوش می‌دم! 🎧

#### حسین:

حالا فکر کن یه نفر می‌خواد این دوچرخه رو خیلی خفن کنه. مثلاً براش دکمه‌ی تنظیم سرعت وای‌فای بزاره، یا چراغ‌هایی که با صدا روشن شن! 😅

#### مارال:

آخرش چی میشه؟ دوچرخه‌ش اینقدر پیچیده میشه که دیگه حتی رکاب زدن هم سخت میشه! 😵

#### کیان:

اوه، یعنی انقدر شلوغش کرده که دیگه نمی‌شه ازش استفاده کرد؟

#### پیمان:

دقیقاً! اصل KISS می‌گه: «همیشه تا جایی که می‌تونی، ساده نگهش دار!» چون طراحی ساده‌تر، بهتر کار می‌کنه و راحت‌تر هم می‌فهمیش. 💡

#### ماهان:

توی برنامه‌نویسی هم همینه. مثلاً اگه قراره یه تابع فقط جمع دو عدد رو حساب کنه، دیگه لازم نیست توش ۵۰ تا شرط و حلقه بذاری! 😂

#### حسین:

هر چی کدت ساده‌تر باشه، کمتر باگ می‌خوره، راحت‌تر تست میشه، و آدمای دیگه هم سریع‌تر می‌تونن بخوننش. ✨

#### کیان:

پس یعنی اصل KISS می‌گه پیچیدگی اضافه نکنیم؟

#### مارال:

آفرین! بذار مثل یه آشپز ماهر فکر کنیم. اگه یه غذای خوشمزه رو می‌تونی با ۳ تا ماده درست کنی، چرا ۱۰ تا بریزی که فقط طعمش رو خراب کنه؟ 🍳

#### کیان:

چه باحال! یعنی تو کدنویسی هم باید مثل آشپزای ماهر عمل کنیم! ساده و خوشمزه! 😋

#### پیمان:


آره کیان جان! حالا اگه دیدی یه چیزی خیلی پیچیده شد، یه نفس بکش و بپرس: «می‌تونم ساده‌ترش کنم؟» این میشه روح KISS! 🧘‍♂️  
بذار برات یه مثال ساده هم بزنم که کامل جا بیفته:

فرض کن توی یه برنامه می‌خوایم یه تابع داشته باشیم که دو عدد `x` و `y` رو می‌گیره و حاصل جمعشون رو برمی‌گردونه.

در ساده‌ترین حالت ممکن، این تابع می‌تونه این‌طوری باشه:

<div dir="ltr">

```python
def sum(x, y):
    return x + y
```

</div>

این تابع خیلی ساده و سرراسته، معلومه چی‌کار می‌کنه و همون کار رو به بهترین شکل انجام می‌ده.

اما بعضی‌ها همین تابع رو اینطوری می‌نویسن:

<div dir="ltr">


```python
def sum(*args):
    sum_value = 0
    for i in args:
        sum_value += i 
    return sum_value
```

</div>
درسته که این نسخه هم کار می‌کنه و حتی انعطاف‌پذیرتره، ولی برای هدف ساده‌ای مثل جمع دو عدد، پیچیدگی غیرضروری داره.
هر چی کد ساده‌تر باشه، در آینده نگهداری و توسعه‌ش هم راحت‌تره.



#### کیان:

مرسی بچه‌ها! دیگه این KISS رو هیچ‌وقت فراموش نمی‌کنم. از حالا هر وقت یه چیز طراحی می‌کنم، می‌پرسم: آیا این واقعاً ساده‌ست؟ 🤓

