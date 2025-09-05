# Future Vision Image Generation

## Current Status
The `index.html` file currently uses a placeholder for the future vision image in the hero section. To complete the design, you'll need to generate an AI image showing the transformed garden.

## Recommended AI Image Generation Prompt

Use this prompt with tools like DALL-E, Midjourney, or Stable Diffusion:

**Prompt:**
```
A beautiful front yard edible landscape in Burlington, Vermont. The scene shows a gently curving garden bed with multiple layers: semi-dwarf apple and peach trees in the background (12-15 feet tall), mid-level shrubs including elderberry and chokeberry with colorful berries, raspberry canes with red fruit, and a groundcover carpet of wild strawberry plants with small white flowers and red berries. Creeping thyme along the edges with tiny purple flowers. The garden is lush and productive but organized, with a flagstone path winding through. South-facing exposure with a house visible in the background. Zone 5 climate, late summer/early fall timing with some colorful foliage. Realistic, well-composed garden photography style.
```

**Alternative Simpler Prompt:**
```
A productive edible front yard garden with fruit trees, berry bushes, and groundcover plants. Layered food forest design with apple trees, raspberry canes, and wild strawberry groundcover. Natural, organic garden style in Vermont.
```

## Implementation
1. Generate the image using your preferred AI tool
2. Save it as `future-vision-garden.jpg` in this directory  
3. Update the image source in `index.html` line ~47 from the placeholder to:
   ```html
   <img src="future-vision-garden.jpg" alt="Future edible landscape vision" class="w-full h-64 object-cover rounded-lg mb-4">
   ```

## Alternative Options
If you prefer not to generate an AI image, you could:
- Use a stock photo of a food forest or edible landscape
- Create a simple illustration or diagram
- Keep the current gradient placeholder with descriptive text

The current placeholder includes a simple house icon and "AI-Generated Image" text that works as a temporary solution.
