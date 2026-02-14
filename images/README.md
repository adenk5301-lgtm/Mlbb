# MLBB Hero Platform - Images Guide

## How to Add Hero and Item Images

### Hero Images
1. **Location**: Place hero images in `mlbbwebsite/images/heroes/`
2. **Naming Convention**: Use the hero name in lowercase with `.png` extension
   - Example: `gusion.png`, `fanny.png`, `ling.png`, `kagura.png`
3. **Supported Formats**: `.png`, `.jpg`, `.jpeg`, `.webp`
4. **Recommended Size**: 96x96 pixels or larger (will be automatically resized)

### Item Images  
1. **Location**: Place item images in `mlbbwebsite/images/items/`
2. **Naming Convention**: Use the item name in lowercase, replace spaces and special characters with hyphens
   - Example: `hunter-strike.png`, `malefic-roar.png`, `calamity-reaper.png`
3. **Supported Formats**: `.png`, `.jpg`, `.jpeg`, `.webp`
4. **Recommended Size**: 48x48 pixels or larger

### Current Heroes with Image Support:
- Gusion (`gusion.png`)
- Fanny (`fanny.png`) 
- Ling (`ling.png`)
- Kagura (`kagura.png`)
- Layla (`layla.png`)
- Miya (`miya.png`)
- Eudora (`eudora.png`)
- Chou (`chou.png`)
- Hayabusa (`hayabusa.png`)
- Franco (`franco.png`)
- Johnson (`johnson.png`)
- Natalia (`natalia.png`)
- Alucard (`alucard.png`)
- Zilong (`zilong.png`)
- Saber (`saber.png`)
- Chang'e (`chang-e.png`)
- Cyclops (`cyclops.png`)
- Claude (`claude.png`)
- Karrie (`karrie.png`)
- Tigreal (`tigreal.png`)
- Khufra (`khufra.png`)
- Estes (`estes.png`)
- Balmond (`balmond.png`)
- Lancelot (`lancelot.png`)
- Granger (`granger.png`)
- Esmeralda (`esmeralda.png`)
- Hanabi (`hanabi.png`)
- Aurora (`aurora.png`)
- Diggie (`diggie.png`)
- Aamon (`aamon.png`)
- Akai (`akai.png`)
- Alice (`alice.png`)
- Beatrix (`beatrix.png`)
- Brody (`brody.png`)
- Guinevere (`guinevere.png`)
- Harley (`harley.png`)
- Irithel (`irithel.png`)
- Jawhead (`jawhead.png`)
- Karina (`karina.png`)
- Lesley (`lesley.png`)
- Lunox (`lunox.png`)
- Moskov (`moskov.png`)
- Nana (`nana.png`)
- Odette (`odette.png`)
- Pharsa (`pharsa.png`)
- Rafaela (`rafaela.png`)
- Roger (`roger.png`)
- Selena (`selena.png`)
- Sun (`sun.png`)
- Valir (`valir.png`)
- Wanwan (`wanwan.png`)
- Xavier (`xavier.png`)
- Bruno (`bruno.png`)
- Clint (`clint.png`)
- Gord (`gord.png`)
- Hilda (`hilda.png`)
- Hylos (`hylos.png`)
- Vale (`vale.png`)
- Alpha (`alpha.png`)
- Angela (`angela.png`)
- Argus (`argus.png`)
- Badang (`badang.png`)
- Bane (`bane.png`)
- Belerick (`belerick.png`)
- Benedetta (`benedetta.png`)
- Barats (`barats.png`)
- Baxia (`baxia.png`)
- Carmilla (`carmilla.png`)
- Cecilion (`cecilion.png`)
- Dyrroth (`dyrroth.png`)
- Gatotkaca (`gatotkaca.png`)
- Gloo (`gloo.png`)
- Grock (`grock.png`)
- Hanzo (`hanzo.png`)
- Harith (`harith.png`)
- Kadita (`kadita.png`)
- Kaja (`kaja.png`)
- Kimmy (`kimmy.png`)
- Leomord (`leomord.png`)
- Lolita (`lolita.png`)
- Lylia (`lylia.png`)
- Martis (`martis.png`)
- Minotaur (`minotaur.png`)
- Paquito (`paquito.png`)
- Popol (`popol.png`)
- Ruby (`ruby.png`)
- Terizla (`terizla.png`)
- Uranus (`uranus.png`)
- Wanwan (`wanwan.png`)
- Yi Sun-shin (`yss.png`)
- Zhask (`zhask.png`)
- Zilong (`zilong.png`)
- Jawhead (`jawhead.png`)
- Thamuz (`thamuz.png`)
- Freya (`freya.png`)
- Minsitthar (`minsitthar.png`)
- Faramis (`faramis.png`)
- Floryn (`floryn.png`)
- Mathilda (`mathilda.png`)
- Edith (`edith.png`)
- Estes (`estes.png`)
- Melissa (`melissa.png`)
- Valentina (`valentina.png`)
- Xavier (`xavier.png`)
- Joy (`joy.png`)
- Novaria (`novaria.png`)
- Chip (`chip.png`)
- Nolan (`nolan.png`)
- Arlott (`arlott.png`)
- Cici (`cici.png`)
- Zhuxin (`zhuxin.png`)
- Aulus (`aulus.png`)
- Lapu-Lapu (`lapu.png`)
- Kagura (`kagura.png`)
- Yin (`yin.png`)
- Julian (`julian.png`)
- Phylax (`phylax.png`)
- Xavier (`xavier.png`)
- Grock (`grock.png`)

### Current Items with Image Support:
- Hunter Strike (`hunter-strike.png`)
- All other items will automatically look for images based on their names

### Fallback Behavior:
- If an image file is not found, the system will automatically generate a colored SVG placeholder
- Hero placeholders use role-based colors (Assassin=Purple, Mage=Blue, etc.)
- Item placeholders show the item type abbreviation

### Tips:
1. Use high-quality PNG images for best results
2. Square aspect ratio works best for heroes
3. Clear, recognizable icons work best for items
4. File sizes should be reasonable (under 500KB each)
5. Test your images by searching for the hero/item in the website

### Adding New Heroes:
When adding a new hero to the database, make sure to:
1. Add the `image: "images/heroes/heroname.png"` property
2. Place the corresponding image file in the heroes folder
3. Use the exact hero name (lowercase) for the filename