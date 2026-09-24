> Please transcribe the questions from the uploaded images into a clean HTML format following the template and guidelines below:
> 
> **Subject:** Physics 1st Paper  
> **Chapter:** [Insert Chapter Name Here]
> 
> **Instructions:**
> 1. Organize questions logically by topic using `<li class="topic-header">`.
> 2. If questions are MCQs, strip out the options and turn them into direct questions.
> 4. If a question contains a diagram that cannot be rendered in text, add a tag: `<span>[চিত্র প্রয়োজন]</span>`.
> 5. Use the exact HTML template provided below:

```

<!DOCTYPE html>
<html lang="bn">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practice Sheet</title>

    <!-- Google Fonts for standard Bengali typography -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+Bengali:wght@400;600;700&display=swap"
        rel="stylesheet">

    <!-- MathJax for rendering math equations -->
    <script>
        window.MathJax = {
            tex: {
                inlineMath: [['$', '$'], ['\\(', '\\)']]
            },
            chtml: {
                matchFontHeight: false
            }
        };
    </script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

    <style>
        @page {
            size: A4;
            margin: 15mm 15mm 15mm 15mm;
        }

        body {
            font-family: 'Noto Serif Bengali', 'Times New Roman', serif;
            color: #111;
            background-color: #fff;
            line-height: 1.5;
            font-size: 13pt;
            margin: 0;
            padding: 15px;
        }

        h2.main-title {
            text-align: center;
            text-decoration: underline;
            margin-top: 0;
            margin-bottom: 25px;
            font-size: 18pt;
        }

        .topic-header {
            padding: 8px 14px;
            margin-top: 30px;
            margin-bottom: 15px;
            font-size: 14.5pt;
            font-weight: 700;
            border-radius: 0 4px 4px 0;
            page-break-after: avoid;
            break-after: avoid;
        }

        .problem-list {
            list-style-type: none;
            padding-left: 0;
            margin: 0;
        }

        .problem-item {
            margin-bottom: 14px;
            padding-left: 5px;
            break-inside: avoid;
            page-break-inside: avoid;
        }

        .q-label {
            font-weight: 700;
            display: inline-block;
            color: #0f172a;
        }

        .ans-tag {
            margin-top: 4px;
            font-size: 12pt;
            font-weight: 600;
        }

        .header-container {
            width: 100%;
            max-width: 850px;
            background-color: #ffffff;
            padding: 30px 20px 10px 20px;
            text-align: center;
            font-family: 'Inter', 'Hind Siliguri', Arial, sans-serif;
        }

        .main-title {
            font-size: 26px;
            font-weight: 800;
            letter-spacing: -0.2px;
            margin: 0 0 10px 0;
        }

        .sub-title {
            font-size: 19px;
            font-weight: 500;
            margin: 0 0 12px 0;
        }

        .sheet-details {
            font-size: 16px;
            font-weight: 500;
            margin: 0 0 18px 0;
            word-spacing: 1px;
        }

        .divider {
            border: none;
            border-top: 1.5px solid #222222;
            margin: 0;
            width: 100%;
        }

        @media print {
            body {
                font-size: 11pt;
                padding: 0;
            }

            .topic-header {
                font-size: 12.5pt;
                padding: 6px 10px;
                margin-top: 20px;
                margin-bottom: 10px;
                background-color: #eee !important;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }

            .problem-item {
                margin-bottom: 10px;
            }
        }


    </style>
</head>

<body>
    <div class="header-container">
        <h1 class="main-title">Kamal’s Physics & Math Nexus</h1>
        <div class="sub-title">Engineering Admission Program</div>
        <div class="sheet-details">
            Physics 1st Paper | Chapter 7: পদার্থের গাঠনিক ধর্ম (Practice Sheet)
        </div>
        <hr class="divider">
    </div>
    <ul class="problem-list">
        <!-- Topic 1 -->
        <li class="topic-header">১. অনুদৈর্ঘ্য পীড়ন, বিকৃতি ও ইয়ং-এর গুণাঙ্ক (Young's Modulus, Stress & Strain)</li>

        <li class="problem-item">
            <span class="q-label">১.</span> একটি তারের দৈর্ঘ্য $T_1$ টানে থাকলে $L_1$ এবং $T_2$ টানে থাকলে $L_2$। কোনো টান না থাকলে তারটির দৈর্ঘ্য কত হবে?
            <div class="ans-tag">[উত্তর: $\frac{T_2 L_1 - T_1 L_2}{T_2 - T_1}$] [2015]</div>
        </li>

        <li class="problem-item">
            <span class="q-label">২.</span> ভিন্ন উপাদানের দুটি অনুরূপ তারকে একই বলের সাহায্যে টানা হল। তার দুটির দৈর্ঘ্য বৃদ্ধির পার্থক্য $0.25\text{ m}$। যদি তার দুটির উপাদানের ইয়ং গুণাঙ্কের অনুপাত $5 : 3$ হয়, তবে এদের প্রত্যেকটির দৈর্ঘ্য বৃদ্ধির পরিমাণ নির্ণয় করো।
            <div class="ans-tag">[উত্তর: $0.375\text{ m}$, $0.625\text{ m}$]</div>
        </li>
        <!-- Topic 2 -->
        <li class="topic-header">২. অনুভূমিক তারের অবনমন (Depression / Sagging of Horizontal Wire)</li>

        <li class="problem-item">
            <span class="q-label">২২.</span> $2\text{ m}$ দীর্ঘ ও $0.8\text{ mm}$ ব্যাসের একটি ইস্পাতের তার উভয় প্রান্তে দৃঢ় ধারকের সাহায্যে অনুভূমিকভাবে টানা আছে। তারটির মধ্যবিন্দুতে একটি ভার ঝোলালে $1\text{ cm}$ পরিমাণ অবনমন হয়। ভারটির পরিমাণ নির্ণয় করো। দেওয়া আছে ইস্পাতের ইয়ং গুণাঙ্ক $= 20 \times 10^{11}\text{ dyn/cm}^2$। [WBJEE '95]
            <div class="ans-tag">[উত্তর: $10.25\text{ g}$]</div>
        </li>

        <li class="problem-item">
            <span class="q-label">২৩.</span> $1\text{ m}$ দীর্ঘ এবং $0.5 \times 10^{-6}\text{ m}^2$ প্রস্থচ্ছেদবিশিষ্ট একটি টানটান অনুভূমিক ধাতব তারের উভয়প্রান্ত দৃঢ়ভাবে আবদ্ধ। $100\text{ g}$ ভরের একটি বস্তুকে ওই তারটির মধ্যবিন্দুতে ঝোলানো হলে মধ্যবিন্দুর অবনমন নির্ণয় করো। প্রদত্ত, তারটির উপাদানের ইয়ং গুণাঙ্ক $2 \times 10^{11}\text{ N}\cdot\text{m}^{-2}$।
            <div class="ans-tag">[উত্তর: $0.01\text{ m}$]</div>
        </li>

    </ul>
    </body>

</html>
```

