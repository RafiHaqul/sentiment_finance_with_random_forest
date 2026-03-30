# PROJEK ANALISIS SENTIMEN KOMENTAR FINANSIAL

> NOTE<br>
> Projek ini berjalan pada operating system linux. Disarankan untuk mengantinya ke linux operating system atau mengunakan WSL jika anda berada di windows operating system

## Quick start (Linux/WSL)
- Clone repository ini
- Download dataset dari link : https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis\
- Buka `random_forest.ipynb` sesuaikan lokasi file .csv ke kodingan ini (Contoh saya menaruhnya di dalam direktori `dataset_1`)
```python
df = pd.read_csv('dataset_1/data.csv')
df.head(5)
```
- (Opsional) Bikin virtual environment python lalu aktifkan
```
$ python3 -m venv .venv
$ source .venv/bin/activate
```
- Install library python yang dibutuhkan
```
$ pip install -r requirement.txt
```
- Jalanin aja `random_forest.ipynb`

## Note
- Hasil prediksi masih jauh dari ekspetasi, disarankan terus melakukan tuning algoritma