# votely

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


Architecture : 

lib/
│
├── core/                  # éléments globaux
│   ├── constants/
│   ├── theme/
│   ├── utils/
│   ├── errors/
│   └── services/          # api, storage, etc.
│
├── features/
│   ├── auth/
│   │   ├── data/
│   │   ├── domain/
│   │   └── presentation/
│   │
│   ├── polls/
│   │   ├── data/
│   │   ├── domain/
│   │   └── presentation/
│   │
│   ├── groups/
│   ├── communities/
│   └── profile/
│
├── shared/
│   ├── widgets/
│   └── models/
│
└── main.dart


Dans chaque dossier features : 

polls/
├── data/
│   ├── models/
│   ├── datasources/
│   └── repositories/
│
├── domain/
│   ├── entities/
│   ├── repositories/
│   └── usecases/
│
└── presentation/
├── pages/
├── widgets/
└── providers/blocs/
