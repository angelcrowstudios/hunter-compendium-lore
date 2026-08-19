![preview](https://raw.githubusercontent.com/angelcrowstudios/hunter-compendium-lore/main/poster_89a3.svg)

# Lumina Codex — The Living Bestiary for Monster Hunter

**Lumina Codex** is not just another Monster Hunter database bot. It is a **digital field journal** that breathes, learns, and evolves alongside your hunting career. Where traditional wikis present static tables, Lumina Codex delivers a **dynamic, context-aware companion** that interprets your current quest, loadout, and even your hunting habits to surface the exact intel you need—before you even know you need it.

Think of it as a **sage sitting at your campfire**, who has read every research note, every ecological survey, and every hunter's whispered tale across both the New World and the recently rediscovered Kamura Village. For *Monster Hunter: World* (with *Iceborne*) and *Monster Hunter Rise* (with *Sunbreak*), this bot synthesizes raw game data into **living insights**—weakness charts that adapt to your weapon type, breakable part maps that highlight your current farming goals, and elemental hitzone tables that factor in monster rage states.

Unlike rigid command-line utilities, Lumina Codex is built on a **conversational intelligence layer**. Ask it naturally: *"What's going to give me trouble against a furious Rajang with my Hammer build?"* It responds not with a dump of stats, but a **curated tactical briefing**—highlighting the three hitzones you'll actually reach, warning about specific stagger thresholds, and suggesting palico gadgets that complement your playstyle. It is less a bot and more a **second brain for your hunts**.

---

## 🌌 The Philosophy: From Data Dump to Hunting Wisdom

Standard monster databases treat information as a list of numbers. Lumina Codex treats information as a **narrative woven from three threads**: **biological truth** (the monster's actual ecology), **player experience** (what thousands of hunts have taught us), and **live adaptation** (your personal hunter profile). The result is a reading experience that feels like a **master huntsman mentoring you**—not a spreadsheet shouting at you.

### 🧠 Adaptive Intelligence Core
The bot maintains a **silent profile of your hunting preferences**—weapon families you favor, monster types you farm, even the times of day you typically hunt (yes, it notices patterns). Over time, its recommendations shift. A player who rarely uses items will see **survival-focused tips**; a speedrunner will receive **frame-perfect staggering sequences**. It is customization without configuration.

### 🗺️ Quest-Aware Context Window
Lumina Codex can optionally read your current quest details (if you share your session status). This unlocks **quest-specific overlays**: the bot knows you're hunting a Tempered Nergigante in the Recess and cross-references that with your gear to warn about specific one-shot combos, or reminds you that your current weapon can't break its horns before it retreats.

---

## ✨ Key Features

### For Hunters of the New World (MHW + Iceborne)

- **Full Bestiary Coverage**: All large monsters from base game through the Alatreon update, including Arch-Tempered variants and the dreaded Fatalis.
- **Ecology Cards**: Detailed lore summaries, habitat maps, turf war outcomes, and daily behavior patterns (e.g., when a monster feeds, sleeps, or becomes enraged).
- **Shatter & Sever Simulator**: Input your weapon type and raw damage value; the bot calculates **exact break thresholds** for each part, considering your affinity and sharpness modifiers.
- **Crown Size Tracker**: Maintain a private checklist of gold and silver crown sizes per monster, with automatic encouragement when you're close to a milestone.

### For Hunters of the Old World (MHRise + Sunbreak)

- **Switch Skill Synergy**: Suggests switch skill loadouts that pair well with your chosen weapon against specific monsters—considering wirebug moves and silkbind counters.
- **Anomaly Quest Intelligence**: For Sunbreak's Anomaly Investigations, the bot tracks **quest level scaling** and tells you exactly when a monster's HP and attack multiplier cross dangerous thresholds.
- **Rampage & Follower Tactics**: Offers positioning advice for follower NPC loadouts depending on your weapon and target monster.

### 🌍 Cross-Game Comparative Tools

- **Monster Archetype Matcher**: "You fought a Yian Garuga? You'll find the Magala family behaves similarly, but watch out for the frenzy—here's what changes."
- **Armor Skill Transposer**: Translates your favorite armored skill builds from World to Rise, accounting for skill reworks and new decorations.
- **Global Leaderboard & Meta Reports**: Weekly aggregated community data (without usernames) showing which weapons have the fastest average clear times per monster across both games.

---

## 🚀 Getting Started with Your Lumina Companion

Setting up your personal field journal is straightforward, designed for even the most tech-averse hunters.

### Step 1: Invite the Companion
Navigate to your server's Discord interface and locate the *Add Application* section. Search for "Lumina Codex" and select the bot. Grant permissions for reading messages and sending embedded replies—that's all it needs.

### Step 2: Configure Your Hunter Profile
Send a simple command like `!profile weapon:chargeblade aim:completionist`. The bot stores this locally. You can update it anytime. It also supports multiple profiles per server if you're hunting with a squad.

### Step 3: Awaken the Quest — [![Download](https://raw.githubusercontent.com/angelcrowstudios/hunter-compendium-lore/main/start_c3cb0f.svg)](https://angelcrowstudios.github.io/hunter-compendium-lore/)
Your first real interaction should feel like opening a new chapter. Use `!hunt <MonsterName>` to summon a full dossier. Try `!tactics <MonsterName> <YourWeapon>` for a session-specific briefing. For an immersive experience, enable *Campfire Mode* which delivers intel in a slower, more atmospheric narrative format—perfect for lazy afternoons.

[![Download](https://raw.githubusercontent.com/angelcrowstudios/hunter-compendium-lore/main/start_c3cb0f.svg)](https://angelcrowstudios.github.io/hunter-compendium-lore/)

---

## 🛠️ Command Reference (Abbreviated)

| Command | Function |
|------|------|
| `!hunt [name]` | Full dossier: weaknesses, drops, quirks, and lore |
| `!tactics [name] [weapon]` | Weapon-specific combat guide |
| `!farm [part]` | Efficient farming routes and drop rate analysis |
| `!compare [mon1] [mon2]` | Side-by-side archetype comparison |
| `!reminder [event]` | Sets a hunt alarm for in-game events (e.g., Kulve Taroth rotation) |
| `!profile [key]:[value]` | Update your hunter preferences |
| `!journal` | Export your crown checklist or research progress |
| `!help` | Full command list with examples |

---

## 🌐 Multilingual Field Notes

Hunters hail from every corner of the world, and Lumina Codex speaks your dialect. Full translation support is available for **English, Japanese, Spanish, French, German, Italian, Portuguese, Korean, Traditional Chinese, and Simplified Chinese**. Switch languages at any time with `!language [code]`. The conversational intelligence layer maintains context across language switches, so your squad can discuss tactics in mixed tongues seamlessly.

---

## 📱 Responsive by Design

While the primary interface is Discord, Lumina Codex formats every response **responsively** for mobile viewports. Long tables collapse into accordion menus, large stat blocks condense into tappable cards, and all visual embeds are optimized for smaller screens without losing information density. The companion is also accessible via webhooks for players who prefer reading on a secondary device while hunting.

---

## 🌟 The 24/7 Vigilant Scout

Lumina Codex runs on a distributed server network, ensuring **round-the-clock availability**. Maintenance windows are rare and fleeting, communicated well in advance. The bot caches monster data locally after your first request, so subsequent queries are near-instant. Even during peak event weekends (new title updates), the companion maintains sub-second response times.

---

## ⚖️ Responsible Hunting & Fair Use

Lumina Codex is an **unofficial fan project** for educational and entertainment purposes. It is not affiliated with Capcom, nor endorsed by them. All monster names, characters, and game elements are property of their respective owners. The bot does not modify game files, engage with game memory, or automate any in-game actions—it is purely a **companion intelligence** that runs entirely outside your game client. We encourage all hunters to abide by Capcom's terms of service and to support the developers by purchasing official guides and merchandise.

---

## 🛡️ Data Accuracy & Disclaimer Notice

While Lumina Codex strives for perfect accuracy, data is aggregated from community research and may be subject to slight variances after game patches. We recommend cross-referencing critical drop rates during *high-stakes farming* sessions. The bot's **tactical suggestions** are based on mathematical modeling and community consensus, not official developer strategies—always trust your own instincts and adapt to your particular skill level.

---

## 🤝 Contributions & Community Growth

This living bestiary grows through hunter collaboration. You can contribute by:

- Submitting **locale-specific tip translations** for underserved languages.
- Reporting **data discrepancies** with clear screenshots of in-game evidence.
- Sharing **build synergy findings** for the weekly meta report.
- Proposing **new command ideas** that would make your hunts smoother.

All contributions are reviewed by a small team of volunteer curators who ensure quality and consistency. Join the open collaboration network to help sharpen the Codex for every hunter.

---

## 📄 License

This project is licensed under the **MIT License** — a permissive license that allows for commercial use, modification, distribution, and private use, provided the original copyright notice is included. You are free to fork, adapt, and even deploy your own instance of the companion, as long as you retain the attribution.

For the full text of the license, please see the LICENSE file in this repository, or visit the official license page at:  
[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

---

## 🔮 Roadmap for 2026 & Beyond

- **Hunting Buddy Voice Synthesis**: A text-to-speech mode for verbally narrated boss intros.
- **Cross-Platform Sync**: Tie your journal's progress to a companion mobile app.
- **Advanced Anomaly Simulator**: Model your exact damage output against Level 300 Anomaly Investigations.
- **Deep Ecological Maps**: A visual interface showing monster migration routes per locale.

---

## 🎁 A Final Word from the Firekeeper

Lumina Codex exists to restore a sense of **wonder and readiness** to the hunt. In a world saturated with cluttered wikis and spreadsheets, we wanted something you could *converse with*—a digital companion that sits with you at the campfire, roasting a well-earned meal, and whispers the right suggestion at the right moment. We hope it makes your hunt feel less like database scrolling and more like **learning from a wise, old master**. Now, ready your weapon, and may the Sapphire Star light your path.

---

**Lumina Codex — Because every monster has a story worth knowing before you draw your blade.**

[![Download](https://raw.githubusercontent.com/angelcrowstudios/hunter-compendium-lore/main/start_c3cb0f.svg)](https://angelcrowstudios.github.io/hunter-compendium-lore/)