# 🎬 Multi-Mode-Movie-Recommender-python

A versatile movie recommendation system supporting both **content-based** and **collaborative filtering** methods.  
This project offers three interfaces to suit your preference and workflow:  
- 🖥️ Command-Line Interface (CLI)  
- 🌐 Flask Web Application  
- 📱 Streamlit Interactive App  

## ✨ Features 

- 🎯 Hybrid recommendation approach combining content-based and collaborative filtering   
- 🔄 Flexible usage with CLI, Flask, and Streamlit interfaces    
- 🛠️ Easy to extend and customize     
- 📊 Interactive visualizations and user-friendly interfaces   
- 🎨 Modern and responsive web design 
- 🔍 Advanced search and filtering capabilities

## 📁 Project Structure

```
Directory structure:
└── hariharans24-multi-mode-movie-recommender-python/
    ├── README.md
    ├── gitignore.txt
    ├── LICENSE.txt
    ├── requirements.txt
    ├── run.py
    ├── run.txt
    ├── setup.py
    ├── app/
    │   ├── main.py
    │   └── __pycache__/
    ├── data/
    │   └── data.txt
    ├── movie_recommender/
    │   ├── __init__.py
    │   ├── collaborative_recommender.py
    │   ├── content_recommender.py
    │   ├── data_loader.py
    │   ├── feature_engineering.py
    │   ├── utils.py
    │   └── __pycache__/
    ├── web_flask/
    │   ├── app.py
    │   ├── __pycache__/
    │   └── templates/
    │       └── index.html
    └── web_streamlit/
        └── app.py
```

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HARIHARANS24/multi-mode-movie-recommender-python.git
   cd multi-mode-movie-recommender-python
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv env
   source env/bin/activate    # On Windows use `env\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 💻 Usage

### 1. Command Line Interface (CLI)
Run the CLI tool to get movie recommendations directly in your terminal:
```bash
python cli.py --movie "The Matrix" --method content
```

Options for `--method`:
- `content` — content-based filtering
- `collaborative` — collaborative filtering
- `hybrid` — combined approach

### 2. Flask Web Application
Start the Flask server:
```bash
python web_flask/app.py
```
Open your browser and go to `http://localhost:5000` to use the web interface.

### 3. Streamlit Interactive App
Run the Streamlit app:
```bash
streamlit run web_streamlit/app.py
```
A browser window will open with a sleek interactive UI for movie recommendations.

## 📊 Data
Place your `movies.csv` file inside the `data/` folder. The CSV should contain:
- Movie titles
- Overviews
- Genres
- User ratings (for collaborative filtering)
- Additional metadata

## 🤝 Contributing

We welcome contributions to improve the Movie Recommender Suite! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their invaluable tools and libraries
- Inspired by various movie recommendation systems and research papers

---

⭐ Star this repository if you find it useful!












