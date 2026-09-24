> Create a comprehensive **Solution Sheet** HTML file based on the attached question sheet. Follow the structural rules and CSS template provided below:
> 
> **Rules:**
> 1. Keep the exact order and numbering of topics and questions as provided in the question file.
> 3. Always highlight the final answer inside `<div class="ans-highlight">`.
> 4. Use the exact template structure below:

```
<!DOCTYPE html>
<html lang="bn">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solution Sheet</title>
    <!-- MathJax Configuration -->
    <script>
        window.MathJax = {
            tex: {
                inlineMath: [['$', '$'], ['\\(', '\\)']],
                displayMath: [['$$', '$$'], ['\\[', '\\]']]
            },
            chtml: {
                scale: 0.98,
                displayAlign: 'left'
            }
        };
    </script>
    <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js" id="MathJax-script" async></script>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans Bengali", sans-serif;
            background-color: #ffffff;
            color: #000000;
            line-height: 1.4;
            /* reduced line spacing */
            font-size: 13px;
            /* reduced overall font size */
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 850px;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            font-size: 18px;
            /* smaller title */
            margin-bottom: 20px;
            border-bottom: 1.5px solid #000000;
            padding-bottom: 10px;
        }

        .qa-card {
            margin-bottom: 16px;
            /* reduced card gap (was 35px) */
            padding-bottom: 12px;
            /* reduced padding (was 25px) */
            border-bottom: 1px solid #e0e0e0;
            break-inside: auto;
            /* allows natural flow across pages */
        }

        .question {
            font-weight: 600;
            font-size: 13.5px;
            /* smaller question font (was 16px) */
            margin-bottom: 6px;
        }

        .solution {
            font-size: 12.5px;
            /* smaller solution font (was 15px) */
            margin-left: 0;
        }

        .solution-title {
            font-weight: 700;
            text-decoration: underline;
            margin-bottom: 4px;
            display: inline-block;
        }

        .ans-highlight {
            font-weight: 700;
            margin-top: 6px;
        }

        .header-container {
            width: 100%;
            background-color: #ffffff;
            padding: 30px 0px 10px 0px;
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

        

        /* Compact MathJax display equations */
        mjx-container[jax="CHTML"][display="true"] {
            margin: 6px 0 !important;
        }

        @media print {
            body {
                padding: 0;
            }

            .qa-card {
                page-break-inside: auto !important;
                /* prevents huge gaps before cards */
                break-inside: auto !important;
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
        }
    </style>
</head>

<body>
    <div class="header-container">
        <h1 class="main-title">Kamal’s Physics & Math Nexus</h1>
        <div class="sub-title">Engineering Admission Program</div>
        <div class="sheet-details">
            Physics 1st Paper | Chapter 7: পদার্থের গাঠনিক ধর্ম (Solution Sheet)
        </div>
        <hr class="divider">
    </div>
    <div class="container">
        <!-- Topic 1 -->
        <div class="topic-header">১. সংযুক্ত বস্তুর গতি, কপিদল ও টান (Connected Bodies, Atwood Machines & String Tension)</div>
        <div class="qa-card">
            <div class="question">
                ১. $5\text{ kg}$ ও $3\text{ kg}$ ভরের দুটি ব্লক হালকা ও অপ্রসারণশীল সুতা দ্বারা যুক্ত। ব্যবস্থাটিকে একটি
                ঘর্ষণহীন তলের উপর রাখা আছে। $5\text{ kg}$ ভরের ব্লকের উপর অনুভূমিকের সাথে $30^\circ$ কোণে
                $20\sqrt{3}\text{ N}$ বল দ্বারা টানা হলে ব্লকদুটির ত্বরণ ও দড়ির টান নির্ণয় কর।
            </div>
            <div class="solution">
                <span class="solution-title">সমাধান:</span><br>
                প্রযুক্ত বলের অনুভূমিক উপাংশ:
                $$F_x = F \cos 30^\circ = 20\sqrt{3} \times \frac{\sqrt{3}}{2} = 30\text{ N}$$
                ব্যবস্থাটির মোট ভর $M = m_1 + m_2 = 5\text{ kg} + 3\text{ kg} = 8\text{ kg}$।<br>
                সুতরাং, সংস্থাটির ত্বরণ:
                $$a = \frac{F_x}{M} = \frac{30}{8} = 3.75\text{ m/s}^2$$
                পিছনের $3\text{ kg}$ ব্লকের ওপর ক্রিয়াশীল একমাত্র অনুভূমিক বল হলো সুতার টান $T$:
                $$T = m_2 a = 3 \times 3.75 = 11.25\text{ N}$$
                <div class="ans-highlight">উত্তর: ত্বরণ: $3.75\text{ m/s}^2$, টান: $11.25\text{ N}$</div>
            </div>
        </div>

        <div class="qa-card">
            <div class="question">
                ২. সর্বাধিক $360\text{ N}$ টান সহ্য করতে পারে এমন দড়ি বেয়ে $30\text{ kg}$ ভরের একটি বানর উপরে উঠছে।
                দড়িটি না ছিঁড়ে সর্বাধিক কত ত্বরণে বানরটি উপরে উঠতে পারবে?
            </div>
            <div class="solution">
                <span class="solution-title">সমাধান:</span><br>
                বানর $a$ ত্বরণে উপরে উঠলে দড়ির কার্যকর টান:
                $$T = m(g + a)$$
                মান বসিয়ে পাই ($g = 9.8\text{ m/s}^2$):
                $$360 = 30(9.8 + a) \implies 12 = 9.8 + a \implies a = 12 - 9.8 = 2.2\text{ m/s}^2$$
                <div class="ans-highlight">উত্তর: $2.2\text{ m/s}^2$</div>
            </div>
        </div>

         <!-- Topic 2 -->
        <div class="topic-header">২. বল, ত্বরণ ও পরিবর্তনশীল বল (Force, Acceleration & Calculus-based Dynamics)</div>
        <div class="qa-card">
        <div class="question">
            ২১. $20\text{ kg}$ বস্তুর উপর কি পরিমাণ বল ক্রিয়া করলে বেগ $10\text{ s}$ এ $(4\hat{i} - 5\hat{j} +
            3\hat{k})$ থেকে $(8\hat{i} + 3\hat{j} - 5\hat{k})$ হবে?
        </div>
        <div class="solution">
            <span class="solution-title">সমাধান:</span><br>
            বেগের পরিবর্তন:
            $$\Delta\vec{v} = (8\hat{i} + 3\hat{j} - 5\hat{k}) - (4\hat{i} - 5\hat{j} + 3\hat{k}) = 4\hat{i} + 8\hat{j}
            - 8\hat{k}$$
            প্রযুক্ত বল:
            $$\vec{F} = m \frac{\Delta\vec{v}}{\Delta t} = 20 \times \frac{4\hat{i} + 8\hat{j} - 8\hat{k}}{10} =
            2(4\hat{i} + 8\hat{j} - 8\hat{k}) = 8\hat{i} + 16\hat{j} - 16\hat{k}\text{ N}$$
            <div class="ans-highlight">উত্তর: $8\hat{i} + 16\hat{j} - 16\hat{k}\text{ N}$</div>
        </div>
    </div>

    <div class="qa-card">
        <div class="question">
            ২২. $10\text{ kg}$ স্থির বস্তুর উপর $(10\hat{i} - 20\hat{j})\text{ N}$ বল $3\text{ s}$ ধরে প্রযুক্ত হলে
            অবস্থান ও গতিশক্তি কত?
        </div>
        <div class="solution">
            <span class="solution-title">সমাধান:</span><br>
            ত্বরণ: $\vec{a} = \frac{\vec{F}}{m} = \frac{10\hat{i} - 20\hat{j}}{10} = (\hat{i} - 2\hat{j})\text{
            m/s}^2$।<br>
            $3\text{ s}$ পর অবস্থান ভেক্টর:
            $$\vec{r} = \frac{1}{2}\vec{a}t^2 = \frac{1}{2}(\hat{i} - 2\hat{j}) \times 3^2 = 4.5\hat{i} - 9\hat{j}\text{
            m}$$
            অর্থাৎ অবস্থান স্থানাঙ্ক: $(4.5, -9)\text{ m}$।<br>
            $3\text{ s}$ পর বেগ:
            $$\vec{v} = \vec{a}t = (\hat{i} - 2\hat{j}) \times 3 = 3\hat{i} - 6\hat{j}\text{ m/s} \implies v^2 = 3^2 +
            (-6)^2 = 45\text{ m}^2/\text{s}^2$$
            গতিশক্তি:
            $$E_k = \frac{1}{2}mv^2 = \frac{1}{2} \times 10 \times 45 = 225\text{ J}$$
            <div class="ans-highlight">উত্তর: অবস্থান: $(4.5, -9)\text{ m}$, গতিশক্তি: $225\text{ J}$</div>
        </div>
    </div>
        </div>
    </div>
</body>

</html>

```

