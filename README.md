# React-Fundamentals-Lesson

مقدمة في React

تعتبر React مكتبة تستخدم لكتابة او تطوير واجهات المستخدم، ونعني بواجهات المستخدم هنا هو كل ما يتفاعل معه المستخدم في الصفحة. يوجد العديد من المكتبات و frameworks التي تساعدنا على كتابة واجهات المستخدم ايضا لكن تمتلك React عدد من المميزات أحدها اعتماد React على مفهوم Components واعادة استخدامها. بحيث تقوم React بتقسيم الواجهة الى أجزاء Components لتمكننا من إعادة استخدام هذه الأجزاء في أي صفحة أخرى.


مثال

![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627564882791_image.png)




أمثلة على صفحات تستخدم React: 
Twitter

![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627564997049_Screen+Shot+1442-12-19+at+4.23.13+PM.png)




instagram 

![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627565081413_Screen+Shot+1442-12-19+at+4.24.37+PM.png)


نلاحظ هنا عدد من الصّور، و بالحقيقة بالرغم من وجود عدد منهم الّا انهم مجرد Component واحد لكن تمت اعادة استخدامه من خلال تغيير البيانات التي سيعرضها فقط. 





ابدأ مع React

للبدء مع React دعونا أولا ننشئ مجلّد بداخله ملف html من ثمّ التطبيق على كيفيّة البدء باستخدام React كالتالي.


![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627565965166_Screen+Shot+1442-12-19+at+4.39.21+PM.png)


لنقم الآن بتجهيز الملف كملف html كالتالي. 

    <html>
        <head>
        </head>
        <body> 
        </body>
    </html>
![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627566315848_Screen+Shot+1442-12-19+at+4.45.10+PM.png)


بهذا الشكل قمنا بتجهيز الملف، المتبقي هو ان نقوم باضافة مكتبة React للتعامل معها من خلال الذهاب الى موقع React عبر الرابط ( https://reactjs.org/ )  من ثمّ نسخ CDN الخاص في React و ReactDOM.

CDN 

    <script crossorigin src="https://unpkg.com/react@17/umd/react.production.min.js"></script>
    
    <script crossorigin src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script>


مثال

    <html>
        <head>
            <script crossorigin src="https://unpkg.com/react@17/umd/react.production.min.js"></script>
            <script crossorigin src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script>
        </head>
        <body> 
        </body>
    </html>
    
![](https://paper-attachments.dropbox.com/s_AF539446F48191BDC6D15DF619AB61846567F12988213478724D17088942E1BE_1627566668395_Screen+Shot+1442-12-19+at+4.51.04+PM.png)

React Project Folders Structure

![](https://paper-attachments.dropbox.com/s_4E006B11E5DBB82EDCA48627D3C762AF436F0810CB03CE9027FA25A16CFDB33C_1648456556250_Screen+Shot+1443-08-25+at+11.35.13+AM.png)

- مجلد node_modules يحتوي على كل المجلدات التي تحوي التبعيات المعتمد عليها مشروع الرياكت.
- مجلد  public يحتوي على ملف الـHTML الاساسي للمشروع.
- في مجلد src ننشئ مجلد باسم Components  بداخله ننشئ أي مكوّن نحتاجه في مشروع الرياكت.
- في ملف .gitignore نضع معلومات الملفات التي لا نريد من git تتبعها.
- ملف package-lock.json يحتوي على تفاصيل كل الحزم والمكتبات التي تم تنزيلها في المشروع، كما يمكن ادارتها في هذا الملف.
- ملف package.json يحتوي على كل الحُزم والمكتبات التي تم تنزيلها في المشروع.
- في ملف README.md نستطيع كتابة وصف المشروع.

بهذا الشكل اصبحنا جاهزين للتطبيق. 
