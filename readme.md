<div align="center">
<h1 align="center">
<br>convert-coordinates-to-address
</h1>
<h3>◦ From Coordinates to Addresses. Swiftly.</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
</p>
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#️-features)
- [📂 Project Structure](#-project-structure)
- [🧩 Modules](#-modules)
- [🚀 Getting Started](#-getting-started)
  - [📦 Installation](#-installation)
  - [🎮 Using convert-coordinates-to-address](#-using-convert-coordinates-to-address)
  - [🧪 Running Tests](#-running-tests)

---


## 📍 Overview

The core functionality of the project is to convert coordinates (Latitude and Longitude) into addresses by using either the Google API or the Nominatim API. The project extracts place IDs and coordinates from an Excel file, performs reverse geocoding to retrieve corresponding addresses, and then updates the Excel file with the resulting address data. The purpose of the project is to automate and simplify the process of converting coordinates to addresses, providing value by saving time and effort for users who need to perform this conversion.

---

## ⚙️ Features

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Architecture**     | The codebase follows a straightforward script-based architecture, with code organized within a Jupyter Notebook. The main logic of extracting coordinates, reverse geocoding, and loading data is contained within this notebook. Limit response to 200 characters.    |
| **📖 Documentation**   | The project lacks comprehensive documentation. Despite its simplicity, having clear comments explaining different sections and functions would improve code readability and maintainability. Limit response to 200 characters.    |
| **🔗 Dependencies**    | This codebase relies on external libraries like Pandas and requests module for data manipulation and making API requests to Google and Nominatim API. No significant dependencies on other systems. Limit response to 200 characters.    |
| **🧩 Modularity**      | The codebase does not exhibit significant modularity. The logic is heavily tied to the specific data input and revolves around a single notebook, limiting code reusability and extensibility. Limit response to 200 characters.    |
| **✔️ Testing**          | There are no specific testing strategies or tools evident in the codebase. Comprehensive testing for input validation, API response validation, and edge cases would be beneficial. Limit response to 200 characters.    |
| **⚡️ Performance**      | Performance is dependent on the API response times for reverse geocoding to complete. Local performance should be fast as there are no computationally intensive tasks. Overall, efficient usage of resources is not a primary concern. Limit response to 200 characters.    |
| **🔐 Security**        | The codebase does not appear to explicitly handle security measures. However, if sensitive data storage and transmission is involved, additional security measures should be put in place, such as secure storage and encrypted communication. Limit response to 200 characters.    |
| **🔀 Version Control** | Version control is utilized within the project, with Git enabling the ability to track changes and collaborate effectively. However, further practices like branching and proper commit messages could enhance code management. Limit response to 200 characters.    |
| **🔌 Integrations**    | The codebase integrates with the Google and Nominatim API to perform reverse geocoding functionality. No explicit integrations with other systems or services. Limit response to 200 characters.    |
| **📶 Scalability**     | The codebase is not optimized for scalability. To handle growth, refactoring the code for better modularity, incorporating best practices, and utilizing extensive error handling can facilitate easier maintenance and extension. Limit response to 200 characters.    |

---


## 📂 Project Structure




---

## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                                                                                              | Summary                                                                                                                                                                                                                                                                   |
| ---                                                                                                                                               | ---                                                                                                                                                                                                                                                                       |
| [convert coordinates to address.ipynb](https://github.com/Mayconpm/convert-coordinates-to-address/blob/main/convert coordinates to address.ipynb) | This code extracts place IDs and coordinates from an Excel file. It then uses either the Google API or the Nominatim API to reverse geocode the coordinates and retrieve the corresponding addresses. The resultant address data is then loaded back into the Excel file. |

</details>

---

## 🚀 Getting Started

### 📦 Installation

1. Clone the convert-coordinates-to-address repository:
```sh
git clone https://github.com/Mayconpm/convert-coordinates-to-address
```

2. Change to the project directory:
```sh
cd convert-coordinates-to-address
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🎮 Using convert-coordinates-to-address

```sh
jupyter nbconvert --execute notebook.ipynb
```

### 🧪 Running Tests
```sh
pytest notebook_test.py
```

---
