<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر حناني الشامل - النسخة النهائية</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root { --green: #1b4332; --orange: #e67e22; --bg: #f8f9fa; }
        body { font-family: 'Tajawal', sans-serif; background: var(--bg); margin: 0; padding-bottom: 120px; direction: rtl; }
        
        header { 
            background: linear-gradient(rgba(27, 67, 50, 0.8), rgba(27, 67, 50, 0.8)), url('https://images.pexels.com/photos/2802527/pexels-photo-2802527.jpeg?auto=compress&cs=tinysrgb&w=1200'); 
            background-size: cover; color: white; padding: 30px; text-align: center; border-bottom: 5px solid var(--orange); 
        }

        /* لوحة الإدارة */
        .admin-panel { background: #fff; padding: 20px; margin: 10px auto; max-width: 950px; border-radius: 15px; display: none; border: 2px solid var(--orange); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .admin-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 10px; margin-bottom: 20px; }
        input, select { padding: 12px; border-radius: 8px; border: 1px solid #ddd; font-family: 'Tajawal'; font-size: 0.9rem; }

        /* البحث والأقسام */
        .nav-tabs { display: flex; justify-content: center; gap: 8px; background: white; padding: 15px; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.1); overflow-x: auto; }
        .tab-btn { padding: 8px 20px; border: 2px solid var(--green); background: none; color: var(--green); border-radius: 20px; cursor: pointer; font-weight: bold; white-space: nowrap; }
        .tab-btn.active { background: var(--green); color: white; }
        .search-container { max-width: 600px; margin: 20px auto; padding: 0 15px; }
        .search-input { width: 100%; padding: 15px; border-radius: 30px; border: 2px solid var(--green); box-sizing: border-box; outline: none; }

        /* المنتجات */
        .container { max-width: 1200px; margin: auto; display: grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap: 20px; padding: 15px; }
        .card { background: white; border-radius: 20px; overflow: hidden; box-shadow: 0 5px 15px rgba(0,0,0,0.05); text-align: center; border-bottom: 4px solid var(--green); transition: 0.3s; display: flex; flex-direction: column; }
        .card img { width: 100%; height: 170px; object-fit: cover; background: #eee; }
        .card-body { padding: 15px; flex-grow: 1; }
        .price { color: var(--orange); font-weight: bold; font-size: 1.2rem; margin: 5px 0; }
        
        /* خاصية اختيار الكمية للزبون */
        .qty-selector { display: flex; align-items: center; justify-content: center; gap: 5px; background: #f0f0f0; padding: 8px; border-radius: 10px; margin: 10px 0; }
        .qty-selector input { width: 70px; text-align: center; font-weight: bold; }

        .btn-add { background: var(--green); color: white; border: none; padding: 12px; width: 100%; border-radius: 10px; cursor: pointer; font-weight: bold; font-size: 1rem; }
        
        /* السلة */
        .footer-cart { position: fixed; bottom: 20px; left: 50%; transform: translateX(-50%); width: 90%; max-width: 500px; background: var(--green); color: white; padding: 15px 25px; border-radius: 50px; display: flex; justify-content: space-between; align-items: center; z-index: 2000; box-shadow: 0 10px 30px rgba(0,0,0,0.5); cursor: pointer; }

        .modal { display: none; position: fixed; z-index: 3000; inset: 0; background: rgba(0,0,0,0.7); overflow-y: auto; padding: 20px; }
        .modal-content { background: white; margin: auto; padding: 25px; max-width: 550px; border-radius: 25px; box-sizing: border-box; }
        .cart-item { display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid #eee; padding: 10px 0; }
        
        .shipping-section { background: #f8f9fa; padding: 15px; border-radius: 15px; margin-top: 15px; border: 1px solid #eee; }
    </style>
</head>
<body>

<header>
    <button onclick="toggleAdmin()" style="float: left; background: var(--orange); border: none; color: white; padding: 8px 15px; border-radius: 8px; cursor: pointer; font-weight: bold;">⚙️ لوحة الإدارة</button>
    <h1>🌿 حناني بيت العطور والبخور</h1>
    <p>الجودة التقليدية بلمسة عصرية</p>
</header>

<div class="admin-panel" id="adminPanel">
    <h3 style="color: var(--green);">📦 إضافة منتج جديد</h3>
    <div class="admin-grid">
        <input type="text" id="newName" placeholder="اسم المنتج">
        <input type="number" id="newPrice" placeholder="السعر (لكل 100غ أو قطعة)">
        <input type="text" id="newImg" placeholder="رابط الصورة">
        <select id="newUnit">
            <option value="غرام">لكل 100 غرام</option>
            <option value="قطعة">لكل قطعة</option>
            <option value="مل">لكل 100 مل</option>
        </select>
        <select id="newCat">
            <option value="توابل">توابل</option>
            <option value="أعشاب">أعشاب</option>
            <option value="زيوت">زيوت</option>
            <option value="عطور">عطور</option>
        </select>
        <button onclick="addNewProduct()" style="background: var(--green); color: white; border: none; border-radius: 8px; cursor: pointer;">+ إضافة للمتجر</button>
    </div>
    <hr>
    <h3 style="color: var(--orange);">🚚 إدارة أسعار الشحن للولايات</h3>
    <div class="admin-grid">
        <select id="shipWilaya" onchange="loadShipPrice()"></select>
        <input type="number" id="shipPriceOffice" placeholder="سعر المكتب">
        <input type="number" id="shipPriceHome" placeholder="سعر المنزل">
        <button onclick="updateShipPrice()" style="background: var(--orange); color: white; border: none; border-radius: 8px; cursor: pointer;">تحديث السعر</button>
    </div>
</div>

<div class="nav-tabs">
    <button class="tab-btn active" onclick="render('الكل', this)">الكل</button>
    <button class="tab-btn" onclick="render('توابل', this)">توابل</button>
    <button class="tab-btn" onclick="render('أعشاب', this)">أعشاب</button>
    <button class="tab-btn" onclick="render('زيوت', this)">زيوت</button>
    <button class="tab-btn" onclick="render('عطور', this)">عطور وبخور</button>
</div>

<div class="search-container">
    <input type="text" id="searchInput" class="search-input" placeholder="🔍 ابحث عن منتجك هنا..." oninput="render()">
</div>

<div class="container" id="grid"></div>

<div class="footer-cart" onclick="toggleCart()">
    <div>سلة الطلبات (<span id="cart-count">0</span>) 🛒</div>
    <div id="total-val" style="font-weight: bold;">0 د.ج</div>
</div>

<div id="cartModal" class="modal">
    <div class="modal-content">
        <span onclick="toggleCart()" style="float:left; cursor:pointer; font-size: 20px;">✖ إغلاق</span>
        <h2 style="text-align: center; color: var(--green);">مراجعة طلبك 📝</h2>
        <div id="cart-items-list" style="max-height: 200px; overflow-y: auto; border-bottom: 2px solid #eee;"></div>
        
        <div class="shipping-section">
            <h4>بيانات التوصيل 🚚</h4>
            <input type="text" id="custName" placeholder="اسمك الكامل" style="width:100%; margin-bottom:10px;">
            <input type="tel" id="custPhone" placeholder="رقم الهاتف (واجب)" style="width:100%; margin-bottom:10px;">
            
            <select id="wilayaSelect" style="width:100%; margin-bottom:10px;" onchange="calcShipping()">
                <option value="">-- اختر الولاية --</option>
            </select>
            
            <div style="display:flex; justify-content: space-around; margin: 10px 0;">
                <label><input type="radio" name="shipType" value="office" checked onchange="calcShipping()"> توصيل للمكتب</label>
                <label><input type="radio" name="shipType" value="home" onchange="changeShipType()"> توصيل للمنزل</label>
            </div>
            <div style="text-align: center; font-weight: bold; color: var(--orange);">
                تكلفة الشحن: <span id="ship-cost">0</span> د.ج
            </div>
        </div>

        <div style="text-align: center; margin-top: 15px; font-size: 1.3rem; font-weight: bold;">
            المجموع النهائي: <span id="grand-total" style="color: var(--green);">0</span> د.ج
        </div>
        <button class="btn-confirm" onclick="sendOrder()" style="background:#25D366; color:white; border:none; padding:15px; width:100%; border-radius:15px; font-weight:bold; cursor:pointer; margin-top:10px;">تأكيد عبر واتساب ✅</button>
    </div>
</div>

<script>
    let isEditMode = false;
    let currentCat = 'الكل';
    const myPhone = "213660913779";
    const wilayas = ["أدرار","الشلف","الأغواط","أم البواقي","باتنة","بجاية","بسكرة","بشار","البليدة","البويرة","تمنراست","تبسة","تلمسان","تيارت","تيزي وزو","الجزائر","الجلفة","جيجل","سطيف","سعيدة","سكيكدة","سيدي بلعباس","عنابة","قالمة","قسنطينة","المدية","مستغانم","المسيلة","معسكر","ورقلة","وهران","البيض","إليزي","برج بوعريريج","الطارف","تندوف","تيسمسيلت","الوادي","خنشلة","سوق أهراس","تيبازة","ميلة","عين الدفلى","النعامة","عين تموشنت","غرداية","غليزان","تيميمون","برج باجي مختار","أولاد جلال","بني عباس","إن صالح","إن قزام","تقرت","جانت","المغير","المنيعة"];

    // قاعدة بيانات المنتجات (أكثر من 100 صنف)
    function generateProducts() {
        const data = [];
        const cats = {
            'توابل': ['فلفل أسود', 'كمون', 'كركم', 'زنجبيل', 'رأس الحانوت', 'قرفة', 'بابريكا', 'قصبر', 'هيل', 'قرنفل', 'ثوم بودرة', 'بصل بودرة', 'زعفران', 'كروية', 'بسباس', 'ملح صخري', 'شطة حارة', 'بهارات دجاج'],
            'أعشاب': ['زعتر بري', 'إكليل الجبل', 'بابونج', 'مريمية', 'شيح', 'حبة البركة', 'خزامى', 'سنا مكي', 'قشور الرمان', 'ورد مجفف', 'بردقوش', 'زيزفون'],
            'زيوت': ['زيت زيتون', 'زيت الضرو', 'زيت الحبة السوداء', 'زيت اللوز المر', 'زيت الخروع', 'زيت الجرجير', 'زيت جوز الهند'],
            'عطور': ['مسك الطهارة', 'عود كمبودي', 'بخور ملكي', 'عنبر أصلي', 'جاوي أحمر', 'سرغينة', 'مبخرة خشبية']
        };
        const defaultImg = 'https://images.pexels.com/photos/1615562/pexels-photo-1615562.jpeg?auto=compress&cs=tinysrgb&w=400';
        let id = 1;
        for (let cat in cats) {
            cats[cat].forEach(name => {
                data.push({ id: id++, name, price: 150, unit: cat === 'عطور'?'قطعة':'غرام', cat, img: defaultImg });
            });
        }
        return data;
    }

    let products = JSON.parse(localStorage.getItem('hanani_final_v10')) || generateProducts();
    let shippingPrices = JSON.parse(localStorage.getItem('hanani_ship_v10')) || {};
    let cart = [];

    if (Object.keys(shippingPrices).length === 0) {
        wilayas.forEach(w => shippingPrices[w] = { office: 400, home: 700 });
    }

    function toggleAdmin() {
        isEditMode = !isEditMode;
        document.getElementById('adminPanel').style.display = isEditMode ? 'block' : 'none';
        render();
    }

    function render(cat, btn) {
        if (cat) currentCat = cat;
        if (btn) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            btn.classList.add('active');
        }
        const search = document.getElementById('searchInput').value.toLowerCase();
        const grid = document.getElementById('grid');
        grid.innerHTML = "";

        products.filter(p => (currentCat === 'الكل' || p.cat === currentCat) && p.name.includes(search)).forEach(p => {
            grid.innerHTML += `
                <div class="card">
                    <img src="${p.img}">
                    <div class="card-body">
                        ${isEditMode ? `
                            <div style="display:flex; flex-direction:column; gap:5px;">
                                <input type="text" value="${p.name}" onchange="updateProduct(${p.id}, 'name', this.value)">
                                <input type="number" value="${p.price}" onchange="updateProduct(${p.id}, 'price', this.value)">
                                <input type="text" value="${p.img}" placeholder="رابط الصورة" onchange="updateProduct(${p.id}, 'img', this.value)">
                                <button onclick="deleteProduct(${p.id})" style="background:red; color:white; border:none; padding:5px; border-radius:5px; cursor:pointer;">حذف</button>
                            </div>
                        ` : `
                            <h3>${p.name}</h3>
                            <div class="price">${p.price} د.ج <small style="color:#777; font-size:0.7rem;">/${p.unit==='غرام'?'100غ':p.unit}</small></div>
                            <div class="qty-selector">
                                <input type="number" id="qty-${p.id}" value="${p.unit==='غرام'?100:1}" min="1" step="${p.unit==='غرام'?50:1}">
                                <span>${p.unit}</span>
                            </div>
                            <button class="btn-add" onclick="addToCart(${p.id})">أضف للسلة 🛒</button>
                        `}
                    </div>
                </div>
            `;
        });
    }

    function updateProduct(id, field, val) {
        const idx = products.findIndex(p => p.id === id);
        products[idx][field] = field === 'price' ? parseFloat(val) : val;
        localStorage.setItem('hanani_final_v10', JSON.stringify(products));
    }

    function deleteProduct(id) {
        if(confirm('حذف نهائي؟')) {
            products = products.filter(p => p.id !== id);
            localStorage.setItem('hanani_final_v10', JSON.stringify(products));
            render();
        }
    }

    function addNewProduct() {
        const n = document.getElementById('newName').value, p = document.getElementById('newPrice').value, i = document.getElementById('newImg').value, u = document.getElementById('newUnit').value, c = document.getElementById('newCat').value;
        if(n && p) {
            products.unshift({ id: Date.now(), name:n, price:parseFloat(p), unit:u, cat:c, img:i||'https://via.placeholder.com/200' });
            localStorage.setItem('hanani_final_v10', JSON.stringify(products));
            render();
            alert('تم الإضافة!');
        }
    }

    // الشحن
    const wSel = document.getElementById('wilayaSelect');
    const awSel = document.getElementById('shipWilaya');
    wilayas.forEach(w => {
        wSel.innerHTML += `<option value="${w}">${w}</option>`;
        awSel.innerHTML += `<option value="${w}">${w}</option>`;
    });

    function loadShipPrice() {
        const w = awSel.value;
        document.getElementById('shipPriceOffice').value = shippingPrices[w].office;
        document.getElementById('shipPriceHome').value = shippingPrices[w].home;
    }

    function updateShipPrice() {
        const w = awSel.value;
        shippingPrices[w] = { office: parseFloat(document.getElementById('shipPriceOffice').value), home: parseFloat(document.getElementById('shipPriceHome').value) };
        localStorage.setItem('hanani_ship_v10', JSON.stringify(shippingPrices));
        alert('تم الحفظ لولاية ' + w);
    }

    function addToCart(id) {
        const p = products.find(x => x.id === id);
        const qty = parseFloat(document.getElementById(`qty-${id}`).value);
        let finalPrice = p.unit === 'غرام' ? (p.price/100)*qty : p.price*qty;
        cart.push({ cid: Date.now(), name: p.name, qty, unit: p.unit, total: finalPrice });
        updateCartTotal();
        alert('تمت الإضافة ✅');
    }

    function toggleCart() {
        const m = document.getElementById('cartModal');
        m.style.display = m.style.display === 'block' ? 'none' : 'block';
        updateCartUI();
    }

    function updateCartUI() {
        const list = document.getElementById('cart-items-list');
        list.innerHTML = cart.length === 0 ? "السلة فارغة" : "";
        cart.forEach((item, index) => {
            list.innerHTML += `<div class="cart-item">
                <span><b>${item.name}</b> (${item.qty}${item.unit})</span>
                <span>${item.total} دج <button onclick="removeFromCart(${index})" style="color:red; border:none; background:none; cursor:pointer;">🗑️</button></span>
            </div>`;
        });
        calcShipping();
    }

    function removeFromCart(index) {
        cart.splice(index, 1);
        updateCartUI();
        updateCartTotal();
    }

    function updateCartTotal() {
        const t = cart.reduce((sum, item) => sum + item.total, 0);
        document.getElementById('total-val').innerText = t + " د.ج";
        document.getElementById('cart-count').innerText = cart.length;
    }

    function calcShipping() {
        const w = wSel.value;
        const type = document.querySelector('input[name="shipType"]:checked').value;
        let sCost = (w) ? shippingPrices[w][type] : 0;
        document.getElementById('ship-cost').innerText = sCost;
        const sub = cart.reduce((sum, item) => sum + item.total, 0);
        document.getElementById('grand-total').innerText = sub + sCost;
    }

    function sendOrder() {
        const n = document.getElementById('custName').value, ph = document.getElementById('custPhone').value, w = wSel.value;
        const type = document.querySelector('input[name="shipType"]:checked').value === 'office' ? 'استلام من المكتب' : 'توصيل للمنزل';
        if(!ph || !w || cart.length === 0) return alert('أكمل البيانات!');
        let m = `طلب من: ${n || 'زبون'}\nهاتف: ${ph}\nالولاية: ${w} (${type})\n\nالمنتجات:\n`;
        cart.forEach(i => m += `- ${i.name}: ${i.qty}${i.unit} (${i.total}دج)\n`);
        m += `\nالشحن: ${document.getElementById('ship-cost').innerText} دج\nالإجمالي: ${document.getElementById('grand-total').innerText} دج`;
        window.open(`https://wa.me/${myPhone}?text=${encodeURIComponent(m)}`);
    }

    render();
    loadShipPrice();
</script>
</body>
</html>
