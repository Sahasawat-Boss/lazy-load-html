## Pure CSS + JS Blur Load (No Low-Res Image Needed)

This method shows the full-size image with a blurry style first, then clears the blur when it fully loads. It's super easy, lightweight, and doesn't require extra image files.

![image](https://github.com/user-attachments/assets/0f7d48cc-eab5-4bf9-ae30-241eccf04e89)

### 💡 How This Works
- Apply filter: blur(20px) and scale(1.1) to make the image appear blurry and slightly zoomed while loading.

- When the image is fully loaded, we remove the blur and zoom using a smooth transition.

- No small image needed – it all works using the full-size image.

---
### 🧪 Tips for Testing
- Open DevTools > Network tab, set throttling to "Slow 3G"

- Refresh the page to see the effect clearly

- You can adjust the blur amount, scale, and transition speed to your liking

