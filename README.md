AI Powered Early Detection System for Aquaculture Diseases

This project is an AI-powered solution for detecting fish diseases in aquaculture environments using image processing and deep learning. It allows fish farmers, researchers, and aquaculture professionals to identify diseases early, estimate how many days before the infection started, and measure the severity percentage of the disease, all from a single fish image.

Project Overview

Fish farming plays a vital role in food production and the economy, but disease outbreaks can cause severe financial losses and threaten sustainability. Early detection is crucial for taking preventive measures. This project uses transfer learning with EfficientNetB0 to build a multi-output model that can:

Identify the disease type from an uploaded image.

Predict the estimated number of days before the fish got infected (based on learned regression patterns).

Calculate the disease severity percentage using classification confidence.

The model is trained on a labeled dataset of fish images, with each image tagged with both its disease type and the approximate infection timeline. The application is built with Streamlit, providing a simple web interface for image uploads and instant predictions.

Key Features

Multi-Output Deep Learning Model: Simultaneously performs disease classification and days-before-infection estimation.

Transfer Learning: Uses EfficientNetB0 pretrained on ImageNet for high accuracy with limited data.

User-Friendly Interface: Streamlit app for easy interaction — no programming knowledge required.

Real-Time Inference: Get predictions within seconds after uploading an image.

Disease Severity %: Confidence score is converted into an easy-to-read percentage for farmers.

How It Works

Upload an image of a fish.

The model processes the image and predicts:

Disease name

Estimated days since infection started

Confidence percentage

Results are displayed in a clean, understandable format.

Use Cases

Aquaculture farms for disease monitoring and prevention.

Research on fish health management.

Educational purposes in marine biology and aquaculture technology.
