# Продаж Command Center (CC) у Zero Hour 1.04: перевірка твердження

> Твердження користувача: «всі про-гравці після будівництва Supply Center і реактора продають головну базу (Command Center) за гроші, бо вона більше не потрібна».
> Середовище: C&C Generals – Zero Hour 1.04 (GenTool, CnC Online, Generals Online). Терміни гри англійською.
> Позначки джерел: [відео: назва, mm:ss] / [дані гри] / [веб: URL] / [висновок] / [невизначеність] / [немає даних].
> [дані гри] = INI-файли оригінальної ZH 1.04 (`Patch104pZH/GameFilesOriginalZH/Data/INI` у репозиторії TheSuperHackers/GeneralsGamePatch) та вихідний код EA (`electronicarts/CnC_Generals_Zero_Hour`). Точні шляхи наведено в розділі «Джерела».

## Короткий вердикт (окремо по кожній частині твердження)

| Частина твердження | Вердикт | Підстава |
|---|---|---|
| «Про-гравці продають CC» | **Так.** У 1v1 на старті це домінуюча практика. | GameReplays TotW #30: "the strategy became almost universal within the competitive community"; "it is the only way that China and USA players can pull off most 2-supply build orders" [веб: GameReplays TotW #30]. DoMiNaToR: "you're going to have to get used to it if you want to be competing with some of the best players" [відео: How to Play USA - Tutorial for beginners, 04:36–04:40]; "let's say I just played this like a normal 1 V one I just sold my Command Center" [відео: ZH - 2vs2 Strategy Guide - Part 1, 15:54]. Fandom: "sometimes sold for a small cash boost after basic construction had been completed" [веб: cnc.fandom]. |
| «Всі» / «завжди» | **Ні.** | GR прямо називає «MUST sell … 100% of the time» поширеною помилкою: "(and even some of the experts too!) sell their CC out of habit". USA Air Force часто тримає CC завдяки Chinook за $950, але це залежить від білду, а не є дефолтом (рядки 4, 8, 16, 18, 21, 24, 62, 65 — тримають; 9, 12, 13, 15, 28 — продають). Laser у реплеях проти GLA тримав CC (рядки 17, 19). У FFA на Flower Oases автор тримав CC (рядок 27). Для GLA обидва джерела кажуть «завжди» (рядки 47, 49; GR: "100% of the time for any general"). |
| «Після Supply і реактора» | **USA — по суті так. China — ні, раніше. GLA — не застосовне.** | USA: Power Plant у грі називається Cold Fusion Reactor [дані гри: `DisplayName = OBJECT:ColdFusionReactor`]. Порядок: Power першою → обидва Dozer ставлять 2 Supply Center → drone/scan → продаж; Supply в цей момент ще будуються (рядок 1). China: CC продають, щойно 2-й Dozer вийшов, коли Reactor ще будується, а Supply ще не поставлено (рядки 41, 43, 45). GLA: енергії й реактора немає, тригер інший — 5 Workers і поставлено fake Barracks / Tunnel (рядки 47, 50, 52). |
| «За гроші» | **Так.** | +$1000 (50% від ціни $2000), гроші приходять приблизно через 6 с після команди [дані гри]. |
| «Бо вона більше не потрібна» | **Ні.** | Без CC немає нових Dozer (USA/China), радару (USA/China), сил на CC (A-10, Artillery, Rebel Ambush…) і Cash Bounty (GLA). CC часто будують знову: "if you watch a lot of pro players, especially in 1v1, they'll put the CCs towards the sides of the map" [відео: Guide: How to play Defcon 6 FFA, 08:39–08:47]; повторний CC у реальній 1v1 [відео: 10x Pro 1v1 Matches, 32:08–32:45]; fandom: "a second center would be constructed later in the game". |

**Підсумок одним реченням:** про-гравці справді здебільшого продають стартовий CC у 1v1 заради $1000, але не «всі» і не «завжди», у China — ще до Supply, а не після, і CC потім часто будують знову, бо він потрібен для Dozer, радару й сил.

**Про квантори.** Слова «завжди» (GLA) і «майже завжди» (China) нижче — це заяви авторів (DoMiNaToR; для GLA і China ще й GameReplays 2007), а не підрахунок матчів. Статистики продажу CC за реплеями немає [невизначеність].

**Пошук.** Перевірено 76 транскриптів (75 з текстом). Ширший пошук (sell/sold/cell + cc/command/commands in/see see/the base) додав 10 фрагментів. Разом **71 релевантний фрагмент у 28 відео**: 66 рядків таблиці (у 25 відео) + 5 фрагментів механіки під нею (ще 3 відео). Кожен рядок має тип: **Р** — рішення продати чи тримати CC (свій або спостереження за суперником), **Н** — наслідки, ризики, повторне будівництво CC, **М** — механіка. Підрахунок: **Р = 44 рядки (у 17 відео), Н = 14 (у 10 відео), М = 8 (у 7 відео)**. Лічбу можна відтворити за колонкою «Тип».

---

## 1. Таблиця доказів з відео (автор усіх відео — DoMiNaToR)

Цитати взято з автосубтитрів YouTube дослівно, виправлення розпізнавання — у [квадратних дужках]. «Коли» — порядок дій, описаний автором. Таймкод відео ≠ ігровий таймер.

### USA (vanilla / Laser / Superweapon / Air Force)

| # | Тип | Відео (дата) / посилання | Контекст | Цитата (EN) | Що радить |
|---|---|---|---|---|---|
| 1 | Р | How to Play USA - Tutorial for beginners (2024-06-01) — [04:15](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=255s) | USA vanilla, базовий білд, Oil Oasis | "in reality here what we're going to do is actually sell our Command Center there are situations when there are loads of builds where you can keep your command center but in all of my initial builds here I'm going to sell my command center you need to get used to playing without that radar … you're going to have to get used to it if you want to be competing with some of the best players" | **Продати.** Коли: Dozer у черзі з першої секунди («only going to make two [dozers]», 02:20–02:26), першою Power («always make a power first», 02:30), обидва Dozer ставлять 2 Supply Center (03:19–04:10), drone/scan (04:11–04:13), продаж (04:13–04:15). Supply в цей момент ще будуються. Навіщо: гроші. Виняток: «loads of builds where you can keep». |
| 2 | Р | там само — [18:36](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=1116s) | No-eco білд (2 Humvee + Ambulance), гра проти AI (18:30) | "we're going to que up a load of missile Defenders sell our CC as always make a war factory" | **Продати.** Коли: Barracks попереду, Power, 1 Supply, у Barracks у черзі MD. Потім War Factory. |
| 3 | Р | там само — [26:44](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=1604s) | Проти GLA, Gold Cobra | "as if we are against some kind of a gla um yeah even beginner or mid-level glas or even top level glas … sell a cc in my case I can sell my CC by my [sell] key [hotkey] Z" | **Продати** проти GLA будь-якого рівня (26:29–26:48). Коли: після drone/scan, далі 2 Supply. |
| 4 | Р | там само — [33:07](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=1987s) | Розділ «Keeping CC with Air Force» | "why do players always sell CC in the beginning well if you get USA Air Force … what we're going to do now is keep the CC … our [chinook] here only cost $950 for USA Air Force … and they cost $1,200 … for the other USAs. Here I can still make my War Factory and still get two supplies with four [chinooks] … you can also keep your CC and it doesn't really slow your build down that much and then you've got unlimited scans" | **Тримати (Air Force).** Навіщо: дешеві Chinook дозволяють 2 Supply + 4 Chinook + WF без продажу. Скани CC працюють і далі. |
| 5 | Р | там само — [34:28](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=2068s) | Розділ «Keeping CC with USA» | "I'm going to keep our CC because our [chinook] cost more here as the USA our war Factory should be later … if I sold the CC I would be able to make a war [factory] now … your first fully loaded V is going to be a little bit slower in which case a gat or a technical might already [be] here" | **Тримати можна, але це ціна:** WF і перший loaded Humvee пізніше. |
| 6 | Р | там само — [35:28](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=2128s) | Там само | "so I mean you big see big size doing it a lot keeping his CC no matter what he is but if you are going to keep your CC i'd probably recommend dropping a dozer and just being a bit of a nuisance … which buys you some time to get your War Factory" | **Якщо тримаєш CC — зроби Dozer drop**, щоб відіграти час. [невизначеність]: «big size» — зіпсовані автосубтитри; чи це ім'я гравця і чи мова про CC «за будь-яких умов», не встановлено (див. §5). |
| 7 | Р | там само — [35:59](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=2159s) і [36:36](https://www.youtube.com/watch?v=CkSCpFsNY9c&t=2196s) | USA mirror drop (3 MD + Barracks) | "going to [sell] our Dozer sorry [sell] our CC build a second Dozer make a power" … "when your first missile Defender comes out sell your CC" | **Продати пізніше:** коли з Barracks вийде перший Missile Defender (36:36). [невизначеність]: у відео суперечність — на 35:59 «sell our CC build a second Dozer» (продаж перед 2-м Dozer неможливий: черга скасується), а на 36:36 — продаж після першого MD. Правило взято з 36:36. |
| 8 | Р | How to Play USA AIR FORCE (2023-07-14) — [01:44](https://www.youtube.com/watch?v=NtY82fKA82Q&t=104s) (розділ з 00:23) | Розділ «Commanches keep CC» | "we're gonna press D for a dozer on the CC and we're going to select our other Dozer and press R to build a power plant" (продажу в розділі немає; назва розділу — «Commanches keep CC») | **Тримати:** Dozer, Power, drone+scan, Supply, Chinook, Airfield, Comanche. |
| 9 | Р | там само — [08:23](https://www.youtube.com/watch?v=NtY82fKA82Q&t=503s) | Розділ «Commanches sell CC» | "this time we're going to sell the CC so it's a bit of a risk but you're gonna be able to get more units out quicker that's why you're selling it you get an extra 1000" | **Продати** після: Dozer у черзі на старті, Power, drone. Навіщо: більше юнітів раніше. Ризик визнає сам автор. |
| 10 | М | там само — [09:19](https://www.youtube.com/watch?v=NtY82fKA82Q&t=559s) | Там само | "so that cost eight hundred dollars your CC cost a thousand so you've actually still saved 200 overall" | Гроші з CC ($1000) повністю покривають 2-й Airfield ($800) [дані гри: AirF_AmericaAirfield = 800]. |
| 11 | Н | там само — [10:34](https://www.youtube.com/watch?v=NtY82fKA82Q&t=634s) | Там само | "if you time that two minutes 30 and I've got five Comanches out with another one on the way you will have more than if you [keep] the CC … more units are quicker you're less likely to die in the beginning and then you can rebuild your CC at any moment when you know you are in safety" | **Навіщо:** 5 Comanche на 2:30. **CC можна збудувати знову**, коли безпечно. |
| 12 | Р | там само — [20:20](https://www.youtube.com/watch?v=NtY82fKA82Q&t=1220s) | Carpet-bomb білд проти China Tank, 1 Supply | "Barracks sell CC" | **Продати** одразу після постановки Barracks; далі WF і Strategy Center. Автор сам каже, що білд «not that much recommended». |
| 13 | Р | там само — [23:12](https://www.youtube.com/watch?v=NtY82fKA82Q&t=1392s) | Fast strat проти Infantry | "sell the CC" | **Продати** на старті; далі Airfield, MD, Firebase, King Raptor. |
| 14 | Н | там само — [25:05](https://www.youtube.com/watch?v=NtY82fKA82Q&t=1505s) | Там само (атака) | "you hoping he sold this CC as well you can now use the carpet bomb to finish … then he's out of production out of [dozers] out of War Factory barracks" | **Ризик продажу для суперника (China):** без CC знищення Dozer і заводів = він не відновиться. |
| 15 | Р | там само — [26:27](https://www.youtube.com/watch?v=NtY82fKA82Q&t=1587s) | 1 WF + 1 Airfield проти Infantry, 2 Supply | "I'm gonna sell the CC … this is more normal because you're going to go two supplies it's more safe" | **Продати** на старті. |
| 16 | Р | там само — [30:20](https://www.youtube.com/watch?v=NtY82fKA82Q&t=1820s) | Air Force проти USA (drop), CC залишено | "if you did feel like you were gonna get really heavily dropped in the beginning you could have sold a cc you could have stopped one of these Chinooks and you could have built loads of infantry" | **Умовний продаж:** якщо чекаєш важкий drop, продай CC і вклади гроші в піхоту/Firebase. |
| 17 | Р | ZH - USA vs GLA Early/Mid Game Guide (2016-01-29) — [15:23](https://www.youtube.com/watch?v=wv7XnteELfo&t=923s) | Реплей: Laser проти GLA | "we're laser so you don't have to sell your command center is what I'm trying to show here" | **Тримати можна:** 100% збирання з першої секунди і рання War Factory. |
| 18 | Р | там само — [19:12](https://www.youtube.com/watch?v=wv7XnteELfo&t=1152s) | Реплей: Air Force проти GLA | "again there's no need to sell your command center this is another reason why air force is so strong because air force can [not-sell] a command center and get both supplies up straight away and build that war factory straight away because these Chinooks are cheaper" | **Тримати (AF).** |
| 19 | Р | там само — [20:12](https://www.youtube.com/watch?v=wv7XnteELfo&t=1212s) | Реплей: Laser проти GLA (Sanko) | "I'm laser in the top against the guy called Sanko again kept the command center and doing a dozer [drop]" | **Тримати + Dozer drop.** |
| 20 | М | там само — [21:45](https://www.youtube.com/watch?v=wv7XnteELfo&t=1305s) | Там само | "because I've got a command [center] you're able to place drones and scans everywhere so you can see what's coming" | Перевага CC: розвідка (Spy Drone, Spy Satellite Scan). |
| 21 | Р | 10x Pro 1v1 Matches With Commentary (2021-01-26) — [01:41](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=101s) | Game 1: Air Force, Summer Arena | "i'm going to keep my cc a lot of people say why do you always sell you[r] cc or why'd you keep your cc in certain situations well all i can tell you is that air force is one of the ones where you can … keep … your cc because the [chinooks] are cheaper" | **Тримати (AF)** у реальній 1v1. |
| 22 | Н | там само — [02:58](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=178s) | Там само | "yeah you see i kept the cc i've got a same amount of these out it's a little bit slower" | Ціна збереження CC: трохи повільніше. |
| 23 | Р | там само — [47:26](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=2846s) | Game 5 за розділами відео (автор на 46:59 рахує її шостою): USA проти GLA | "the thing is here there's only one oil here … let's keep the cc … instead of the oil I could do a third chinook" | **Тримати.** [невизначеність]: зв'язок «одна нафта → тримати CC» з субтитрів не однозначний; як правило не використовується (див. §5). |
| 24 | Р | там само — [54:31](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=3271s) | Game 6: USA проти Air Force | "he's keeping his cc and then i think he's placing the drone down earlier" | **Суперник-AF тримає CC** (і користується Spy Drone). |
| 25 | Н | ZH - 2vs2 Strategy Guide - Part 1 (2016-10-27) — [15:54](https://www.youtube.com/watch?v=0XsA_eRACbA&t=954s) | 2v2 проти Air Force, що будує Raptors | "let's say I just played this like a normal 1 V one I just sold my Command Center I went War Factory uh Barracks uh the first raptor is going to come along and he's going to kill one Dozer … two dozers … the second raptor … hit the power … I'm going to be left with no power" | **Ризик:** у командній грі проти Raptors звичний «1v1-продаж CC» веде до втрати Dozer без можливості відновлення. Заодно підтверджує, що в 1v1 продаж — норма. |
| 26 | Р | How to Play Defcon 6 - 3v3 No Rules (2021-01-19) — [05:49](https://www.youtube.com/watch?v=K9tZd7yzbtc&t=349s) | 3v3, USA | "gonna build one chinook i'm gonna sell my cc i'm going to build two missile defenders" | **Продати навіть у 3v3:** після Power, Barracks (2-й Dozer), Supply і 1 Chinook у черзі. |
| 27 | Р | How to play Flower Oases (FFA guide) (2025-12-28) — [06:42](https://www.youtube.com/watch?v=8IxbGLthyw4&t=402s) | FFA, USA eco boom | "If you've sold your CC, I mean, I kept my CC in this one. You could also sell it if you wanted to. If you sold the CC, what would be the benefit of it? You'd be able to afford the fire bases a little bit quicker. You might be able to drop down a second supply a little bit quicker. But I think on this map probably unless you're against some like mega mega top players, I think you can afford to keep your CC" | **Тримати (FFA, ця карта)**, якщо суперники не топові. |
| 28 | Р | He sold his CC before making dozer [Funny rush] (2025-10-17) — [00:27](https://www.youtube.com/watch?v=buBGjk5aVHg&t=27s), [04:00](https://www.youtube.com/watch?v=buBGjk5aVHg&t=240s), [21:56](https://www.youtube.com/watch?v=buBGjk5aVHg&t=1316s) | Generals Online, FFA на 6 гравців; гравець Diablo (Air Force) | "we've got an air force. Is he just sold his CC? Yeah, he has." … "Sold his CC, man … we've actually got one of the strongest players in here out." … "He sold his CC before a second dozer came out" (опис: "Diablo sold his CC before second dozer so we have to rush him!") | **Сильний AF-гравець продав CC** навіть у FFA, тобто AF теж продає. Помилка була в таймінгу: продаж до виходу 2-го Dozer (черга скасовується) → один Dozer → раш. |
| 29 | М | ZH - USA Air Force All-In Build Order (дата невідома) — [00:37](https://www.youtube.com/watch?v=zX82fLitLcw&t=37s), [01:23](https://www.youtube.com/watch?v=zX82fLitLcw&t=83s) | AF all-in: 2 Combat Chinook | "we're not going to build a dozer. We're going to have one dozer for this to save on cash" … "We can sell the war factory to get the extra 1,000 back" | Тут продають **War Factory** після замовлення Combat Chinook. Про CC у транскрипті нічого — [невизначеність]. |
| 30 | Р | Top 10 tips for beginners (2026-01-14) — [03:46](https://www.youtube.com/watch?v=-atetgj1_0E&t=226s) | Tip 5 «selling your CC», усі армії | "don't be afraid to sell your CC and learn to play without a radar. Now, if your aim is just to play against the easy or medium AI … then you can probably ignore this tip. However, if you do intend to play with anyone even remotely decent … or play against one or more hard AIs …" | **Продавати** проти сильних суперників і Hard AI. |
| 31 | Р | там само — [04:31](https://www.youtube.com/watch?v=-atetgj1_0E&t=271s) | Там само | "For sure, later on in the game, and especially on large maps and large team games like 3v3 and 4v4, then radar can help massively … But at the start of most matches, especially during 1v ones on simple maps … you're going to need that extra 1,000 cash to support bigger and better build orders than if you kept your CC." | **Обмеження:** продаж — це про старт 1v1 на простих картах. Пізніше і в 3v3/4v4 радар дуже допомагає. |
| 32 | Р | там само — [06:12](https://www.youtube.com/watch?v=-atetgj1_0E&t=372s) | Tip 6, USA | "Remember, you'll be selling your CC, making two supplies, and each of the supplies will have two shinuks on each before making a war factory and a barracks." | **USA-стандарт:** продати CC → 2 Supply × 2 Chinook → WF + Barracks. |
| 33 | Р | 5x PRO TIPS - Generals Zero Hour (2021-07-22) — [08:10](https://www.youtube.com/watch?v=gL-W3UM6lj8&t=490s) | Реплей | "i've got two cc's here this one was my starting one i didn't sell it in the beginning and then i've since built this one … to my knowledge the from what i remember the support powers always come from the latest cc" | Стартовий CC **не продано**, другий **добудовано**. Що сили летять від останнього CC — «to my knowledge» автора; код це підтримує (див. §2.2). |
| 34 | Н | там само — [10:07](https://www.youtube.com/watch?v=gL-W3UM6lj8&t=607s) | Мідгейм | "you might always want to build your cc defensively in front of oils … you can even build two ccs if you want to give that like extra protection" | Повторно збудований CC можна ставити як щит перед нафтою. |
| 35 | Н | Guide: How to play Defcon 6 FFA (2025-12-21) — [08:16](https://www.youtube.com/watch?v=e41NL-Spnfk&t=496s) | FFA, USA | "When I'm building a CC, I would not build a CC out of the front … most CCs, you want to be building against the corner of the map … because that's where the support powers are coming from" | CC будують знову пізніше; ставити біля краю карти. |

### China (vanilla / Tank / Nuke / Infantry)

| # | Тип | Відео (дата) / посилання | Контекст | Цитата (EN) | Що радить |
|---|---|---|---|---|---|
| 36 | Р | How to Play China - Tutorial for beginners (2024-04-24) — [05:00](https://www.youtube.com/watch?v=FeD9mpO9c2w&t=300s) | China vanilla, Double War Factory | "you can build two War factories two suppliers double War Factory and you can sell your CC for the extra 1,000 bonus otherwise you won't be able to afford the two War factories straight away" | **Продати** заради 2 Supply + 2 WF. |
| 37 | Р | там само — [07:59](https://www.youtube.com/watch?v=FeD9mpO9c2w&t=479s) | Загальна порада | "I've actually manually amended my hot keys so I can press Zed to sell my uh CC I would always probably recommend selling your CC as China vanilla … no matter pretty much what you're against um unless you start with like a 1K crate like you do on some maps … you want to get that extra [$1,000] remember you got one of the weakest armies in the game" | **China vanilla: продавати майже завжди.** Виняток: карти зі стартовим ящиком $1000. Цитата саме про vanilla («one of the weakest armies»). |
| 38 | Р | там само — [19:42](https://www.youtube.com/watch?v=FeD9mpO9c2w&t=1182s) | Double WF, Snowy Drought | "we're going to get this Dozer all the way over here cuz this is the longest distance away sell my CC I've got that on a hot key which is Zed" | **Продати** одразу після виходу Dozer. |
| 39 | Р | там само — [28:53](https://www.youtube.com/watch?v=FeD9mpO9c2w&t=1733s) | All-in проти USA (Red Guard) | "clear the mines through the CC [sell] CC once the [dozer] is left" | **Коли:** щойно 2-й Dozer покинув CC. |
| 40 | Р | там само — [37:05](https://www.youtube.com/watch?v=FeD9mpO9c2w&t=2225s) | Double Barracks, oil capture | "we're always going to build one Dozer rarely very rarely do you want to be building a third Dozer and very rarely do you want to be keeping your CC … always just get in the habit of playing without the radar" | **Продати.** Стандарт: 1 додатковий Dozer (разом 2). |
| 41 | Р | How to Play China - Part 1 (2020-06-29) — [04:41](https://www.youtube.com/watch?v=N_QRHPZkI5A&t=281s) | 2 Supply + 2 WF | "which is basically going to build two [dozers] you're going to sell your [command center] and then we're going to send our dozers to both of our two supplies" | **Продати** до будівництва Supply, одразу після 2-го Dozer; Reactor у цей момент ще будується (03:59–04:39). |
| 42 | Н | там само — [22:58](https://www.youtube.com/watch?v=N_QRHPZkI5A&t=1378s), [23:57](https://www.youtube.com/watch?v=N_QRHPZkI5A&t=1437s) | Мідгейм | "and then behind this you want to get a command center and then you want to uh try and expand" … "my command center is now built i'm gonna press a to get the radar" | **Повторно збудувати CC** у мідгеймі й купити Radar ($500). |
| 43 | Р | ZH - China Mirror All-In Build (2016-02-15) — [01:02](https://www.youtube.com/watch?v=ArZ0Bf-rxSM&t=62s) | China mirror, 1 Supply, WF + Helix | "we're going to build a dozer straight away we're going to build a power plant this first Dozer is going to go to the supply the one from the command center … immediately sell the command center … so you can get the supply as soon as this power plant is ready" | **Продати негайно**, щойно Dozer вийшов з CC (00:49–01:05). Power Plant ще будується, Supply ще не поставлено. |
| 44 | Р | ZH - Infantry Mirror Guide (2015-12-05) — [24:27](https://www.youtube.com/watch?v=9MAob362xiU&t=1467s) | China Infantry, MiG-білд; гра проти AI (23:52) | "[china's] going to sell the command [center] here" | **Продати** після виходу Dozer (Dozer замовлено 24:12–24:15, продаж 24:27). Єдиний рядок по Infantry, і це гра проти AI. |
| 45 | Р | How to play Flower Oases (FFA guide) (2025-12-28) — [08:17](https://www.youtube.com/watch?v=8IxbGLthyw4&t=497s), [08:36](https://www.youtube.com/watch?v=8IxbGLthyw4&t=516s) | FFA, China eco boom | "we're going to do an eco [boom] and we are going to sell our CC as the China … Always want to have two dozers … So, as soon as the dozer is ready, uh sell the CC, want to build a barracks." | **Продати навіть у FFA**, щойно готовий 2-й Dozer. |
| 46 | Н | How To All In Rush with China vs USA (2020-07-22) — [06:50](https://www.youtube.com/watch?v=IXN5QRA8XkE&t=410s) | Про ворожий CC | "the reason I didn't kill the CC first there is because the CC [is] useless yeah it can make [dozers] but the [dozer's] not gonna be able to do anything against this anyway" | Оцінка CC як цілі: у пізній атаці CC — низький пріоритет. Чи продавав автор свій CC у цьому білді, у тексті не сказано. |

### GLA (vanilla / Toxin / Demo / Stealth)

| # | Тип | Відео (дата) / посилання | Контекст | Цитата (EN) | Що радить |
|---|---|---|---|---|---|
| 47 | Р | How to Play GLA - Part 3 (2019-06-22) — [18:26](https://www.youtube.com/watch?v=g-6P9ar-aEg&t=1106s) | Tech/terror білд | "[sell] my command center they're not need a command center [as] GLA never ever do you want to be keeping it" | **Продати завжди.** Коли: 5 Workers у черзі, Barracks, Supply Stash, Tunnel, Terrorist. |
| 48 | М | How to Play GLA - Part 1 (2019-06-19) — [03:13](https://www.youtube.com/watch?v=haH2teyo1fc&t=193s) | Порівняння армій | "like if you are with the other factions if you're gonna be selling your command [center] you only got two [dozers] you can be hunted whereas with GLA you've got so many workers and your supply stashes can make workers you're not gonna be hunted" | **Чому GLA ризикує найменше:** Workers робить і Supply Stash. |
| 49 | Р | Top 10 tips for beginners (2026-01-14) — [04:56](https://www.youtube.com/watch?v=-atetgj1_0E&t=296s) | Tip 5, GLA | "Of course, with GLA, you should always be selling your CC as that doesn't provide radar or any other benefit at all in the early stages of the game. That comes way later from the radar van" | **Продавати завжди** (GLA CC не дає радару). |
| 50 | Р | ZH - GLA All-In Strategy vs USA (2016-01-18) — [00:53](https://www.youtube.com/watch?v=m8PeUyRTaZg&t=53s) | All-in проти USA | "we're going to do five workers one Supply … tunnel there … [I will wait for your command] center sell build a arms dealer" | **Продати (ймовірно CC)** після 5 Workers, Supply і тунелів; гроші — на Arms Dealer. [невизначеність]: слово «command» — частина голосової репліки юніта «I will wait for your command» (00:51–00:53), тож що продано саме CC — висновок. |
| 51 | Р | ZH - Stealth vs Tox Strategy Guide (2015-12-20) — [08:45](https://www.youtube.com/watch?v=SgeSosh79MM&t=525s) | Аналіз реплею, GLA mirror | "second worker I would always do to the supply … and I probably would sell now or another worker and or even two more workers" | **Продати** після fake Barracks і Worker на Supply (вибір: продати або ще 1–2 Workers). Об'єкт продажу прямо не названо: [висновок] найімовірніше це CC. |
| 52 | Р | Guide: How to play Defcon 6 FFA (2025-12-21) — [13:44](https://www.youtube.com/watch?v=e41NL-Spnfk&t=824s) | FFA, GLA | "I would always queue up five workers … Fake barracks … Upgrade that by pressing B … The one worker left, one worker right. Sell that." | **Продати (ймовірно CC)** після 5 Workers і апгрейду fake Barracks до справжньої. [невизначеність: «that» не уточнено] |
| 53 | Р | How to play Flower Oases (FFA guide) (2025-12-28) — [15:40](https://www.youtube.com/watch?v=8IxbGLthyw4&t=940s) | FFA, GLA | "Two terrorists and the capture upgrade. Sell that." | Те саме: «Sell that» після 5 Workers і fake Barracks — найімовірніше CC [невизначеність]. |
| 54 | М | 5x PRO TIPS (2022-03-03) — [01:08](https://www.youtube.com/watch?v=_HEptJ1WL0A&t=68s) | GLA, Cash Bounty | "when you get to 1500 xp you then get the bounty money when you get the bounty money you can place down a cc scaffold let's say there and you can cancel it and then you will automatically be getting all the bounty money" | **CC потрібен для Cash Bounty:** досить поставити й скасувати каркас CC. |
| 55 | Н | Replay Review - Improve GLA Mirror on Sand Scorpion (2022-11-17) — [07:31](https://www.youtube.com/watch?v=0TMkTbGrd0g&t=451s), [10:10](https://www.youtube.com/watch?v=0TMkTbGrd0g&t=610s) | GLA mirror | "both players are not level three yet so we don't need a cc in Bounty money just yet" … "satanic is now past level three so if [he] do[es] [build] a cc he's gonna have Rebel Ambush" | **Коли повертати CC:** після Level 3 (Bounty, Rebel Ambush). |
| 56 | М | Guide: How to play Defcon 6 FFA (2025-12-21) — [20:18](https://www.youtube.com/watch?v=e41NL-Spnfk&t=1218s) | FFA, GLA | "the only support power that GLA is going to have where it's going to come from a CC is the Anthrax plane … later on if you get level five … then the Anthrax plane could come from there" | Розміщення повторного CC важливе для Anthrax Bomb. |

### Доповнення: рядки 57–66, знайдені під час перевірки

| # | Тип | Армія | Відео (дата) / посилання | Цитата (EN) | Що це дає |
|---|---|---|---|---|---|
| 57 | Н | USA (усі армії) | Guide: How to play Defcon 6 FFA (2025-12-21) — [08:39](https://www.youtube.com/watch?v=e41NL-Spnfk&t=519s) | "if you watch a lot of pro players, especially in 1v1, they'll put the CCs towards the sides of the map cuz that's where the support powers are going to come from" | Про-гравці в 1v1 **будують CC знову** і ставлять його біля краю карти. Сильний аргумент проти «CC більше не потрібна». |
| 58 | М | USA | там само — [12:28](https://www.youtube.com/watch?v=e41NL-Spnfk&t=748s) | "If you build a second CC like here, the support powers are naturally going to come from there if you select it from the side. But if you click on the CC itself and then click it from here, then it's going to come from that CC" | При двох CC джерело сили можна вибрати кліком по конкретному CC (12:28–12:48). |
| 59 | Н | China | там само — [27:25](https://www.youtube.com/watch?v=e41NL-Spnfk&t=1645s) | "You can build a a CC protecting your oils. It's also quite close to the edge here." | Повторний CC як захист нафти й точка виклику сил біля краю. |
| 60 | Н | GLA | 10x Pro 1v1 Matches With Commentary (2021-01-26) — [32:08](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=1928s) | "once i kill that oil it's a good position i can even sell / we'll cancel the cc once i've built it … i'm gonna make a cc now because uh i wanna get ready" | Реальна 1v1 (Game 3, GLA проти China): у мідгеймі CC знову ставлять (каркас для Bounty / повний CC) (32:08–32:45). |
| 61 | Р | GLA | там само — [42:08](https://www.youtube.com/watch?v=-YkOy3e4Ibs&t=2528s) | "fake barracks here / this is going to now be sold" | Реальна 1v1 за GLA: продаж (ймовірно CC) після fake Barracks (41:39–42:14). [невизначеність]: об'єкт «this» не названо; розділ відео підписано «USA vs GLA», але fake Barracks є лише в GLA. |
| 62 | Н | USA Air Force | ZH - Air Force General Basic King Raptor Firing Tips (2016-01-08) — [02:03](https://www.youtube.com/watch?v=fIl764PSc-8&t=123s), [03:33](https://www.youtube.com/watch?v=fIl764PSc-8&t=213s) | "how many Raptors do you think it takes to kill a command center so in an Air Force mirror you'll often have a load of Raptors … it only takes seven" … "often in an Air Force mirror you will have eight or more Raptors and going for the command center and Dozer Hunt is actually a really good idea" | В AF mirror CC суперника зазвичай стоїть (його тримають), а полювання на CC і Dozer — стандартна ціль. Узгоджується з GR («тримати CC в AF mirror»). |
| 63 | Н | GLA | DoMiNaToR vs MERRYS - BO11 (2020-06-30) — [14:57](https://www.youtube.com/watch?v=6BpEu0u96Jw&t=897s) | "I never know I had a command center … couldn't make a radar scan even" | [невизначеність, низька впевненість]: можливо, CC у цій грі не продано. Субтитри зіпсовані. |
| 64 | М | China | 5x PRO TIPS - Generals Zero Hour (2021-07-22) — [09:24](https://www.youtube.com/watch?v=gL-W3UM6lj8&t=564s) | "use a lotus to capture the enemy cc and then you've got a carpet ready to go you can capture the enemy cc and then you can decide you can either sell it …" | Захоплений ворожий CC можна продати або використати як нову точку виклику сил (09:24–09:50). |
| 65 | Р | USA Air Force | ZH - USA vs GLA Early/Mid Game Guide (2016-01-29) — [19:58](https://www.youtube.com/watch?v=wv7XnteELfo&t=1198s) | "we've kept our command sent[er] again" | Той самий AF-реплей проти GLA, що й рядок 18: CC **тримають**. |
| 66 | Р | China (усі) | How to Play China - Part 1 (2020-06-29) — [03:43](https://www.youtube.com/watch?v=N_QRHPZkI5A&t=223s) | "the build what i'm going to show you now you can apply to all the um all the china's pretty much with the exception of infa is a little bit different" | Область дії рядка 41: білд із продажем CC застосовний до vanilla, Tank і Nuke; Infantry «a little bit different» (03:43–03:51). |

### Додаткові фрагменти (механіка, без окремого рядка в таблиці)

- AI ніколи не продає CC: "the computer never sells a command center so we know the command center is there" [відео: ZH - What is Waypoint Scouting?, 01:19](https://www.youtube.com/watch?v=ndeMKOKJVC4&t=79s) (2015-12-29).
- Захоплення ворожого CC позбавляє його Dozer: "enemy thinks he's safe he's got a cc and he's got multiple dozers but if you go and capture the cc and then come in with a couple of [MiGs] pick off that [dozer] and then all of a sudden he's got no dozer" [відео: 5x PRO TIPS, 08:04](https://www.youtube.com/watch?v=_HEptJ1WL0A&t=484s). Microwave Tank вимикає CC/Supply, і їх не можна продати [там само, 05:16](https://www.youtube.com/watch?v=_HEptJ1WL0A&t=316s).
- 50% повернення у словах автора: Superweapon "costs you 5k when you sell it you get two and a half k back" [відео: What is Pro Rules in Zero Hour?, 06:37](https://www.youtube.com/watch?v=SK2olkdvTtM&t=397s) (2021-02-18). Bunker "400 each. I'm going to sell them and get 200 back" [відео: ZH - 5x Top Level Tips, 06:22](https://www.youtube.com/watch?v=yXdfytqDEeg&t=382s) (2016-07-01).

---

## 2. Механіка (дані гри ZH 1.04 + вихідний код EA)

### 2.1. Гроші

| Параметр | USA | China | GLA | Джерело |
|---|---|---|---|---|
| BuildCost CC | $2000 (усі 4 генерали) | $2000 (усі 4) | $2000 (усі 4) | [дані гри: FactionBuilding.ini та *General.ini, усі 12 CC] |
| BuildTime CC | 45 с | 45 с | 45 с | [дані гри: `BuildTime = 45.0`] |
| Повернення при продажу | 50% → **$1000** | 50% → **$1000** | 50% → **$1000** | [дані гри: GameData.ini `SellPercentage = 50%`; BuildAssistant.cpp: `calcCostToBuild × m_sellPercentage`] |
| Dozer / Worker | Dozer $1000, 5 с | Dozer $1000, 5 с | Worker $200, 3 с | [дані гри] |
| Харвестер | Chinook $1200 (Air Force: $950) | Supply Truck $600 | Worker $200 | [дані гри: AFG_AmericaVehicleChinook = 950] |
| Supply-будівля | Supply Center $2000 (+1 безкоштовний Chinook) | Supply Center $1500 (+1 Truck) | Supply Stash $1500 (+1 Worker) | [дані гри: SpawnBehavior OneShot] |
| Power | Cold Fusion Reactor: vanilla **$800**, Air Force **$800**, Laser **$700**, Superweapon **$900** | Nuclear Reactor: vanilla/Tank/Infantry **$1000**, Nuke **$1200** | — (GLA не має енергії) | [дані гри: FactionBuilding.ini, AirforceGeneral.ini, LaserGeneral.ini (`Lazr_AmericaPowerPlant = 700`), SuperWeaponGeneral.ini (`SupW_AmericaPowerPlant = 900`), NukeGeneral.ini (`Nuke_ChinaPowerPlant = 1200`)] |

- **Гроші приходять не одразу.** Каркас «розбирається» ~1,5 с, далі будівля опускається ~4,5 с, тобто приблизно 6 с ігрового часу. Гроші зараховуються лише в кінці продажу. Коментар у коді: "It is still a legal target, since you get the money at the completion of sale". Якщо CC знищать під час продажу, грошей не буде [дані гри: BuildAssistant.cpp, `FRAMES_TO_ALLOW_SCAFFOLD = 1.5 s`, `TOTAL_FRAMES_TO_SELL_OBJECT = 3 s`, поріг −50%].
- **Продаж скасовує чергу виробництва** з поверненням грошей (`cancelAndRefundAllProduction()` на початку продажу). Якщо продати CC, поки Dozer ще будується, цього Dozer не буде. Саме це сталося з Diablo [дані гри: BuildAssistant.cpp] [відео: He sold his CC before making dozer, 21:56].
- **Чому без продажу не вистачає (старт $10 000).** Спрощений розрахунок [висновок з даних гри]: статичний бюджет без доходу від перших харвестерів. Типовий старт: 2-й Dozer + Power + 2 Supply + по 1 додатковому харвестеру на кожен Supply. Критерій для всіх армій однаковий — чи вистачає на одну War Factory ($2000). Окремо вказано ціль типового білду.

| Армія | Витрати на старт | Залишок без продажу | Залишок з продажем | 1 WF ($2000) без продажу? | Ціль типового білду |
|---|---|---|---|---|---|
| USA vanilla | 1000 + 800 + 4000 + 2×1200 = 8200 | $1800 | $2800 | ні, бракує $200 | WF + Barracks ($2600): лише з продажем |
| USA Laser | 1000 + 700 + 4000 + 2400 = 8100 | $1900 | $2900 | ні, бракує лише $100 | те саме |
| USA Superweapon | 1000 + 900 + 4000 + 2400 = 8300 | $1700 | $2700 | ні, бракує $300 | те саме |
| USA Air Force | 1000 + 800 + 4000 + 2×950 = 7700 | $2300 | $3300 | **так** | WF або 2 Airfield ($1600): без продажу; WF + Barracks — лише з продажем |
| China vanilla / Tank / Infantry | 1000 + 1000 + 3000 + 2×600 = 6200 | $3800 | $4800 | так | 2 WF ($4000): лише з продажем (бракує $200) |
| China Nuke | 1000 + 1200 + 3000 + 1200 = 6400 | $3600 | $4600 | так | 2 WF: лише з продажем (бракує $400) |
| GLA | — | — | +$1000 | — | ще один Tunnel ($800) або швидший Tech/Terror [веб: GameReplays TotW #30] |

  - Реальний ефект збереження CC — це **затримка**, а не «неможливо»: харвестери вже возять гроші, тож WF просто з'являється пізніше. Так каже й автор: «if I sold the CC I would be able to make a war [factory] now … your first fully loaded V is going to be a little bit slower» [відео: How to Play USA - Tutorial for beginners, 34:49–35:28].
  - Laser бракує лише $100 до WF. Це може пояснювати, чому в реплеях Laser тримав CC (рядки 17, 19) [висновок].
- `DefaultStartingCash = 10000` [дані гри: GameData.ini]. На деяких картах на старті є ящик $1000. Тоді в China сенс продажу зникає [відео: How to Play China - Tutorial for beginners, 07:59].

### 2.2. Що втрачаєш разом із CC

| Що | USA (vanilla/Laser/SW) | USA Air Force | China | GLA | Джерело |
|---|---|---|---|---|---|
| Виробництво будівельників | **Dozer — тільки з CC** | так само | **Dozer — тільки з CC** | Worker — з CC **і з Supply Stash** | [дані гри: CommandSet.ini — `Command_ConstructAmericaDozer`/`ChinaDozer` лише в CommandSet CC; `Command_ConstructGLAWorker` у CC та `GLASupplyStashCommandSet`] |
| Радар | Вбудований (апгрейд видається автоматично при створенні CC) | так само | Лише апгрейд **Radar $500** на CC | **CC радару не дає**; радар — лише Radar Van | [дані гри: `GrantUpgradeCreate Upgrade_AmericaRadar`; `RadarUpgrade TriggeredBy Upgrade_ChinaRadar`; у GLACommandCenter модулів радару немає] [веб: cnc.fandom] |
| Розвідка без промоції | **Spy Satellite Scan** (без промоції, перезарядка 60 с) | так само | — | — | [дані гри: SpecialPower.ini `SpecialPowerSpySatellite`, ReloadTime 60000, без RequiredScience] |
| **Сили Rank 1 на CC** | **Spy Drone** (`SCIENCE_SpyDrone`, Rank 1, перезарядка 90 с) | Spy Drone; **Early Emergency Repair** | Tank, Nuke: **Early Emergency Repair**; Infantry: **Early Frenzy** | Stealth: **Early Emergency Repair** | [дані гри: Science.ini (`SCIENCE_Rank1`), CommandSet.ini `*_CommandSetRank1`, модулі в блоках CC] |
| Генеральські сили (Special Powers) на CC | Spy Drone, A-10 Strike, Paradrop, Spectre Gunship, Leaflet Drop, Fuel Air Bomb (Daisy Cutter), Emergency Repair, Supply/Crate Drop | так само (A-10/Spectre у версіях AirF). **Carpet Bomb — НЕ на CC, а на Strategy Center** | Artillery Barrage, Cluster Mines, EMP Pulse, Cash Hack, Emergency Repair, Carpet Bomb, Napalm Strike, Frenzy. Tank: ще **Tank Paradrop** (`Tank_SuperweaponTankParadrop`, Rank 3). Infantry: ще Infantry Paradrop. Плюс апгрейд Mines ($600) | Rebel Ambush, Anthrax Bomb, Sneak Attack, GPS Scrambler, Emergency Repair, **Cash Bounty** | [дані гри: OCLSpecialPower / CashBountyPower у блоках CC; `AirF_AmericaStrategyCenter` має `AirF_SuperweaponCarpetBomb`, у `AirF_AmericaCommandCenter` цей модуль закоментовано; TankGeneral.ini `Tank_ChinaCommandCenter`] |
| Пререквізит інших будівель | Ні | Ні | Ні | **Так:** Fake Barracks ($125), Fake Supply Stash ($375), Fake Command Center ($500) вимагають справжній CC. (GLA Hole в INI теж має цей пререквізит, але гравець її не будує: дірка з'являється сама після знищення GLA-будівлі, тож на рішення про продаж це не впливає.) | [дані гри: Prerequisites у FactionBuilding.ini та Demo/Stealth/ChemicalGeneral.ini] |
| Точка виклику сил | Сили з `CREATE_AT_EDGE_NEAR_SOURCE` (A-10, Fuel Air Bomb, Paradrop, Carpet, Cluster Mines, EMP, Anthrax…) летять від краю карти біля CC-джерела | | | | [дані гри] [відео: 5x PRO TIPS - Generals Zero Hour, 08:10] |

- **Який CC стає джерелом сили.** Автор каже «to my knowledge … the support powers always come from the latest cc» [відео: 5x PRO TIPS - Generals Zero Hour, 08:18–08:23]. За кодом кнопка сили на бічній панелі шукає CC, який не будується, не продається і не мертвий (`Player::findMostReadyShortcutSpecialPowerOfType` → `doFindSpecialPowerSourceObject` перевіряє `OBJECT_STATUS_UNDER_CONSTRUCTION` і `OBJECT_STATUS_SOLD`). Вимкнений CC береться лише в останню чергу. Береться перший готовий CC у порядку обходу. Нові об'єкти додаються на початок списку команди (`prependTo_TeamMemberList` в Object.cpp), тому з однаковими таймерами першим знаходиться найновіший CC. Це узгоджується зі словами автора [висновок з коду, у грі не перевірено]. Клік по конкретному CC і виклик сили з нього задає джерело вручну [відео: Guide: How to play Defcon 6 FFA, 12:28–12:48].
- **CC під будівництвом сил не дає**: такий CC пропускається при пошуку джерела сили [дані гри: Player.cpp]. Тобто повторний CC «вмикає» сили лише після завершення 45 с будівництва. Виняток — Cash Bounty, див. §2.3.
- **Поразка.** У мультиплеєрі за замовчуванням (`VICTORY_NOBUILDINGS | VICTORY_NOUNITS`) гравець програє, коли в нього не лишилося жодного об'єкта (не рахуються снаряди, INERT і міни). Продаж CC сам по собі поразки не дає. Але якщо після продажу загинуть усі Dozer (USA/China), нових будівель уже не буде, хоча формально гра триває, поки живі юніти [дані гри: VictoryConditions.cpp, Team::hasAnyObjects] [відео: How to Play USA AIR FORCE, 25:05].
- **USA CC при знищенні (не продажу) випускає 10 Rangers** (`OCL_AmericanRangerDebris10`, не для недобудованого) [дані гри]. GameReplays описує трюк «розстріляти власний CC заради 10 Rangers» проти China [веб: GameReplays TotW #30]. Продаж іде через `destroyObject` без die-модулів, тому Rangers при продажі не з'являються [висновок з коду].

### 2.3. General's Promotions без CC

- **Купити промоцію без CC можна, використати силу на CC — ні.** Вікно покупки (`ControlBar::populatePurchaseScience`) залежить лише від PlayerTemplate, перевірки наявності CC там немає [дані гри: ControlBar.cpp / GeneralsExpPoints.cpp — висновок з коду]. Пасивні та юніт-промоції (Technical Training, Red Guard Training, Battlemaster Training, Paladin, Stealth Fighter тощо) працюють без CC. Сили, що «живуть» на CC, без CC використати не можна. Саме це GameReplays має на увазі, коли пише «will not be able to use their general points … until the command center is rebuilt»: очки купити можна, але більшість куплених сил не працюватимуть [веб: GameReplays TotW #30] [висновок].
- **Rank 1.** Сили Rank 1, що живуть на CC: Spy Drone (усі USA), Early Emergency Repair (AF, Tank, Nuke, Stealth), Early Frenzy (Infantry) [дані гри]. Якщо взяти їх на старті і продати CC, до повторного CC вони мертві. DoMiNaToR за USA завжди бере Spy Drone і використовує drone + scan **до** продажу [відео: How to Play USA - Tutorial for beginners, 01:46–01:49, 04:11–04:15].
- Після нового CC сили знову доступні. У більшості таких сил `SharedSyncedTimer = Yes`: таймер прив'язаний до гравця, а не до будівлі. Отже, після перебудови CC сила не обов'язково заряджається з нуля [дані гри: SpecialPower.ini, SpecialPowerModule.cpp] [невизначеність: у грі не перевірено].
- **GLA Cash Bounty (усі три рівні).** У CC є три модулі `CashBountyPower` (Bounty 5% / 10% / 20%, `SCIENCE_CashBounty1/2/3`, усі Rank 3). Бонус вмикається у двох випадках: (1) при покупці рівня, якщо CC вже існує (`onSpecialPowerCreation`); (2) при створенні нового CC, якщо рівень уже куплено (`onObjectCreated`). Каркасу досить, і бонус не зникає після скасування чи знищення CC (`setCashBounty` лише підвищує значення) [дані гри: CashBountyPower.cpp, FactionBuilding.ini]. Отже, **після кожного апгрейду Bounty без CC каркас треба ставити знову** [висновок з коду]. Це підтверджує трюк «поставити каркас CC і скасувати» [відео: 5x PRO TIPS, 01:08]. Rebel Ambush — Rank 3; Anthrax, Sneak Attack, GPS Scrambler — Rank 5 [дані гри: CommandSet.ini `SCIENCE_GLA_CommandSetRank3/8`].

### 2.4. Чи можна збудувати CC знову

- **Так.** `Command_Construct…CommandCenter` є в CommandSet Dozer (USA, China) і Worker (GLA). Пререквізитів CC не має, ліміту кількості теж (жодного `MaxSimultaneousOfType`) [дані гри]. Автор будує 2 CC [відео: 5x PRO TIPS - Generals Zero Hour, 08:10; Guide: How to play Defcon 6 FFA, 12:28, 22:53] і радить «rebuild your CC at any moment when you know you are in safety» [відео: How to Play USA AIR FORCE, 10:46].
- Для USA/China потрібен живий Dozer: без Dozer немає CC, а без CC немає Dozer. Через це втрата обох Dozer після продажу фатальна [висновок] [веб: GameReplays TotW #30]. Будівництво CC займає 45 с роботи Dozer [дані гри], тому будувати CC останнім Dozer під загрозою — погана ідея. Джерела в такій ситуації радять боксувати й ховати Dozer [відео: ZH - USA vs GLA Early/Mid Game Guide, 00:52; ZH - USA Air Force All-In Build Order, 02:56].
- Для GLA CC може відбудувати будь-який Worker, а Workers роблять Supply Stash [дані гри], тож «полювання на Workers» GLA майже не зупиняє: "it is nearly impossible to fully worker hunt" [веб: GameReplays TotW #30].

---

## 3. По арміях (із силою доказів)

| Генерал | Що робити з CC на старті 1v1 | Сила доказів |
|---|---|---|
| USA vanilla | Продавати | **Сильні:** рядки 1–3, 7, 26, 30, 32; GR |
| USA Laser | Немає чіткого дефолту; у наявних реплеях проти GLA CC **тримали** | **Слабкі:** лише рядки 17, 19 (тримання). Прямих доказів продажу саме за Laser немає. Загальні поради для «USA» (рядки 30, 32) можуть стосуватися й Laser [висновок] |
| USA Superweapon | [немає даних] | Окремих доказів немає. Бюджет як у vanilla, ще трохи гірший ($1700) [висновок з даних гри] |
| USA Air Force | Залежить від білду (див. таблицю в §4) | **Середні:** профільний AF-туторіал продає CC у 4 білдах (рядки 9, 12, 13, 15) і тримає в 2 (рядки 8, 16); тримання також у рядках 4, 18, 21, 24, 62, 65 і в GR; продаж — рядок 28 |
| China vanilla | Продавати | **Сильні:** рядки 36–41, 43, 45; GR |
| China Tank / Nuke | Продавати (той самий білд) | **Опосередковані:** «you can apply to all the chinas pretty much» (рядок 66) + GR «Most China build orders include the selling» |
| China Infantry | Ймовірно продавати, але білд «a little bit different» | **Слабкі:** лише рядок 44, і це гра проти AI |
| GLA (усі 4) | Продавати | **Сильні, два незалежні автори:** рядки 47, 49–53, 61; GR "100% of the time for any general" |

### USA (vanilla; Laser і Superweapon — див. силу доказів)
- **Стандарт 1v1 (vanilla):** Dozer у черзі з першої секунди → Power (Cold Fusion Reactor) першою → обидва Dozer ставлять 2 Supply Center → drone/scan → **продаж** → по 2 Chinook на кожен Supply → War Factory + Barracks [відео: How to Play USA - Tutorial for beginners, 02:20–04:15; Top 10 tips for beginners, 06:12]. Тут формулювання користувача «після Supply і реактора» по суті правильне.
- **Варіанти таймінгу:** в агресивних/no-eco білдах продають після постановки Barracks і замовлення MD [там само, 18:36; гра проти AI]. У USA mirror drop — коли вийде перший MD [там само, 36:36; у відео є суперечність, див. рядок 7].
- **Проти GLA:** дефолт — продати, навіть проти «top level glas» [там само, 26:29–26:48]. Альтернатива — тримати CC і робити Dozer drop, що показано в Laser-реплеях [відео: ZH - USA vs GLA Early/Mid Game Guide, 15:23, 20:12; How to Play USA - Tutorial for beginners, 35:34–35:47]. Ціна — пізніша WF і перший loaded Humvee [там само, 34:28–35:28].
- **Найбільший ризик:** Dozer hunt (Raptors, King Raptor, GLA-рейди) [відео: ZH - 2vs2 Strategy Guide - Part 1, 15:54] [веб: GameReplays TotW #30].

### USA Air Force
- **AF часто може тримати CC завдяки Chinook за $950, але це залежить від білду, а не є дефолтом.** GameReplays: у білдах 2 Airfield / Airfield + Barracks **не продавати**, особливо в AF mirror, де King Raptor полює на Dozer; те саме для білдів із 2 Airfield проти GLA [веб: GameReplays TotW #30].
- **Продають** у Comanche-білді заради максимуму юнітів на 2:30, в 1-Supply fast strats (Carpet проти Tank, King Raptor проти Infantry), у WF + Airfield проти Infantry і коли scan показав, що буде важкий drop [відео: How to Play USA AIR FORCE, 08:23–10:46, 20:20, 23:12, 26:27, 30:20]. Сильний AF-гравець Diablo теж продав CC [відео: He sold his CC before making dozer, 04:00–04:17].
- **Carpet Bomb у AF — на Strategy Center**, тож продаж CC його не забирає [дані гри].

### China (vanilla, Tank, Nuke, Infantry)
- **Стандарт:** продати CC, щойно 2-й Dozer покинув CC. Reactor у цей момент ще будується, Supply ще не поставлено [відео: How to Play China - Part 1, 03:59–04:48; ZH - China Mirror All-In Build, 00:49–01:05; How to play Flower Oases, 08:36; How to Play China - Tutorial for beginners, 28:53]. Тобто China продає **раніше**, ніж «після Supply і реактора». Без продажу немає 2 Supply + 2 WF [висновок з даних гри].
- **Винятки:** стартовий ящик $1000 [відео: How to Play China - Tutorial for beginners, 07:59]. Також Toxin, який полює на Dozer під Gamma Battle Bus (патч 1.04), і великі карти (Twilight Flame, Defcon 6), де базу важче захистити [веб: GameReplays TotW #30].
- **Пізніше:** будують CC позаду, біля краю карти або перед нафтою, і купують Radar $500 [відео: How to Play China - Part 1, 22:58–23:59; Guide: How to play Defcon 6 FFA, 27:25] [дані гри].

### GLA (vanilla, Toxin, Demo, Stealth)
- **Продають «завжди»** — так кажуть обидва джерела [відео: How to Play GLA - Part 3, 18:26; Top 10 tips for beginners, 04:56] [веб: GameReplays TotW #30 — "must be sold 100% of the time for any general"]. Це заяви авторів, а не статистика.
- **Коли:** після 5 Workers (їх можна замовити ще на екрані завантаження, K×5) і після постановки fake Barracks (і/або Tunnel, Supply) [відео: Guide: How to play Defcon 6 FFA, 13:13–13:44; ZH - GLA All-In Strategy vs USA, 00:26–00:53; 10x Pro 1v1 Matches, 42:08]. Реактора й енергії в GLA немає, тож частина твердження «після реактора» тут не застосовна. Fake-будівлі вимагають справжній CC [дані гри].
- **Чому ризик малий:** Workers робить Supply Stash; GLA CC не дає радару [дані гри] [відео: How to Play GLA - Part 1, 03:13].
- **Повертати CC** після Level 3 (Cash Bounty — досить каркаса, Rebel Ambush) і Level 5 (Anthrax) [відео: 5x PRO TIPS, 01:08; Replay Review - Improve GLA Mirror on Sand Scorpion, 07:31, 10:10; 10x Pro 1v1 Matches, 32:08–32:45; Guide: How to play Defcon 6 FFA, 20:18].

---

## 4. Правила для ШІ-агента (ЯКЩО … → ТО …)

Кожне правило має дефолт і тригери, які агент може спостерігати: час гри, банк, ворожі юніти біля бази, режим, генерал, карта, результат drone/scan. Числові пороги, яких немає в джерелах, позначено [висновок]. «Біля бази» = у радіусі ~600 одиниць від CC/Dozer [висновок].

### Загальні (усі армії)
- ЯКЩО в черзі CC є Dozer/Worker → ТО **не продавати** CC: продаж скасує чергу [дані гри: BuildAssistant.cpp] [відео: He sold his CC before making dozer, 21:56].
- ЯКЩО віддано команду Sell → ТО гроші ($1000) з'являться приблизно через 6 с. Плануй наступну будівлю з урахуванням затримки. ЯКЩО біля CC ворожі юніти, що атакують його, → ТО не продавати: якщо CC загине під час продажу, грошей не буде [дані гри].
- ЯКЩО на Rank 1 обрано силу, що живе на CC (Spy Drone — USA/AF; Early Emergency Repair — AF/Tank/Nuke/Stealth; Early Frenzy — Infantry) → ТО використати її **до** продажу (USA: drone + scan, як у рядку 1, 04:11–04:15) АБО на Rank 1 обрати пасивну/юніт-промоцію (Red Guard Training, Technical Training, Battlemaster Training, Stealth Fighter, Paladin) [дані гри: CommandSet.ini Rank1] [висновок].
- ЯКЩО CC продано (USA/China) → ТО: (1) боксувати Dozer будівлями, не відпускати вперед без потреби [відео: ZH - USA vs GLA Early/Mid Game Guide, 00:52; ZH - USA Air Force All-In Build Order, 02:56]; (2) розвідувати без радару: прокрутка, waypoint scouting, юніти [відео: How to Play USA - Tutorial for beginners, 04:15; Top 10 tips for beginners, 03:46].
- ЯКЩО (USA/China) лишився 1 Dozer і біля нього є ворожі юніти → ТО **не починати CC**. Спершу забоксувати або сховати Dozer [відео: ZH - USA vs GLA Early/Mid Game Guide, 00:52; ZH - USA Air Force All-In Build Order, 02:56]. Причина: CC будується 45 с силами того самого Dozer, а сили з недобудованого CC не працюють [дані гри: BuildTime 45.0; Player.cpp].
- ЯКЩО (USA/China) лишився 1 Dozer, біля бази немає ворожих юнітів і банк ≥ $3000 (CC $2000 + новий Dozer $1000) [висновок] → ТО збудувати CC у найзахищенішому місці; після завершення одразу замовити Dozer.
- ЯКЩО куплено силу, що живе на CC (Rank 3/5: A-10, Artillery, Rebel Ambush, Tank Paradrop тощо), біля бази немає ворожих юнітів і банк ≥ $2000 + $1000 резерву [висновок] → ТО **збудувати CC знову**: біля краю карти, у кутку або перед нафтою [відео: How to Play USA AIR FORCE, 10:46; 5x PRO TIPS - Generals Zero Hour, 08:10–10:20; Guide: How to play Defcon 6 FFA, 08:16–08:47, 27:25].
- ЯКЩО режим 3v3/4v4 або велика карта, ігровий час ≥ 10:00 [висновок] і банк ≥ $2500 (CC + Radar для China) [висновок] → ТО збудувати CC заради радару (China: одразу купити Radar $500) [відео: Top 10 tips for beginners, 04:31; How to Play China - Part 1, 23:57].
- ЯКЩО суперник — skirmish AI → ТО його CC завжди на місці: AI не продає CC [відео: ZH - What is Waypoint Scouting?, 01:19].
- ЯКЩО суперник **USA або China** продав CC (drone/scan/розвідка не бачить CC на місці) → ТО полювання на Dozer вирішальне: без Dozer і CC він не відновиться. Пріоритет цілей: Dozer > Power > War Factory/Barracks [відео: How to Play USA AIR FORCE, 25:05, 30:15; ZH - 2vs2 Strategy Guide - Part 1, 15:54].
- ЯКЩО суперник **GLA** продав CC → ТО **не** розраховувати, що він не відновиться: будь-який Worker може знову поставити CC, а Workers роблять Supply Stash. Пріоритетні цілі: Supply Stash, Workers, Tunnel Network (енергії в GLA немає) [дані гри: CommandSet.ini `GLASupplyStashCommandSet`] [відео: How to Play GLA - Part 1, 03:13] [веб: GameReplays TotW #30 — "nearly impossible to fully worker hunt"].

### USA (vanilla; Laser і Superweapon — за аналогією, див. §3)
- **Дефолт 1v1:** на 0:00 замовити 1 Dozer (разом 2) → перший Dozer будує Power → обидва Dozer ставлять 2 Supply Center → використати drone/scan → **продати CC**. Тригер продажу: **обидва Supply Center поставлено (каркаси існують), 2-й Dozer вийшов (черга CC порожня), drone/scan використано**. Далі: на кожен Supply ще 1 Chinook → WF + Barracks [відео: How to Play USA - Tutorial for beginners, 02:20–04:15; Top 10 tips for beginners, 06:12].
- ЯКЩО білд no-eco / рання агресія (Barracks попереду, 1 Supply) → ТО продати CC після постановки Barracks + Supply і замовлення MD [відео: How to Play USA - Tutorial for beginners, 18:36; гра проти AI].
- ЯКЩО USA mirror з drop (3 MD + Barracks) → ТО продати CC, коли з Barracks вийде перший MD [там само, 36:36].
- ЯКЩО суперник GLA → ТО **дефолт — продати** [там само, 26:29–26:48]. Альтернатива: тримати CC і зробити Dozer drop, прийнявши пізнішу WF [відео: ZH - USA vs GLA Early/Mid Game Guide, 15:23, 20:12; How to Play USA - Tutorial for beginners, 35:34–35:47].
- ЯКЩО генерал Laser → ТО обидва варіанти допустимі. Без продажу бракує лише $100 до WF, і в реплеях проти GLA CC тримали [висновок з §2.1] [відео: ZH - USA vs GLA Early/Mid Game Guide, 15:23, 20:12].
- ЯКЩО режим 2v2/командний і drone/scan до продажу показав у суперника-AF Airfield → ТО **не продавати** CC: Raptors виб'ють Dozer і Power [відео: ZH - 2vs2 Strategy Guide - Part 1, 15:54] [висновок: Airfield як спостережуваний тригер].
- ЯКЩО 1v1 і drone/scan показав у суперника-AF Airfield, поставлений раніше за його 2-й Supply [висновок] → ТО не продавати або продавати лише разом із ≥ 2 MD біля Dozer [висновок] [веб: GameReplays TotW #30 — Dozer hunt KR].

### USA Air Force

| Білд / ситуація (видно до продажу) | CC | Джерело |
|---|---|---|
| 2 Supply + 2 Airfield або Airfield + Barracks | **Тримати** | [веб: GameReplays TotW #30] |
| AF mirror (drone/scan показав AF-суперника) | **Тримати** | [веб: GameReplays TotW #30]; рядки 24, 62 |
| Білд із 2 Airfield проти GLA | **Тримати** | [веб: GameReplays TotW #30]; рядки 18, 65 |
| Comanche-білд, варіант «keep» | Тримати | рядок 8 |
| Comanche-білд на максимум юнітів до 2:30 | **Продати**; $1000 → 2-й Airfield ($800) | рядки 9–11 |
| 1-Supply fast strat (Carpet проти Tank / King Raptor проти Infantry) | **Продати** одразу після Barracks | рядки 12, 13 |
| WF + 1 Airfield проти Infantry, 2 Supply | **Продати** на старті | рядок 15 |
| Scan показав, що суперник готує важкий drop (Chinook з піхотою біля бази) | **Продати**, гроші — у піхоту/Firebase | рядок 16 |

- ЯКЩО карта довга й без бункерів біля бази → ТО обрати Comanche-білд [відео: How to Play USA AIR FORCE, 00:25–01:42]. Це умова вибору білду, а не продажу.
- ЯКЩО Comanche-білд → ТО продаж CC — окремий компроміс «більше Comanche на 2:30» проти «a bit of a risk» раннього Dozer hunt [там само, 08:23–08:30, 10:34–10:49]. Продавати, якщо drone/scan не показав у суперника Airfield / Raptors / тунелю біля твоєї бази [висновок]. Інакше тримати.
- ЯКЩО план використовує Carpet Bomb → ТО потрібен Strategy Center (сила на ньому, не на CC) [дані гри].

### China (vanilla / Tank / Nuke; Infantry — див. §3)
- **Дефолт:** старт $10 000, білд 2 Supply + 2 WF (або 1 Supply + WF + Airfield / all-in) → на 0:00 замовити 1 Dozer → перший Dozer ставить Reactor → **продати CC, щойно 2-й Dozer покинув CC** (Reactor ще будується, Supply ще не поставлено) → Supply/Barracks/WF [відео: How to Play China - Part 1, 03:59–04:48; ZH - China Mirror All-In Build, 00:49–01:05; How to Play China - Tutorial for beginners, 28:53].
- ЯКЩО карта дає стартовий ящик $1000 → ТО **не продавати** [відео: How to Play China - Tutorial for beginners, 07:59].
- ЯКЩО 1v1 на великій карті (Twilight Flame, Defcon 6 або подібна з розкиданою базою) → ТО тримати CC [веб: GameReplays TotW #30].
- ЯКЩО суперник — Toxin GLA і з попередніх ігор чи реплеїв цього гравця відомо, що він полює на Dozer → ТО тримати CC [веб: GameReplays TotW #30] [висновок: потрібен профіль суперника; в перші секунди гри інакше не спостерігається].
- ЯКЩО мідгейм (≥ 8:00 [висновок]), біля бази немає ворожих юнітів і банк ≥ $2500 → ТО збудувати CC позаду/біля краю або перед нафтою і купити Radar ($500) [відео: How to Play China - Part 1, 22:58–23:59; Guide: How to play Defcon 6 FFA, 27:25] [дані гри].

### GLA (vanilla / Toxin / Demo / Stealth)
- **Дефолт:** на старті замовити 5 Workers (K×5 на екрані завантаження) → Supply Stash першою (або fake Barracks першою) → **до продажу поставити всі потрібні fake-будівлі** (вони вимагають CC) → **продати CC** → гроші на Tunnel / Arms Dealer. Тригер продажу: 5 Workers вийшли й поставлено fake Barracks / Tunnel [відео: How to Play GLA - Part 3, 18:26; ZH - GLA All-In Strategy vs USA, 00:53; Guide: How to play Defcon 6 FFA, 13:13–13:44] [дані гри].
- ЯКЩО потрібні ще Workers → ТО будувати їх із Supply Stash (CC не потрібен) [дані гри].
- ЯКЩО куплено **будь-який** рівень Cash Bounty (1, 2 або 3) і CC зараз немає → ТО поставити каркас CC (можна одразу скасувати). Повторювати після кожного нового рівня [відео: 5x PRO TIPS, 01:08] [дані гри: CashBountyPower.cpp].
- ЯКЩО потрібні Rebel Ambush (Rank 3) / Anthrax, Sneak Attack, GPS Scrambler (Rank 5), біля бази немає ворожих юнітів і банк ≥ $2000 + резерв [висновок] → ТО збудувати повноцінний CC. Для Anthrax ставити його ближче до краю карти або входу [відео: Replay Review - Improve GLA Mirror on Sand Scorpion, 10:10; 10x Pro 1v1 Matches, 32:08–32:45; Guide: How to play Defcon 6 FFA, 20:18].
- Винятків «не продавати» для GLA у джерелах не знайдено [висновок].

---

## 5. Невизначеності

1. **Одне основне джерело практики.** 28 відео — від одного автора (DoMiNaToR). Незалежні джерела — GameReplays (2007) і fandom. Багато демонстрацій у sandbox або проти AI. Реальних матчів і реплеїв із сильними гравцями мало (рядки 17–24, 60, 61, 65 — 1v1; рядок 28 — FFA). Твердження «всі про» перевірити неможливо, бо статистики немає. Прямі контрприклади: AF-гравці (рядки 21, 24, 62), Laser-реплеї (17, 19).
2. **«big size» (рядок 6).** Підстава — зіпсовані субтитри: "you big see big size doing it a lot keeping his CC no matter what he is" (35:28–35:33). Що це ім'я гравця і що мова саме про CC за будь-яких умов, не встановлено. У вердикті не використовується.
3. **Автосубтитри.** «SL»/«cell»/«commands in it» інтерпретовано як «sell»/«command center». «Sell that» у GLA-фрагментах (рядки 52, 53) і «this is going to now be sold» (рядок 61) найімовірніше означають CC, але прямо не названо. У рядку 50 «command» — частина репліки юніта. Рядок 63 (BO11) — низька впевненість.
4. **«Одна нафта → тримати CC» (рядок 23)** — гіпотеза без узагальнення: з субтитрів незрозуміло, чи рішення тримати CC пов'язане з кількістю нафти. Як правило агента не використовується.
5. **Таймінги — відео, не гра.** Ігрового часу продажу (наприклад, 0:25 чи 0:40) у транскриптах немає. Точний таймінг треба брати з реплеїв (GenTool) [невизначеність].
6. **Версія даних.** Числа взято з INI оригінальної ZH 1.04 (той самий `SellPercentage = 50%` і CC $2000 у Patch104p). Чи змінює Generals Online (форк коду TheSuperHackers) баланс, не перевірено. GenTool, наскільки відомо, геймплей не змінює [невизначеність].
7. **Fake-будівлі GLA.** Пререквізит «справжній CC» перевірено за INI. Чи добудується вже розміщена fake-будівля після продажу CC, не перевірено; безпечніше продавати після постановки [невизначеність].
8. **Сили після перебудови CC і вибір джерела.** За кодом таймери `SharedSyncedTimer` ведуться на рівні гравця, тож після нового CC сила може бути готова одразу. Що джерелом стає найновіший CC — висновок із порядку обходу об'єктів. У грі не перевірено.
9. **Командні ігри / FFA.** Свідчення змішані: продаж у Defcon 6 3v3 (USA) і FFA (China, GLA, AF Diablo); збереження у Flower Oases FFA (USA). Порада: радар дуже допомагає в 3v3/4v4 пізніше. Однозначного правила для team/FFA немає.
10. **GameReplays (2007)** описує мету патча 1.04 того часу (Toxin, Gamma Battle Bus). Свіжіші відео DoMiNaToR (2020–2026) загалом узгоджуються: GLA завжди, China майже завжди, AF залежно від білду. Але сучасну мету поза цими авторами не перевірено.
11. **Laser / Superweapon / Infantry.** Окремих доказів продажу за Laser і Superweapon немає. По Infantry є лише гра проти AI (рядок 44). Правила для них — екстраполяція [висновок].
12. Порогові числа в правилах агента (банк ≥ $3000 / $2500 / $2000 + резерв, ігровий час ≥ 8:00/10:00, радіус «біля бази» ~600) — [висновок], а не цифри з джерел. Розрахунок бюджету в §2.1 не враховує доходу від харвестерів.

---

## 6. Джерела

### Відео (YouTube, DoMiNaToR)
- How to Play USA - Tutorial for beginners — https://www.youtube.com/watch?v=CkSCpFsNY9c
- How to Play USA AIR FORCE — https://www.youtube.com/watch?v=NtY82fKA82Q
- ZH - Air Force General Basic King Raptor Firing Tips — https://www.youtube.com/watch?v=fIl764PSc-8
- ZH - USA vs GLA Early/Mid Game Guide — https://www.youtube.com/watch?v=wv7XnteELfo
- 10x Pro 1v1 Matches With Commentary — https://www.youtube.com/watch?v=-YkOy3e4Ibs
- DoMiNaToR vs MERRYS - BO11 For Fun Challenge — https://www.youtube.com/watch?v=6BpEu0u96Jw
- ZH - 2vs2 Strategy Guide - Part 1 — https://www.youtube.com/watch?v=0XsA_eRACbA
- How to Play Defcon 6 - 3v3 No Rules - Top 10 Tips for Beginners — https://www.youtube.com/watch?v=K9tZd7yzbtc
- How to play Flower Oases (FFA guide) — https://www.youtube.com/watch?v=8IxbGLthyw4
- He sold his CC before making dozer [Funny rush] — https://www.youtube.com/watch?v=buBGjk5aVHg
- ZH - USA Air Force All-In Build Order — https://www.youtube.com/watch?v=zX82fLitLcw
- Top 10 tips for beginners (Generals Zero Hour) — https://www.youtube.com/watch?v=-atetgj1_0E
- 5x PRO TIPS - Generals Zero Hour — https://www.youtube.com/watch?v=gL-W3UM6lj8
- 5x PRO TIPS — https://www.youtube.com/watch?v=_HEptJ1WL0A
- Guide: How to play Defcon 6 FFA (any army) — https://www.youtube.com/watch?v=e41NL-Spnfk
- How to Play China - Tutorial for beginners — https://www.youtube.com/watch?v=FeD9mpO9c2w
- How to Play China - Part 1 (beginners) — https://www.youtube.com/watch?v=N_QRHPZkI5A
- ZH - China Mirror All-In Build — https://www.youtube.com/watch?v=ArZ0Bf-rxSM
- ZH - Infantry Mirror Guide — https://www.youtube.com/watch?v=9MAob362xiU
- How To All In Rush with China vs USA — https://www.youtube.com/watch?v=IXN5QRA8XkE
- How to Play GLA - Part 1 (beginner level) — https://www.youtube.com/watch?v=haH2teyo1fc
- How to Play GLA - Part 3 (hotkeys, tech rpg/terror combo strike) — https://www.youtube.com/watch?v=g-6P9ar-aEg
- ZH - GLA All-In Strategy vs USA — https://www.youtube.com/watch?v=m8PeUyRTaZg
- ZH - Stealth vs Tox Strategy Guide — https://www.youtube.com/watch?v=SgeSosh79MM
- Replay Review - Improve GLA Mirror on Sand Scorpion — https://www.youtube.com/watch?v=0TMkTbGrd0g
- ZH - What is Waypoint Scouting? — https://www.youtube.com/watch?v=ndeMKOKJVC4
- What is Pro Rules in Zero Hour? (and noob rules) — https://www.youtube.com/watch?v=SK2olkdvTtM
- ZH - 5x Top Level Tips — https://www.youtube.com/watch?v=yXdfytqDEeg

### Веб
- GameReplays, «#30 - 22/04/07 - Selling Your Command Center» (EteRnaL, 23.04.2007) — https://www.gamereplays.org/community/index.php?showtopic=228906
- C&C Wiki (Fandom), «Command center (Generals)» — https://cnc.fandom.com/wiki/Command_center_(Generals)

### Дані гри / код
- TheSuperHackers/GeneralsGamePatch (коміт 6c7f40d), оригінальні INI ZH 1.04:
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/GameData.ini (`SellPercentage = 50%`, `DefaultStartingCash = 10000`)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/FactionBuilding.ini (CC, Supply, Power, Fake-будівлі, пререквізити, Cash Bounty 5/10/20%, `DisplayName = OBJECT:ColdFusionReactor`)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/AirforceGeneral.ini (AFG Chinook $950, AirF Airfield $800, Carpet Bomb на Strategy Center)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/LaserGeneral.ini (`Lazr_AmericaPowerPlant` $700)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/SuperWeaponGeneral.ini (`SupW_AmericaPowerPlant` $900)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/NukeGeneral.ini (`Nuke_ChinaPowerPlant` $1200)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Object/TankGeneral.ini (`Tank_ChinaCommandCenter`: Tank Paradrop, Early Emergency Repair)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/CommandSet.ini (хто виробляє Dozer/Worker, промоції за рангами, `*_CommandSetRank1`)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Science.ini (ранги промоцій: Spy Drone, Early Emergency Repair, Early Frenzy — Rank 1; Cash Bounty 1–3 — Rank 3)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/SpecialPower.ini (перезарядки, RequiredScience, SharedSyncedTimer)
  - https://github.com/TheSuperHackers/GeneralsGamePatch/blob/main/Patch104pZH/GameFilesOriginalZH/Data/INI/Upgrade.ini (China Radar $500, Mines $600)
- electronicarts/CnC_Generals_Zero_Hour (коміт 0a05454):
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/Common/System/BuildAssistant.cpp (продаж: таймінг, 50%, скасування черги)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/Common/RTS/Player.cpp (`findMostReadyShortcutSpecialPowerOfType`, `doFindSpecialPowerSourceObject`: пропуск UNDER_CONSTRUCTION / SOLD)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/GameLogic/Object/Object.cpp (`prependTo_TeamMemberList` — порядок обходу об'єктів)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/GameLogic/ScriptEngine/VictoryConditions.cpp (умови поразки)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/GameLogic/Object/SpecialPower/CashBountyPower.cpp (Cash Bounty: `onObjectCreated`, `onSpecialPowerCreation`)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/GameLogic/Object/SpecialPower/SpecialPowerModule.cpp (таймери сил)
  - https://github.com/electronicarts/CnC_Generals_Zero_Hour/blob/main/GeneralsMD/Code/GameEngine/Source/GameClient/GUI/ControlBar/ControlBar.cpp (покупка промоцій без перевірки CC)

---

Перевірено: дослідник → скептик → редактор
