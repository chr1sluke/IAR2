# IAR2 (IamResponding Concept Clone)

🚒 **IAR2** is a SwiftUI-based prototype inspired by the IamResponding platform, designed to provide a clean, minimal iOS interface for emergency responders.

---

## 🔧 Features (Current)

- ✅ Tab-based navigation: Incidents and Responder Status
- ✅ Preloaded incident list (mock data)
- ✅ Responding toggle for the current user (Chris)
- ✅ Station selector (Station 1 / Station 2)
- ✅ Dynamic responder list (shows Chris if responding)
- ✅ Git-backed version control with clean commits

---

## 📱 Built With

- `SwiftUI`
- `MVVM` architecture
- `Xcode` + GitHub integration
- Ready for CarPlay exploration

---

## 📍 Planned Features

- 🚘 CarPlay UI support
- 🗺️ Route-to-scene map integration
- 🔔 Push notification simulation
- 💾 Persistence using UserDefaults or CoreData
- 🔄 Live ETA and time tracking for responders

---

## 🧪 Dev Notes

This is a solo sandbox project meant for exploration, experimentation, and learning SwiftUI + Git best practices. CarPlay is being developed on a separate branch.

---

## 📂 Project Structure

- `MainTabView.swift` – Tab controller
- `IncidentListView.swift` – Displays mock incidents
- `ResponderStatusView.swift` – Controls your responder state
- `IncidentViewModel.swift` – Central data logic
- `Responder.swift` / `Incident.swift` – Data models

---

## 🔗 GitHub Flow

```bash
# Create a new branch for a feature
git checkout -b carplay-ui

# After changes
git add .
git commit -m "Add basic CarPlay support layout"
git push origin carplay-ui

