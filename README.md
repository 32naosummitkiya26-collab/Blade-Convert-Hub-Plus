# 🔄 Template Converter: HTML -> Blade/Django
BCH+ is a template converter that analyzes the DOM structure across multiple HTML files to identify shared components, then automatically separates them into Blade or Django template structures—Base layout, child views, and subviews.

![2](https://github.com/user-attachments/assets/a249c176-a209-4933-8996-e16cb16e423f) 　![3](https://github.com/user-attachments/assets/d83d35df-7c9e-4b84-bdec-e98198916ae3)


    🔍 Automatically detects and extracts common elements across files
  
    🧩 Converts to Laravel Blade or Django templates with proper layout hierarchy
  
    📦 Pre-registered theme files can be imported instantly—no manual upload required
  
    📁 Original HTML files can be uploaded and stored for reference or reuse(currently not possible due to disk space limitations)
  

Enables team members to share both HTML files and conversion results seamlessly.

## 🚀 Features
✅ Automated structural conversion from HTML to Blade/Django templates

✅ Supports layout constructs like @include, @yield, {% block %}, and more

✅ Batch conversion of multiple files via GUI interface

✅ It is extensible and will support frameworks that use a template structure similar to Smarty

    Twig, Jinja2, Yii2, ThinkPHP
    I haven't looked into what other frameworks' template structures it supports yet...

## 💡 Technical Innovations
- Original, lightweight DOM parsing algorithm

  AI: Analytical processing runs on the world's highest-spec servers.

  BCH+: Runs at a reasonable speed even on the world's lowest-spec development environment (HP Pavilion Win8.1, AMD A4-5000 1.50GHz, 6GB RAM).
On a $5/month rental server (specs unknown), it's blazingly fast!! (Actually, it's $10, but I signed up for it during a half-price campaign. Yay :)

- Flexible Template Structure Adjustment

    While the conversion logic itself is fixed, BCH+ allows developers to freely specify the DOM hierarchy to be converted. This allows developers to flexibly adjust the output template structure to suit project policies and client coding rules.

- Dynamic database sharding via .env configuration

    By simply modifying the .env file, the system can instantly adapt to changes in the number of sharded databases.

※As of May 2024, Copilot was unable to perform conversion. On August 16, 2025, I asked again—and now it can parse the DOM and perform conversion. On September 4, 2025, I asked Gemini, and it can do it too. Apparently this has been made possible with a recent system update.
    
## 📘 How to Use
BCH+ features an intuitive GUI, making it easy to operate without technical setup. No personal data is collected—just register a nickname and email address to get started. If you're curious, feel free to give it a try: 👉 https://bchplus.com

## 📌 Why I Created This

In September 2017, the Japanese takeaway restaurant that I ran with my wife went bankrupt. That's when I had the idea to improve the ordering system we were using and make it available for other people to use. In the process, the idea for Converter came about by chance.

The system was being developed using Laravel. After changing the .html extension and creating a blade file, I read Taylor Otwell's documentation and felt something was off.
The root cause of this feeling of discomfort was, in other words, that the "alternative methods" were in the spotlight, while the methods advocated by the framework developers were in the shadows.
Also, doing the manual work was a pain, so I looked for an automation tool, but there weren't any. So I started making it myself.

In November 2021, I successfully converted the first sample. In January 2022, I successfully converted the second.
The display tests in the execution environment also passed, so I was confident that this method would work.
In the end, I think the reason I've been able to continue developing BCH+ for eight years is because I wanted to eliminate this sense of incongruity.
And before I knew it, the AI ​​had caught up with me and surpassed me. Please laugh. :)

※I've been working as a baker since October 2017, and instead of sitting in front of my laptop for eight hours a day, I spend eight hours a day baking bread in front of the oven.
I developed it in an environment where I could code for just one or two hours a day.

## 📅 Future Development Schedule
If BCH+ is useful to you, I'll prioritize 1. If it's unnecessary, I'll prioritize 2.
1. Functional upgrade
2. Rewrite the source code to be more polished

※If I can develop at this level, I thought maybe I could quit being a baker and become a programmer, so I interviewed at several companies.
The results were disastrous: "Why a query builder? Use Eloquant," "Write classes, not functions," "Don't manage your own source code. Use GitHub," "What? You've never used PHPUnit?"...
I'll continue making and baking bread!! Summer is almost here... It's hard to stand in front of an oven big enough to roast a whole human body. The temperature is over 50 degrees...

Bonus: I think I'm a good baker. I won both a gold and silver medal in the sour dough category at the 2018 baking show in my town.
Hahaha.

## 📚 Documentation
For detailed usage instructions and test results, please refer to https://doc.bchplus.com/

## 🔙 Looking back over the past eight years,

I feel incredibly fortunate to have been given the opportunity to develop BCH+ for eight years.

There are many reasons for giving up. It's not just boredom, but also more external reasons.
For example, a pandemic could completely change my life and make it impossible to continue development, or health issues or family circumstances could make it impossible to continue development.
I gave up once. I think it was the third year. One winter morning, around 4am, I was sleepy and made some coffee (instant),
and while trying to code at the kitchen table, my hand slipped and the small cup of coffee ended up being gulped down by my laptop. . . . I heard a "bang!" and when my laptop fell, I thought, "It's over."
I hadn't made a backup in about three months, and I was working on something quite complicated, so I couldn't start over from memory.
I propped the laptop up on a bath towel, removed the coffee, and left it to dry in the shade for a week. I was honestly nervous when I turned it on.
I told myself that if it turned on, I'd keep going, but if not, I'd give up.

I just love coding. My wife likes to write blogs as a hobby, but I prefer writing code to writing.
Otherwise, I couldn't have continued for eight years without a salary.
During that time, I was making, baking and bagging bread every day. I sometimes wonder if BCH+ development was a way to relieve the stress of my monotonous and boring daily life.

Switching from the local development environment to the server took more time than I expected. I also spent a fair amount of time preparing things like writing documentation.
I realized that I hadn't properly coded in six months.
Whether or not BCH+ is popular with everyone, it's time to get back to coding.

Anyway, I'm going to the bakery again today to earn some money!!
