# Hello, I'm oldip 👋

<div id="language-switcher">
    <a href="#english">English</a> | 
    <a href="#traditional-chinese">繁體中文</a> | 
    <a href="#simplified-chinese">简体中文</a>
</div>

<div id="english">
    <h2>Hello, I'm oldip 👋</h2>
    <p>I work in cybersecurity, with a strong interest in the field. I particularly enjoy researching emerging security threats and developing tools to address these challenges. My current focus is on malware analysis, threat intelligence, and penetration testing.</p>
    <p>Although my experience is still growing, I am committed to continuous learning and improving my skills through practice. I also enjoy working with various hardware tools, such as Flipper Zero, and have developed some auxiliary tools like <a href="https://github.com/oldip/FlipperNested-GUI">FlipperNested GUI</a> and <a href="https://github.com/oldip/DumpNFC-Converter">DumpNFC Converter</a> to simplify processes and enhance user experience.</p>
    <p>Thank you for your attention and support. I will continue to work hard to contribute more to the field of cybersecurity.</p>
</div>

<div id="traditional-chinese" style="display:none;">
    <h2>你好，我是oldip 👋</h2>
    <p>從事網絡安全相關工作，對這個領域充滿了濃厚的興趣。我特別喜歡研究新興的安全威脅，並開發工具來應對這些挑戰。目前，我主要關注惡意軟件分析、威脅情報收集和滲透測試。</p>
    <p>儘管我的經驗還在積累中，但我始終保持學習的熱情，並通過實踐不斷提升自己的技能。我也喜歡動手操作各種硬件工具，如Flipper Zero，並開發了一些輔助工具，比如 <a href="https://github.com/oldip/FlipperNested-GUI">FlipperNested GUI</a> 和 <a href="https://github.com/oldip/DumpNFC-Converter">DumpNFC 轉換器</a>，旨在簡化操作並提升用戶體驗。</p>
    <p>感謝您的關注和支持，我將繼續努力，為網絡安全領域貢獻自己的力量。</p>
</div>

<div id="simplified-chinese" style="display:none;">
    <h2>大家好，我是oldip 👋</h2>
    <p>从事网络安全相关工作，对这个领域充满了浓厚的兴趣。我特别喜欢研究新兴的安全威胁，并开发工具来应对这些挑战。目前，我主要关注恶意软件分析、威胁情报收集和渗透测试。</p>
    <p>尽管我的经验还在积累中，但我始终保持学习的热情，并通过实践不断提升自己的技能。我也喜欢动手操作各种硬件工具，如Flipper Zero，并开发了一些辅助工具，比如 <a href="https://github.com/oldip/FlipperNested-GUI">FlipperNested GUI</a> 和 <a href="https://github.com/oldip/DumpNFC-Converter">DumpNFC 转换器</a>，旨在简化操作并提升用户体验。</p>
    <p>感谢您的关注和支持，我将继续努力，为网络安全领域贡献自己的力量。</p>
</div>

<script>
    document.getElementById("language-switcher").addEventListener("click", function(e) {
        if (e.target.tagName === 'A') {
            var selectedLanguage = e.target.getAttribute('href').substring(1);
            document.getElementById("english").style.display = selectedLanguage === 'english' ? 'block' : 'none';
            document.getElementById("traditional-chinese").style.display = selectedLanguage === 'traditional-chinese' ? 'block' : 'none';
            document.getElementById("simplified-chinese").style.display = selectedLanguage === 'simplified-chinese' ? 'block' : 'none';
        }
    });
</script>
