# Rose Gold Alloy Mod
Minecraft 1.21.10 | Fabric | Mojang Mappings  
Mod ID: rosegoldalloy  
Package Root: dev.maleficent.rosegoldalloy

This document outlines the current state of the mod as of v0.6.0 and the broader design plan shaping its evolution.

--------------------------------------------------------------------
## 0. Implemented Features (v0.6.0)

This section presents all features currently available in the mod, focusing on concept, identity and gameplay experience rather than technical detail.

### 0.1 Rose Gold Alloy

• The Rose Gold Ingot is the signature material of the mod.  
• It is crafted intentionally from Copper, Gold and Amethyst, reinforcing the idea that Rose Gold is a refined alloy created by skilled players rather than a natural resource.  
• Positioned between Iron and Diamond, it offers stronger refinement, better durability and high enchantability without overshadowing later-game tiers.

### 0.2 Rose Gold Block

• Ingots can be condensed into a Rose Gold Block for compact storage or use in decorative builds.  
• The block reflects the alloy’s warm, polished aesthetic and serves as a visual anchor for the material set.

### 0.3 Rose Gold Tools and Weapon

The mod includes a complete family of Rose Gold equipment that defines the mid-tier identity of the alloy:

• Rose Gold Sword  
• Rose Gold Pickaxe  
• Rose Gold Axe  
• Rose Gold Shovel  
• Rose Gold Hoe

These tools emphasize refined craftsmanship, balanced performance and strong synergy with enchantments, giving players a smooth progression step between Iron and Diamond.

### 0.4 Rose Gold Armor (New in v0.6.0)

A full wearable armor set has been introduced, completing the Rose Gold equipment tier:

• Helmet  
• Chestplate  
• Leggings  
• Boots

The armor maintains the alloy’s design philosophy:
• Protection between Iron and Diamond  
• High enchantability and strong compatibility with enchantment-based builds  
• A warm, elegant appearance that matches the material’s visual identity  
• Unique armor textures supplied through a custom equipment asset

This addition solidifies Rose Gold as a self-contained, fully functional material tier.

### 0.5 Crafting and Progression

• Rose Gold is not mined; it is crafted with intention and refinement.  
• Its shaped recipe reflects its symbolic components and rewards players who explore multiple biomes and gather diverse resources.  
• Tools, armor and the Rose Gold Block unlock naturally through inventory-based progression, mirroring vanilla’s advancement-driven recipe discovery style.  
• The progression from Ingot → Tools → Armor → Block forms a coherent upgrade path without overwhelming new players.

### 0.6 Data-Driven Foundation

• All items, blocks, models, recipes and tags use a clean data-driven layout.  
• This ensures easy expansion in future versions, including decorative blocks, trims and gameplay features.  
• The mod structure is prepared for long-term maintenance and compatibility with future Minecraft updates.

--------------------------------------------------------------------
## 1. Core Concept

Rose Gold is a player-crafted alloy introduced to fill the gap between Iron and Diamond.  
It blends elegance, refinement and magical affinity, offering utility without power creep.

Unlike traditional progression metals:
• It cannot be mined  
• It cannot be looted  
• It must be *made*, reflecting craftsmanship and intention

This positions Rose Gold as a creative mid-tier material with personality and purpose.

--------------------------------------------------------------------
## 2. Materials

### 2.1 Rose Gold Ingot

The foundational material of the mod.  
Crafted, not discovered.  
Warm, polished, versatile and highly enchantable.

--------------------------------------------------------------------
## 3. Crafting and Progression

### 3.1 Alloy Creation

Rose Gold is created through a shaped recipe combining Gold, Copper and Amethyst.  
This symbolic combination represents purity, structure and crystalline refinement.

Pattern (rows):  
Row 1: G A  
Row 2: C C

Result: 2 Rose Gold Ingots

### 3.2 Storage Cycle

• 9 Ingots → 1 Rose Gold Block  
• 1 Block → 9 Ingots

A familiar metal loop for tidy storage and resource management.

### 3.3 Recipe Unlocking Philosophy

• Recipes unlock automatically as players obtain relevant materials.  
• This mirrors vanilla’s invisible advancement system, giving players intuitive progression without cluttering the recipe book.

--------------------------------------------------------------------
## 4. Equipment

### 4.1 Design Philosophy

Rose Gold equipment emphasizes refined craftsmanship, magical affinity and increased enchantability.  
It offers better durability and smoother handling than Iron, while stopping short of Diamond’s raw strength.

Its niche is “mid-tier elegance”:  
reliable, enchanting-friendly and visually distinct.

### 4.2 Tool Set

The mod includes a complete tool set:  
• Sword  
• Pickaxe  
• Axe  
• Shovel  
• Hoe

These tools are suited for players who want a refined mid-tier experience with strong enchantment synergy.

### 4.3 Armor Set

Added in v0.6.0, the Rose Gold Armor Set completes the equipment family.

Its identity:  
• Protection between Iron and Diamond  
• High enchantability  
• Distinct, warm metallic visuals  
• Custom equipment asset for proper 1.21+ rendering  
• Consistent mid-tier gameplay progression

--------------------------------------------------------------------
## 5. Blocks

### 5.1 Rose Gold Block

A decorative and storage block reflecting the alloy’s visual style.  
Future updates may introduce additional variations such as plates, tiles, bars or polished forms.

--------------------------------------------------------------------
## 6. Armor Trim Integration (Planned)

Rose Gold will later be introduced as a trim material, enabling elegant warm-toned highlights on customizable armor.  
The intended palette blends golden shine with copper warmth.

--------------------------------------------------------------------
## 7. Future Ideas

Long-term possibilities include:  
• Decorative block families (tiles, polished forms, bars, ornaments)  
• Optional patina/tarnish states  
• Crafting refinements or thematic utilities  
• World flavor content or optional datapack integration  
• Community-driven expansions

These remain fluid and will evolve as feedback grows.

--------------------------------------------------------------------
## 8. Development Notes

• Built for Minecraft 1.21.10 using Fabric Loader 0.18.1  
• Uses Mojang official mappings  
• Data generation is implemented for recipes, models, tags and loot tables  
• The structure is optimized for future additions and clean maintainability

--------------------------------------------------------------------
## 9. Roadmap Overview (Revised)

Rose Gold Alloy is designed as a complete but finite material tier.  
Its purpose is to behave like a fully-realized vanilla metal, without introducing exclusive items or mechanics that belong only to Iron or Gold.  
Once the full “vanilla metal package” is complete, the mod will be considered functionally finished.

### Phase 1 — Material Foundation
• Completed: Rose Gold Ingot  
• Completed: Alloy recipe  
• Completed: Rose Gold Block (standard storage block)

### Phase 2 — Complete Equipment Tier
• Completed: Full tool set (sword, pickaxe, axe, shovel, hoe)  
• Completed: Full armor set (helmet, chestplate, leggings, boots)  
• Completed: Proper enchantment support and repair materials  
• Completed: Custom armor visuals via equipment assets  
• Planned: Introduce Rose Gold as an optional armor trim material

### Phase 3 — Decorative Block Family (Vanilla Parity Only)
Rose Gold will get the standard building/decorative variations that other metals receive when applicable.

Planned:
• Polished / refined block variants  
• Cut / tiled / chiseled forms  
• Slab  
• Stairs  
• Wall

Important notes:
• No redstone functionality  
• No unique mechanics  
• No oxide/patina system (Rose Gold does not rust or weather)  
• Decorative variants remain purely visual

### Phase 4 — Parity with Vanilla Metal Usage
This phase completes all “normal metal” behavior that appears across multiple ingots in vanilla.

Planned:
• Smithing compatibility (where appropriate without breaking balance)  
• Full tag inclusion: metal, beacon payment item (optional), crafting material tags  
• No exclusive utility items (no minecarts, no anvils, no rails, no clocks, no apples)  
• No Rose Gold–only mechanics or systems

Rose Gold becomes a reliable, mid-tier alternative to Iron with better enchantability and a distinct personality, without overlapping the unique identities of Iron, Gold, or Netherite.

### Phase 5 — Polish and Finalization
Once all parity features are complete, the mod reaches its intended end state.

Planned:
• Texture refinements  
• Minor balance tuning  
• Optional datapack with alternate crafting progression (community request-based)  
• Performance and compatibility checks  
• Final documentation and maintenance updates

At this point, Rose Gold Alloy stands as a finished material tier:  
complete, self-contained, and fully integrated into the Minecraft ecosystem without feature creep or unnecessary expansion.