<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>اختيار الموضوع</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(135deg, #e3f2fd, #bbdefb);
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px;
    }

    h1 {
      color: #0d47a1;
      margin-bottom: 20px;
      text-align: center;
    }

    form {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 90%;
      max-width: 600px;
    }

    label {
      font-weight: bold;
      color: #0d47a1;
    }

    input {
      width: 100%;
      margin: 8px 0 15px;
      padding: 10px;
      border: 1px solid #90caf9;
      border-radius: 8px;
      font-size: 1em;
    }

    #searchTopic {
      margin-bottom: 15px;
    }

    .topics {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
      margin-top: 10px;
    }

    .topic-card {
      background: #f5f5f5;
      border-radius: 10px;
      padding: 10px;
      cursor: pointer;
      text-align: center;
      transition: all 0.2s;
    }

    .topic-card:hover {
      background: #bbdefb;
    }

    .topic-card.selected {
      background: #2196f3;
      color: white;
      font-weight: bold;
    }

    button {
      background: #0d47a1;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      font-size: 1em;
      cursor: pointer;
    }

    button:hover {
      background: #1565c0;
    }

    @media (max-width: 768px) {
      form { width: 100%; }
      h1 { font-size: 1.6em; }
    }
  </style>
</head>
<body>
  <h1>📚 اختيار الموضوع</h1>
  <form id="studentForm">
    <label>الاسم:</label>
    <input type="text" id="firstName" required placeholder="أدخل اسمك">

    <label>اللقب:</label>
    <input type="text" id="lastName" required placeholder="أدخل لقبك">

    <label>ابحث في المواضيع:</label>
    <input type="text" id="searchTopic" placeholder="ابحث في المواضيع...">

    <div class="topics" id="topicsContainer"></div>

    <button type="submit">تأكيد الاختيار ✅</button>
  </form>

  <script>
    const topics = [
      "الذات والوعي",
      "رحلتك الخاصة: كيف تكتشف نفسك قبل أن تختار طريقك؟",
      "من الفوضى إلى التركيز: فن إدارة انتباهك في زمن التشويش",
      "الذكاء العاطفي… كيف تفهم قلبك قبل أن تحاول فهم الآخرين؟",
      "القيم الشخصية: البوصلة الخفية التي تقود قراراتك",
      "بين الشغف والواقعية: كيف تختار مسارك دون أن تندم؟",
      "فن الهدوء الذكي: كيف تكون ثابتًا في عالم متسارع؟",
      "لغة الجسد الخفية: كيف “تتحدث” دون أن تنطق؟",
      "التأثير بدون سلطة: كيف تقود الآخرين بأسلوبك فقط؟",
      "كيف تبدأ محادثة تغيّر حياتك؟",
      "الكاريزما… مهارة أم طبيعة؟ كيف تبني حضورك بثقة؟",
      "الذكاء الاجتماعي في العلاقات الجامعية والمهنية",
      "فن الإقناع: كيف تزرع فكرة في ذهن شخص آخر؟",
      "كيف تولد الأفكار العظيمة؟ (تقنيات التفكير الإبداعي)",
      "من فكرة إلى تأثير: كيف تحوّل حلمك إلى مشروع يخدم الآخرين؟",
      "الريادة الهادفة: أن تربح وتُحدث فرقًا في الوقت نفسه",
      "التجارة الإلكترونية والذكاء الاصطناعي: فرص جيل جديد",
      "العمل الحر: الحرية كخيار مهني حقيقي",
      "الذكاء الاصطناعي والإنسان: من يخدم من؟",
      "كيف تتعامل مع الفشل دون أن تفقد شغفك؟",
      "فن المثابرة: كيف تستمر حين يتوقف الآخرون؟",
      "كيف تتغلب على التسويف دون أن تعتمد على التحفيز؟",
      "العادات الصغيرة تصنع العظمة: قانون 1٪ يوميًا",
      "مواجهة الخوف من التحدث أمام الناس: خطوات عملية",
      "الطالب القائد: كيف تصنع تأثيرًا حقيقيًا داخل الجامعة؟",
      "بين لغتين: كيف تحافظ على هويتك وتتقن لغة العالم؟",
      "الرسول ﷺ كقدوة قيادية وإنسانية في العصر الحديث",
      "القراءة كرحلة وليس هواية: كيف تقرأ لتتغيّر؟",
      "قوة التطوع: أن تكون نافعًا أكثر من أن تكون مشهورًا",
      "جيل المعرفة: كيف تتعلم ذاتيًا وتصبح خبيرًا بدون شهادة؟",
      "من الجامعة إلى العالم: كيف تبدأ قصتك الآن؟"
    ];

    const topicsContainer = document.getElementById('topicsContainer');
    const searchInput = document.getElementById('searchTopic');
    const form = document.getElementById('studentForm');
    let selectedTopic = null;

    // IMPORTANT: Paste your Google Web App URL here
    const webAppUrl = 'https://script.google.com/macros/s/AKfycbyxJPycyBM5IEr2KeUSg_93yDZpIhXdhIoWZdTMuDXoRnKtBFeG05PngI4X8jFHMHEP/exec';

    function loadTopics() {
      topicsContainer.innerHTML = '';
      // This example does not use localStorage to check for taken topics to align with saving to Google Sheets
      topics.forEach(topic => {
        const card = document.createElement('div');
        card.className = 'topic-card';
        card.textContent = topic;
        card.addEventListener('click', () => {
          document.querySelectorAll('.topic-card').forEach(c => c.classList.remove('selected'));
          card.classList.add('selected');
          selectedTopic = topic;
        });
        topicsContainer.appendChild(card);
      });
    }

    searchInput.addEventListener('input', e => {
      const term = e.target.value.toLowerCase();
      document.querySelectorAll('.topic-card').forEach(card => {
        card.style.display = card.textContent.toLowerCase().includes(term) ? 'block' : 'none';
      });
    });

    form.addEventListener('submit', e => {
      e.preventDefault();
      
      const firstName = document.getElementById('firstName').value.trim();
      const lastName = document.getElementById('lastName').value.trim();

      if (!selectedTopic) {
        alert("يرجى اختيار موضوع أولاً!");
        return;
      }

      const submitButton = form.querySelector('button[type="submit"]');
      submitButton.disabled = true;
      submitButton.textContent = 'جار الإرسال...';

      const dataObject = {
        firstName: firstName,
        lastName: lastName,
        topic: selectedTopic
      };

      fetch(webAppUrl, {
        method: 'POST',
        body: JSON.stringify(dataObject),
        headers: {
          'Content-Type': 'text/plain;charset=utf-8',
        },
      })
      .then(response => response.json())
      .then(data => {
        if (data.result === 'success') {
          alert("✅ تم الحجز بنجاح!");
          form.reset();
          document.querySelectorAll('.topic-card').forEach(c => c.classList.remove('selected'));
          selectedTopic = null;
        } else {
          throw new Error(data.message || 'An unknown error occurred.');
        }
      })
      .catch(error => {
        console.error('Error:', error);
        alert("حدث خطأ. يرجى المحاولة مرة أخرى.");
      })
      .finally(() => {
        submitButton.disabled = false;
        submitButton.textContent = 'تأكيد الاختيار ✅';
      });
    });

    loadTopics();
  </script>
