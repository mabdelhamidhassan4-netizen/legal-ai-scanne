Legal AI Scanner — MVP (Lovable + AWS)

MVP: وكيل ذكي لفحص العقود والمستندات لكشف التزوير. واجهة بسيطة من صفحتين مبنيةن على Lovable، وباك-إند تحليلي على AWS (S3, Textract, Comprehend). الكود الخلفي تم توليده بمساعدة Amazon Q Developer.

الروابط الخاصه بالمشروع: -MVP (Lovable): https://ai-doc-guard-60.lovable.app/ Video Demo (YouTube) https://youtube.com/shorts/EV4jSbirLVk?si=w2vKATsn0WfsVt2M  :
محتوى هذا الريبو

/src/document_analyzer.py ← كود التحليل (Amazon Q generated)

/docs/project_documentation.pdf ← توثيق المشروع
https://drive.google.com/file/d/1FF5fSezcHRPyXmpf40K3r8R3d0ZZRweU/view?usp=drivesdk

/docs/amazon_q_proof.png ← إثبات استخدام Amazon Q Developer (Screen shot & Video)

https://drive.google.com/file/d/14UmoFp2pV-GMiJYr4ozZRmMxPTkAAwNz/view?usp=drivesdk-
https://drive.google.com/file/d/11hKudv-EpdGS6LXOBAsdwBBky6S7hrQg/view?usp=drivesdk
https://drive.google.com/file/d/1ahTabWArmu80WHPew2iq69A5_OixCOqe/view?usp=drivesdk https://drive.google.com/file/d/1lDYXaea84YvuI9FiIHdESXTDcV5jMYiS/view?usp=drivesdk

/demo/video-link.txt ← رابط فيديو اليوتيوب

/mvp/lovable-link.txt ← رابط الـMVP

إثبات استخدام Amazon Q Developer تم استخدام Amazon Q Developer لتوليد منطق التحليل واحرى أجزاء الكود الخلفي. راجع: /docs/amazon_q_proof.png. ملاحظة سريعة

النظام MVP يعمل عبر رابط Lovable أعلاه.
الكود المصدري موثّق في /src/README_CODE.md (تعليمات تشغيل قصيرة: إعداد AWS credentials، إنشاء S3 bucket، تشغيل script
