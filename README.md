# cxGridToPersian
ترجمه گرید دواکسپرس به فارسی.
در صورت نیاز برای انجام تغییرات میتوانید فایل cxLocalizerEditor.exe را از محل نصب کامپوننت های دواکسپرس اجرا نموده و این فایل رو باز کرده و تغییر دهید.
یک کامپوننت cxLocalizer بر روی فرم اصلی یا دیتاماژول قرار دهید. سپس :
<div dir="ltr">
<br>cxLocalizer1.FileName := 'path_to_file\' + 'cxPersian.ini';
<br>cxLocalizer1.Active := True;
<br>cxLocalizer1.Locale := 1065;
</div>
