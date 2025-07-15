/phase1-foundation
├── README.md  # This file: Phase guide.
├── templates/  # Scaffolds: e.g., catalog-info.yaml (for visibility entities).
├── prompts/  # AI prompts: e.g., hub_setup_prompt.txt ("Generate Docker for Backstage shell.").
├── context/  # Instructions: e.g., plugin_instructions.md ("Build frontend for AI UI; backend for adapters.").
└── plugins/
    ├── ai-assistant-frontend/  # Frontend plugin subdir.
    │   ├── src/  # React: index.ts, AIChat.tsx.
    │   ├── package.json  # Dependencies.
    │   └── README.md  # Plugin-specific notes.
    └── llm-adapter-backend/  # Backend plugin subdir.
        ├── src/  # Node: router.ts (API endpoints/adapters).
        ├── package.json
        └── README.md
