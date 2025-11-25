# Simucube Active Pedals Pro - Review Notes

## Initial Impressions & Unboxing

### Packaging & Build Quality
- Massive crate shipped by Simucube
- First product ever sent directly by Simucube to reviewer
- Very tightly packed with foam protection (same foam used in wheelbase packaging)
- Heavy, premium construction throughout
- Includes power supply, networking cables, mounting hardware, spare cables
- Kettle lead power cables (standard, replaceable)
- Cat 5e networking cables for communication between pedals

### Physical Specifications
- **Extremely heavy pedals** - each pedal is a substantial unit
- All three pedals are **identical SKUs** - no master/secondary pedal distinction
- Base plate is massive - requires significant space
- Pedals extend beyond the pedal plate considerably
- Wide angle lens needed to capture them on camera
- Orange accents (similar to Asetek, Simagic - possible motorsport connection to McLaren)

### Components Included
- Base plate (requires assembly, time-consuming but not difficult)
- Three identical active pedal units
- Power supplies: **280W Meanwell power supply per pedal** (3 total)
- SC Link Hub (USB interface/control box)
- Networking switch (for connecting more than 2 pedals)
- Mounting hardware
- Adhesive pads for pedal faces
- Simucube stickers
- Small user manual

## Technical Features

### Force Feedback System
- **Motor-driven pedals** - small servo motors similar to SC2 Pro motors
- Worm gear mechanism allows pedal to move forwards/backwards
- Load cell sensors (not exposed like on Ultimates - integrated internally)
- Motor chamber visible on pedal body
- Slot shows range of motor travel
- Power button on each pedal
- External pedals port on each unit
- SC Link connection
- Flashing orange lights indicate firmware update needed

### Connectivity
- Each pedal has identical ports:
  - Power
  - SC Link
  - External pedals port
- Network-based communication system
- SC Link Hub acts as USB interface to PC
- **Power requirements: 5 sockets total** (3 pedals + hub + extras)
- Concern about power draw - 280W per pedal at full load (more than PC at full load)
- Older houses may trip breakers

### Adjustability
- **Software-controlled settings** - no physical adjustments needed for most parameters
- Pedal face angle adjustable
- Height slightly adjustable
- Can adjust pedal spacing left/right on base plate
- Pedals fit side-by-side with extra width to spare
- Close enough together for heel-toe despite bulky units

## Software Experience

### Initial Setup Issues
- Flashing red lights on SC Link Hub initially
- Flashing orange lights on pedals
- "Equipment offline" message despite proper connections
- **Solution: Firmware update required** (not immediately obvious)
- Had to search Ultimate documentation for troubleshooting (Pro documentation lacks troubleshooting section)
- Firmware update button hidden - not in-your-face like most devices
- **User experience needs improvement** - should be easier for premium product

### Simucube Tuner Software
- Separate from True Drive wheelbase software (being amalgamated in future)
- Calibration process:
  - "Calibrate Force Sensor" for each pedal
  - Pedals move automatically during calibration (impressive to watch)
  - Slider movement actually moves the physical pedal
  - Real-time pressure display in kilograms

### Software Features - Per Pedal

#### Throttle Settings
- Pedal pressure adjustment
- Force curve customization
- Preload (though definition differs from traditional - affects overall weight, not ramping)
- Friction
- End point adjustment
- Motor vibration
- Travel distance adjustable via software
- Can create "lumps" in force curve for tactile reference points (e.g., half-throttle position)

#### Brake Settings
- Pedal travel adjustable (software-controlled - mind-blowing)
- Maximum force: **110kg+ available** (more than enough for most users)
- Hard stop position remains exact regardless of force setting
- ABS effects:
  - Intensity adjustable
  - Smoothness adjustable
  - 25% intensity already quite strong
  - Clear feedback when ABS activates
- Traction control effects (when game reports it - ACC does, iRacing doesn't)
- Can be set extremely light for city driving or very heavy for racing

#### Clutch Settings
- Clutch bite point fully adjustable
- Can create **double bite points** (or triple if desired)
- Multi-stage feel possible
- Trigger input level
- Intensity
- Effect frequency
- Motor vibration
- Travel distance adjustable
- Can make it feel exactly like various real clutches (high/low bite points)

## Performance & Feel

### Throttle
- Initial feel: slight metal-on-metal sensation when not in-game
- Not the smoothest throttle out of the box
- High confidence in software to dial it in perfectly
- Can be made very heavy or very light
- Tested at 30kg (very aggressive), then 19kg, settled around comfortable range
- Half-throttle reference point creation is game-changing
- Clear tactile feedback at desired positions

### Brake
- **Maximum force tested: 110kg** (reviewer is 6ft tall, relatively strong)
- Most users won't need more than 110kg
- **Pro vs Ultimate question: Pro has enough force for anyone**
- Initial feel: relatively bland, not confidence-inspiring immediately
- Different from elastomer stack feel (which reviewer is used to)
- May be trying to mimic elastomer feel to avoid being too alien
- Settled around 80kg for comfortable use
- Hard stop remains precise
- Slight bump feedback felt over track bumps
- ABS feedback very clear and instant
- Staying out of ABS zone is easier with feedback

### Clutch
- Can feel exactly like a real clutch with proper setup
- Two-stage engagement possible
- Initial press, then bite point
- Travel length needs tuning for personal preference
- Double bite point feature is incredible
- Different clutch characteristics achievable (various car types)

### Haptic Feedback
- **ABS feedback: Excellent** - instant, clear indication
- **Traction control feedback: Excellent** - clear when it activates (ACC tested)
- Indicators visible on pedal base (color changes)
- Comparable to dedicated haptic reactors
- **May not need additional haptic devices** (Buttkicker, Simagic haptic reactors, etc.)
- Reviewer has tactile feedback experience - these meet expectations
- Important: Haptics are NOT the main benefit - adjustability is

#### **CRITICAL ISSUE: Effects Impact Pedal Input**
- **If ABS/traction control effects set too high, they affect simulator input** - major problem
- Forward/back rumbling from motor physically moves the pedal
- This movement registers as input changes to the sim
- **Simucube software does NOT compensate for its own effects**
- Does not smooth out brake input to account for rumble movement
- **Must keep ABS and traction control rumble fairly tame/low** to avoid input corruption
- **For competitive lap times: ANY rumbling affects pedal input negatively**
- Serious sim racers will quickly conclude rumble motors impact performance
- **Third-party rumble motors may be better option** for those prioritizing lap times
  - External motors don't move the pedal itself
  - Provide haptic feedback without affecting input accuracy
  - Explains why people buy Geyser 3D adapters for Simagic HPR motors
- Trade-off: immersion/feedback vs. input precision
- Disappointing limitation for a premium product

## Driving Experience

### First Drive Impressions
- Immediate confidence in brake control
- Throttle control feels natural
- Can already drive competitively without extensive setup
- Rally driving tested (difficult to talk while driving)
- GT3 driving tested (ACC)
- Formula car feel achievable
- Road car feel achievable

### Key Benefits Realized
- **No more physical adjustments needed** - slide rig out, disassemble, reassemble, test, repeat
- Can search for perfect settings without losing 20-30 minutes per change
- Can compare settings immediately
- **Game-changing for different car types**:
  - Formula car setup
  - GT3 setup  
  - Rally/H-pattern setup
  - Road car setup
- All achievable with software changes

### Ergonomics & Comfort
- **Can turn clutch into brake for long stints** - huge for people with knee issues
- Target demographic: 40s, 50s, 60s, 70s (disposable income, potential knee problems)
- Two-pedal configuration for GT/LMP endurance racing
- Three-pedal configuration for H-pattern/rally
- Pedal angle adjustable via software (not just hardware)
- Can accommodate different driving positions

## Comparisons & Context

### Force Feedback Pedals - The Future
- Reviewer has been saying "force feedback pedals are the future" for years
- Before streaming, said this on stream
- Now they exist and are attainable (though expensive)
- Others have promised (Moza, Simagic) but haven't delivered yet
- Simucube has delivered and people with high standards love them

### Pro vs Ultimate
- **Reviewer's verdict: No reason to get Ultimate for most users**
- Pro has more than enough maximum force (110kg+)
- Pro is already extremely capable
- Ultimate is even beefier but unnecessary for most

### vs Traditional Pedals
- Traditional pedals: bound by physical restrictions
- Performance kits help but still limited
- Elastomer stacks feel different (arguably better than real in some cases)
- Active pedals: everything is software-controlled
- Fear: Will unlock preferences that will be missed on all other non-active pedals

## Concerns & Issues

### Setup & Documentation
- **Documentation incomplete for multiple Pro pedals**
- Had to reference Ultimate documentation
- Troubleshooting guide missing from Pro docs
- Broken link in software documentation
- Firmware update process not intuitive
- Needs improvement for premium product price point

### Space & Installation
- Base plate assembly time-consuming (though not difficult)
- Must mount base plate before pedals (can't access mounting points after)
- Rig can't be as close to wall due to pedal depth and cables
- Requires significant space
- Wide pedal stance may be issue for some rigs

### Power Requirements
- **3x 280W power supplies + hub = 5 sockets needed**
- Potential to trip breakers in older houses
- More power than PC at full load (if all drawing max)
- Likely doesn't draw full 280W continuously
- Many cables to manage
- Generic Meanwell power supplies (replaceable, available in bulk)

### Cost
- **Over $5,000 for three-pedal set** with base plate and networking switch
- "Saucy to say the least"
- Unattainable for most
- Target market: high disposable income

## Unique Features & Innovations

### Software-Controlled Everything
- Pedal travel
- Force curves
- Bite points
- Maximum force
- Haptic effects
- Angle (via software, not just hardware)
- No physical disassembly needed for changes

### Pedal Interchangeability
- All three pedals identical
- Can assign any pedal to any function
- **Can swap clutch to brake for endurance racing**
- No master/secondary pedal limitation
- External pedals port on each unit enables this

### Profile Sharing
- Simucube allows profile sharing
- Reviewer will release profiles
- Community can share settings
- Eliminates guesswork for new users

## Future Content Plans

### Planned Videos
1. **Individual throttle video** - why get active throttle, traction loss, haptics
2. **Individual brake video** - main reason for development, deserves deep dive
3. **Individual clutch video** - bite point details, double bite points, H-pattern use
4. **Long-term review** - encompassing all findings
5. **Profile/settings videos** - how to dial in for different car types

### Testing Plans
- More competitive driving needed
- H-pattern driving (mentioned but not fully tested in initial impressions)
- Different sim titles (ACC tested, iRacing mentioned)
- Simhub integration testing (can Simhub effects be sent to pedals?)
- Long-term reliability
- Different car types and disciplines

## Overall Assessment (Initial)

### Strengths
- **Dream product realized** - force feedback pedals are here
- Software adjustability is game-changing
- Build quality is premium
- Force range is more than adequate (Pro model)
- Haptic feedback works well
- Pedal interchangeability is brilliant
- Profile sharing capability
- Immediate competitive driving possible
- Accommodates different driving styles and physical needs

### Weaknesses
- **Price: $5,000+** (unattainable for most)
- Documentation needs improvement
- Setup process not intuitive
- Power requirements are significant
- Space requirements are large
- Initial throttle feel needs tuning
- Brake feel different from traditional (may need adjustment period)

### Key Quotes
- "The future of sim racing is force feedback pedals"
- "Money doesn't buy you happiness, it does buy you options"
- "This is the definition of that"
- "I can make it feel exactly like the real deal"
- "My mind is blown by the possibilities"
- "I fear I'm going to unlock things I like that I will miss in every other non-active pedal for the rest of my life"

## Technical Notes

### Compatibility
- ACC: Reports both ABS and traction control ✓
- iRacing: Does not report traction control ✗
- Simhub integration: Unknown (to be tested)

### Reviewer Context
- Never watched an active pedals review before (wanted fresh perspective)
- Used them at expos previously
- Gave feedback to Simucube at expos
- Software engineer background (appreciates complexity)
- Extensive pedals review experience (15-20+ long-term reviews)
- Used to haptic feedback (tactile transducers, etc.)
- Used to elastomer stack feel
- 6ft tall, relatively strong (relevant for force testing)

## Questions to Explore

1. Can Simhub effects be sent to these pedals?
2. Do you need additional haptic devices (Buttkicker, etc.)?
3. How does it perform in competitive racing long-term?
4. How do profiles transfer between users?
5. What's the actual power draw during normal use?
6. How does brake feel compare after extended use?
7. Best settings for different sim titles?
8. H-pattern driving experience in depth?
9. Reliability over time?
10. How does it compare to real car pedals?

## Reviewer's Personal Notes

- "I'm like a child at Christmas"
- "Mad excited" about next couple of weeks
- Streams Tuesday & Thursday 9pm Irish/UK time
- Will use these live on stream
- Will play with software live
- Avoided all reviews to form own opinions
- Wanted it to be "my dream, my vision"
- Has been dreaming about this for years
- "Double bite points" concept particularly exciting
- Concerned about becoming spoiled by these pedals

## Bottom Line (Initial)

**"If we had the money, surely it's this pedal set. It has to be."**

The Simucube Active Pedals Pro represent the realization of force feedback pedals that the reviewer has been anticipating for years. While expensive and with some setup/documentation issues, the software adjustability and performance capabilities make them a dream product for those who can afford them. The Pro model provides more than enough force for any user, making the Ultimate unnecessary for most. The ability to transform the pedal set for different car types and accommodate physical limitations (knee issues, comfort) through software alone is revolutionary.

**Key Innovation:** Software-controlled everything eliminates the need for physical adjustments, saving hours of setup time and enabling instant comparisons.

**Target Market:** Sim racers in their 40s-70s with high disposable income who want the ultimate in adjustability and performance, especially those with physical considerations.

**Recommendation:** If budget allows, these are the pedals to get. Pro model is sufficient for virtually everyone - no need for Ultimate unless you want the absolute maximum.

---

## Active Throttle - Deep Dive (After 2+ Weeks Use)

### Why You Should NOT Buy an Active Throttle

#### 1. Price
- **€2,000 per pedal** (approximately)
- Many other throttles give great feeling at 1/4 the price or less
- Cheaper alternatives work USB standalone
- Some can piggyback into these pedals
- Expensive even by high-end sim racing standards

#### 2. Limited Effects/Compatibility - **MAJOR ISSUE**
- **iRacing does NOT report:**
  - Traction control
  - Traction loss/tire slip
- **This is a dealbreaker if iRacing is your primary sim**
- Simucube Tuner software has limited effects compared to Simhub
- **No Simhub compatibility** (as of review time)
  - No plan to integrate with Simhub visible
  - This is one of the biggest issues
  - People are buying Geyser 3D adapters to attach Simagic rumble motors (HPRs) to active pedals
  - Alien concept: adding rumble motors to pedals that already have force feedback
  - Shows there's demand for more effects than Tuner provides
- Available effects in Tuner:
  - Motor vibration
  - Traction control (not in iRacing)
  - G-Force
- **Only 3 effects total** - very limited

#### 3. Cannot Be Inverted
- Cannot mount in inverted fashion
- Moza and Simagic claim their future active pedals will support inversion
- But those pedals are "nowhere to be seen" yet
- No inverted option in the market currently

#### 4. Size and Weight
- **Huge pedals** - "really really really big"
- **Absolute no-no for motion sims** - added weight has adverse effects on motion
- Difficult to mount even with Simucube base plate
- Take up huge amount of space
- Overhang ASR Pro rig by ~20cm at the back
- Forces rig further from wall
- Major consideration if in confined space

#### 5. Mounting Complexity
- Relatively difficult to mount
- Space requirements are significant

### Why You SHOULD Buy an Active Throttle

#### 1. Adjustable Travel, Weight, and Software Control - **GAME CHANGER**
- **Adjustability is even more important than the feel**
- Completely phenomenal adjustability
- **No recalibration needed after adjustments** - HUGE benefit
  - Traditional pedals: change hardware → must recalibrate in-game
  - Active pedals: adjust in software → game automatically knows new 100% point
  - Software tells the game, so calibration is automatic
- "Not having to calibrate is a beautiful thing"
- At this price point, you're buying choice, not just good pedals
- Choice is worth a lot of money to many people

#### 2. Consistent Feel Between Shoes/Socks
- Very consistent and great feel whether using shoes or socks
- Can switch mid-race if needed
- **Can adjust mid-race** (e.g., on long straight)
  - "I wish throttle was slightly less far away"
  - Just adjust it - no recalibration needed
  - Automatically knows where 100% should be
- Lovely luxury for those who appreciate it

#### 3. Can Feel as Good as Any Other Pedal - **BOLD CLAIM**
- "My reputation is on the line" - huge claim
- Can make it feel:
  - **Impossibly hard** - achieved
  - **Like a truck** - massive throw, more than you'd ever need
  - **Very rigid like a go-kart** - does it absolutely perfectly
- **"Never been able to do that with a pedal"** (applies to throttle, brake, clutch)
- Can achieve any feel you want
- Is it worth €2,000? "That's up to you to decide"
- "If I had the money I definitely would"

#### 4. Effects (Limited but Present)
- Traction control and traction loss available (when sim reports it)
- **But iRacing doesn't report these** - see cons section
- Main reason should be adjustability, not effects
- Ability to position throttle perfectly for heel-toe
- Can slide off brake with heel easily
- Perfect positioning for longer stints
- **Infinitely adjustable for aches, cramps, ailments**
- Not about what's most realistic - about what works for YOU
- Incredible enjoyment from customization

#### 5. Non-Traditional Adjustments Possible

**Travel Distance:**
- Can have 17mm of travel or 3x that length
- Game still sees 0-100% regardless of physical travel
- **Adjust on the fly - even on back straight**
- No calibration needed
- Game doesn't know anything changed

**Force/Weight:**
- Can set to 57kg throttle (unrealistically heavy) - still reads 100%
- Try doing that with non-active pedals - "almost impossible"
- Typically around 8kg for comfortable use
- Can adjust from super light to extremely heavy

**Force Curves:**
- Predetermined curves available:
  - Starts slow (40% physical = low input, then ramps up)
  - S-curve
  - Linear (reviewer's preference)
- **Affects both input to sim AND physical feel** (compound effect)
- Can replicate real throttle characteristics:
  - Cable slack at beginning
  - Progressive resistance
- **Can add "lumps" for reference points:**
  - Example: wheels spin at 60% throttle
  - Add tactile lump at 50-60% as reference
  - Feel the lump through the pedal
  - **Not realistic, but could make you faster**
  - Helps if you struggle with on-track cues/sound
  - Learning aid for some drivers
  - Reviewer doesn't use it much personally (can learn without it)

**Friction:**
- "Absolutely love this"
- Slows pedal return without making it lighter
- Not damping (damping also available but reviewer doesn't like it much)
- Only 5-6% friction used
- **"Difference between an amazing throttle pedal and an average throttle pedal"**
- Comparable to dampers on pedals like Simagic P200 throttle
- "This can feel every little bit as good"
- Adjustable in software

### Hardware Technical Details

#### Worm Gear System
- Motor with worm gear and pedal attached
- **Worm gears are almost impossible to push through** - very strong
- Even without motor attached, leverage makes it nearly impossible
- Moving the worm gear gives lots of leverage on pedal
- **Load cell reads pressure and turns motor just enough**
- Makes you feel like you're pressing the pedal
- Sophisticated engineering
- "This stuff blows my mind"

#### Why No Competition Yet?
- Simucube showed these ~2 years ago
- Still the only ones doing this (as of review)
- **Moza and Simagic** (fastest companies to launch products) still haven't delivered
- "Says a lot about what Simucube have achieved"
- Not a subpar product - "really good"
- "Could be almost in its final form already"
- Except for Simhub support - "really want that at some stage"

### Software Deep Dive - Simucube Tuner

#### Key Settings Available:
1. **Force/Weight** - adjustable from light to 57kg+ (unrealistic max)
2. **Travel distance** - 17mm to 50mm+ (3x range)
3. **Force curves** - multiple presets, custom curves with nodes
4. **Friction** - 0-100%, reviewer uses 5-6%
5. **Damping** - available but not preferred by reviewer
6. **End point** - adjustable
7. **Motor vibration** - intensity adjustable
8. **Traction control effects** - when sim reports it
9. **G-Force effects** - available

#### Software Philosophy:
- "Software is one of the biggest parts of this"
- Hardware can be instructed by software
- Easy sliders
- **"That's really the thing that you're paying for"**
- Many people will "set it up once and forget it"
- Is easy setup worth €2,000?
  - To some: yes
  - To others: no
- Cheaper pedal sets (~€1,000 for all three with base plate):
  - Simlab, Sim Forge, others
  - Can feel extremely good
  - Just don't have that adjustability and confidence

### Comparison to Other Products

#### vs. Cheaper Alternatives
- €1,000 pedal sets (Simlab, Sim Forge, etc.) can feel extremely good
- Just need time investment in setup
- Active pedals reduce setup time dramatically
- Can change and feel instantly (10 seconds vs. hours)
- With traditional pedals, eventually you settle
- Curiosities remain: "how would this feel? how would that feel?"
- Very few people go to the effort with traditional pedals
- Active pedals let you change whenever you want

#### vs. Simagic P200 Throttle
- P200 has damper that makes throttle feel great
- Active throttle can feel "every little bit as good"
- But active throttle is adjustable in software

#### Wheelbase Analogy
- Like Simucube wheelbases: Sport, Pro, Ultimate
- "Buy the one you can afford"
- Top tier "eliminates all doubts"
- **"These pedals eliminate all doubt"**
- "There is no better pedal set in the world"
- Many pedal sets can be set up better with time investment
- Tuner software reduces setup time dramatically

### Target Demographic

#### Age and Physical Considerations
- Mainly people aged **40, 50, 60, 70, 80**
- People at this stage of life who can afford them
- Many have:
  - Knee issues
  - Back issues
  - Posture concerns
- Put a lot of force on pedals (especially brake)
- **Being able to adjust is huge**
- Sometimes just don't feel like heavy brake/throttle
- Don't want realistic - just want to sit and drive
- **Having that choice without getting under rig is "absolute game changer"**

### Future Predictions

#### Active Pedals Sport (Speculation)
- Reviewer thinks we'll see **Active Pedals Sport** at some stage
- For throttle specifically:
  - Don't need 110kg (that's for brake)
  - Don't even need 30kg for throttle
  - Nobody has 30kg throttle
  - Many don't even have 30kg brake
- **Keep an eye out for Sport model**
- Estimated pricing: **~€1,500 per pedal** (still expensive)
- Question: Is waiting worth it?
  - Opportunity cost may not be worth it
  - May want toys right now

#### Industry Direction
- "The same way all wheelbases are direct drive right now"
- Expects many active pedal type pedals in future
- "That's a good time to look forward to"
- But right now, Simucube is only option

### Real-World Usage Notes

#### What Reviewer Actually Uses:
- **Linear force curve** (probably just habit)
- **5-6% friction** (makes huge difference)
- **~8kg force** for comfortable use
- **Doesn't use lumps/reference points much** (can learn without them)
- **Doesn't like damping much**
- Adjusts for comfort rather than maximum realism

#### Heel-Toe Considerations:
- Can position throttle perfectly for heel-toe
- Easy to slide off brake with heel
- Pedal positioning is critical
- Software adjustment makes this trivial

#### Long Stint Comfort:
- Can adjust for fatigue
- Don't have to maintain uncomfortable positions
- Reduces strain on knees/back
- Can make lighter when tired

### Community Feedback

#### People Buying Geyser 3D Adapters:
- Attaching Simagic HPR rumble motors to active pedals
- Paul from Geyser 3D uses them himself
- Reason: Simhub effects that Tuner doesn't provide
- Shows demand for more effects
- "I understand it completely"
- If Simhub compatibility existed, wouldn't need external motors

#### Common Questions:
- "What's the point in having all three?" - asked repeatedly
- Many people ready to pull trigger but not quite there
- Need detailed information before spending this much

### Bottom Line on Active Throttle

**Pros Summary:**
- Eliminates all doubt (no better pedal exists)
- Infinite adjustability without recalibration
- Can feel as good as any pedal
- Perfect for people with physical considerations
- Helps you sleep at night knowing you have the best
- "That's what money buys you - that choice"

**Cons Summary:**
- €2,000 per pedal
- No Simhub support (biggest gripe)
- iRacing doesn't report traction control/loss
- Cannot invert
- Huge size, not for motion rigs
- Many will set up once and never adjust (wasted potential)

**Final Verdict:**
- "Pretty damn good"
- "No alternatives"
- Not a subpar product - nearly final form
- Worth it? Depends on individual
- If you can afford it and value choice/adjustability: yes
- If you want effects/haptics primarily: maybe wait or add external motors
- If on motion rig or need inversion: no
- If iRacing is primary sim and you want traction effects: no

**Key Quote:**
"There is no better pedal set in the world. There are many pedal sets which are set up better [with time investment], but Simucube Tuner just allows you to reduce that time."

---

# Simucube SC3 Pro Wheelbase & Savu Steering Wheel - Meeting Notes

## Meeting Attendees & Context
- **Mika Takala** - Product Manager (steering lead and software side)
  - With Simucube since day one
  - Worked on Simucube 1, Simucube 2
  - Software and product management expertise
- **Toni** - Senior Digital Marketing
- **Antti** - Lead Designer for wheelbase
  - Presented technical overview (~20 minutes)
- **Purpose:** Get reviewer feedback to audience, provide comprehensive product information

## Reviewer Setup & Approach
- Installed new software the night before meeting
- **Testing methodology:** Wiped all settings to default
  - Simulates new user experience
  - Reviews target new users primarily
  - Important to test ease of first-time setup
- **Big improvement noted** in latest software version
- Hadn't driven with new software yet at time of meeting

## Software Development Status
- New software released night before meeting
- **Development continues** - active roadmap
- **Paddock feature coming later** - highly requested, won't be forgotten
- Software being amalgamated (combining with True Drive in future)

## Company Philosophy & Values
- **Reviewer's priority:** Understanding company values and excitement
  - Why did they do this?
  - How did they do this?
  - What's the purpose of features?
- Company presentation approach welcomed
- Focus on explaining philosophy behind design decisions

## Quick Release System - P3G Polygon

### Technical Design
- Based on **P3G polygon** - harmonic shape
- Used in CNC machines for shaft and hub connections
- **Harmonic nature = very stable connection without play**
- Engineering ideology: "maybe overkill, but that's the approach"

### Front Hub Assembly (Three Bolt System)
- **Known issue identified:** Slight play possible from factory
- Two separate pieces on wheel-side hub
- Issue discovered during Expo
- **Root cause:** Counter-sink screws
  - If tightened to exact torque immediately, screws may not line up perfectly
  - Vibrations can loosen them over time

### Updated Tightening Instructions
- **Correct procedure:**
  1. Pre-tighten all three bolts
  2. Then tighten to final torque
- **Best method:** Turn wheelbase to end stop
  - Make end stop hard
  - Lean on end stop while tightening
  - Wheelbase helps get bolts tight
- Video instructions created and sent to customers
- Production instructions updated for early units

### SC2 to SC3 Compatibility
- **SC3 to SC2 quick release adapter coming**
- Allows SC2 wheels to connect to SC3 wheelbase
- Maintains backward compatibility with existing wheel ecosystem

### USB Passthrough Modifications
- **Simucube is open to USB passthrough custom mods**
- Not officially supported but company is receptive
- **Warranty implications not yet clear**
- Already requires shaft disassembly to attach QR extensions
- **Companies researching USB port exposure on shaft**
  - Would utilize Simucube's Light Bridge technology behind the scenes
  - Third-party development in progress
- Important: Simucube's openness to community innovation

## Light Bridge Technology - Power & Data Transfer

### Power Transfer - Magnetic Induction
- **Coil-based system** (electronic component)
- **How it works:**
  - Electric current through coil → creates magnetic field around it
  - Magnetic field applied to coil → creates electric current
- **Two parts:**
  - Stationary coil on wheelbase
  - Rotating coil on quick release
- **Same technology as wireless phone chargers**

### Key Benefits
- **Galvanically isolating** - no conducting path through wheel to wheelbase
- Completely isolates wheel from ground
- **Completely wireless** - no physical connection for power transfer
- **Longevity is main goal**

### Data Transfer - Infrared Light Bridge
- **Infrared LEDs and receivers**
- Stationary side and rotating side both have LEDs/receivers
- **Very fast light pulses** transmit data
- **Two-way communication:**
  - Wheelbase sends data to wheel
  - Wheel sends data back (button presses, etc.)

### Light Bridge Construction
- Artistic representation shows:
  - Coils with color coding
  - Infrared LEDs for data transfer
- **Fundamentally isolated and completely wireless**
- Longevity-focused design

### Future Light Bridge Capabilities
- **Will support displays and digital dashboards in the future**
- Expansion of Light Bridge technology beyond current functionality
- Planned feature development for wheel-mounted displays

## Motor Technology

### Electric Motor Basics
- **Two main parts:**
  - **Rotor** - rotating part
  - **Stator** - stationary part
- **How it works:**
  - Coils in stator
  - Electric current controlled to stator
  - Rotor follows magnetic field produced in stator

### SPM Motors (Sport & Pro Models)
- **SPM = Surface Permanent Magnet**
- Used in SC3 Sport and SC3 Pro
- Used in Simucube 2
- **Industry standard** - every meaningful manufacturer uses SPM motors

### IPM Motor (Ultimate Model Only)
- **IPM = Interior Permanent Magnet**
- **Why created:** Ultimate specs were too difficult to achieve with SPM
- **Key difference:** Magnetic field angled 90 degrees from SPM
  - Points in direction of rotation
  - Magnetic field lines pinpointed very densely
- **Benefits:**
  - Higher torque levels
  - Much faster response
  - Smaller power supply needed
  - Ultimate and Pro share exact same power supply

### Manufacturing Challenges
- **IPM manufacturing tolerances very strict**
- "Closer and closer to an ideal motor"
- **Very difficult to manufacture**
- Difficulty reflected in price
- **Only one of its kind in the market** (as of meeting)

## Control Electronics & Architecture

### Ultimate Model Electronics
- **Completely new control electronics**
- Based on **Simucube Link style motor control**
  - Same as Active Pedals
  - Adapted for wheelbase use
- **Main PCB responsibilities:**
  - Simucube Link communication
  - Acts as IO interface
  - Control box communication via I2C bus
  - Knobs and LEDs control

### External Bus Communication
- **Expandable architecture** - could support other devices beyond control box
- **No decisions made yet** on future expansion
- Possibility exists for future devices

## Hardware Assembly

### Component Layout
- **Left:** Light bridge (rotating + stationary parts)
- **Right:** Main PCB
- **Middle:** Motor construction
- **Quick release PCB** - where wheel connects
- **Motor shell cover** - gives final SC3 appearance

## Product Lineup

### Three Models
- **Sport:** 15 Nm
- **Pro:** 25 Nm  
- **Ultimate:** 35 Nm
- **Identical design** - only difference is motor length

### Encoder Upgrade
- **23-bit absolute optical encoder** (all models)
- Previous generation (SC2 Sport/Pro): 22-bit
- Optical, T-format based encoder

## Mounting & Connections

### Mounting Options
- **Bottom mounting:** 135mm bolt pattern
  - Different from SC2 Sport/Pro (145mm)
  - Most rigs use slots instead of exact holes
  - Should work with 99% of connections
- **Front mounting:** Available
  - **Front mount pattern slightly smaller than SC2**
  - Make sure existing front mount can accommodate SC3
  - Check compatibility before assuming SC2 mount will work (if slot type, should be fine. if exact hole, may need to drill or modify or buy new mount)

### Rear Connections
- Power supply
- Simucube Link
- Control box
- **No antenna on the back** (unlike SC2 which had antenna)
  - Still supports SC2 wireless despite no visible antenna

## Control Box - New Device

### Features
- **Sleep and activate functions**
- Activates wheelbase
- **Activates Active Pedals** - no need to go into Tuner
  - Automatic homing sequence for pedals
- **Parameter adjustment knob:**
  - **Launch:** Torque control only
  - **Future expansion planned:**
    - Pedal travel adjustment
    - Maximum pedal force adjustment
    - User-definable settings
- **Simucube Link based** - controls both wheelbase and pedals

### Future Plans
- On-the-fly adjustments for pedals
- User-definable parameter selection
- Not available at launch but planned

## Firmware - Digital Twin Motor Control

### Philosophy
- **"Firmware is the most important thing"**
- Can make wheelbase very good or not so good
- More important than hardware in many ways

### SC3 Firmware - Written from Ground Up
- **Purpose-built for sim racing** (not industrial motor control like SC2)
- **Controls the end effector** - the actual newton meters
- Very different architecture from previous generation

### Digital Twin Concept

**What is a Digital Twin?**
- **Parameters/specs measured for each unit:**
  - Inductance of coils
  - Cogging the motor has
  - Friction levels
  - All physical characteristics
- **Measured during manufacturing**
- **Also measured dynamically** in user's setup
  - Different wheels automatically accounted for
  - Everything dynamically adjusted

**How It Works:**
- Parameters combined into "digital twin"
- Digital representation of physical wheelbase
- Very accurate digital version
- **Control the digital version**
- Physical wheelbase follows digital version

### Benefits of Digital Twin Control

**1. Eliminates Non-Idealities**
- Sensor signal noise removed
- Temperature effects compensated
- Consistent feel regardless of conditions

**2. Cross-Model Calibration**
- **Entire lineup is calibrated together**
- Create profile on Sport → transfer to Pro/Ultimate
- **Feels exactly the same across all models**
- Within limitations (can't create 35 Nm profile on Sport)
- 15 Nm profile on Sport = identical feel on Pro/Ultimate

**3. Profile Creation Benefits**
- **Much easier for content creators**
- Profiles transfer between units
- Reduces setup time dramatically

**4. Silent Operation**
- **SC3 is very silent**
- Due to new algorithm
- Dynamic adjustment all the time

**5. Wheel Compatibility**
- **Automatically adjusts for different wheels**
- Takes wheel weight/characteristics into account
- No manual adjustment needed

**6. Cogging Elimination**
- **SC3 has technology to recognize cogging and eliminate it on the fly**
- Software setup for most bases can highlight cogging issues
- SC3's digital twin system compensates automatically
- Real-time adjustment without user intervention

### Industry Leadership
- **"No one else in this market is controlling their wheelbase this way"**
- Hand on heart statement from lead designer
- Very advanced control method

## New Tuner Software

### Design Philosophy
- **Two-tier approach:**
  - **Simple:** Two sliders only (max torque + feel)
  - **Advanced:** Deep dive options available if wanted
- **Capable of creating very good feel with just two sliders**
- But advanced options always available

### Reviewer Feedback on New Software
- **Setup is easy even without profiles**
- Ran on completely default settings successfully
- **Easy to adjust** - not overwhelming
- **Uses real words** instead of engineering terms
  - Creates implicit trust
  - User trusts it's doing something meaningful
- **Big improvement** from previous versions
  - Old software: all sliders presented immediately (overwhelming)
  - New software: must go look for advanced options

### User Experience Focus
- **Getting rid of difficult engineering terms**
- Making setup discrete and approachable
- **Online documentation** coming (same week as meeting)

### Known Issue - Device Detection
- **Reviewer experienced:** Devices not detected on PC startup
  - Wheelbase not detected
  - Pedals not detected
- **Workaround:** Unplug and replug Link Box USB
  - Then devices appear
- **Company response:** "Not the user experience we want"
  - Not a minor thing
  - Spent significant time on user experience
  - Will request logs from reviewer
  - Actively working on USB power suspend features

## Target Market & Use Cases

### Accessibility Focus
- **60-70% of users:** Just want to buy the best and adjust easily
- **30-40% of users:** Hardcore, want to adjust every slider
- Software accommodates both groups

### Social/Shared Rig Scenarios
- **Friend sits in rig:** "This is too strong"
- **Old way:** Go into software, adjust slider, test, repeat
- **New way:** Turn control box knob while they're driving
  - "How does it feel now?"
  - Real-time adjustment
  - Much more attractive experience

### Endurance Racing
- **On-the-fly adjustment during race**
- Sometimes need "a little bit more or a little bit less"
- Control box enables this without leaving sim
- **Small thing, huge quality of life improvement**

### Professional Drivers
- **Team Red Line feedback:** "Get faster earlier"
  - Can find settings faster
  - Less time experimenting
  - More time actually racing
- **Formula 1 drivers using Simucube** (at least 3 known)
  - Not wheelbase engineers
  - Don't know what "slew rate" means
  - New software helps them too

### Engineering vs. Usability
- **Old feedback from pros:** "This is so engineering and overwhelming"
- Some pros are into engineering side
- Others just want to drive
- **End customers need to push without caring about setup**
- Settings can make or break a wheelbase
- Goal: Pro-level simulator at home without engineering degree

## Telemetry & Effects
- **Reviewer wanted to know more** about telemetry side
- Hadn't had good chance to play with it yet
- (Details not extensively covered in this meeting - focused on hardware/firmware)

## Savu Steering Wheel

### Reviewer's Initial Impressions
- **"Really nice" for OEM wheel** (company-made, not third-party)
- Good grips
- Really pleasant to use
- **Liked it more after using it than before**
- "Probably like it more after I used it than before I used it"

### Design Philosophy Discussion
- Reviewer wanted to understand:
  - Philosophy behind steering wheel
  - Design decisions
  - Use cases and intentions

### LED Color Customization - Feedback & Request

**Current Situation:**
- Individual LED selection can be complex
- Many people leave it on default orange
- May not like default but don't want to configure each LED

**Reviewer's Suggestion:**
- **Allow users to choose 2-3 favorite colors**
- Get button layout that matches those colors
- Don't have to select all individual LEDs
- **Much easier for most users**
- More people would customize if simpler

**Target User:**
- People who want customization
- But don't want complexity
- Would rather pick favorite colors and get matching layout
- Avoids leaving on default when they don't love it

### Company Background
- **Industrial background since day one**
- Wanted to provide pro-level simulator to home users
- "Don't need to settle for second best or third best"
- Same product pros use, available at home

## Software Calibration & Profiles

### Cross-Model Compatibility
- **Major benefit of digital twin system**
- Profile created on Sport works on Pro/Ultimate
- Feels exactly the same (within model limitations)
- **Huge for content creators and profile sharing**

### Parameter Interaction (Old System)
- **SC2 problem:** Tweaking one parameter affects others
- Doesn't get you in direction you're looking for
- New system addresses this

### New System Benefits
- **Steers you in right direction**
- More easy to understand
- Get faster earlier in your journey
- Less time finding settings, more time racing

## Meeting Structure
- ~20 minute presentation from Antti
- Most time left for questions
- Company prepared common questions about wheelbase
- Reviewer could ask anything needed
- Focus on getting most out of meeting for review purposes

## Reviewer's Familiarity
- **Already quite familiar** with wheelbase concept
- Reviewed many, many wheelbases
- **Very confident** with force feedback quality already
- "Force feedback is not a concern of mine"
- "Quality of force feedback is there"
- Wanted deeper dive on specific aspects (telemetry, philosophy, design)

## Key Takeaways for Review

### What Makes SC3 Special
1. **Digital twin motor control** - industry-leading, unique approach
2. **Light bridge technology** - longevity and isolation focused, future display support
3. **IPM motor in Ultimate** - only one of its kind in market
4. **Cross-model profile compatibility** - huge for users and creators
5. **User experience focus** - from overwhelming to approachable
6. **Control box integration** - quality of life for adjustments
7. **Silent operation** - result of advanced algorithm
8. **Automatic cogging elimination** - recognizes and compensates on the fly
9. **SC2 compatibility** - adapter coming for existing SC2 wheels
10. **Community-friendly** - open to USB passthrough mods and innovation

### Company Values Demonstrated
- **Engineering excellence** - "maybe overkill" approach
- **User experience priority** - spent significant time on UX
- **Longevity focus** - wireless, isolated design
- **Accessibility** - pro-level for everyone, not just engineers
- **Continuous improvement** - active roadmap, listening to feedback
- **Industrial heritage** - bringing professional tools to consumers

### Areas for Improvement Acknowledged
- USB detection issue (actively working on it)
- LED customization complexity (feedback received)
- Documentation timing (coming same week)

### Future Development
- Paddock feature coming
- Control box expansion for pedal control
- Continued firmware development
- Possible external device support via bus

## Reviewer Notes
- Force feedback quality already confirmed (not a concern)
- Setup experience is easy and improved
- Implicit trust from real-word terminology
- Minor USB detection issue needs addressing
- LED customization could be simpler
- Overall very positive on product direction and company approach

---

## Hands-On Review Notes - SC3 Pro & Savu Wheel

### Quick Release - Physical Experience

**What Was Received:**
- **Only one QR included** (didn't receive second QR)
- May be standard, but worth noting for review

**Build Quality Issues:**
- **Paint scuffs on QR handle**
- Likely fault in anodization or deburring of sharp edge
- Quality control issue on review unit

**QR Performance:**
- **Much better than V1** - no awkward pin
- **Rock solid connection** - no play, very secure
- **Still a bit sticky to release** - doesn't release as smoothly as:
  - Asetek quick releases
  - NRG style quick releases
- **Effective but a bit stiff**
- **Easier to use for GT and Formula wheels** (than other wheel types)

### Savu Steering Wheel - Detailed Impressions

**Visual Appeal:**
- **Looks nicer in real life than in photos**
- Photos don't do it justice
- Better presence and finish in person

**Grips:**
- **Sensational grips**
- **Similar quality to Bavarian Sim Tech** (high praise)
- Comfortable and premium feel

**Clutch Functionality:**
- **Bite point easy to adjust in software**
- Software control works well
- User-friendly adjustment process

**LED Issues:**
- **Wheel LEDs in Savu not behaving as expected**
- **LED issues in early firmware**
- Likely to be resolved in updates
- Worth noting for early adopters

### Software Experience - Tuner 3

**Startup Issues:**
- **Doesn't detect attached devices on startup** (confirmed issue)
- "Start devices" greyed out in app tray
- Must unplug/replug Link Box USB to detect
- Consistent problem, not isolated incident

**Software Updates:**
- **Nice and easy** - smooth update process
- User-friendly update experience

**Color Picker Performance:**
- **Color picker is slow**
- **Creating a color layout takes too long**
- Shouldn't be this time-consuming
- Needs optimization for better UX

**Overall Software Feel:**
- **Nice and smooth** when working
- Good UI/UX when devices are detected
- Detection issue is main problem

### USB Passthrough - Critical Concern

**The Problem:**
- **No USB passthrough is "a bit crazy in this era"**
- Industry standard feature missing
- Forces wheel manufacturers to use Simucube protocol specifically
- **Simucube seems to have turned its back on USB completely**

**The Irony:**
- **Simucube Link Box still communicates to PC via USB**
- So USB isn't completely avoided
- Inconsistent philosophy

**The Argument:**
- "I understand USB can cause issues"
- **But issues aren't common enough to justify:**
  - Extra hardware required
  - Extra cabling required
  - Forcing proprietary protocol adoption
- Creates barrier for third-party wheel manufacturers
- Limits ecosystem growth

**Impact:**
- Wheel manufacturers must go out of their way to support Simucube
- Not plug-and-play with standard USB wheels
- May limit wheel options for SC3 owners

### Technical Issues Encountered

**QR Issue:**
- Had a QR issue initially
- **Root cause: Loose bolt** (as discussed in meeting)
- Not a design flaw, assembly/QC issue
- Easily fixed once identified

### Active Pedals - Throttle Settings

**Optimal Configuration:**
- **Active throttle works best with logarithmic curve set**
- **Feels most natural** to reviewer
- Personal preference but worth noting
- Linear may work for others, but logarithmic recommended to try

## Summary of Concerns for Review

### Quality Control
1. Paint scuffs on QR handle
2. Only one QR received (if two expected)
3. Loose QR bolt from factory

### User Experience Issues
1. Device detection on startup (critical)
2. Color picker performance (slow)
3. QR release stiffness (functional but not best-in-class)
4. LED behavior in early firmware

### Design Philosophy Concerns
1. **No USB passthrough** - major limitation in modern era
2. Forces proprietary ecosystem
3. Limits third-party wheel compatibility

### What Works Well
1. Rock solid QR connection when assembled correctly
2. Software updates are smooth
3. Savu grips are exceptional
4. Software control for clutch bite point
5. Overall software UI is nice when working
6. Active throttle with logarithmic curve feels natural
