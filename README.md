# 📈 SaaS Investor Dashboard

Este dashboard en **Streamlit** permite:

- Analizar KPIs SaaS (MRR, ARR, churn, expansión, quick ratio, NRR/GRR).
- Visualizar cohortes de clientes por tarifa o globales.
- Aplicar filtros por plan y componentes de Net New MRR.
- Calcular valoraciones por plan usando múltiplos editables.

## 🚀 Uso

1. Clona el repositorio y accede a la carpeta:

   ```bash
   git clone <TU_REPO_URL>
   cd <TU_REPO>
   ```

2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Lanza el dashboard:

   ```bash
   streamlit run app.py
   ```

4. Carga un Excel con hojas **Data** y **Prices** siguiendo la plantilla incluida en `/examples`.

## 📂 Archivos

- `app.py`: Código principal de Streamlit (pega aquí el código con cohortes y filtros que te pasé).
- `requirements.txt`: Dependencias (Python 3.12 compatible).
- `README.md`: Instrucciones.
