Generate markdown summary readme and introduction to map, explain, and guide programmers, based in this format:

# Summary

# Major Files and components

# Related Files
List out the related files in the codebase here

# File tree

.
├── HiveMind
│   ├── AnalyticsAndCrashLogs
│   │   ├── AnalyticsManager.swift
│   │   └── CrashReporterManager.swift
│   ├── Assets.xcassets
│   │   ├── AccentColor.colorset
│   │   │   └── Contents.json
│   │   ├── AppIcon.appiconset
│   │   │   ├── AppIcon.png
│   │   │   └── Contents.json
│   │   ├── Contents.json
│   │   ├── chatGPTColor.colorset
│   │   │   └── Contents.json
│   │   ├── chatGPTColorDark.colorset
│   │   │   └── Contents.json
│   │   ├── chatGPTColorIcon.colorset
│   │   │   └── Contents.json
│   │   ├── chatGPTColorLight.colorset
│   │   │   └── Contents.json
│   │   └── chatGPTColorLight2.colorset
│   │       └── Contents.json
│   ├── Auth
│   │   ├── Auth0.plist
│   │   └── AuthManager.swift
│   ├── Base.lproj
│   │   └── LaunchScreen.storyboard
│   ├── Data
│   │   ├── CoreData+Extensions
│   │   │   ├── Conversation+Utils.swift
│   │   │   └── Message+Utils.swift
│   │   ├── HiveMind.xcdatamodeld
│   │   │   └── HiveMind.xcdatamodel
│   │   │       └── contents
│   │   ├── Managers
│   │   │   ├── ConversationHistoryManager.swift
│   │   │   ├── LibraryManager.swift
│   │   │   └── ShortcutManager.swift
│   │   ├── Models
│   │   │   ├── Action.swift
│   │   │   ├── Function.swift
│   │   │   ├── Prompt+Intent.swift
│   │   │   └── User.swift
│   │   ├── PersistenceController.swift
│   │   ├── PersistentHistoryCleaner.swift
│   │   ├── PersistentHistoryFetcher.swift
│   │   ├── PersistentHistoryMerger.swift
│   │   ├── PersistentHistoryObserver.swift
│   │   └── SwiftData
│   │       ├── Conversation.swift
│   │       ├── Credits.swift
│   │       ├── HivemindTask.swift
│   │       ├── Message.swift
│   │       ├── PreviewSampleData.swift
│   │       ├── Prompt.swift
│   │       └── Shortcut.swift
│   ├── Global.swift
│   ├── HiveMind.entitlements
│   ├── HivemindApp.swift
│   ├── Info.plist
│   ├── Intents
│   │   └── Intents.intentdefinition
│   ├── Network
│   │   ├── Hivemind.paw
│   │   ├── HivemindBackend.swift
│   │   ├── NetworkManager.swift
│   │   ├── Services
│   │   └── SupabaseManager.swift
│   ├── PromptLib
│   │   ├── CodeTreasureMap.md
│   │   ├── ConvertCodeToPrompt.md
│   │   ├── Formatter.md
│   │   ├── GPTEngineer.md
│   │   ├── Generator.md
│   │   ├── SoS.md
│   │   └── debug.md
│   ├── README.md
│   ├── SceneDelegate.swift
│   ├── Subscriptions
│   │   ├── HivemindStoreKitConfig.storekit
│   │   └── SubscriptionManager.swift
│   ├── UtilsAndMisc
│   │   ├── Date+Hivemind.swift
│   │   ├── UIView+Hivemind.swift
│   │   └── UserDefaults+CoreDataSync.swift
│   ├── Views
│   │   ├── Base.lproj
│   │   │   └── Main.storyboard
│   │   ├── ChatCells
│   │   │   ├── ActionApprovalView.swift
│   │   │   ├── MessageBubbleView.swift
│   │   │   └── StreamingView.swift
│   │   ├── ChatView.swift
│   │   ├── ChatViewModel.swift
│   │   ├── HivemindTabsView.swift
│   │   ├── ResponseInterpreter
│   │   │   ├── ResponseInterperterForcedFunctions.swift
│   │   │   ├── ResponseInterpreter.swift
│   │   │   └── Tools
│   │   │       ├── NotificationManager.swift
│   │   │       ├── ShortcutDetailView.swift
│   │   │       └── ToolsView.swift
│   │   ├── RootViewController.swift
│   │   ├── Subpages
│   │   │   ├── Common Standard pages
│   │   │   │   ├── SettingsView.swift
│   │   │   │   └── StoreView.swift
│   │   │   ├── HistoryView.swift
│   │   │   ├── Library
│   │   │   │   ├── LibraryPromptDetailView.swift
│   │   │   │   └── LibraryPromptView.swift
│   │   │   ├── TaskListView.swift
│   │   │   └── Under construction
│   │   │       └── LoginView.swift
│   │   └── UI components
│   │       ├── CircularCountdownView.swift
│   │       ├── DesignSystem.swift
│   │       ├── Gradients.swift
│   │       └── Styles.swift
│   └── lib
│       └── Models
├── HiveMind.xcodeproj
│   ├── project.pbxproj
│   ├── project.xcworkspace
│   │   ├── contents.xcworkspacedata
│   │   ├── xcshareddata
│   │   │   ├── IDEWorkspaceChecks.plist
│   │   │   └── swiftpm
│   │   │       ├── Package.resolved
│   │   │       └── configuration
│   │   └── xcuserdata
│   │       └── nicholasdobos.xcuserdatad
│   │           ├── IDEFindNavigatorScopes.plist
│   │           └── UserInterfaceState.xcuserstate
│   ├── xcshareddata
│   │   └── xcschemes
│   │       └── HiveMind.xcscheme
│   └── xcuserdata
│       └── nicholasdobos.xcuserdatad
│           ├── xcdebugger
│           │   └── Breakpoints_v2.xcbkptlist
│           └── xcschemes
│               └── xcschememanagement.plist
├── HiveMindTests
│   └── HiveMindTests.swift
├── HiveMindUITests
│   ├── HiveMindUITests.swift
│   └── HiveMindUITestsLaunchTests.swift
├── HivemindCoreDataLab.coredataproj
├── HivemindIntentExtension
│   ├── Info.plist
│   └── IntentHandler.swift
└── HivemindWidget
    ├── AppIntent.swift
    ├── Assets.xcassets
    │   ├── AccentColor.colorset
    │   │   └── Contents.json
    │   ├── AppIcon.appiconset
    │   │   └── Contents.json
    │   ├── Contents.json
    │   └── WidgetBackground.colorset
    │       └── Contents.json
    ├── HivemindWidget.entitlements
    ├── HivemindWidget.swift
    ├── HivemindWidgetBundle.swift
    └── Info.plist
