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

I also found the manual work tedious and looked for automation tools—but none existed. So I decided to build one myself.

In November 2021, I successfully converted the first sample. In January 2022, I successfully converted the second.
Since the display test in the runtime environment also passed, I was confident that this approach would work.
Ultimately, I think the reason I've been able to continue developing BCH+ for eight years is to resolve this sense of discomfort.
It was to resolve my own indigestion. Sometimes I wonder if I'm stupid for taking so long.

If I had focused solely on the conversion, the AI ​​would have caught up with me and surpassed me in no time. Please laugh. :)

※I've been working as a baker since October 2017, and instead of sitting in front of my laptop for eight hours a day, I spend eight hours a day baking bread in front of the oven.
I developed it in an environment where I could code for just one or two hours a day.

## 📅 Future Development Schedule
If BCH+ proves useful to others, I’ll prioritize option 1. If it turns out to be unnecessary for the world, I’ll focus on option 2.

1.Functional upgrades

2.Refactoring into more elegant, polished source code

※At one point, I thought: “If I can develop something like this, maybe I should quit baking and become a programmer.” So I went to a few job interviews. The results were… brutal. “Why are you using Query Builder? Use Eloquent.” “Don’t write functions—write classes.” “Don’t manage your source code manually. Use GitHub.” “What? You’ve never used PHPUnit?”

So yeah… I’m still baking bread.

Bonus: I think I’m a pretty solid baker, actually. In 2018, I won both gold and silver medals at this town’s baking show. Hahaha.

## 📚 Documentation
For detailed usage instructions and test results, please refer to https://doc.bchplus.com/
