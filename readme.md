# Quiz 9

## Part 1: Project Direction

### Chosen Path
We will reinterpret an existing artwork.

### Artwork and Artist
**The Starry Night** by **Vincent van Gogh**.

### Team Vision (max 150 words)
Our team will reinterpret *The Starry Night* as an interactive pixel-painting environment. We will preserve the painting’s swirling rhythm, dramatic contrast, and emotional night atmosphere, then translate these qualities into a grid-based visual system. Instead of copying the original image directly, we will rebuild the scene as living pixel blocks that react to sound, user input, and controlled randomness. Our main inspiration comes from van Gogh’s brush movement and from pixel-art nightscape aesthetics that simplify detail into readable color clusters. Through this approach, we aim to connect classical fine art and contemporary creative coding, so the audience can “play” the painting while still recognizing its iconic visual identity.

### Inspiration Images
![The Starry Night by Vincent van Gogh](https://commons.wikimedia.org/wiki/Special:FilePath/Van_Gogh_-_Starry_Night_-_Google_Art_Project.jpg)

![The Starry Night detail inspiration](https://commons.wikimedia.org/wiki/Special:FilePath/Van-gogh-starry-night-lower-right.jpg)

### Inspiration Sources
- [MoMA collection entry: The Starry Night](https://www.moma.org/collection/works/79802)
- [Wikimedia: Van Gogh - The Starry Night](https://commons.wikimedia.org/wiki/File:Van_Gogh_-_Starry_Night_-_Google_Art_Project.jpg)
- [Wikimedia: Van Gogh - Starry Night detail](https://commons.wikimedia.org/wiki/File:Van-gogh-starry-night-lower-right.jpg)

---

## Part 2: Mechanics

### Team Members and Ownership
- Team Member 1: Audio mechanic
- Team Member 2: User input mechanic
- Team Member 3: Perlin noise and randomness mechanic

### Audio Mechanic (Team Member 1)
The audio mechanic converts frequency and amplitude data into visual energy on the pixel canvas. In practice, low frequencies will influence large swirl areas in the sky, while mid and high frequencies will modulate local brightness, color shift, and twinkle intensity around stars. When the soundtrack becomes louder or denser, the pixel strokes will appear to thicken and pulse, creating a sense that the painting is breathing. User interaction with this mechanic is indirect: the audience presses play and experiences a continuously changing visual state driven by the sound itself. This mechanic connects to our project vision by replacing van Gogh’s static brushstroke rhythm with a living temporal rhythm, allowing the emotional force of the artwork to be felt as movement rather than only seen as a still image.

### User Input Mechanic (Team Member 2)
The user input mechanic gives the audience direct control over selected parts of the reconstructed painting through mouse and keyboard actions. Mouse movement will distort nearby pixel vectors to mimic flowing brush motion, while mouse clicks can trigger local “paint bursts” that temporarily increase color saturation in the sky. Keyboard input will switch interaction modes, such as star enhancement mode, village glow mode, and reset mode, so users can explore different layers without breaking the composition. The mechanic is designed to feel expressive but bounded, meaning users can intervene creatively while the work still remains visually recognizable as *The Starry Night*. This strongly supports our vision because reinterpretation here is not passive viewing: the audience actively co-authors motion, contrast, and emphasis inside the familiar artwork structure.

### Perlin Noise and Randomness Mechanic (Team Member 3)
The Perlin noise and randomness mechanic provides organic variation so the piece never feels repetitive or mechanically looped. Perlin noise will generate smooth motion fields that drive cloud-like drift, subtle sky turbulence, and gradual transitions in pixel clusters. Random values and seeded random events will introduce occasional star flickers, micro-color mutations, and irregular wave timing, while still staying within a controlled visual palette derived from the original painting. Users do not need to trigger this mechanic directly; they perceive it as a constantly evolving atmosphere that supports both audio response and input response. This mechanic connects to our vision by translating van Gogh’s expressive unpredictability into code: instead of fixed pixels, the scene behaves like a living painted system where order and variation coexist.

### Mechanics Reference Image
![FFT and interactive visualization reference](https://i.ytimg.com/vi/2O3nm0Nvbi4/hqdefault.jpg)

---

## Part 3: Putting It Together

Our project uses one shared canvas transformed into a pixel grid. Each mechanic controls a different layer of change independently: audio drives global rhythm and intensity, user input edits local pixel behavior, and Perlin noise/randomness adds organic variation over time. Although each mechanic can operate on its own, all outputs are applied to the same pixel system, so the piece stays visually unified while still allowing distinct interaction modes.
