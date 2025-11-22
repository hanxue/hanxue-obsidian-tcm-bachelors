---
{"dg-publish":true,"permalink":"/productivity/integrate-deepseek-with-obsidian/"}
---

集成Copilot 的Obsidian插件
Integrate the Copilot Obsidian plugin

-> <kbd>Ctrl</kbd>-<kbd>P</kbd> to open Settings
-> Go to <kbd>Community Plugins</kbd>, click <kbd>Browse</kbd>
-> Search for Copilot obsidian://show-plugin?id=copilot 
-> Install Copilot plugin, <kbd>Enable plugin</kbd>, click on <kbd>Options</kbd>
-> In <kbd>Copilot Settings</kbd>, in the <kbd>General</kbd> tab, scroll down to <kbd>API keys</kbd>

![20251122_obsidian_deepseek_01.webp](/img/user/Productivity/20251122_obsidian_deepseek_01.webp)

-> Scroll down to <kbd>DeepSeek</kbd>, and enter your **Deepseek API** key. You will need to first purchase Deepseek API credits at https://platform.deepseek.com (you can always start with $1). The key looks something like <kbd>sk-182b7e9a9xxxxxxxx</kbd>
-> DISABLE <kbd>Include Current Note in Context Menu</kbd> , or else every time you chat with deepseek, it will send the entire Obsidian note, and cause a lot of input token ($ $ $)
![20251122_obsidian_deepseek_02.webp](/img/user/Productivity/20251122_obsidian_deepseek_02.webp)


-> Click on the Model tab, select only the deepseek-chat and deepseek-reasoner models

-> In the Command tab, select Translate to Chinese. You can also make Translate to English command with the following code:

Translate {} into English:
    1. Preserve the meaning and tone
    2. Maintain appropriate medical and scientific context
    3. Keep formatting and structure
    Return only the translated text.

Take note that when you include Obsidian Note, it will cost 10,000 tokens or more, especially if your Note is lengthy. 
