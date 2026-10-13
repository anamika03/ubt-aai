# Exercise 4: Deployment

In dieser Übung entsteht eine kleine, vollständige Deployment-Kette mit dem
Iris-Datensatz:

1. `4_1_Model_Training.ipynb`: Wiederholung von Split, Pipeline, Training und
   Evaluation; danach wird die Pipeline unter
   `artifacts/iris_pipeline.joblib` gespeichert.
2. `backend/4_2_FastAPI_Backend.ipynb`: Python-Module vervollständigen und ein
   minimales FastAPI-Backend bauen. Start im Ordner `backend` mit
   `python run.py`.
3. `frontend/4_3_Streamlit_Frontend.ipynb`: einen API-Client und ein kleines
   Streamlit-Frontend ergänzen. Start im Ordner `frontend` mit
   `streamlit run app.py`.

## Umgebung vorbereiten

In der aktivierten Miniconda-Umgebung aus diesem Ordner ausführen:

```bash
python -m pip install -r requirements.txt
```

Falls der Befehl `streamlit` im Terminal nicht gefunden wird:

```bash
python -m streamlit run app.py
```

Das bisherige Notebook `4_0_Recap_Initiation_Training_Evaluation.ipynb` bleibt
als optionales Zusatzmaterial zu Eigenfaces und SVM erhalten.
