# Exercise 6 - JSON and XML

## JSON چیست؟

JSON مخفف **JavaScript Object Notation** است.

JSON یک فرمت متنی برای ذخیره و انتقال اطلاعات است و در APIها و برنامه‌های وب کاربرد زیادی دارد.

## XML چیست؟

XML مخفف **Extensible Markup Language** است.

XML نیز برای ذخیره و انتقال اطلاعات استفاده می‌شود و اطلاعات را با استفاده از Tagها نمایش می‌دهد.

## کاربرد JSON و XML

از JSON و XML می‌توان برای موارد زیر استفاده کرد:

* انتقال اطلاعات بین Client و Server
* ارتباط بین APIها
* ذخیره اطلاعات
* انتقال اطلاعات بین برنامه‌های مختلف

## تفاوت JSON و XML

### JSON

* ساختار ساده و خوانایی دارد.
* معمولاً حجم کمتری نسبت به XML دارد.
* در APIها و برنامه‌های وب بسیار رایج است.
* پردازش آن معمولاً ساده‌تر است.

### XML

* از Tagها برای نمایش اطلاعات استفاده می‌کند.
* معمولاً حجم بیشتری نسبت به JSON دارد.
* ساختار آن می‌تواند پیچیده‌تر باشد.
* در برخی سیستم‌ها و سرویس‌ها استفاده می‌شود.

## Student با JSON

```json
{
  "name": "Ali",
  "studentId": 1001,
  "age": 20,
  "major": "Computer Engineering"
}
```

## Student با XML

```xml
<Student>
    <Name>Ali</Name>
    <StudentId>1001</StudentId>
    <Age>20</Age>
    <Major>Computer Engineering</Major>
</Student>
```
