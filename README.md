# OS8
zahra amini 97440289
سوال 1:
1- chmod 397 
این دستور نامعتبر است چون سطح دسترسی باید بین 0 تا 7 باشد
2- chmode 440
یوزر و گروه فقط اجازه خواندن دارند و دیگران هیچ مجوز دسترسی ندارند
3- chmod a=rx file1
همه مجوز ها قبلی برای همه لغو میشه سپس به همه افراد مجوز خواندن و اجرا کردن فایل1 داده میشه اما اجازه نوشتن ندارند
4- chmod g=w sample
مجوزهای قبلی گروه لغو میشه و به گروه اجازه نوشتن در سمپل داده میشود ولی اجازه خواندن و اجرا کردن ندارند
5- chmod r+x sample
دستور نا معتبر است 
6- chmod u+g test 
تمام مجوز ها ی دسترسی گروه رو به یوزر هم میدهد

سوال 2:
chmode -R
بصورت بازگشتی به فایل ها و دایرکتوری ها اجازه دسترسی میدهد
chmod -c
تغییرات جدید را نمایش میدهد
chmod -v 
تغییرات سطح دسترسی را نمایش میدهد
