##Install

       git clone https://github.com/meysam-kurd/TabChi-master/
       cd TabChi-master
       chmod 777 install.sh
       ./install.sh

******  
 
##Create a bot
   
        python3 creator.py
        
Enter Tabchi ID : 111
Enter Full Sudo ID : 123456
  
   
Then
        ./tabchi-111.sh

*****
         
##Anti crash

        tmux new-session -s script "bash tabchi-111.sh"
        
*****    

Enter id of tabchi in "ID" part (it can be anything but should be unique)

Enter your telegram Id in "Full Sudo ID" part

Enjoy Your New Bot!

You can stop the script by pressing Control+C in the script session. Alternatively, you can tmux kill-session -t script or also killing all tmux processes killall tmux

```
killall screen
killall tmux
```


#Important
##Dont Forget


***

##Run
   
Use `./tabchi-ID.sh` to run your bot normaly or use `screen ./tabchi-ID.sh` for auto launch mode (put tabchi-id in ID part)

##Help and more

/pm <userid> <text>
ارسال <text> به <userid> بطور مارک داون

/block <userid>
بلاک کردن <userid> از خصوصی ربات

/unblock <userid>
آن بلاک کردن <userid> از خصوصی ربات

/panel
پنل مدیریت ربات

/addsudo <userid>
اضافه کردن <userid> به صاحبان ربات

/remsudo <userid>
حذف <userid> از صاحبان ربات

/bc <text>
ارسال <text> به همه چت ها

/fwd <all/users/gps/sgps> (on reply)
فوروارد پیام به همه/کاربران/گروه ها/سوپر گروه ها

/lua <str>
پردازش <str> به عنوان کد لوا

/echo <text>
باز گرداندن <text>

/addedmsg <on/off>
اگر روشن باشد بعد ازارسال مخاطب در گروه پیامی مبنی بر ذخیره شدن شماره مخاطب

/setaddedmsg <text>
شخصی سازی متن ذخیره شده

/markread <on/off>
⁧روشن یا خاموش کردن بازدید پیام ها

/setanswer '<word>'  <text>
تنظیم <text> به عنوان جواب اتوماتیک <word>

 نکته:‌<word> باید داخل '' باشد

/delanswer <word>
حذف جواب مربوط به <word>

/answers
لیست جواب های اتوماتیک

/addmembers
اضافه کردن اعضای ربات به گروه

/links
دریافت لینک های ذخیره شده توسط ربات

/contactlist
دریافت مخاطبان ذخیره شده توسط ربات


##Developers

*[open by (MEYSAM)](https://telegram.me/M3YS4M)

###Powered by [M3YS4M](https://telegram.me/M3YS4M)



/panel
پنل مدیریت ربات

/addsudo <userid>
اضافه کردن <userid> به صاحبان ربات

/remsudo <userid>
حذف <userid> از صاحبان ربات

/bc <text>
ارسال <text> به همه چت ها

/fwd <all/users/gps/sgps> (on reply)
فوروارد پیام به همه/کاربران/گروه ها/سوپر گروه ها

/lua <str>
پردازش <str> به عنوان کد لوا

/echo <text>
باز گرداندن <text>

/addedmsg <on/off>
اگر روشن باشد بعد ازارسال مخاطب در گروه پیامی مبنی بر ذخیره شدن شماره مخاطب

/setaddedmsg <text>
شخصی سازی متن ذخیره شده

/markread <on/off>
⁧روشن یا خاموش کردن بازدید پیام ها

/setanswer '<word>'  <text>
تنظیم <text> به عنوان جواب اتوماتیک <word>

 نکته:‌<word> باید داخل '' باشد

/delanswer <word>
حذف جواب مربوط به <word>

/answers
لیست جواب های اتوماتیک

/addmembers
اضافه کردن اعضای ربات به گروه

/exportlinks
دریافت لینک های ذخیره شده توسط ربات

/contactlist
دریافت مخاطبان ذخیره شده توسط ربات


##Developers

*[open by (meysamkurd)](https://telegram.me/m3ys4m)

###Powered by [meysamkurd](https://telegram.me/m3ys4m)

Telegram Id : @M3YS4M

