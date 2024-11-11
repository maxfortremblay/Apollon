# Apollon
apollon/
├── src/
│   ├── app/
│   │   ├── layout.tsx         # Layout principal
│   │   ├── page.tsx          # Page d'accueil
│   │   ├── patients/         # Routes patients
│   │   │   └── page.tsx
│   │   ├── prescriptions/    # Routes ordonnances
│   │   │   └── page.tsx
│   │   └── pillbox/         # Routes piluliers
│   │       └── page.tsx
│   │
│   ├── components/
│   │   ├── ui/              # Composants UI réutilisables
│   │   └── shared/          # Composants partagés spécifiques
│   │
│   ├── features/
│   │   ├── patients/
│   │   │   ├── PatientList.tsx
│   │   │   ├── PatientDetail.tsx
│   │   │   └── PatientForm.tsx
│   │   │
│   │   ├── prescriptions/
│   │   │   ├── PrescriptionList.tsx
│   │   │   ├── PrescriptionDetail.tsx
│   │   │   └── PrescriptionForm.tsx
│   │   │
│   │   └── pillbox/
│   │       ├── PillboxManager.tsx
│   │       ├── PillboxVerification.tsx
│   │       └── PillboxBatch.tsx
│   │
│   └── lib/
│       ├── types/           # Types TypeScript
│       │   ├── patient.ts
│       │   ├── prescription.ts
│       │   └── pillbox.ts
│       │
│       └── utils/           # Utilitaires
│           ├── api.ts
│           └── formatters.ts
