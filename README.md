# 🦜🎨 BirdColorizer

Projet expérimental créatif de **La Science Musicale**, explorant les correspondances entre les chants d'oiseaux (ou autres sons naturels) et des formes visuelles abstraites générées automatiquement.

## Concept

- Convertir un son enregistré (bioacoustique, oiseau, amphibien…) en représentation abstraite numérique (embedding audio).
- Générer une visualisation abstraite en 3D à partir de cet embedding.
- Synchroniser précisément audio et visuel pour obtenir des vidéos abstraites immersives.

## Workflow technique

1. **Python** (AudioCLIP) : extraction d'embeddings audio.
2. **Swift/Xcode/Metal ou SceneKit** : visualisation abstraite synchronisée à l'audio.
3. Export vidéo final (Instagram, installations artistiques).

## Outils et dépendances

- WebGl - Html

## Exemple d'utilisation

```bash
# Générer embeddings audio
cd python
python audio_to_embedding.py ton_son.wav
