محمد عرفان بدیعی
97440156



تمرین شماره 
5
1.
برای این که برای هر بار push  نیازی به وارد کردن هر بار user name  و password  نباشد میتوانیم از دستور زیر استفاده نماییم

git config --global user.name “name”

git config --global user.email “email”

که در دستورات بالا به جایname  نام کاربری و به جا email  ایمیلی که با آن اکانت درست شده است را تایپ میکنیم




2.

.gitignore:

فایل هایی که نمیخواهیم تغییر داده شوند یا آپلود شوند از این دستور استفاده مینماییم

.git:

باعث ایجاد تغییر در فایل میشود

git pull:

دانلود اخرین نسخه فایل های گیت هاب

branch:

مشخص کننده شاخه های repository




3.
ابتدا یک پوشه میسازیم با وارد کردن دستورcd foldername  وارد آن پوشه میشویم حال دستورات زیر را به ترتیب وارد میکنیم
git init

git add --all

git commit -m "comment”

git branch -M main

git remote add origin <Address>
  
git push -u origin main

در دستور خط سوم به جای comment  يک توضيح دلخواه برای فايل هایمان مينويسم
و در خط  پنجم به جايه address  آدرس صفحه repository  نوشته میشود




4.
با وارد کردن هریک دستورات زیر زمان بوت یا روشن شدن سیستم عامل لینوکس مشخص میشود


uptime

systemd-analyze
