# car_price_predict_streamlit_huggingface


Overview
This project utilizes the Cars dataset to predict second-hand car prices using a Linear Regression model. The application interface is developed with Streamlit, and the model is hosted on Hugging Face.

Overview (Türkçe)
Bu proje, Linear Regression modeli kullanarak ikinci el araç fiyatlarını tahmin etmek için Cars veri setini kullanmaktadır. Uygulama arayüzü Streamlit ile geliştirilmiş olup, model Hugging Face üzerinde barındırılmaktadır.

Dataset
The Cars dataset contains information about various features of cars such as mileage, model year, brand, and other relevant attributes. It is used to train the Linear Regression model for predicting car prices.

Dataset (Türkçe)
Cars veri seti, araçların kilometre, model yılı, marka ve diğer ilgili özellikleri hakkında bilgi içermektedir. Bu veri seti, araç fiyatlarını tahmin etmek için Linear Regression modeli için eğitimde kullanılmaktadır.

Model
The prediction model is based on Linear Regression, which is trained using the Cars dataset to estimate the prices of second-hand cars based on their features.

Model (Türkçe)
Tahmin modeli, Linear Regression'a dayanmaktadır. Bu model, araçların özelliklerine dayanarak ikinci el araç fiyatlarını tahmin etmek için Cars veri seti ile eğitilmiştir.

Usage
To use the application:

Visit the Hugging Face Space to access the model and interact with the predictions.
Run the Streamlit application locally or deploy it using the provided instructions in the repository.
Kullanım
Uygulamayı kullanmak için:

Modeli incelemek ve tahminlerle etkileşime geçmek için Hugging Face Space adresini ziyaret edin.
Uygulamayı yerel olarak çalıştırın veya depolama talimatlarıyla dağıtın.
Installation
To install and run the application locally:

bash
Kodu kopyala
git clone https://github.com/kerimbirtem/car_price_predict_streamlit_huggingface.git
cd car_price_predict_streamlit_huggingface
pip install -r requirements.txt
streamlit run app.py
