🔍 **Exploration du Code Python pour la Génération d'un Document Word avec python-docx**

🔧 **Importation des Modules**
- `from docx import Document`: Importe la classe `Document` pour la création de documents Word.
- `from docx.shared import Pt`: Importe `Pt`, qui permet de spécifier des tailles en points pour les styles de texte.

📑 **Création et Structure du Document**
- `doc = Document()`: Crée un nouveau document Word.
- `doc.add_heading('...', level=1)`: Ajoute un titre principal au document.

📄 **Ajout de Contenu au Document**
- `doc.add_heading('...', level=2)`: Utilisé pour les sous-titres.
- `doc.add_paragraph('...')`: Ajoute un paragraphe de texte.
- Les sections variées (Introduction, Téléchargement et Installation, etc.) sont structurées avec des titres de niveaux différents pour une meilleure organisation.

🔧 **Insertion de Commandes et de Réponses**
- Les commandes nécessaires pour l'installation et la configuration sont ajoutées en utilisant `doc.add_paragraph('...', style='Intense Quote')`, ce qui donne un style distinct aux blocs de commande dans le document.

💾 **Sauvegarde et Chemin du Document**
- `file_path = "C:\\Users\\Lenovo\\Desktop\\TP1 Hadoop\\Rapport.docx"`: Définit le chemin où le document sera sauvegardé.
- `doc.save(file_path)`: Sauvegarde le document au chemin spécifié.
- `file_path`: Retourne le chemin complet du fichier pour vérification.

Ce script Python utilise le module `python-docx` pour générer un rapport structuré sur l'installation de Hadoop, en le sauvegardant directement dans un emplacement désiré sur le disque dur.
