# Solution 4: Deployment

Diese Einheit zeigt eine kleine, vollständige Deployment-Kette mit dem
Iris-Datensatz:

1. `4_1_Model_Training.ipynb`: Recap von Split, Pipeline, Training und
   Evaluation; anschließend wird die komplette scikit-learn-Pipeline unter
   `artifacts/iris_pipeline.joblib` gespeichert.
2. `backend/4_2_FastAPI_Backend.ipynb`: Einführung in Python-Module und ein
   minimales FastAPI-Backend. Start im Ordner `backend` mit `python run.py`.
3. `frontend/4_3_Streamlit_Frontend.ipynb`: minimales Streamlit-Frontend und
   HTTP-Kommunikation mit dem Backend. Start im Ordner `frontend` mit
   `streamlit run app.py`.

## Umgebung vorbereiten

In der aktivierten Miniconda-Umgebung aus diesem Ordner ausführen:

```bash
python -m pip install -r requirements.txt
```

Falls der Befehl `streamlit` im Terminal nicht gefunden wird, funktioniert
plattformunabhängig auch:

```bash
python -m streamlit run app.py
```

Das bisherige Notebook `4_0_Recap_Initiation_Training_Evaluation.ipynb` bleibt
als optionales Zusatzmaterial zu Eigenfaces und SVM erhalten.
