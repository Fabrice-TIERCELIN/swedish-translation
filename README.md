# How to contribute

[This page](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md) explains how to translate VCMI. You can find original content [here](https://github.com/vcmi-mods/h3-for-vcmi-englisation) and text-free images [here](https://github.com/vcmi-mods/empty-translation). If you can't translate images or sounds on your own, write the translation and the exact location in this file.

Please create a new issue [here](https://github.com/vcmi-mods/swedish-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Swedish

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Swedish_
1. Install the _Översättning till svenska_ mod
1. Launch the game

# Hur man spelar Heroes of Might and Magic III på svenska

1. Köp _Heroes of Might and Magic III Complete Edition_ på GOG (inte HD-versionen)
1. Installera spelet
1. Ladda ner VCMI (gratis)
1. Installera VCMI
1. När du installerar VCMI, ange platsen för grundspelets mappar `Data`, `MP3` och `Maps`.

1. Ställ in språket till _Swedish_
1. Installera modden _Översättning till svenska_
1. Starta spelet

# How to dub

1. Copy a prolog/epilog from [`swedish-translation/content/config/vcmi-swedish/campaigns.json`](https://github.com/vcmi-mods/swedish-translation/tree/vcmi-1.7/swedish-translation/mods/AITranslated/Content/config/vcmi-swedish-ai/)
2. Go to [this](https://huggingface.co/spaces/k2-fsa/OmniVoice) OmniVoice TTS
3. Click on _Clone voice_
4. Paste the speech text
5. Select _swedish_
4. Upload a voice
3. Paste the reference text
6. Click on _Generate_
7. Download the audio file
8. Retrieve the property for the speech in the [`swedish-translation/content/config/vcmi-swedish/campaigns.json`](https://github.com/vcmi-mods/swedish-translation/tree/vcmi-1.7/swedish-translation/mods/AITranslated/Content/config/vcmi-swedish-ai/) file
9. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
10. Rename the audio file
11. Move the file to `swedish-translation/content/sounds/` folder

# How to contribute

1. Go to the GitHub mod page: https://github.com/vcmi-mods/swedish-translation
2. Fork the repository by clicking on the "Fork" button
3. Browse to the file you want to change
4. Click on the pencil button to edit the file
5. Edit the file
6. Click on the "Commit changes..." button
7. Click on the "Pull request" tab
8. Click on the "Create Pull Request" button
9. Write a description and create the PR (Pull Request)