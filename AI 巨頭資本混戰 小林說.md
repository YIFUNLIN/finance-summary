我把整份逐字稿完整看完了，也把裡面容易辨識錯的人名、公司名、產品名稱與幾個重要數字重新核對過。這一集真正想講的，其實不是單純「誰投資了誰」，而是：**AI 產業已經形成一張非常複雜的資本＋算力＋晶片＋雲端服務網路。表面上大家互相競爭，實際上又互相投資、互相買服務、互相綁長期訂單。** 只要先理解這個核心，後面所有看似混亂的關係就會變得很好懂。

## 先理解整個 AI 產業鏈：其實可以拆成四層

這集把目前 AI 產業大致拆成四層。最底層是**晶片與 AI 加速器**，包括 NVIDIA GPU、AMD Instinct、Google TPU、Amazon Trainium，以及 Broadcom 協助設計的客製化 ASIC。再上去是**資料中心與雲端算力**，主要玩家包括 AWS、Microsoft Azure、Google Cloud，以及近年大量興建 AI 資料中心的其他基礎設施業者。第三層才是大家最熟悉的**前沿大型模型公司**，例如 OpenAI、Anthropic 的 Claude，以及 Google 的 Gemini。最上面則是各種真正給使用者使用的 AI 應用。

這裡最重要的是理解：**每一層的商業邏輯不一樣。** NVIDIA 想賣更多 GPU；AWS、Azure、Google Cloud 想賣更多算力；OpenAI、Anthropic 想取得足夠便宜而且穩定的算力來訓練與運行模型；Google、Amazon、Microsoft、Meta 這類超級巨頭則同時跨好幾層，所以它們既是供應商、客戶、競爭者，又可能是彼此的股東。這就是為什麼 AI 資本圈看起來會那麼亂。

以晶片來說，NVIDIA 目前仍然是整個 AI 基礎設施最關鍵的供應商之一，近期估計在 AI 加速器領域仍占超過 80% 的主導地位；但 Google、Amazon、Meta、OpenAI 等大型玩家都在想辦法降低單一依賴，這也是 TPU、Trainium、AMD Instinct 與客製化 ASIC 愈來愈重要的原因。([Reuters][1])

---

# 整場資本混戰的中心，其實就是 OpenAI 與 Anthropic

如果把 Google、Microsoft、Amazon、Meta 這些巨頭先放到旁邊，真正站在這場資本競賽中心的是 **OpenAI 與 Anthropic**。原因很簡單：它們不像 Google 一樣背後有龐大搜尋、廣告和雲端業務可以自己供血，而是純粹以前沿 AI 模型為核心，因此需要不斷籌集非常巨額的資本來買 GPU、租資料中心、訓練模型。逐字稿也把這兩家公司視為整張投資關係圖的中心。

而 2026 年最戲劇性的變化，就是 **Anthropic 已經不再只是 OpenAI 後面的小追兵**。Anthropic 在 2026 年 5 月完成高達 **650 億美元 Series H 融資，投後估值來到 9,650 億美元**，一度正式超過 OpenAI。Anthropic 官方公布，其 annualized run-rate revenue，也就是按照目前營收速度推算的一年收入水準，已經突破 **470 億美元**。這裡要特別理解：ARR 並不等於它真的在過去十二個月已經收到 470 億美元，而是「以目前收入速度年化」後的數字。([Anthropic][2])

OpenAI 這邊也完全不是弱者。2026 年 2 月 OpenAI 完成規模驚人的 **1,100 億美元融資**，投資者包含 Amazon 500 億、NVIDIA 300 億與 SoftBank 300 億美元，交易後估值約 **8,400 億美元**。換句話說，現在已經不是「OpenAI 遙遙領先、Anthropic 追趕」，而是兩家接近兆美元估值的 AI 公司，同時在瘋狂搶資金與算力。([Reuters][3])

而 Anthropic 爆發性成長的一個重要原因就是 **Claude Code**。逐字稿裡多次被轉錄成「Cloud Code」，正確名稱是 Claude Code。它在程式開發、Agent 與企業工作流程中的快速普及，使 Anthropic 在企業與開發者市場的地位快速上升，也讓原本只需要防 OpenAI 的 Google、Microsoft、Amazon、NVIDIA 開始重新評估自己的下注方式。

---

# Microsoft：最早押中 OpenAI，但現在開始分散風險

Microsoft 是這場 AI 投資大戰裡非常重要的一家公司，因為它是最早真正大規模押注 OpenAI 的科技巨頭。早期累計投入 OpenAI 約 130 億美元，使 Azure 成為 OpenAI 最重要的基礎設施合作夥伴之一，也讓 Microsoft 取得大量技術授權與經濟權益。經過後續重組，目前 Microsoft 仍持有 OpenAI 約 **27% 權益**。([Breakingviews][4])

所以早期 Microsoft 的策略非常簡單：**我不一定要自己打造世界第一的大模型，只要 OpenAI 成為世界第一，而它大量使用 Azure，我一樣可以贏。**

但問題也因此出現。OpenAI 愈長愈大之後，就愈不希望自己完全被 Microsoft 綁死。因此 OpenAI 開始與 Oracle、Amazon、NVIDIA、AMD、Broadcom 等其他公司合作，Microsoft 與 OpenAI 的關係逐漸從「幾乎綁在一起」變成更正常的戰略合作。

更有意思的是 Microsoft 後來甚至開始投資 **Anthropic**。2025 年 Microsoft、NVIDIA 與 Anthropic 宣布合作，Anthropic 承諾購買 **300 億美元 Azure 算力**；Microsoft 最多投資 Anthropic 50 億美元，NVIDIA 最多投資 100 億美元。([Microsoft Blog][5])

也就是說，Microsoft 現在的邏輯變成：**OpenAI 我當然繼續押，但我也不能假設 OpenAI 一定永遠贏，所以 Claude 也進 Azure。**

這其實就是整個 AI 資本圈的共同心態。

---

# Amazon：原本重押 Anthropic，後來乾脆 OpenAI 也一起押

Amazon 的故事更能看出這個變化。

Amazon 很早就在扶持 Anthropic，因為當 Microsoft 已經深度綁定 OpenAI 時，再去當 OpenAI 的第二順位合作夥伴吸引力沒那麼大。因此 Amazon 把 Anthropic 拉進 AWS 生態系，讓 Claude 使用 AWS 和 Amazon 自研的 **Trainium AI 晶片**。

到 2026 年雙方合作進一步擴大，Anthropic 承諾未來十年向 AWS 採購超過 **1,000 億美元**的雲端與算力服務，取得最多約 **5GW** 的 AI 運算容量，而且 Anthropic 已經大量使用 Trainium2。([Anthropic][6])

但 Amazon 後來也發現：「如果最後贏的是 OpenAI 呢？」

於是 2026 年 Amazon 又宣布最高投資 **500 億美元 OpenAI**。第一階段投入 150 億，其餘按照條件陸續投入。([Amazon News][7])

同一時間，Amazon 對 Anthropic 的投資承諾又提高到最多約 **250 億美元**。([Reuters][8])

所以 Amazon 現在的打法就是典型的：

**我不猜誰是最後的 AI 王者，我兩個都押。**

而且只要 OpenAI、Anthropic 最後都大量使用 AWS、Trainium 或 Amazon 的基礎設施，Amazon 不一定需要自己擁有最強模型也能賺錢。

---

# Google 更有趣：Claude 明明是 Gemini 的競爭對手，Google 卻照樣砸 400 億美元

Google 的情況是整集最能代表 AI 時代「競爭與合作同時存在」的例子。

Google 自己有 Gemini，理論上 Anthropic 的 Claude 就是直接競爭者。但 Google 同時又有非常強大的 Google Cloud 和 TPU，所以從另一個角度看，Anthropic 又是 Google 非常理想的大客戶。

2026 年 4 月，Google 宣布最高投資 **400 億美元 Anthropic**。其中 100 億美元先投入，另外 300 億美元視 Anthropic 達成特定績效條件後投入。([Reuters][8])

更重要的是，Anthropic 還與 **Google＋Broadcom** 簽署數 GW 等級的 TPU 算力合作，新的容量將從 2027 年陸續上線。([Anthropic][9])

所以 Google 實際上的思維不是：

「Claude 是 Gemini 的敵人，所以我不能幫它。」

而是：

**「模型層我跟你打，但基礎設施層你最好把錢付給我。」**

這就是現在 AI 產業非常重要的特徵：**同一家公司可以同時是競爭者、供應商和股東。**

---

# Anthropic 的真正厲害之處：它把所有雲端與晶片供應商都拉進來了

Anthropic 現在有一個非常特殊的優勢，就是它幾乎成為主要 AI 基礎設施供應商的共同客戶。

它使用 Amazon 的 **Trainium**，使用 Google 的 **TPU**，同時也使用 **NVIDIA GPU**；Microsoft Azure 上也有 Claude。

Anthropic 官方甚至直接說，它現在的模型會運行在 **AWS Trainium、Google TPU 和 NVIDIA GPU** 等多種硬體上。([Anthropic][10])

因此不能簡化成「Anthropic 不使用 NVIDIA」。比較精確的理解是：**Anthropic 是目前最積極採取多供應商策略的前沿模型公司之一。**

這對 Anthropic 有一個巨大好處：不會被單一晶片或雲端供應商掐住脖子，而且 Amazon、Google、Microsoft、NVIDIA 全部都有經濟利益希望 Claude 繼續成長。

甚至連馬斯克陣營都加入了。2026 年 5 月 Anthropic 與 SpaceX 達成算力合作，取得 Colossus 1 資料中心全部算力，包含超過 **22 萬顆 NVIDIA GPU、300MW 以上容量**。([Anthropic][10])

所以現在 Anthropic 的真正戰略優勢之一，不只是 Claude 模型強，而是它把自己變成了一個「**所有基礎設施巨頭都不希望它失敗的公司**」。

---

# OpenAI 的策略則不同：我要把全世界的算力都先訂下來

OpenAI 的風格比 Anthropic 更激進。

它不只是跟某一家雲端公司合作，而是在同時向 Microsoft、Amazon、Oracle、NVIDIA、AMD、Broadcom 等大量公司鎖定未來算力。

最知名的當然就是 **Stargate（星際之門）**。

Stargate 最初在 2025 年公布時，目標是在四年內於美國投資最高 **5,000 億美元** AI 基礎設施，初期計畫先投入 1,000 億美元。主要初始出資方為 **SoftBank、OpenAI、Oracle 與阿布達比 MGX**。SoftBank 主要負責資金，OpenAI 主要負責營運。([OpenAI][11])

而 Stargate 並沒有消失。比較準確的理解是：它後來從一個看起來像單一巨大聯合計畫的概念，逐步演變成由不同合作夥伴共同建設的多個資料中心專案。OpenAI 與 Oracle 已宣布額外 **4.5GW** Stargate 容量，加上德州 Abilene 等基地，已有超過 5GW 容量進入開發；2026 年包括密西根等新的 Stargate 資料中心也仍在施工。([OpenAI][12])

所以你可以把 Stargate 理解為：

**OpenAI 不想永遠只是租 Microsoft Azure，而是想建立一個跨 Oracle、SoftBank、能源公司、資料中心商與晶片商的巨大算力供應網。**

---

# NVIDIA 才可能是整張圖最舒服的人

如果 OpenAI 與 Anthropic 是牌桌中央兩個最受矚目的玩家，那 NVIDIA 就很像「開賭場的人」。

因為不管最後 OpenAI 贏、Anthropic 贏、Meta 贏、Google 贏，市場只要需要更多 AI 算力，就有人需要買 NVIDIA GPU。

而 NVIDIA 現在又不滿足於只當供應商，它開始利用自己龐大的現金流**投資自己的客戶與整個 AI 生態系**。

例如 OpenAI 2026 年 1,100 億美元融資中，NVIDIA 就承諾投入 **300 億美元**。([Reuters][3])

NVIDIA 又與 Anthropic 建立技術合作，並承諾最高投資約 **100 億美元**。([Microsoft Blog][5])

它同時還投資 Intel、SpaceX、CoreWeave 以及大量 AI 基礎設施與新創公司。

因此 NVIDIA 的商業邏輯非常漂亮：

**我給你錢 → 你有錢建 AI → 你需要算力 → 最後很多錢又拿來買我的 GPU。**

這正是市場現在常講的 **circular financing（循環融資）** 或 vendor financing（供應商融資）爭議。

---

# AMD 為了搶進這張牌桌，甚至拿「股權選擇權」換 OpenAI 和 Meta 的超大訂單

AMD 是另一個非常值得理解的案例。

OpenAI 在 2025 年與 AMD 達成協議，未來最高部署約 **6GW AMD GPU**。為了換取這個巨大客戶，AMD 同時給 OpenAI 一份 performance-based warrant，也就是績效條件式認股權證，最高可以購買 **1.6 億股 AMD 股票，履約價每股 0.01 美元**。([Advanced Micro Devices, Inc.][13])

這不是「AMD 立刻免費送 OpenAI 10% 股份」。真正的條件是：OpenAI 必須真的逐步購買 AMD GPU、達成不同的採購與股價等里程碑，認股權才一批批 vest。

2026 年 AMD 又把幾乎相同的模式用在 Meta 身上：Meta 最高部署 **6GW AMD Instinct GPU**，AMD 也給 Meta 最高 1.6 億股、每股 0.01 美元的績效式 warrant。([SEC][14])

這其實透露了一個非常重要的產業現象：

**現在頂級 AI 客戶的議價能力已經強到，晶片公司願意拿潛在股權來換長期算力訂單。**

因為一旦 OpenAI、Meta 真的大規模採用 AMD，AMD 就有機會打破 NVIDIA 的部分壟斷。

---

# Broadcom 則是另一種玩法：它不一定跟 NVIDIA 正面打，而是幫巨頭打造自己的晶片

Broadcom 在這張圖裡的角色比較不像 NVIDIA 或 AMD。

它的核心價值在於**客製化 ASIC 與網路晶片**。Google TPU 本身就是 Google 長期自研的 AI 加速器，而 Broadcom 是 Google 重要的客製化晶片合作夥伴；Anthropic 2026 年擴張 Google TPU 算力的合作中，也直接把 Google 與 Broadcom 一起列為合作對象。([Anthropic][9])

因此 Broadcom 其實是在押另一條未來：

如果未來所有科技巨頭都開始覺得「NVIDIA 太貴，我想打造自己的 AI 晶片」，那**Broadcom 反而可能是最大的受益者之一**。

---

# 真正需要理解的不是「投資金額」，而是這些錢通常附帶算力訂單

這其實是整集最重要的一個觀念。

OpenAI 和 Anthropic 看起來好像一直在瘋狂融資，幾百億、幾千億美元不斷進來，但這些並不是傳統意義上的「投你錢，你拿去隨便發展」。

很多投資實際上都有非常深的商業條件。

例如 Amazon 投資 OpenAI，同時希望 OpenAI 使用 AWS 與 Trainium；Google 投資 Anthropic，同時供應 TPU；NVIDIA 投資 OpenAI、Anthropic，同時希望它們持續使用 NVIDIA 架構；Microsoft 投資 AI 公司，最終又會帶來 Azure 消耗量。逐字稿真正想指出的就是：這些融資往往伴隨大量未來算力、雲端與晶片採購承諾。

所以整個循環可能變成：

**科技巨頭投資 AI 公司 → AI 公司拿到資金 → AI 公司向這些巨頭購買 GPU／雲端／資料中心 → 巨頭營收增加 → 巨頭再投入更多 AI。**

這也是為什麼外界會爭論這到底是健康的產業投資，還是某種程度上的「循環資本」。

---

# 為什麼大家明明互相競爭，卻還一直互相投資？

因為現在沒有人真的知道 5 年後誰會贏。

Google 當然希望 Gemini 最強，但如果最後 Claude 最強，它至少還希望 Claude 用 Google TPU。

Amazon 當然希望 AWS 和 Trainium 成為主流，但它不知道 OpenAI 還是 Anthropic 會贏，因此乾脆兩家公司都投。

Microsoft 已經重押 OpenAI，但又開始把 Claude 拉進 Azure。

NVIDIA 更簡單，只要整個 AI 市場愈大，它就能賣更多晶片。

因此逐字稿最後用一句話概括整個關係其實非常準：

**「同一層互相競爭，不同層互相捆綁。」** 

模型跟模型競爭、GPU 跟 GPU 競爭、雲端跟雲端競爭；但晶片公司＋雲端公司＋模型公司之間，卻會形成非常深的合作。

---

# 但這也創造了一個很大的系統性風險

這種模式對單一公司反而可以降低風險。

Anthropic 同時用 TPU、Trainium、NVIDIA GPU，就不怕某一個供應商出問題；OpenAI 同時找 Azure、AWS、Oracle、NVIDIA、AMD、Broadcom，也降低單一供應商風險。

但從整個 AI 產業來看，反而產生另一種風險：

**所有大公司開始被綁在一起。**

逐字稿用「很多艘船綁在一起」形容得非常好。單獨一艘船比較不容易翻，但如果真的發生一場足夠大的火災，可能一起出事。

最可能的「火」並不一定是 AI 技術突然失敗，而可能是**算力需求沒有市場原本預估那麼高、AI 商業化收入跟不上資本支出、電力與資料中心建設跟不上、融資成本上升，或者某個關鍵大型 AI 公司出現財務問題**。

因為現在已經有大量 GPU、土地、電力、資料中心與長期租約，是建立在「未來 AI 算力需求會繼續暴增」這個假設之上。

如果這個假設成立，整個鏈條非常漂亮：

AI 使用量增加 → 模型公司營收增加 → 買更多算力 → AWS/Azure/Google Cloud 成長 → NVIDIA/AMD/Broadcom 出貨增加 → 資料中心持續建設。

但如果需求低於預期，反方向同樣會連鎖傳導。

---

# 把整集濃縮成一張腦中的圖

你可以把現在的 AI 世界想像成這樣：

最中間是 **OpenAI 與 Anthropic**，兩家公司瘋狂需要「錢＋晶片＋電力＋資料中心」。

外圍第一圈是 **Microsoft、Amazon、Google**，手上握著錢和全球最大的雲端基礎設施，所以它們一邊發展自己的 AI，一邊投資最強的模型公司。

再外面是 **NVIDIA、AMD、Broadcom**。NVIDIA 現在仍是最強的 AI 晶片供應商；AMD 用低價與股權激勵積極搶大型客戶；Broadcom 則押注科技巨頭自研 ASIC。

再外面則是 **Oracle、SoftBank、SpaceX、資料中心商、能源公司與主權基金**，負責提供土地、資金、電力與超大型資料中心。

而這些圈層現在正在愈綁愈緊。

---

## 最值得你從這集真正帶走的結論

如果你只是記「Amazon 投了誰幾百億、Google 又投了誰幾百億」，很快數字就會過時。真正值得記住的是：**AI 競爭已經從單純比較「誰的模型比較強」，進化成比較誰能建立最強的資本與算力聯盟。**

OpenAI 的武器是極度積極地提前鎖定全球算力；Anthropic 的武器是快速成長加上高度多元化的雲端與晶片供應商；Google 的優勢是 Gemini＋TPU＋Google Cloud 垂直整合；Amazon 的優勢是 AWS＋Trainium＋龐大現金流；Microsoft 則有 Azure 與 OpenAI 長期關係；NVIDIA 的位置更特殊，它不一定需要猜最後哪個模型贏，只要整個產業持續擴張就可能是最大受益者之一。

而到了 2026 年，資本市場又進入下一個階段：**SpaceX 已在 6 月完成史上規模極大的 IPO；OpenAI 已秘密遞交上市申請但尚未確定上市時間；Anthropic 也已秘密申請上市，並傳出最快可能在 2026 年 9 月底至 10 月掛牌。** ([Investing.com][15])

所以接下來真正值得觀察的，不只是「下一代 GPT、Claude 或 Gemini 誰 Benchmark 第一」，而是三件事：**AI 公司營收能不能追上恐怖的算力支出、數兆美元級資料中心投資能不能產生足夠報酬，以及 OpenAI／Anthropic 上市後，公開市場願意給這種高成長但同時背負巨額算力承諾的公司多少估值。**

這三件事，才會真正決定現在這場 AI 資本盛宴究竟是下一個長達十年以上的科技基礎建設週期，還是最後會出現一次很大的資本重新定價。

[1]: https://www.reuters.com/commentary/breakingviews/financiers-are-set-turn-nvidia-into-an-ai-baron-2026-09-02/?utm_source=chatgpt.com "Financiers are set to turn Nvidia into an AI baron"
[2]: https://www.anthropic.com/news/series-h?asuniq=8ef50cfd&utm_source=chatgpt.com "Anthropic raises $65B in Series H funding at $965B post-money valuation \ Anthropic"
[3]: https://www.reuters.com/business/retail-consumer/openais-110-billion-funding-round-draws-investment-amazon-nvidia-softbank-2026-02-27/?utm_source=chatgpt.com "OpenAI's $110 billion funding round draws investment from Amazon, Nvidia, SoftBank"
[4]: https://www.breakingviews.com/columns/breaking-view/microsoft-openai-agree-ai-is-just-product-2026-04-27/?utm_source=chatgpt.com "Microsoft and OpenAI agree AI is just a product | Reuters"
[5]: https://blogs.microsoft.com/blog/2025/11/18/microsoft-nvidia-and-anthropic-announce-strategic-partnerships/?utm_source=chatgpt.com "Microsoft, NVIDIA and Anthropic announce strategic partnerships - The Official Microsoft Blog"
[6]: https://www.anthropic.com/news/anthropic-amazon-compute?source=syndication&utm_source=chatgpt.com "Anthropic and Amazon expand collaboration for up to 5 gigawatts of new compute \ Anthropic"
[7]: https://www.aboutamazon.com/news/aws/openai-amazon-partnership-explained?utm_source=chatgpt.com "Amazon’s $50 billion investment in OpenAI: What to know"
[8]: https://www.reuters.com/business/google-plans-invest-up-40-billion-anthropic-bloomberg-news-reports-2026-04-24/?utm_source=chatgpt.com "Google to invest up to $40 billion in AI rival Anthropic"
[9]: https://www.anthropic.com/news/google-broadcom-partnership-compute?gsid=44d84525-2cee-4a37-a6d7-ff2c2aa95f78&utm_source=chatgpt.com "Anthropic expands partnership with Google and Broadcom for multiple gigawatts of next-generation compute \ Anthropic"
[10]: https://www.anthropic.com/news/higher-limits-spacex?_bhlid=5426c5c4aec5de4d46656cbc5ae2953314c7a824&utm_source=chatgpt.com "Higher usage limits for Claude and a compute deal with SpaceX \ Anthropic"
[11]: https://openai.com/index/announcing-the-stargate-project/?utm_source=chatgpt.com "Announcing The Stargate Project | OpenAI"
[12]: https://openai.com/index/stargate-advances-with-partnership-with-oracle/?utm_source=chatgpt.com "Stargate advances with 4.5 GW partnership with Oracle | OpenAI"
[13]: https://ir.amd.com/financial-information/sec-filings/content/0001193125-25-230895/d28189d8k.htm?utm_source=chatgpt.com "October 6, 2025 - 8-K: Current report | Advanced Micro Devices, Inc. (AMD)"
[14]: https://www.sec.gov/Archives/edgar/data/2488/000000248826000045/amd-20260223.htm?utm_source=chatgpt.com "amd-20260223"
[15]: https://www.investing.com/news/stock-market-news/musks-spacex-prices-record-75-billion-ipo-at-135-a-share-4738207?utm_source=chatgpt.com "Musk’s SpaceX prices record $75 billion IPO at $135 a share By Reuters"
