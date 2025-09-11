# 🔄 Template Converter: HTML -> Blade/Django
BCH+ is a template converter that analyzes the DOM structure across multiple HTML files to identify shared components, then automatically separates them into Blade or Django template structures—Base layout, child views, and subviews.

![2](https://github.com/user-attachments/assets/a249c176-a209-4933-8996-e16cb16e423f) 　![3](https://github.com/user-attachments/assets/d83d35df-7c9e-4b84-bdec-e98198916ae3)


    🔍 Automatically detects and extracts common elements across files
  
    🧩 Converts to Laravel Blade or Django templates with proper layout hierarchy
  
    📦 Pre-registered theme files can be imported instantly—no manual upload required
  
    📁 Original HTML files can be uploaded and stored for reference or reuse
  

Enables team members to share both HTML files and conversion results seamlessly.

## 🚀 Features
✅ Automated structural conversion from HTML to Blade/Django templates

✅ Supports layout constructs like @include, @yield, {% block %}, and more

✅ Batch conversion of multiple files via GUI interface

✅ Designed for extensibility—potentially adaptable to:

    Ruby on Rails (Ruby): ERB (Embedded Ruby)

    Flask (Python): Jinja2

    Next.js (JavaScript/React): JSX / React Components

## 💡 Technical Innovations
- Original, lightweight DOM parsing algorithm

    AI runs the analysis on a high-spec server, but BCH+ can also run on a low-spec server (Win8.1, AMD A4-5000 1.50GHz, 6GB RAM).

- Dynamic database sharding via .env configuration

    By simply modifying the .env file, the system can instantly adapt to changes in the number of sharded databases.

※As of May 2024, Copilot was unable to perform conversion. On August 16, 2025, I asked again—and now it can parse the DOM and perform conversion. On September 4, 2025, I asked Gemini, and it can do it too. Apparently, this became possible thanks to a recent system update.
    
## 📘 How to Use
BCH+ features an intuitive GUI, making it easy to operate without technical setup. No personal data is collected—just register a nickname and email address to get started. If you're curious, feel free to give it a try: 👉 https://bchplus.com

## 📌 Why I Created This

In September 2017, the Japanese takeaway restaurant that I ran with my wife went bankrupt. That's when I had the idea to improve the ordering system we were using and make it available for other people to use. In the process, the idea for Converter came about by chance.

The system was being developed using Laravel. After changing the .html extension and creating a blade file, I read Taylor Otwell's documentation and felt something was off.
The root cause of this feeling of discomfort was, in other words, that the "alternative methods" were in the spotlight, while the methods advocated by the framework developers were in the shadows.
Also, doing the manual work was a pain, so I looked for an automation tool, but there weren't any. So I started making it myself.

In November 2021, I successfully converted the first sample. In January 2022, I successfully converted the second.
The display tests in the execution environment also passed, so I was convinced that this method would work.
In the end, I think the reason I've been able to continue developing BCH+ for eight years is because I was able to resolve this sense of discomfort.
It was a way to resolve my own indigestion.
And then, before I knew it, the AI ​​had caught up with me and surpassed me. Please laugh. :)

※I've been working as a baker since October 2017, and instead of sitting in front of my laptop for eight hours a day, I spend eight hours a day baking bread in front of the oven.
I developed it in an environment where I could code for just one or two hours a day.

## 📅 Future Development Schedule
If BCH+ is useful to you, I'll prioritize 1. If it's unnecessary, I'll prioritize 2.
1. Functional upgrade
2. Rewrite the source code to be more polished

※If I can develop at this level, I thought maybe I could quit being a baker and become a programmer, so I interviewed at several companies.
The results were disastrous: "Why a query builder? Use Eloquant," "Write classes, not functions," "Don't manage your own source code. Use GitHub," "What? You've never used PHPUnit?"...
I'll continue making and baking bread!!

Bonus: I think I'm a good baker. I won both a gold and silver medal in the sour dough category at the 2018 baking show in my town.
Hahaha.

## 📚 Documentation
For detailed usage instructions and test results, please refer to https://doc.bchplus.com/
