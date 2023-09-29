# Proyecto Mercado inmobiliario Ruso de Sberbank

## Miembros del grupo

* Jhon Jader Caro Sánchez, CC. 1001137636, Ingeniería de Sistemas

* Leider Steven Caro Mejía, CC. 1017260248, Ingeniería Civil            

* José Manuel Ladino Villa, CC. 1010075481, Ingeniería Civil

## Datos
Los datos del proyecto vienen de [Sberbank Russian Housing Market](https://www.kaggle.com/competitions/sberbank-russian-housing-market) y se pueden hacer disponibles ejecutando desde cualquier notebook en Colab los siguientes comandos:

<pre>
url = 'https://drive.google.com/file/d/11kx9xw2EppTi1_SnOc_iN1D6K_rQ_F9g/view?usp=sharing'
! wget "$url" -O kaggle.json
! pip install kaggle
! mkdir ~/.kaggle
! cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
! kaggle competitions download sberbank-russian-housing-market
! unzip sberbank-russian-housing-market.zip
</pre>
