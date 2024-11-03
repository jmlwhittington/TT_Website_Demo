---
layout: default
title: Projects
---

Below lies a mixture of academic (▲), game design/development (■), and programming (●) projects.

# Ongoing
## [Appalachian Game Presence Repository](https://jmlwhittington.com/agpr/) ▲
- The objective of the repository is to document instances of Appalachian presence in games both digital or analog, be it through setting, characters, or cultural markers. Presence may also be felt through paratextual elements. While originally envisioned as a solely video game catalog, the project has extended to include tabletop games, sports, and situated examples of traditional play. As it is of a historical nature, the goal is to direct attention to cases of Appalachia's portrayal, reception, and experience in the ludic form, possibly inspiring other projects and research. It's worth noting that this repository will likely remain in a perpetual state of incompleteness. That’s okay, as a total inventory is not the point.
- **Technologies used:** A self-hosted [WordPress](https://en.wikipedia.org/wiki/WordPress) installation based in Charleston, West Virginia, complete with custom domain name; a variety of search engines and academic databases (e.g., [Primo Search](https://ucf-flvc.primo.exlibrisgroup.com/discovery/search?vid=01FALSC_UCF:UCF) @ UCF, [JSTOR](https://www.jstor.org/))

## [AppalachianGameStudies Google Group](https://groups.google.com/g/appalachian-game-studies/about) ▲
- A centering point for the discussion of an Appalachian game studies, which is to say all intersections of Appalachian studies and game studies. Such projects under this banner are only beginning to be considered. This group thus aims to keep interested parties apprised of recent developments, concentrate appraisals, and network projects new and in-progress. As an inherently interdisciplinary endeavor, this group still intends to loosely coordinate efforts in a direction unified by shared, common goals. What these goals are is of course to be determined through our collaboration. They may be conceptualized, however, through the label of [regional game studies as proposed by Bjarke Liboriussen and Paul Martin](https://gamestudies.org/1601/articles/liboriussen). To borrow the open embrace of perspective from our source disciplines, we are open to all scholars, educators, practitioners, activists, students, professionals, developers, and individuals interested in this subject matter.
- **Technologies used:** [Google Groups](https://en.wikipedia.org/wiki/Google_Groups)

## Machine learning model trained on video game covers categorized by genre ▲
- As part of a class project that may potentially grow into more, I've begun training a machine learning model on video game covers, categorized by a currently evolving typology of genre, and testing these out via a confusion matrix that includes a category for low confidence. I'm seeking to see if the model can identify patterns I can't, see what patterns emerge in its confusions, identify relationships between the model's best guess and lowered ordered guesses, and possibly more. The project began as an attempt at investigating how video game genre is communicated.
- **Technologies used:** [Teachable Machine](https://teachablemachine.withgoogle.com/); [OpenProcessing](https://openprocessing.org/); various search engines

## Untitled scifi Western campaign setting ■
- A scifi Western campaign setting for a slightly modified ruleset based on [*Pathfinder First Edition*](https://en.wikipedia.org/wiki/Pathfinder_Roleplaying_Game), a tabletop roleplaying game. This project began as a bringing-to-life of the idea "What if the ['Knights of Cydonia' music video by Muse](https://www.youtube.com/watch?v=G_sBOsh-vyI) were a campaign setting?," and has since evolved into its own entity independent of its original inspiration. It has been on and off development since September 2020 due to various life events. A release date is not yet in sight. My master's degree final project in critical game design explored the project. In this, I developed an iterative design framework inspired by [Mary Flanagan's critical play game design model](https://mitpress.mit.edu/9780262518659/critical-play/) and the [Method for Design Materialization (MDM) in game design as detailed by Rilla Khaled and Pippin Barr](https://doi.org/10.1162/desi_a_00706). Thus, public alpha and beta releases are being considered as resources (namely time) allow.
- **Technologies used:** A self-hosted [Mediawiki](https://en.wikipedia.org/wiki/MediaWiki) installation based in Charleston, West Virginia, complete with custom domain name, for organizing and presenting materials in version-controlled iterative design; [Roll20](https://roll20.net/) for multimedia-enabled (e.g., background music) and distance playtests; C# in Visual Studio to create various companion tools such as character creators; the [Pathfinder Reference Document](https://legacy.aonprd.com/) database

# On hold
## PF1e Character Manager ●
- A character creation and management tool written in C# for *Pathfinder First Edition*.
- **Technologies used:** C# in Visual Studio; the [Pathfinder Reference Document](https://legacy.aonprd.com/) database; GitHub for version control

# Completed
## Automation/process digitization for [Marshall University HELP Program](https://www.marshall.edu/help/) weekly logs and reports ●
- Digital forms and scripts for analysis of weekly tutoring logs at Marshall University's H.E.L.P. Program, per request by director to digitize and create quantifiable results for reporting to higher administration, designed for ease of maintenance after my graduation. Designed to be easily maintained and upgraded with low future skill barrier.
- **Technologies used:** [Microsoft Forms](https://en.wikipedia.org/wiki/Microsoft_Forms); [Google Forms](https://en.wikipedia.org/wiki/Google_Forms); [Visual Basic for Applications](https://en.wikipedia.org/wiki/Visual_Basic_for_Applications) in macro-enabled Excel spreadsheets; user documentation in Microsoft Word

## Experimental panels in public digital humanities with game fan communities at popular culture conventions ▲
- Two attempts to bring game scholarship to gaming communities at large (as well as to invite audience participation and discussion) at popular culture conventions during summer 2023. The first was presented at [HerdCon](https://www.marshall.edu/herdcon/), hosted at Marshall University in Huntington, West Virginia, and was titled "The Relationship between Video Games and US Foreign Policy," adaptated from a conference paper presentation also at the university. The second occurred at [PopCon Louisville](https://popcon.us/popcon-louisville/) in Louisville, Kentucky, and was titled "Wandering in the Expanse: Meaning-Making in *Minecraft*," which went on to inform my [2024 DiGRA extended abstract](https://dl.digra.org/index.php/dl/article/view/2249).
- **Technologies used:** Microsoft PowerPoint; Google Slides; audiovisual equipment for presentation provided by venues

## Sha Ka Ree modpack for *Minecraft* version 1.18.2 ■
- A *Minecraft* modpack developed for exploring environmentalist and postcolonial play, resulting in the work that became my [2024 DiGRA extended abstract](https://dl.digra.org/index.php/dl/article/view/2249).
- **Technologies used:** *Minecraft* version 1.18.2; [Forge mod loader](https://files.minecraftforge.net/net/minecraftforge/forge/); various mods developed by a larger community available at [CurseForge](https://www.curseforge.com/minecraft); [Notepad++](https://en.wikipedia.org/wiki/Notepad%2B%2B) for configuration of mods; various pieces of virtualization and server software for self-hosting the multiplayer aspect of the modpack

## [RandomRSSTwitterBot](https://github.com/jmlwhittington/RandomRSSTwitterBot) ●
- A Twitter bot written in C# using Tweetinvi and System.ServiceModel.Syndication to tweet a random article from a custom list of RSS feeds at a custom frequency in hours.
- **Technologies used:** C# in Visual Studio; [Tweetinvi](https://github.com/linvi/tweetinvi) library; [System.ServiceModel.Syndication](https://www.nuget.org/packages/System.ServiceModel.Syndication/) package; Twitter API; [RSS](https://en.wikipedia.org/wiki/RSS); GitHub for version control and releases

## Project Prometheus ■
- A prototype of a [multiplayer online battle arena (MOBA)](https://en.wikipedia.org/wiki/Multiplayer_online_battle_arena) in Unreal Engine 4.26 based off a custom scenario from [*Empire Earth: The Art of Conquest*](https://en.wikipedia.org/wiki/Empire_Earth:_The_Art_of_Conquest) called "Mech Warrior."
- **Technologies used:** [Unreal Engine](https://en.wikipedia.org/wiki/Unreal_Engine) with [Blueprints](https://www.unrealengine.com/fr/blog/introduction-to-blueprints); [Unreal Marketplace](https://www.unrealengine.com/marketplace/en-US/) free assets (now [Fab](https://www.fab.com/)); [Mixamo](https://www.mixamo.com/) for animations; [Mixamo Converter](https://terribilisstudio.fr/?section=MC) for making Mixamo animations usable; [Trello](https://en.wikipedia.org/wiki/Trello) for project management; [Google Workspace](https://en.wikipedia.org/wiki/Google_Workspace) for design documents and other materials

## [UESRPG3eGMTool](https://github.com/jmlwhittington/UESRPG3eGMTool) ●
- A tool written in C# which assists the gamemaster of an [*Unofficial Elder Scrolls Roleplaying Game* (UESRPG)](https://uestrpg.com/) 3rd Edition session in automating the reading of stat blocks from the bestiary and other sources, as well as player attack and damage rolls against these.
- **Technologies used:** C# in Visual Studio; Google Drive for accessing gameplay materials; GitHub for version control and releases

## [econSuite](https://github.com/jmlwhittington/econSuite), economy apps contracted for public Minecraft server ●
- A suite of economy apps written in Lua via ComputerCraft for a public *Minecraft* server, including banking/virtual currency, trading exchange akin to [*RuneScape*](https://en.wikipedia.org/wiki/Old_School_RuneScape)'s [Grand Exchange](https://oldschool.runescape.wiki/w/Grand_Exchange), trade booths, and individual shops for players.
- **Technologies used:** [Lua](https://en.wikipedia.org/wiki/Lua_(programming_language)) via the [ComputerCraft](https://computercraft.cc/) mod for *Minecraft*; GitHub for version control

## [Modulate.ai](https://www.modulate.ai/) VoiceWear closed alpha tester ●
- Testing of an AI-powered voice changing software, for my purposes to be used in running tabletop roleplaying games for providing more immersive experiences.
- **Technologies used:** Modulate.ai's [VoiceWear](https://www.modulate.ai/blog/voicewear-individual-identity) (no longer available due to ethical consideration of product, new product shifts burden from abused to abusers)

##  West Virginia campaign setting for [Jason Mical's Fallout PnP 2.0 system](https://falloutpnp.fandom.com/wiki/Jason_Mical%27s_Pen_and_Paper_2.0) ■
- As titled, developed first a campaign amongst friends before developing into a larger project, planned for conversion into a [*Fallout 4*](https://en.wikipedia.org/wiki/Fallout_4) mod but abandoned following the announcement of [*Fallout 76*](https://en.wikipedia.org/wiki/Fallout_76).
- **Technologies used:** [Fandom wiki](https://en.wikipedia.org/wiki/Fandom_(website)) for system; [Google Workspace](https://en.wikipedia.org/wiki/Google_Workspace) for recording materials
