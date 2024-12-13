# Visualisasi Covid-19 Dari 1 Maret 2020 - 15 September 2022
Untuk dataset yang saya gunakan ada di [Dataset Covid-19 Indonesia](https://www.kaggle.com/datasets/hendratno/covid19-indonesia?select=covid_19_indonesia_time_series_all.csv).

## Langkah-Langkah Menjalankan Project

> [!TIP]
> Disarankan menggunakan virtual environment agar tidak bercampur dengan global.

1. **Jika menggunakan virtual environment:**
    - Buat virtual environment dengan perintah berikut:
      ```bash
      python -m venv .venv
      ```
      atau
      ```bash
      python3 -m venv .venv
      ```
    - Aktifkan virtual environment:
        - **Linux dan Mac**:
          ```bash
          source .venv/bin/activate
          ```
        - **Windows**:
          ```bash
          .venv\Scripts\activate
          ```

2. **Install semua dependensi:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Jalankan aplikasi dengan Streamlit:**
    ```bash
    streamlit run app.py
    ```
