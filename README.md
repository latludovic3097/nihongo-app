# 日本語学習 — NihonGo Flashcards

Application web mobile de flashcards japonaises avec répétition espacée (SM-2).

## Fonctionnalités

- 🈵 Hiragana (78 caractères) et Katakana (46 caractères)
- 📖 Vocabulaire N5 (50 mots de base, extensible)
- ⚡ Grammaire N5 (structures essentielles)
- 🔊 Prononciation TTS (Web Speech API — japonais natif)
- 📱 Interface mobile optimisée (swipe gauche/droite)
- 🔄 Sync bidirectionnel avec sessions orales Claude Code (`/nihongo`)

## Utilisation

Ouvrir directement dans le navigateur. Les données sont stockées en `localStorage` sur l'appareil.

## Sync avec Claude Code

1. Dans Claude Code : `/nihongo` puis `/export`
2. Copier le contenu de `sync-export.json`
3. Dans l'app : onglet 同期 → Importer → coller
4. Pour renvoyer sa progression : onglet 同期 → Exporter → `/import` dans Claude
