# ♻️ Recycling Guide — "Wait, where does this go?"

Started from a question I kept asking myself every trash day.

## 💡 The Idea

Snap a photo of any item and instantly know if it can be recycled —
based on your specific region's rules.
Not just "yes or no", but actionable solutions when it can't be recycled as-is.

## 🎯 Goals

- [ ] Identify items via photo and determine recyclability
- [ ] Apply region-specific recycling rules based on user's location
- [ ] Flag contaminated items (e.g. stained containers, leftover liquid)
- [ ] Suggest fixes — like "dry in sunlight for 30+ minutes" before recycling

## 🛠️ Planned Stack

- Image recognition AI
- Region-based recycling regulation data
- Built with Claude Code

## 🗺️ Development Roadmap

### Phase 1 — Data Collection & Organization
- [ ] Collect South Korea's national recycling laws and standards
- [ ] Gather region-specific recycling policies by municipality
- [ ] Organize data by material type (plastic film / PET / glass / paper / metal, etc.)
- [ ] Build image dataset per item type for AI recognition training

### Phase 2 — Core Features
- [ ] Snap a photo → identify item → determine recyclability
- [ ] Clear result display: ✅ Recyclable / ❌ Not recyclable
- [ ] Text input UI as fallback when image recognition fails
- [ ] Region selection (GPS or manual) to apply local recycling rules

### Phase 3 — Detail & UX
- [ ] Guidance for edge cases
  - e.g. Container with sauce residue → ⚠️ Heads up! Rinse before recycling
  - e.g. PET bottle with plastic label → ⚠️ Heads up! Remove label first
- [ ] Proper disposal instructions for non-recyclables
  - e.g. Sharp objects (knives, scissors) → wrap thickly in newspaper, label "SHARP"
- [ ] Inquiry/request feature for unclear or unlisted items
- [ ] Encouraging message after each scan
  - "You helped lower the Earth's temperature today 🌍"
  - "Thanks to you, the planet lives a little longer 🌱"

### Phase 4 — Scale Up
- [ ] Code architecture planning
- [ ] Select and integrate image recognition AI model
- [ ] Deploy as app / web service
