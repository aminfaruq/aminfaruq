# Amin Faruq
**iOS Engineer**

I build iOS apps with a focus on clean architecture, testing, and reliability.

---

## Projects

| Project | Domain | Key Technologies | Highlights |
|---------|--------|------------------|------------|
| **Market App** | Stock market feed, search, live prices | `UIKit` `Texture` `IGListKit` `RxSwift` | Three modules, REST + WebSocket, unit-tested core and view models |
| **StreakOS** | Offline-first habit tracking | `SwiftUI` `SwiftData` `CloudKit` `watchOS` | Counter-based model for conflict-free sync |
| **Essential Chess** | Elo-based tactics trainer | `SwiftUI` `UIKit` `Combine` | Zero leaks, 42+ test suites, hybrid UI |

---

### Market App: Stock Market Client

![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=apple&logoColor=white)
![Texture](https://img.shields.io/badge/Texture-000000?style=flat-square&logo=apple&logoColor=white)
![IGListKit](https://img.shields.io/badge/IGListKit-0A66C2?style=flat-square&logo=meta&logoColor=white)
![RxSwift](https://img.shields.io/badge/RxSwift-B7178C?style=flat-square&logo=reactivex&logoColor=white)

[![Repository](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aminfaruq/MarketApp)

| Aspect | Details |
|--------|---------|
| **What it does** | Shows a market feed (quotes and news), stock search, and a detail screen with a price chart and live trades. Data comes from the Finnhub REST and WebSocket APIs. |
| **Architecture** | Three modules: `MarketCore` (domain, services, HTTP/WebSocket clients, Foundation only), `MarketPresentation` (RxSwift view models, no UIKit), and `MarketApp` (Texture nodes, IGListKit lists). A composition layer wires them together. |
| **Testing** | Unit tests for the core services and clients, and for every view model. Network clients are injected, so tests run without network access. |

---

### StreakOS: Offline-First Habit Tracking

![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-007AFF?style=flat-square&logo=swift&logoColor=white)
![CloudKit](https://img.shields.io/badge/CloudKit-2D7CBF?style=flat-square&logo=icloud&logoColor=white)
![watchOS](https://img.shields.io/badge/watchOS-000000?style=flat-square&logo=apple&logoColor=white)

[![Repository](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aminfaruq/streakOS-project)

| Aspect | Details |
|--------|---------|
| **Challenge** | A habit tracker for macOS, iOS, and watchOS with offline-first sync. Three device surfaces change the same data, so conflicts have to be resolved without a constant connection. |
| **Solution** | A counter-based domain model instead of binary checkboxes. Persistence becomes cumulative state that can be merged, not toggles that can conflict. |
| **Result** | Offline-first sync across Apple platforms without data conflicts. |

---

### Essential Chess: Elo-Based Tactics Trainer

![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=apple&logoColor=white)
![Combine](https://img.shields.io/badge/Combine-FFB800?style=flat-square&logo=apple&logoColor=black)

[![Repository](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aminfaruq/essential-chess-project)

| Aspect | Details |
|--------|---------|
| **Challenge** | An offline chess training app with no memory leaks and good test coverage. |
| **Solution** | Clean Architecture with MVVM, where view models act as deterministic state machines. UIKit handles the chessboard gestures and SwiftUI handles the other views. |
| **Result** | A fully offline trainer with 42+ test suites and no leaks. |

---

## Experience

### PT Phincon: iOS Engineer
- Worked on **MyTelkomsel**, which has over **100 million active users**.
- Reduced the production crash rate by **40%** (1.5% to 0.9%) through instrumentation, targeted refactoring, and code reviews.
- Delivered **30+ features** in a 50-person engineering team.

### PT Gits Indonesia: iOS Engineer
- Led development of **three iOS apps**, with an average App Store rating of **4.7**.
- Led technical discovery for **five large feature epics** and turned business requirements into scoped technical plans.

---

## Skills

### Languages & Frameworks
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=for-the-badge&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=for-the-badge&logo=apple&logoColor=white)
![Combine](https://img.shields.io/badge/Combine-FFB800?style=for-the-badge&logo=apple&logoColor=black)
![RxSwift](https://img.shields.io/badge/RxSwift-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

### Data & Persistence
![Core Data](https://img.shields.io/badge/CoreData-3E4C59?style=for-the-badge&logo=apple&logoColor=white)
![CloudKit](https://img.shields.io/badge/CloudKit-2D7CBF?style=for-the-badge&logo=icloud&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-007AFF?style=for-the-badge&logo=swift&logoColor=white)

### Architecture & Practices
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1A1A1A?style=for-the-badge&logo=archlinux&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-4B8BBE?style=for-the-badge&logo=apple&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-8A2BE2?style=for-the-badge&logo=testing-library&logoColor=white)

### Testing & Performance
![XCTest](https://img.shields.io/badge/XCTest-147EFB?style=for-the-badge&logo=apple&logoColor=white)
![Instruments](https://img.shields.io/badge/Instruments-FF2D55?style=for-the-badge&logo=apple&logoColor=white)

### Tools
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white)

---

## Education & Training

- **iOS Lead Essentials Program**: software architecture, modular design, TDD/BDD/DDD, and technical leadership.
- **Bangkit Academy 2022**: one of 4,636 participants selected from 45,000+ applicants; top 10% of the Mobile Development path.
- **B.S. Information Systems**, Mulia University (GPA 3.69/4.00)

---

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aminfaruk.fa@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amin-faruq/)

</div>

Open to iOS engineering roles and collaborations.
