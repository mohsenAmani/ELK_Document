# ELK_Document
Document about ELK stack learning
 
<p align="center">
 <img alt="ELK-Logo" src="image/elk.png">
</p>

<p dir=rtl>
  گیت، یک سیستم کنترل نسخه منبع آزاد و رایگان است که در ابتدا Linus Torvalds  در سال 2005 ایجاد کرد.
</p>
<p dir=rtl>
گیت توزیع می شود: به این معنی که هر توسعه دهنده، تاریخچه ی کامل مخزن کد خود را به صورت محلی دارد. این باعث می شود که Clone اولیه مخزن کندتر شود، اما عملیات بعدی مانند Commit, blame, diff, Merge و Log سریع تر انجام می شود.
 </p>
 <p dir=rtl>
وی‌سی‌اس (سیستم کنترل نسخه) Version Control System یا به اختصار VCS به ابزاری اطلاق می‌گردد که این امکان را در اختیارمان می‌گذارد تا دست به مدیریت نسخه‌‌بندی یک پروژه بزنیم.
  </p>


<h3 dir=rtl>
  اصطلاحات رایج در Git:
</h3>

<table>
  <tr>
    <th><b><i>اصطلاح</i></b></th>
    <th><b><i>توضیحات</i></b></th>
  </tr>
  <tr>
    <td><b>Repo</b></td>
    <td dir=rtl>این اصطلاح برگرفته از واژه Repository به معنی «مخزن» یا «منبع» است</td>
  </tr>
  <tr>
    <td><b>Clone</b></td>
    <td dir=rtl> چنانچه بخواهیم یک ریپازیتوری آنلاین را دریافت نموده و روی سیستم لوکال خود شروع به کار روی آن نماییم، نیاز است تا ابتدا کل پروژه را دانلود نماییم که به این کار کلون کردن گفته می‌شود. </td>
  </tr>
</table>

</br>
<h3 dir=rtl>
  دستورات رایج در Git:
</h3>

<table>
  <tr>
    <th><b><i>دستورات</i></b></th>
    <th><b><i>توضیحات</i></b></th>
  </tr>
  <tr>
    <td><b>git init</b></td>
    <td dir=rtl> کامند init برگرفته از کلمه Initialize به معنی «شروع کردن» است. پس از اجرای موفقیت‌آمیز این کامند،‌ پوشه‌ای تحت عنوان git. ساخته می‌شود </td>
  </tr>
  <tr>
    <td><b></b></td>
    <td dir=rtl>  </td>
  </tr>
  </table>

</br>
<h3 dir=rtl>
  سایر دستورات در Git:
</h3>

<table>
  <tr>
    <th><b><i>دستورات</i></b></th>
    <th><b><i>توضیحات</i></b></th>
  </tr>
  <tr>
    <td></br><b>git tag</br>git tag -a V2.0 -m 'کامنت'</br>git tag -l "v*"</br>git show V2.0</br>git push origin V2.0</br>git push origin --tags</br>git checkout V2.0</b></br></td>
    <td dir=rtl>مشاهده تگ ها</br>اضافه کردن تگ با کامنت مناسب</br>دیدن همه تگ ها که با حرف v شروع میشن</br>دیدن جزییات برای لاگی که تگ V2.0 دارد</br>اعمال تغییرات بر روی گیت هاب با تگ بجای شماره کامیت</br>اعمال تگ های ایجاد شده به گیت هاب</br>رفتن به تگ V2.0</td>
  </tr>
  <tr>
    <td><b>git help blame</br>git blame {اسم فایل} -L{شماره خط یا رنجی از خط ها}</b></td>
    <td dir=rtl>برای دیدن توضیحات دستورات گیت</br>برای پیدا کردن آخرین شخصی که خط از فایل رو تغییر داده</td>
  </tr>
  </table>
