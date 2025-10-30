# Module 4: Creating high-fidelity prototypes

## Contents (TOCS)

```md
- Understand high-fidelity prototypes
- Explore gestures and motion
- Module 3 review
```

## High-Fidelity Prototypes

### Definitions

- Prototype: An early model of a product demonstrating functionality.
- Low-fidelity prototype: Interactive design using placeholders for content.
- High-fidelity prototype: Detailed and interactive design closely matching the final product.

### Key Differences

- Low-fidelity: Focus on structure and flow; uses lines or placeholder text.
- High-fidelity: Focus on realistic visuals and interactivity.

### Core Components of a High-Fidelity Prototype

1. **Visual Elements**

   - Include finalized content such as color, typography, icons, and images.
   - Confirm written content, graphics, and links.
   - Use realistic text and images instead of placeholders.
   - Example: Replace “Dog Walker A” with actual names and photos.

2. **Navigation**

   - Ensures users can move between screens.
   - Based on the main user flow identified earlier.
   - Includes buttons, icons, back arrows, and exit (X) options.
   - Key questions to evaluate:
     - How does the user get from one screen to another?
     - How easy is it to locate navigation icons?
     - Where does the user journey end?

3. **Interactivity**
   - Connects screens to simulate real app use.
   - Involves gestures and motion for realistic experience.

### Creating Interactivity in Figma

1. **Select hotspot:** Choose item (button, icon, heading) where interaction occurs.
2. **Make the connection:** Draw the arrow or “noodle” to link hotspot to destination.
3. **Indicate destination:** Connection must lead to a frame or screen, not an element within it.
4. **Add interaction & animation:** Apply gestures and motion for dynamic feel.

### Key Takeaway

High-fidelity prototypes transform visual mockups into interactive, realistic product simulations — combining visuals, navigation, and interactivity to test real user experiences.

## Creating a High-Fidelity Prototype in Figma

### Overview

There are **six steps** to build a high-fidelity prototype in Figma:

1. Lay out the mockups
2. Connect the screens
3. Add interaction details
4. Adjust the animation
5. Complete for all screens
6. Share your work

This section covers the **first two steps**.

### Step 1: Lay Out the Mockups

1. **Set up workspace:**
   - Create a new page within the same Figma file containing your wireframes and mockups.
2. **Copy mockups:**
   - Copy and paste your mockups into the new high-fidelity prototype page.
3. **Order by user flow:**
   - Arrange screens according to the user’s journey.
   - Example (Dog Walker app):
     - Home screen → Choose date/time → Select dog walker → Booking confirmation.
   - If your screens are not ordered by flow, reorder them before continuing.

### Step 2: Connect the Screens

1. **Select hotspot:**
   - Choose an interactive element (e.g., “Book appointment” button) to start the connection.
2. **Switch to Prototype mode:**
   - Go to the right panel and click **Prototype** to enable it.
3. **Use prototype node:**
   - A blue circle with a plus sign (node) appears on the hotspot.
   - Click and drag the arrow (connection) from the node to the **destination frame**.
4. **Set destination:**
   - The destination must be another frame or screen.
   - Example: “Book Appointment” button → first “Book Appointment” screen.
5. **Define starting frame:**
   - The first connection you make becomes the **starting point** of your prototype.
6. **Continue connecting:**
   - Repeat the process for remaining screens in the user flow.

**Key Tip:** Always **arrange screens in user flow order** before connecting, ensuring a smooth and logical prototype experience.

### Step 3: Add Interaction Details

Each interaction in Figma has **three parts**:

1. **Trigger:**

   - Defines what initiates the interaction (e.g., mouse click, tap, or time delay).
   - Example: Set trigger to **“On Click/On Tap”** for the “Book Appointment” button.

2. **Action:**

   - Defines what happens after the trigger.
   - Common action: **Navigate To**, used to move between frames or screens.
   - Example: “Book Appointment” → navigate to “Appointment Booking” screen.

3. **Destination:**
   - Specifies where the user goes next.
   - Can be another frame or an overlay on top of the current screen.

### Step 4: Adjust the Animation

- **Purpose:** Controls how screens transition, adding **motion** for smoother flow.
- Figma offers **8 animation types** (e.g., Instant, Slide In, Slide Out).

#### Example Process:

1. Test **Instant** → feels abrupt.
2. Switch to **Slide In** → smoother, more natural.
   - Direction is indicated by the arrow (e.g., Up = slide from bottom to top).
3. To return to the home screen:
   - Connect “X” button → homepage.
   - Use **Slide Out** animation with **Down** direction to mirror the opening motion.

**Key Tip:** Use consistent animations for opening and closing screens to improve wayfinding and create a cohesive experience.

### Step 5: Complete for All Screens

- Repeat Steps 3–4 across all screens.
- Add gestures and motion to every interaction in the user flow.
- Test frequently to refine transitions and confirm usability.

### Step 6: Share Your Work

1. Click **Share** (top-right corner in Figma).
2. Choose permissions:
   - **View** for feedback.
   - **Edit** for team collaboration.

### Key Takeaways

- A complete high-fidelity prototype combines **interactions**, **motion**, and **navigation** for realistic testing.
- **Gestures + Motion** help users understand flow and feedback.
- Experiment, test, and iterate — refining until the experience feels natural and intuitive.

## Gestures and Motion in High-Fidelity Prototypes

### Definitions

- **Gesture:** Any touch-based interaction with a device using a finger or stylus.  
  → Describes _how_ users interact with screens.
- **Motion:** Animation that brings static elements to life to:
  - Focus user attention
  - Communicate state changes
  - Provide visual feedback
  - Make experiences more engaging

### Common Gestures

- **Swipe:**

  - Quick horizontal or vertical movement across the screen.
  - Used to switch screens or navigate carousels.

- **Tap:**

  - Brief touch with one or more fingers.
  - Single tap selects items; two-finger tap may open context menus.

- **Drag:**

  - Tap-and-hold, then move the finger/stylus across the screen.
  - Common for rearranging or revealing items (e.g., notification menus).

- **Pinch:**
  - Two fingers moving together or apart.
  - Used for zooming in/out on photos, maps, or websites.

### Gestures Across Operating Systems

#### iOS vs Android

- **Apple (iOS):**

  - Based on **Human Interface Guidelines (HIG)**.
  - Example: Undo text → swipe **three fingers right to left**.

- **Google (Android):**
  - Based on **Material Design**.
  - Example: Undo text → **tap and hold**, then press delete.

**Key Insight:**  
Designers must understand and apply platform-specific guidelines so gestures feel _native_ to the OS. Always test designs across devices to ensure usability consistency.

### Motion in UX Design

- **Purpose:**

  - Draws user attention
  - Provides feedback after gestures
  - Communicates interaction possibilities
  - Enhances storytelling in digital interfaces

- **Examples:**
  - **Add-to-cart animation:** Highlights that an action occurred.
  - **iOS “Jiggle Mode”:**
    - Press-and-hold app icons → icons shake, minus signs appear (edit mode).
  - **Android App Menu Motion:**
    - Press-and-hold app icon → slight bounce + contextual menu opens.

### Key Takeaways

- **Gestures** enable interaction; **motion** provides visual context and feedback.
- Both together:
  - Enhance usability and engagement.
  - Help users understand system behavior.
  - Make high-fidelity prototypes feel closer to real apps.
- Designers should align motion and gesture behaviors with **platform conventions** (HIG or Material Design) and **test across devices** for accessibility and consistency.

## Accessibility in Gestures and Motion

### Key Accessibility Principles

1. **Provide Alternatives to Gestures**

   - Gestures should **not be the only way** to complete an action.
   - Some users may have limited hand control or visual impairments.
   - **Example:** In Gmail, users can **swipe left** to archive an email **or** press the **Archive button** — offering both options ensures accessibility.

2. **Control Motion Speed and Duration**

   - Motion that’s **too fast** can be alarming; **too long** can be distracting or confusing.
   - The **W3C recommends animations under five seconds** for accessibility.
   - In Figma, motion duration is measured in **milliseconds**, allowing precise control.

3. **Allow Users to Turn Off Motion**
   - Users should have the ability to **toggle looping or autoplay motion** on or off.
   - Continuous or looping animations (like GIFs or autoplay videos) can be distracting.
   - **Example:** YouTube provides a toggle to turn **autoplay** on or off — a good accessibility practice.

### Key Takeaway

To make designs **inclusive and accessible**, ensure that:

- Gestures have alternative methods.
- Motion is kept brief and comfortable.
- Users can control or disable motion when desired.

Designers should collaborate with product and engineering teams to implement these accessibility features effectively.

## Designing for Accessibility — Insights from Jen, Head of Google Accessibility UX

### Role and Mission

- **Jen and her team** help Google’s product teams design **accessible and usable products**.
- Their goal is to create products **based on the real needs of people with disabilities**.
- **Assistive technologies**—like pinch-to-zoom, screen magnifiers, or closed captions—enable equitable participation for all users.

### Accessibility Throughout Product Development

1. **Research Phase:**

   - Include people with disabilities during **user interviews**, **foundational research**, and **market analysis**.
   - Builds a strong foundation of insights rooted in diverse user needs.

2. **Design Phase:**

   - Apply **inclusive design principles**, such as:
     - Adequate **text and image contrast**.
     - **Representative imagery** of people.
     - **Readable text** at a basic comprehension level.
   - These practices ensure usability for everyone.

3. **Testing and Iteration:**
   - Conduct **user testing** that includes people with disabilities.
   - Continue gathering feedback **after launch** to refine accessibility.

### Co-Design and Impact

- **Co-designing** with people with disabilities brings richer insights and more meaningful products.
- Accessible design allows users to **work, learn, and fully participate in society**.
- Seeing the **real-life impact** of accessibility is deeply rewarding.

### Key Takeaway

- **Accessibility = Good Design.**  
  It’s not an extra task or burden — it **improves the final product** and makes designers better at their craft.  
  Inclusive design benefits **everyone**, not just users with disabilities.

  ## Creating and Sharing an Interactive Prototype in Figma

### Overview

This lesson builds upon previous Figma exercises to create a **multi-screen interactive prototype**, including **menu**, **profile**, and **search** screens.  
Prototypes let designers visualize app flow, test interactions, and gather feedback before development.

### Setting Up the Prototype

1. **Duplicate your design page** to start prototyping.
2. Switch to **Prototype Mode** in the right sidebar.
3. Create connections between frames using:
   - **Hotspot** → element that triggers the interaction.
   - **Connection** → the interaction line storing behavior details.
   - **Destination** → the target frame.

**Example:**  
Connect the **menu icon** to the **menu page**, and add a connection from the **menu’s “Home” text** back to the home screen.

### Customizing Interactions and Animations

- **Default:** “Instant” (no transition).
- To enhance context, use **animations**:
  - **Move In / Move Out:** Menu slides over or off the current screen.
  - **Push:** Moves screens laterally (used between Home and Search).
- Set **direction** (left, right, up, down) and adjust **duration** and **easing** for smoother motion.
- Reverse animations for closing screens to maintain consistency.
- Figma remembers your last-used animation settings for faster workflow.

### Expanding the Prototype

- Add interactions for other screens (e.g., Profile, Search).
- Use **Push** animation between horizontally related pages.
- Include **Cancel** buttons or back navigation for easy return flows.
- The **Back action** can automatically return users to the previous frame without manually connecting every page.

### Sharing and Team Collaboration

1. Click **Share** → adjust permissions to “Anyone with the link → Can View.”
2. Copy and share the link with your team.
3. Team members’ avatars appear as they join; **Observation Mode** lets you watch their interactions during testing.
4. Use **Comments** (shortcut: `C`) to leave feedback directly on frames.
   - Comments appear in both prototype and editor views.

### Incorporating Feedback

- Example feedback:
  - Add interactive **Like, Comment, Bookmark** icons for posts.
  - Include a **Back icon** in the menu for easier dismissal.
- Use **components and auto layout** to quickly update design elements across instances.

### Key Takeaways

- Prototypes visualize flow, motion, and usability early in design.
- Animation enhances user context and hierarchy.
- Sharing prototypes supports **team collaboration**, **usability testing**, and **feedback integration**.
- The next step in the workflow: prepare assets for **writers and developers**, manage file thumbnails, and export production-ready elements.

## Enhancing High-Fidelity Prototypes with Sound and Video

### Sound in UX Design

- **Purpose:** Enhances usability by providing **feedback** and confirming user actions.
- **Benefits:**
  - Signals status or progress (e.g., notification ping in Google Chat).
  - Creates an **emotional connection**, making interactions feel more human.
  - Can confirm outcomes — like a sound indicating a **successful download** or **failed upload**.
- **Best Practices:**
  - Use sound **sparingly** to enhance clarity, not distract users.
  - Provide a **sound toggle** so users can mute or disable sounds as needed.
  - Design sounds that align with user expectations and the context of use.

### Video in UX Design

- **Purpose:** Enhances **engagement**, **immersion**, and **visual storytelling**.
- **Example:** Netflix autoplay previews engage users with personalized video suggestions.
- **Benefits:**
  - Captures attention and highlights key areas or features.
  - Increases time spent on apps or websites.
  - Adds depth and motion to static designs.
- **Best Practices:**
  - Allow users to **adjust volume**, **replay**, or **stop** videos.
  - Offer **auto-mute** and **autoplay controls** for flexibility.
  - Provide **captions**, **transcripts**, or **visual alternatives** to ensure accessibility.

### Accessibility Considerations

- **Sound:** Include visual or textual indicators for users who can’t hear.
- **Video:** Add captions, transcripts, and controls to ensure accessibility for all users.

### Creating Better User Experiences

When integrating **sound and video** into high-fidelity prototypes:

- Evaluate how they **support or distract** from usability.
- Design for **diverse user needs**, ensuring optionality and accessibility.
- Use multimedia thoughtfully to create **engaging, inclusive, and emotionally resonant** user experiences.

## References

- Material Design, [Gestures](https://m3.material.io/foundations/interaction/gestures)
- Nielsen Norman Group, [The Role of Animation and Motion in UX](https://www.nngroup.com/articles/animation-purpose-ux/#:~:text=Summary%3A%20Animation%20in%20UX%20must,metaphors%2C%20and%20to%20enhance%20signifiers.&text=Share%20this%20article%3A&text=Motion%20is%20most%20often%20appropriate,induce%20delight%20or%20entertain%20users)
- Medium, [Motion Manifesto](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc)
- Toptal, [Sound Advice: A Quick Guide to Designing UX Sounds](https://www.toptal.com/designers/ux/ux-sounds-guide)
- Nielsen Norman Group, [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/)
- UX Planet, [Best Practices for Video](https://uxplanet.org/best-practices-for-video-e279efcfe7eb)
