# 🔄 Template Converter: HTML -> Blade/Django
BCH+ is a template converter that analyzes the DOM structure across multiple HTML files to identify shared components, then automatically separates them into Blade or Django template structures—Base layout, child views, and subviews.

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
    
## 📘 How to Use
BCH+ features an intuitive GUI, making it easy to operate without technical setup. No personal data is collected—just register a nickname and email address to get started. If you're curious, feel free to give it a try: 👉 https://bchplus.com

## 💡 Technical Innovations
- Original, lightweight DOM parsing algorithm

    While AI typically performs parsing on ultra high-spec servers, BCH+ can handle parsing on a modest setup
    (Windows 8.1, AMD A4-5000 1.50 GHz, 6GB RAM).

- Dynamic database sharding via .env configuration

    By simply modifying the .env file, the system can instantly adapt to changes in the number of sharded databases.

※As of May 2024, Copilot was unable to perform conversion. On August 16, 2025, I asked again—and now it can parse the DOM and perform conversion. On September 4, 2025, I asked Gemini, and it can do it too. Apparently, this became possible thanks to a recent system update.

## 📌 Why I Created This

In September 2017, the Japanese takeaway business I ran with my wife went bankrupt. That experience sparked the idea to improve the ordering system we had built and make it usable for others.

The system was developed in Laravel. After converting the .html files into Blade templates, I read Taylor Otwell’s documentation and felt a sense of discomfort. That discomfort, when I tried to put it into words, came from the fact that “alternative methods” were in the spotlight, while the approach proposed by the framework’s creator seemed to be left in the shadows.

I also found the manual work tedious and looked for automation tools—but none existed. So I decided to build one myself.

In November 2021, I successfully converted the first sample. In January 2022, I completed the second. After passing display tests in the runtime environment, I felt confident that this method would work.

Looking back, I think the reason I’ve been able to keep developing BCH+ for eight years is because I needed to resolve that discomfort. It was about digesting something that hadn’t sat right with me. Sometimes I wonder if I’m a fool for spending so much time on this—but here I am.

When I focused solely on conversion, AI quickly caught up and overtook me. Go ahead and laugh. :)

※Since October 2017, I’ve been working as a baker. Instead of sitting in front of a laptop for 8 hours a day, I spend 8 hours in front of an oven baking bread. I developed this in an environment where I could maybe code for 1–2 hours a day, if I was lucky.

## 📅 Future Development Schedule
If BCH+ proves useful to others, I’ll prioritize option 1. If it turns out to be unnecessary for the world, I’ll focus on option 2.

1.Functional upgrades

2.Refactoring into more elegant, polished source code

※At one point, I thought: “If I can develop something like this, maybe I should quit baking and become a programmer.” So I went to a few job interviews. The results were… brutal. “Why are you using Query Builder? Use Eloquent.” “Don’t write functions—write classes.” “Don’t manage your source code manually. Use GitHub.” “What? You’ve never used PHPUnit?”

So yeah… I’m still baking bread.

Bonus: I think I’m a pretty solid baker, actually. In 2018, I won both gold and silver medals at this town’s baking show. Hahaha.

## 📚 Documentation
For detailed usage instructions and test results, please refer to https://doc.bchplus.com/
