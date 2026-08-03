# ReLook — Best Prompts Library
**Harry the hirer • AI Champions • curated from the real prompts used in the department workshops**

Every prompt below was actually used on a real HTH job. The matching images live in the numbered
folder named at the end of each entry. Copy the prompt, swap the bracketed values, generate.

Platform: relook.hthsystems.com.au

---

## 1. The five prompt moves that cover 90% of the work

| Move | The prompt | Folder |
|---|---|---|
| **Swap an element** | `Change the [stools] of the 1st pic with the [stool] in the 2nd pic` | 04, 19 |
| **Change a material or colour** | `Change all the metal finishing (background and base object) to [black metal matte]` | 05, 08 |
| **Sketch inpaint** | `Raise the height of the [curved wall] as per the pink sketch` | 06, 07, 16 |
| **Sketch → render** | `Photorealistic 3D render of a modern exhibition booth based on this conceptual sketch. Realistic geometry, clean edges, accurate proportions.` | 01, 02 |
| **Venue placement** | `Generate a photorealistic render of the booth from the 1st pic placed inside the venue shown in the 2nd pic` | 14 |

---

## 2. By technique

### Sketch → 3D render
> Photorealistic 3D render of a modern exhibition booth based on a conceptual sketch. Transform the
> sketch into a fully built structure with realistic geometry, clean edges, and accurate proportions.
> Booth design: a **[CLIENT]** branded expo stand with **[angular / curved / open]** architecture,
> illuminated fascia, and a reception counter. Integrated lighting within edges and signage.
> Materials: **[matte white laminated panels]**, **[brushed aluminium framing]**, **[soft LED strip lighting]**.

Neutral base first: `Generate the rendered version of these line drawings, neutral colour palette` —
then apply branding as a second prompt. → *Folders 01, 02*

### Material interpolation (2-image superpower)
> Generate a photorealistic 3D render of the **1st pic** using the **materials of the 2nd pic**

Image 1 = your structure. Image 2 = any booth whose finishes you like. → *Folder 03*

### Element & furniture swaps (multi-reference)
> change the stools of the 1st pic with the stool in the 2nd pic
> Swap the chairs in 1st pic with the chair in 2nd pic
> Remove the surfboard in first pic and swap with the mascot in the 2nd pic
> Change the logo in the first pic with the logo in the 2nd pic
> Add two stools from the 2nd pic and a bar table from the 3rd pic into the 1st pic

→ *Folders 04, 19, 22 (A & B)*

### Materials, finishes, colour
> Change all the metal finishing (background and base object) to **[black metal matte / brushed gold / polished chrome]**
> Change the exterior cladding from **[dark panels]** to **[white aluminium composite / timber battens]**
> Change the booth panels from **[current]** to **[gloss white / brushed aluminium / timber veneer]**
> Change the stool colour to **#[hex code]**

Hex codes beat colour names. "Black metal matte" beats "dark metal". → *Folders 05, 08, 17, 22 (F)*

### Sketch inpaint — structural changes
> Raise the height of the **[curved wall / partition / bar counter]** as per the pink sketch
> Add a **[canopy / awning / window]** to the area marked in the sketch
> Remove the **[column / barrier / signage]** in the marked area and fill with the surrounding material
> Change the branding in the rig banner of the 1st pic with the illustration of the 2nd pic

**Pink = where it goes. Green = boundaries. Reference image = what it looks like.**
Add `remove the sketch marks` to get a clean output. → *Folders 06, 07, 16*

### Multi-image panel graphics (signage superpower)
> Add the graphics on panels A, B, C of the first pic using the image 1, 2 and 3

Label the panels A, B, C on the booth image first — the AI reads the labels. Up to 4 references.
→ *Folders 10, 22 (G)*

### Venue placement & camera control
> Generate a photorealistic render of the booth from the 1st pic placed inside the venue shown in the 2nd pic
> move the camera 10 meters up

→ *Folders 14, 15, 18*

### Atmosphere, time of day, clean-up
> Change lighting to midday
> Show this venue at golden hour with a dramatic sunset sky and warm ambient lighting
> Convert to nighttime with festoon lighting, warm uplights on the structure, and a twilight sky
> Remove the **[scaffolding / barriers / equipment / people]** and show a clean finished setup
> Remove the background — keep the scene intact

→ *Folders 07, 08, 11, 20, 22 (C & D)*

### Production — lighting on CAD
> Generate a light beam where the pink arrows are
> Generate light beams where the pink arrows are to illuminate the green grid on the floor,
> avoid the light to go beyond the green line boundary
> Add atmospheric haze to make the light beams visible, with **[subtle / dramatic]** effect
> Change all truss from **[silver]** to **[black HD34 / silver HD44 / white powder-coated]**

→ *Folder 21*

### CAD ↔ realistic conversion
> Generate a photorealistic render of this technical drawing with **[lighting effects, materials, and atmosphere]**
> Generate a 2D front elevation technical drawing from this photo with dimensions and annotations

→ *Folders 07, 21*

---

## 3. Master prompt — hyper-realistic exhibition render (3-image method)

*Image 1 = concept layout (master) • Image 2 = lighting plan • Image 3 = venue HDRI*

> Create a hyper-realistic **[CLIENT]** exhibition render.
>
> **ABSOLUTE MASTER LOCK:** Image 1 defines everything. Do not change, move, scale, or redesign:
> stand layout, car positions, camera angle, signage placement, overall composition.
> **VEHICLES:** real production models only — **[Polestar 2, 3, 4]**. Exact positions, realistic proportions.
> **FLOOR (HARD RULE):** max 20mm height. Visually flush with the surrounding floor. White glossy
> surface, soft reflections, thin metallic edge trim. Subtle shadow line only. *If it looks raised → incorrect.*
> **NO ADDITIONS:** no furniture, barriers, props, extra signage or decoration. Keep minimal.
> **LIGHTING:** black minimal architectural fittings. Warm-neutral white spotlights. Medium
> atmospheric haze for visible beams. Soft beam falloff.
> **LIGHTBOX (if your tech drawings show one):** suspended **[CLIENT]** lightbox — black structure,
> white logo, even illumination. Must remain.
> **PEOPLE:** walking naturally, some crossing the stand seamlessly (no step). Neutral modern clothing. Don't overcrowd.
> **ENVIRONMENT:** large modern exhibition hall, clean architecture, HDRI-style lighting, slight cool tone.
> **CAMERA REALISM:** natural lens behaviour, soft highlights, micro-contrast, realistic depth, clean
> gradients. No stylisation.

**Check every render — these are fails:** floor looks raised or staged • vehicles aren't recognisable
production models • the suspended lightbox is missing or restyled • extra props have appeared.

→ *Folder 21*

---

## 4. Reusable template — any client

> A photorealistic architectural visualization of an exhibition stand inside a busy convention centre.
> **STRUCTURAL BASIS:** booth structure (overhead trussing + fixture placement) must follow the
> technical design in **[YOUR INPUT IMAGE]**.
> **CENTREPIECE:** replace **[PLACEHOLDER]** with a detailed 3D model of **[CLIENT PRODUCT]**.
> **FLOORING:** **[describe floor]** — e.g. raised high-gloss white plinth with integrated LED strip lighting.
> **BRANDING:** large backwalls + reception counter with illuminated logos for **[CLIENT NAME]** and
> text for **[EVENT NAME]**.
> **ATMOSPHERE & LIGHTING:** mood = **[describe mood]**. Fixtures active, casting bright light on the
> product. Accent palette: **[colour choice]**.
> **ENVIRONMENT:** diverse business professionals in suits / smart casual interacting with the space.
> Background: realistic, slightly blurred exhibition hall with distant booths.

---

## 5. Power tips that actually move the needle

1. **Sketch = structural, type = cosmetic.** Changing shape, height or position? Draw it. Changing colour or material? Just type it.
2. **Say what stays.** "Change the metal finish to black matte but keep the glass and timber as is" prevents collateral damage.
3. **Generate neutral first**, brand second. Easier to pivot when the brief changes.
4. **Iterate, don't restart.** V1 = structure. V2 = branding. V3 = graphics. V4 = lighting. V5 = furniture.
5. **Be precise with material names.** "Matte white laminated panel" beats "white wall".
6. **Hex codes** beat colour words. Pull them from the brand guidelines.
7. **Premium 2K for anything client-facing.** Fast model for internal checks only.
8. **State fail conditions in the prompt.** Explicitly saying "if it looks raised, it's incorrect" measurably improves output.
9. **Label your panels A, B, C** before using multi-image panel graphics.
10. **Add "remove the sketch marks"** so your pink arrows don't end up in the client deck.

---

*Sources: ReLook Prompt Cheat Sheets (Custom Build, Events, Exhibition, Exhibition Viz, Production,
Signage) and the AI Champions workshop sessions, Mar–Apr 2026.*
