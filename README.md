[twitter-shield]: https://img.shields.io/twitter/follow/Tabnine_?style=social
[twitter-url]: https://bit.ly/2WHsEtD
[github-shield]: https://img.shields.io/github/stars/codota/Tabnine?style=social
[github-url]: https://bit.ly/36iGtUU
[youtube-shield]: https://img.shields.io/youtube/views/TKLkXh_c-Gw?style=social
[youtube-url]: https://bit.ly/36slY7c

[![Github Repo][github-shield]][github-url]
[![Youtube Demo Video][youtube-shield]][youtube-url]
[![Twitter Follow][twitter-shield]][twitter-url]

# Tabnine - AI Code Completion

**tl;dr** jump to [installation section](#installation)

Tabnine is an AI-powered code completion extension **trusted by millions of developers** around the world. Whether you’re just getting started as a developer or if you’ve been doing it for decades, Tabnine will help you code twice as fast with half the keystrokes – all in your favorite IDE.

### **The Right Tool for The Job**

Whether you call it **IntelliSense, intelliCode, autocomplete, AI-assisted code completion, AI-powered code completion, AI copilot, AI code snippets, code suggestion, code prediction, code hinting**, or **content assist**, you probably already know that it can save you tons of time, easily cutting your keystrokes in half.

Powered by sophisticated **machine learning models** trained on billions of lines of trusted **Open Source code** from GitHub, Tabnine is the most advanced **AI-powered code completion** copilot available today. And like GitHub, it is an essential tool for professional developers.

![With and without Tabnine Java](https://github.com/codota/TabNine/raw/master/with-and-without-tabnine-java.gif)

#### **Tabnine works with all major programming languages including:**

|     Python     |   Javascript    |   Java   |
| :------------: | :-------------: | :------: |
|  extended JS   |    **React**    |   PHP    |
| **Typescript** |    C Header     |   Bash   |
|       ML       |      Swift      | **Ruby** |
|      Perl      |    **Rust**     |   SQL    |
|    **Vue**     |       F#        |  Scala   |
|     Julia      |      TOML       |  Shell   |
|      YMAL      | **C / C++/ C#** |   HTML   |
|      Lua       |    Markdown     | Haskell  |
|     **Go**     |   Objective C   | **JSON** |
|   CSS / SCSS   |   **Angular**   |  Kotlin  |


### **Our Vision**

Knowing that most of the code generated today has been created before begs the question - what if developers didn’t need to remember it, search for it, and type it again?

Learning from the past, focusing on the future, that’s the bedrock Tabnine is built on. Our AI-powered code completion tool embodies that vision by harnessing the collective achievements of every qualified piece of open source code ever written and serving that knowledge to our users in the form of code completion suggestions. As we move forward, Tabnine’s AI will play a valuable role in shaping the entire software development lifecycle.

Tabnine’s AI studies mountains of publicly available open source code and combines that with knowledge of your specific project and preferences creating code suggestions customized just for you. That saves you tons of keystrokes, and tons of time, all while keeping you aligned with best practices, and avoiding frustrating typos.

### **Pick the Plan that Works Best for You!**

**Tabnine Basic**
Tabnine’s Basic AI-powered code completion model is a fantastic time-saving tool for any developer. The Basic plan has plenty of free daily code completion suggestions to get you started, with no cost, no credit card, and no commitment.

**Tabnine Pro**
Supercharge your AI code completion suggestions with our advanced ML model, unlock unlimited code suggestions, customize your experience, and get priority support. Experience the power of Tabnine Pro today!

## **Installation**

Tabnine plugs into the following completion engines:

- YouCompleteMe 
- coc.nvim
- completion-nvim
- nvim-cmp
- deoplete.nvim
- ddc.vim
- nvim-compe

##### Not using any of the above? 
- If your completion engine is not supported - file a [feature request](https://github.com/codota/tabnine-vim/issues/new).
- If you don't use any completion engine - it's recommended that you follow the [YouCompleteMe](#youcompleteme) installation instructions.

### YouCompleteMe
Tabnine supports YouCompleteMe through a fork.
Follow the instructions here:
https://github.com/tabnine/YouCompleteMe#installation

### coc.nvim
A community plugin is available here:
https://github.com/neoclide/coc-tabnine

### completion-nvim
A community plugin is available here:
https://github.com/aca/completion-tabnine#install

### nvim-cmp
A community plugin is available here:
https://github.com/tzachar/cmp-tabnine

### deoplete.nvim
A community plugin is available here:
https://github.com/tbodt/deoplete-tabnine

### ddc.vim
A community plugin is available here:
https://github.com/LumaKernel/ddc-tabnine

### nvim-compe
A community plugin is available here:
https://github.com/tzachar/compe-tabnine


### **Investing In Our Community**

**FREE Tabnine Student Plan**
We know that tuition, books, rent, and food can get crazy expensive, that’s why Tabnine helps support the community and the dev superstars of tomorrow with a 100% free Tabnine Student license with all our Pro perks renewable for as long as you are a student.

[Join the Tabnine Student Program for free](https://www.tabnine.com/students?utm_source=ide_marketplace&utm_medium=organic&utm_campaign=vim_marketplace)


#### **FAQ**

Got a question? We’ve got the answer - Check out our [FAQ](https://www.tabnine.com/faq) page

#### **Tabnine Support**

Having some trouble with installation? Something not working the way you hoped? **Tabnine Support** is always happy to help. Feel free to contact us anytime at support@tabnine.com

#### **Privacy**

Your privacy is paramount, that’s why Tabnine uses a dual model design. While the public GPT-2 model works its magic continuously scanning hundreds of millions of trusted open source parameters, a second separate model runs locally on your machine keeping your code 100% private.

In addition, the local model focuses on learning your personal and project coding preferences, constantly improving the quality and accuracy of your code suggestions. Always separate. Always secure. Always private.

Find out more about how we keep your code private [here](https://www.tabnine.com/code-privacy)

#### **Tabnine Hub**

A quick click on **_Tabnine_** on your IDE status bar takes you directly to your **_Tabnine Hub_** where you can easily update and manage all your account options and customize your suggestion preferences.

### **Usage**

Tabnine is a textual autocomplete extension. When you type a specific string in your editor, you will be shown the Tabnine completion dialog box with suggestions for completing the code you’ve begun typing.

#### **Deep Completion**

Deep Tabnine is trained on millions of files from GitHub. During training, Tabnine’s goal is to predict the next token given the tokens that came before. To achieve this goal, Tabnine learns complex behavior, such as type inference in dynamically typed languages.

Deep Tabnine can use subtle clues that are difficult for traditional tools to access. For example, the return type of `app.get_user()` is assumed to be an object with setter methods, while the return type of `app.get_users()` is assumed to be a list.

Deep Tabnine is based on GPT-2, which uses the **_Transformers Network Architecture_**. This architecture was first developed to solve problems in natural language processing. Although modeling code and modeling natural language might appear to be unrelated tasks, modeling code requires understanding English in some unexpected ways.

- Tabnine Indexes your entire project and determines which files to ignore by reading your `.gitignore`
- Tabnine cuts your number of keystrokes in half and eliminates unnecessary typos
- Tabnine works right out of the box ensuring frictionless installation and configuration
- Tabnine offers code completion suggestions in less than 10 milliseconds

### Commuinities

- [Join the Tabnine Discord server](https://discord.gg/5GnbDg5Jmg)
- [Join the Tabnine community in Slack](https://join.slack.com/t/tabnine-community/shared_invite/zt-mi5n0v6f-4W0Ap4yAUQXS~nVvxwSoJg)

### **_Recommended by developers everywhere:_**

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-27.png" alt="William Candillon Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-7.png" alt="Imed Boumalek Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-14.png" alt="ramnivas Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-16.png" alt="bob paskar Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-19.png" alt="Nick Radford Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-28.png" alt="Hugues BR Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-32.png" alt="JohnyTheCarrot Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-33.png" alt="Donald E Fredrick Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-36.png" alt="Joshua Kelly Tweet" width="50%">

<img src="https://raw.githubusercontent.com/codota/tabnine-vscode/master/assets/twitter-ps-38.png" alt="JDerek Braid Tweet" width="50%">

### **Note:**

---

A note on licensing: this repo includes source code as well as packaged Tabnine binaries. The MIT license only applies to the source code, not the binaries. The binaries are covered by the [Tabnine Terms of Use](https://www.tabnine.com/terms).

---

The Vim client for Tabnine is adapted from [YouCompleteMe](https://github.com/Valloric/YouCompleteMe).
This client is an incompatible fork of YouCompleteMe, so please do not contact the YCM maintainers regarding any problems with it. Instead, create an issue in this repository.
