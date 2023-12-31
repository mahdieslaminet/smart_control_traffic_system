# smart-control-traffic-system
سیستم هوشمند کنترل ترافیک 
### Read Me
لینک فیلم بک اند و اجرای پروژه :         
https://drive.google.com/drive/folders/1hjSYSZesWQOOvJAjXUo3i2X-3ND0eDB1?usp=sharing


# سامانه مدیریت ترافیک

این برنامه نمونه‌ای از یک سامانه مدیریت ترافیک است که از PyQt5 برای رابط کاربری گرافیکی، Pandas و NumPy برای کار با داده‌ها، و scikit-learn برای تحلیل خوشه‌بندی استفاده می‌کند.

## توضیحات

این برنامه شامل دو قسمت اصلی است: کلاس `TrafficManagementSystem` و کلاس `TrafficControlApp`.

### TrafficManagementSystem

کلاس `TrafficManagementSystem` شامل متدهایی برای مدیریت داده‌ها و عملکردهای مرتبط با ترافیک است:

- `collect_data()`: متد برای جمع‌آوری داده‌های ترافیک.
- `process_data(data)`: متد برای پردازش داده‌های جمع‌آوری شده.
- `read_data(input_path)`: متد برای خواندن داده‌های ورودی از یک فایل CSV.
- `optimize_k(df, k_range)`: متد برای بهینه‌سازی خوشه‌بندی KMeans.
- `run_kmeans(df, k)`: متد برای اجرای الگوریتم KMeans.
- `write_output(df, output_path)`: متد برای نوشتن داده‌های پردازش‌شده به یک فایل CSV.
- `execute_strategies(processed_data)`: متد برای اجرای استراتژی‌ها بر اساس داده‌های پردازش‌شده.
- `monitor_performance(strategies)`: متد برای نظارت بر عملکرد سیستم.
- `create_map()`: متد برای ایجاد یک نقشه.

### TrafficControlApp

کلاس `TrafficControlApp` نمایشگر رابط کاربری برای کنترل ترافیک است:

- این کلاس یک پنجره را با فیلدهای ورودی برای نام خیابان‌ها و زمان ایجاد می‌کند.
- متد `get_routes()` اطلاعات وارد شده را دریافت کرده و مسیر انتخابی را نمایش می‌دهد.

## استفاده

1. اطمینان حاصل کنید که PyQt5، pandas، NumPy، scikit-learn و folium در محیط شما نصب شده باشند.
2. اسکریپت را در پایتون اجرا کنید تا برنامه راه‌اندازی شود.


  گروه NE : علی شمس / حسین پاتیمار
  منتور پروژه : امیر صدرا نام آور
  استاد راهنما : دکتر مهدی اسلامی 
---
برای سوالات و اطلاعات بیشتر، با(hsyngzwz@gmail.com, alishmas8309@gmail.com) تماس بگیرید.
