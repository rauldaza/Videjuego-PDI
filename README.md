------- Por: Raul Daza Liñan raul.daza@udea.edu.co -----------------------
------------ Sebastian Bonilla Cruz sebastian.bonillac@udea.edu.co -------
------------ Estudiantes de ingenieria electronica UdeA  -----------------
------- Curso Básico de Procesamiento de Imágenes y Visión Artificial-----
------- V1 septiembre de 2023 --------------------------------------------

# JIMMED EXPRESSWAY - DIP and AI-based Video Game

This project is an interactive video game developed in Python that integrates Digital Image Processing (DIP) techniques and basic Artificial Intelligence concepts. The goal is to avoid vehicles on a highway, controlling the main car using face detection from a webcam.

## Main Features

- **Facial Detection Control:** Uses OpenCV to detect your face and control the vehicle in real-time.
- **Interactive Graphical Interface:** Developed with Pygame, featuring animations, score tracking, and a game over screen.
- **Image Processing:** Grayscale conversion of video and Haar classifier-based face recognition.
- **Graphic Resource Management:** Optimized images for smooth visual experience.

## Project Structure

- `main.py`: Main game logic and video processing.
- `assets/`: Images for vehicles, background, and game screens.
- `README.md`: Documentation and credits.

## Demonstrated Skills

- Digital Image Processing with OpenCV.
- Integration of computer vision into video games.
- Graphical interface and game logic development with Pygame.
- Image rendering and manipulation in Python.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- Pygame

## Running the Game

Install dependencies and run the game with the following commands:

```sh
pip install opencv-python pygame
python main.py
