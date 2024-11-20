# **Project 2029 Style Guide**  
This guide outlines the visual and typographic rules for the project, ensuring a consistent and impactful design.

---

## **Color Palette**  
| **Name**           | **Hex**      | **Usage**                          |
|---------------------|--------------|-------------------------------------|
| **Neon Green**      | `#39FF14`    | Primary highlight and call-to-action elements. |
| **Midnight Black**  | `#0B0C10`    | Background for dark theme.          |
| **Digital Cyan**    | `#00F6FF`    | Accents, links, and hover states.   |
| **Crisis Orange**   | `#FF4500`    | Alerts, countdowns, and hover effects. |
| **Ash Grey**        | `#4B5261`    | Borders, dividers, and secondary text. |
| **Moonlight White** | `#F4F4F9`    | Primary text and highlights on dark backgrounds. |

---

## **Typography**  

### **Primary Font**:  
- **Exo 2** (Sans-serif)  
  - Usage: Headers, titles, and prominent text elements.  
  - Style: Futuristic, geometric, and bold.  

### **Secondary Font**:  
- **Roboto Mono** (Monospace)  
  - Usage: Body text, code snippets, secondary details.  
  - Style: Clean and modern with technical appeal.  

---

## **Typography Rules**  
1. **Headers**: Use **Exo 2** in uppercase with slight letter spacing (`letter-spacing: 1px`).  
2. **Body Text**: Use **Roboto Mono**, ensuring clear readability and contrast against the background.  
3. **Links**:  
   - Default color: Digital Cyan (`#00F6FF`).  
   - Hover state: Crisis Orange (`#FF4500`).  
4. **Emphasis**: Highlight critical text with Neon Green (`#39FF14`).

---

## **Component Guidelines**  

### **Buttons**  
- **Default Style**:  
  - Background: Neon Green (`#39FF14`).  
  - Text: Midnight Black (`#0B0C10`).  
  - Border: Ash Grey (`#4B5261`).  
  - Rounded corners for a modern look (`border-radius: 4px`).  
- **Hover State**:  
  - Background: Crisis Orange (`#FF4500`).  
  - Text: Moonlight White (`#F4F4F9`).  

### **Sections**  
- Use a **slightly lighter black background** (`#1C1E24`) for content blocks.  
- Add a **1px solid Ash Grey border** for separation and structure.  

### **Countdown Timer**  
- Font: Exo 2  
- Size: 3rem (or larger, depending on the context).  
- Color: Crisis Orange (`#FF4500`).  

### **Highlights**  
- Use Neon Green (`#39FF14`) for keywords or critical phrases.  

---

## **Spacing and Layout**  
- **Section Padding**: `40px` all around.  
- **Margin Between Components**: `20px`.  
- **Button Spacing**: Use `flex` with `gap: 15px` for buttons in rows.  

---

## **Sample HTML Structure**  

```html
<section>
  <h1>Project 2029</h1>
  <p>
    The <span class="highlight">future</span> won’t wait. Prepare for action.
  </p>
  <div class="countdown">10:00:00</div>
  <div class="button-row">
    <button>Activate</button>
    <button>Learn More</button>
  </div>
</section>
```

---

## **Best Practices**  
1. Maintain a **high contrast** ratio for accessibility.  
2. Use **Neon Green** sparingly for highlights to avoid visual overload.  
3. Prioritize **readability** by using Moonlight White for body text on dark backgrounds.  
4. Ensure all interactive elements (e.g., buttons, links) have hover effects for feedback.  
