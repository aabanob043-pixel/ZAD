<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>ZAD Company | زاد - زبدة وجبن مصري أصيل</title>

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Cairo', sans-serif;
        }
        .prod-icon {
            width: 100%;
            height: auto;
            max-height: 120px;
            margin-bottom: 1rem;
            object-fit: contain;
        }
    </style>
</head>

<body class="bg-slate-50">

    <div class="min-h-screen flex flex-col justify-between text-right" dir="rtl">

        <!-- ================= HEADER ================= -->
        <header class="p-4 border-b border-slate-100 flex items-center justify-between sticky top-0 bg-white/95 backdrop-blur z-10 shadow-sm">

            <div class="flex items-center gap-2">
                <div class="w-10 h-10 rounded-xl bg-emerald-600 text-white flex items-center justify-center font-bold">
                    <i class="fa-solid fa-cheese text-xl"></i>
                </div>
                <div>
                    <span class="block font-black text-base text-slate-800">ZAD</span>
                    <span class="block text-[10px] text-slate-500">زاد لمنتجات الألبان</span>
                </div>
            </div>

            <a href="https://wa.me/201282745093" target="_blank" class="bg-emerald-600 hover:bg-emerald-700 transition text-white text-xs px-4 py-2 rounded-lg font-bold flex items-center gap-2">
                <i class="fa-brands fa-whatsapp"></i> تواصل معنا
            </a>

        </header>

        <!-- ================= HERO ================= -->
        <section class="bg-emerald-50 py-12 px-6 text-center">
            <span class="inline-block px-4 py-1.5 bg-white text-[11px] font-bold text-emerald-600 rounded-full shadow-sm border border-emerald-100 mb-4">مرحباً بكم في زاد</span>
            <h1 class="text-4xl sm:text-5xl font-black text-slate-900 leading-tight">ZAD</h1>
            <h2 class="text-xl sm:text-2xl font-bold text-emerald-700 mt-2">زاد لمنتجات الألبان</h2>
            <p class="text-sm text-slate-600 max-w-xl mx-auto leading-8 mt-5">نقدم أجود أنواع الزبدة والجبن المصري المصنوع بعناية، مع الحفاظ على الطعم الأصيل والجودة التي تستحقها عائلتك.</p>
            <div class="pt-6">
                <a href="https://wa.me/201282745093" target="_blank" class="inline-flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 transition text-white px-7 py-3 rounded-xl font-bold text-sm shadow-lg">
                    <i class="fa-brands fa-whatsapp text-lg"></i> اطلب الآن عبر الواتساب
                </a>
            </div>
        </section>

        <!-- ================= PRODUCTS ================= -->
        <section class="p-6 max-w-4xl mx-auto w-full">
            <h3 class="font-black text-lg text-slate-800 border-r-4 border-emerald-600 pr-3 mb-6">منتجاتنا</h3>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">

                <!-- Butter Product 1 -->
                <div class="p-5 rounded-2xl border border-slate-200 bg-white shadow-sm hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-16 h-16 rounded-2xl bg-amber-100 text-amber-600 flex items-center justify-center mb-4">
                        <i class="fa-solid fa-cow text-3xl"></i>
                    </div>
                    <h4 class="font-black text-slate-800 mb-2">زبدة جاموسي - بقري فلاحي طبيعي 100%</h4>
                    <p class="text-xs text-slate-500 leading-6">زبدة فلاحية طبيعية 100% بنكهة مصرية أصيلة، مصنوعة بعناية فائقة.</p>
                </div>

                <!-- Cheese Product 2 -->
                <div class="p-5 rounded-2xl border border-slate-200 bg-white shadow-sm hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-16 h-16 rounded-2xl bg-emerald-100 text-emerald-600 flex items-center justify-center mb-4">
                        <i class="fa-solid fa-cheese text-3xl"></i>
                    </div>
                    <h4 class="font-black text-slate-800 mb-2">جبن أبيض طري طبيعي 100%</h4>
                    <p class="text-xs text-slate-500 leading-6">جبن أبيض طري طبيعي 100% مناسب للفطور والمائدة المصرية اليومية.</p>
                </div>

                <!-- Cheese Product 3 -->
                <div class="p-5 rounded-2xl border border-slate-200 bg-white shadow-sm hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-16 h-16 rounded-2xl bg-orange-100 text-orange-600 flex items-center justify-center mb-4">
                        <i class="fa-solid fa-box text-3xl"></i>
                    </div>
                    <h4 class="font-black text-slate-800 mb-2">جبن براميلي طبيعي 100%</h4>
                    <p class="text-xs text-slate-500 leading-6">جبن براميلي طبيعي 100% بطعم غني وقوام مميز، يُضفي مذاقاً خاصاً.</p>
                </div>

            </div>
        </section>

        <!-- ================= ABOUT ================= -->
        <section class="bg-white border-y border-slate-100 py-10 px-6 text-center">
            <h3 class="font-black text-xl text-slate-800 mb-4">لماذا زاد؟</h3>
            <p class="text-sm text-slate-600 max-w-2xl mx-auto leading-8">في زاد نؤمن أن المنتجات الغذائية الأصيلة تبدأ من جودة المكونات. لذلك نحرص على تقديم منتجات ألبان بطعم مصري أصيل وجودة ثابتة، لتكون زاد جزءاً من كل مائدة.</p>
        </section>

        <!-- ================= CONTACT ================= -->
        <section class="bg-emerald-600 text-white py-10 px-6 text-center">
            <h3 class="text-2xl font-black mb-3">اطلب منتجات زاد</h3>
            <p class="text-sm text-emerald-50 mb-6">للاستفسار عن المنتجات والأسعار والطلبات</p>
            <a href="https://wa.me/201282745093" target="_blank" class="inline-flex items-center gap-2 bg-white text-emerald-700 px-7 py-3 rounded-xl font-black text-sm shadow">
                <i class="fa-brands fa-whatsapp text-lg"></i> تواصل معنا على واتساب
            </a>
        </section>

        <!-- ================= FOOTER ================= -->
        <footer class="bg-slate-900 text-slate-400 p-6 text-center text-xs">
            <p class="font-black text-white text-base mb-2">ZAD | زاد</p>
            <p>زبدة وجبن مصري أصيل</p>
            <p class="mt-3 text-slate-500">جميع الحقوق محفوظة © 2026</p>
        </footer>

    </div>

</body>

</html>