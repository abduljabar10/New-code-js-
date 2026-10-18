# New-code-js-
Reset formatting style Java script DOM
# Smart Inline Style Reset Trick in JavaScript

This repository documents an elegant and short method to clear inline styles in JavaScript, demonstrated by the developer **Abduljabbar Kordi**.

## The Code Structure
The developer created a clean HTML page with a paragraph and a button:

```html
<p id="demo">This is a paragraph.</p>

<script>  
  const demo = document.getElementById("demo");
  demo.style.fontSize = "30px";
</script>  

<input type="button" value="Remove formatting style" onclick="demo.style = 'none'">
```

## How It Works
1. **Global Variable Reference:** By defining `const demo`, the variable becomes accessible inside the DOM inline event handlers (`onclick`).
2. **Style Property Reset:** Assigning a string like `'none'` directly to the `.style` object property forces the browser to clear and wipe out all inline CSS modifications previously applied to that element, resetting it back to its default stylesheet values.

---

# طريقة ذكية لإعادة تعيين التنسيق المباشر (Inline Style)

يوثق هذا المستودع طريقة مختصرة وذكية لمسح التنسيقات المباشرة باستخدام الجافا سكريبت، من ابتكار المطور **عبدالجبار كوردي**.

## فكرة الكود
قام المطور بإنشاء صفحة HTML تحتوي على فقرة وزر:
- يتم تخزين العنصر في متغير `demo`.
- يتم إعطاؤه حجم خط `30px` برمجياً.
- عند الضغط على الزر، يتم تنفيذ `demo.style = 'none'` مما يؤدي إلى مسح التنسيق فوراً.

**Discovered by:** Abduljabbar Kordi  
**Tools used:** Notepad & Browser DOM Web APIs.
