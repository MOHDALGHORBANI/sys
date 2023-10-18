<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الصفحة</title>
    <style>
        *body{
            background-image: url(image/IMG-20230303-WA0002.jpg);
        }
        .bd-placeholder-img {
          font-size: 1.125rem;
          text-anchor: middle;
          -webkit-user-select: none;
          -moz-user-select: none;
          user-select: none;
        }
  
        @media (min-width: 768px) {
          .bd-placeholder-img-lg {
            font-size: 3.5rem;
          }
        }
  
        .b-example-divider {
          width: 100%;
          height: 3rem;
          background-color: rgba(0, 0, 0, .1);
          border: solid rgba(0, 0, 0, .15);
          border-width: 1px 0;
          box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
        }
  
        .b-example-vr {
          flex-shrink: 0;
          width: 1.5rem;
          height: 100vh;
        }
  
        .bi {
          vertical-align: -.125em;
          fill: currentColor;
        }
  
        .nav-scroller {
          position: relative;
          z-index: 2;
          height: 2.75rem;
          overflow-y: hidden;
        }
  
        .nav-scroller .nav {
          display: flex;
          flex-wrap: nowrap;
          padding-bottom: 1rem;
          margin-top: -1px;
          overflow-x: auto;
          text-align: center;
          white-space: nowrap;
          -webkit-overflow-scrolling: touch;
        }
  
        .btn-bd-primary {
          --bd-violet-bg: #712cf9;
          --bd-violet-rgb: 112.520718, 44.062154, 249.437846;
  
          --bs-btn-font-weight: 600;
          --bs-btn-color: var(--bs-white);
          --bs-btn-bg: var(--bd-violet-bg);
          --bs-btn-border-color: var(--bd-violet-bg);
          --bs-btn-hover-color: var(--bs-white);
          --bs-btn-hover-bg: #6528e0;
          --bs-btn-hover-border-color: #6528e0;
          --bs-btn-focus-shadow-rgb: var(--bd-violet-rgb);
          --bs-btn-active-color: var(--bs-btn-hover-color);
          --bs-btn-active-bg: #5a23c8;
          --bs-btn-active-border-color: #5a23c8;
        }
        .bd-mode-toggle {
          z-index: 1500;
        }
      </style>
      <link href="bootstrap.rtl.min.css" rel="stylesheet">
      <link href="navbars.css" rel="stylesheet">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark" aria-label="Offcanvas navbar large">
        <div class="container-fluid">
            <a style="font-family: 'Times New Roman', Times, serif;" class="navbar-brand" href="#">
                <img style="width: 35px;height: 35px;margin-right: 7px; border-radius: 50%;" src="image/IMG-20230303-WA0002.jpg" width="38" height="30" class="d-inline-block align-top" alt="Bootstrap" loading="lazy">
                مؤسسة جـــود
              </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar2" aria-controls="offcanvasNavbar2" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasNavbar2" aria-labelledby="offcanvasNavbar2Label">
            <div class="offcanvas-header">
              <h5 style="font-family: 'Times New Roman', Times, serif;" class="offcanvas-title" id="offcanvasNavbar2Label"><img style="width: 35px;height: 35px;margin-right: 7px; border-radius: 50%;" src="image/IMG-20230303-WA0002.jpg" width="38" height="30" class="d-inline-block align-top" alt="Bootstrap" loading="lazy">جـــود الرحمن</h5>
              <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item dropdown">
                  <a style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;" class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    ملف
                  </a>
                  <ul class="dropdown-menu">
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فتح</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">جديد</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">قواعد البيانات</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">حفظ نسخة إحتياطية</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">إستعادة نسخة إحتياطية</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#"> تعيين إفتراضي</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">إعدادات الإتصال</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">إعدادات البريد الالكتروني</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">إعدادات الرسائل القصيرة</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close">خروج</a></li>
                  </ul>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      تهيئة
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فتح</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الارصدة الافتتاحية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل فئات الأصناف</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#"> دليل الأصناف</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">مخزون اول المدة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل العملاء والموردين</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      عام
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">البيانات الشخصية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">البيانات المحفوظة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الموظفين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">ترحيل قيودالرواتب</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">مركز الاعدادات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تحديث البيانات الاساسية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تخصيص شريط الادوات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">نقل الارصدة</a></li>
                    </ul>
                  </li>
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      أمان
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل المجموعات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الفروع</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل مستوى الامان</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#"> دليل المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الصلاحيات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تغير كلمة المرور</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">قفل العمليات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تقرير السجلات المقفلة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">جلسات المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">المجموعات المحمية والمسموحة</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                   الفواتير
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فاتورة شراء</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فاتورة مردودات شراء</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فاتورة مبيعات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">فاتورة مردودات مبيعات</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      الحسابات
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل العملات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تسقيف الارصدة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل مراكز التكلفة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">صناديق المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">إعدادات رسائل المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">سندات القبض</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">سندات الصرف</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الارصدةالافتتاحية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">القيود اليومية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">القيود البسيطة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">سند تبديل عملات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">سند قبض يومية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">سند صرف يومية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">قبض شيك</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">صرف شيك</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">القيود الدورية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">ترحيل القيود الدورية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">جرد الصناديق</a></li>
                  </ul>
                  </li>
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      تقارير الحسابات
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">كشف حساب</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">كشف الحركة اليومية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">نقدية الصناديق</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">يومية الحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">يومية الحسابات مجاميع</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">اعمار الديون</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الحركة الشهرية للحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">حركة الحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">حركة الحسابات حسب المستند</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تقارير الشيكات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">ترحيل الحسابات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تقرير الارقام المفقودة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">كشف حساب مراكز التكلفة</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      القوائم المالية
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">ميزان المراجعة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الميزانية العمومية</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الارباح والخسائر</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">ميزان المراجعة بالعملات</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الاقفالات</a></li>
                  </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                     المخازن
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل المخازن</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">مخزون أول الفترة</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">امر توريد مخزني</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">امر صرف مخزني</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">امر نقل مخزني</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">قيد تحويل أصناف</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">قوائم الجرد</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">جرد المخازن</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تسوية جرد مخزني</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">مخازن المستخدمين</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">المجموعات الضريبية</a></li>
                    </ul>
                  </li>
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                    الأصناف
                  </a>
                  <ul class="dropdown-menu">
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل فئات الأصناف</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الأصناف</a></li>
                    <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل الوحدات</a></li>
                </ul>
                </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      العملاء
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل العملاء</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل المناطق</a></li>
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">دليل المندوبين</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                      تقارير المخازن
                    </a>
                    <ul class="dropdown-menu">
                      <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#"> مخزون اخر الفترة</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                          إطار
                      </a>
                      <ul class="dropdown-menu">
                        <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close">إغلاق الكل</a></li>
                          </ul>
                    </li>
                    <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="text-align: right;font-family: 'Times New Roman', Times, serif;color: #ffffff;">
                          تعليمات
                      </a>
                      <ul class="dropdown-menu">
                          <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">تعليمات</a></li>
                          <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">الاتصال بنا</a></li>
                          <li><a style="text-align: center;font-family: 'Times New Roman', Times, serif;color: #000000;" class="dropdown-item" href="#">حول البرنامج</a></li>
                          </ul>
                    </li>  
              </ul>
              <form class="d-flex mt-3 mt-lg-0" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
              </form>
            </div>
          </div>
        </div>
      </nav>
      <script src="bootstrap.bundle.js"></script> 

</body>
</html>
