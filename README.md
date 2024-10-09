# FermentIQ

**FermentIQ** is a robust and user-friendly Python-based application designed for tracking beer fermentation. It seamlessly integrates a **web server** for an intuitive front-end experience and a **TCP server** to receive data from devices like **iSpindel**, enabling precise monitoring of your brewing process.

---

## 📥 Download

<p align="center">
  <strong><span style="font-size: 20px; color: green;">A download will be available soon...</span></strong>
</p>

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
  - [🌐 Responsive Design](#-responsive-design)
  - [⚙️ Simplicity](#-simplicity)
  - [📈 Scalability](#-scalability)
  - [🖥️ Intuitive Interface](#-intuitive-interface)
- [Installation](#installation)
  - [🛠️ Pre-requisites](#-pre-requisites)
  - [🚀 Setup Instructions](#-setup-instructions)
- [Usage](#usage)
  - [📊 Web Server](#-web-server)
  - [📡 TCP Server](#-tcp-server)
- [License](#license)
- [Contributing](#contributing)
- [Support](#support)
- [Acknowledgements](#acknowledgements)

---

## Introduction

FermentIQ is a comprehensive solution for managing and monitoring beer fermentation. Built entirely in **Python**, FermentIQ offers a seamless blend of powerful back-end functionalities with a sleek front-end interface crafted using **HTML**, **JavaScript**, and **CSS**. By leveraging the **TCP protocol**, FermentIQ effortlessly integrates with fermentation monitoring devices like **iSpindel**, ensuring real-time data transmission and accurate fermentation tracking.

Whether you're a homebrewer or a professional in the brewing industry, FermentIQ provides the tools you need to monitor your fermentation process with ease and precision.

---

## Features

### 🌐 Responsive Design

FermentIQ is engineered to provide an optimal user experience across all devices. Whether you're accessing the application from a desktop, tablet, or smartphone, the interface adjusts seamlessly to fit your screen, ensuring easy navigation and monitoring of your beer fermentation process.

<p align="center">
  <img src="FermentIQ_Demo_Images/mobile_landing_page.jpg" alt="Mobile Landing Page" width="250"/>
  <img src="FermentIQ_Demo_Images/responsive_create_brew.jpg" alt="Create Brew" width="250"/>
  <img src="FermentIQ_Demo_Images/responsive_nav_bar.jpg" alt="Responsive Nav Bar" width="250"/>
</p>

---

### ⚙️ Simplicity

Setting up FermentIQ is straightforward and hassle-free. Simply **drag and drop** the FermentIQ root folder onto your Python-supported web server, and launch the TCP server using the provided intuitive user interface. FermentIQ is designed for quick deployment, allowing you to start monitoring your fermentation within minutes.

<p align="center">
  <img src="FermentIQ_Demo_Images/landing_page.png" alt="Landing Page" width="700"/>
</p>

---

### 📈 Scalability

Designed to handle multiple brewing projects simultaneously, FermentIQ supports tracking of **multiple brews** and **connections from multiple devices** concurrently. Whether you're managing a single brew or overseeing a large-scale brewing operation, FermentIQ scales effortlessly to meet your needs.

<p align="center">
  <img src="FermentIQ_Demo_Images/view_active_brews.png" alt="View Active Brews" width="700"/>
</p>

---

### 🖥️ Intuitive Interface

FermentIQ boasts an **intuitive and user-friendly interface**, making it easy to set up brews and monitor fermentation progress without the need for complex configurations or API integrations. Access the application through your browser, configure your brews, and start tracking with just a few clicks—**get started in under 15 minutes!**

<p align="center">
  <img src="FermentIQ_Demo_Images/create_brew_page.png" alt="Create Brew Page" width="700"/>
</p>

---

## Installation

### 🛠️ Pre-requisites

To deploy FermentIQ, ensure you have the following:

- **Python 3.6+** installed on your server.
- A **web server** capable of running Python applications. This can be a:
  - **Home server**
  - **Raspberry Pi**
  - **Cloud-based server** (e.g., AWS, DigitalOcean)
- **TCP port access** (default port: `55000`) to receive data from fermentation devices like iSpindel.

### 🚀 Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/FermentIQ.git
