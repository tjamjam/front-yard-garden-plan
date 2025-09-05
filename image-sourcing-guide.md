# Plant Variety Image Sourcing Guide

## Images Needed for Website

### Fruit Trees
1. **Apple 'Liberty'** - Show tree with fruit, focus on disease-resistant healthy leaves
2. **Apple 'Freedom'** - Show mature apples on tree, healthy foliage
3. **Peach 'Reliance'** - Show peach tree with fruit, cold-hardy characteristics

### Shrubs & Berries  
4. **Everbearing Raspberry 'Caroline'** - Show red raspberries on canes
5. **American Black Elderberry** - Show both white flower clusters AND dark purple berry clusters
6. **Black Chokeberry** - Show dark berries and brilliant fall foliage

### Groundcover & Herbs
7. **Wild Strawberry (Fragaria virginiana)** - Show native strawberry carpet with small white flowers and tiny red berries
8. **Creeping Thyme (Thymus serpyllum)** - Show dense mat with tiny purple/pink flowers
9. **Wild Bergamot (Monarda fistulosa)** - Show lavender flower clusters attracting pollinators

### Specialty Plants
10. **Ostrich Fern (Matteuccia struthiopteris)** - Show both fiddleheads (edible stage) and mature fern fronds

## Recommended Image Sources

### Free/Open Source Options:
1. **Wikimedia Commons** - High-quality plant photos with proper attribution
2. **USDA Plants Database** - Professional botanical photography
3. **University Extension Services** - Often have excellent variety-specific photos
4. **Native Plant Society Websites** - Great for native species

### Professional Options:
1. **Unsplash/Pexels** - High-quality stock photos (check for specific varieties)
2. **Fedco Seeds Website** - May have photos of specific varieties they sell
3. **Academic/Research Institutions** - Often license images for educational use

### Specific Plant Photo Requirements:
- **High Resolution**: Minimum 800px wide for web display
- **Variety-Specific**: Ensure photos show the exact varieties mentioned
- **Multiple Seasons**: Show flowers, fruit, and fall foliage where applicable
- **Plant Context**: Show plant in landscape setting when possible
- **WebP Format**: Convert to WebP for 25-35% better compression than JPEG

## Photo Organization Strategy:
```
/images/
  /fruit-trees/
    liberty-apple.webp
    freedom-apple.webp
    reliance-peach.webp
  /shrubs-berries/
    caroline-raspberry.webp
    elderberry-flowers.webp
    elderberry-berries.webp
    chokeberry-fall.webp
  /groundcover-herbs/
    wild-strawberry.webp
    creeping-thyme.webp
    wild-bergamot.webp
    ostrich-fern-fiddleheads.webp
    ostrich-fern-mature.webp
```

## Implementation Plan:
1. Source and download images with proper licensing
2. Convert to WebP format and optimize for web (compress to ~50-150KB each)
3. Add to fruit tree selection table
4. Enhance plant cards in understory section
5. Create image gallery in shopping list section
6. Add seasonal photos to calendar section

## Attribution Template:
```html
<!-- Example attribution in HTML comment -->
<!-- Image: [Plant Name] by [Author/Source], Licensed under [License Type] -->
```
