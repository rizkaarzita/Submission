# Dashboard E-commerce 

## Setup environment
```
conda create --name main-ds python=3.10
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
```

## Run steamlit app di google colab (https://colab.research.google.com/?hl=id)
1. Dalam file submission, pilih Dashboard lalu klik main_ds
2. Pastikan di dalam dashboard terdapat file berikut:
   * all_data.csv
   * dashboard.py
   * logo_dash.jpg
   * main_ds.ipynb
   * requirement.txt
3. Dalam main_ds.ipynb terdapat code berikut:
```
pip install streamlit
```
```
! wget -q -O - ipv4.icanhazip.com
```

```
! streamlit run dashboard.py & npx localtunnel --port 8501
```
selanjutnya, klik link url sebagai berikut
**your url is: https://chilly-keys-bet.loca.lt**
#
setalah itu, masukkan output kode dari 
```
! wget -q -O - ipv4.icanhazip.com
```
kode: 35.230.108.162 
