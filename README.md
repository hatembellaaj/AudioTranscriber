# 🎙️ Speech To Text - Projet complet

## Structure
- `frontend/` : page web d’upload audio
- `backend/` : serveur Flask
- `colab/` : modèle Whisper (API locale via ngrok)

## Étapes pour lancer le projet
1. Ouvre `colab/whisper_api.ipynb` dans Google Colab et exécute toutes les cellules.
2. Copie l’URL publique affichée (ngrok) et mets-la dans `backend/app.py`.
3. Lance le backend :
   ```bash
   cd backend
   pip install -r requirements.txt
   python app.py