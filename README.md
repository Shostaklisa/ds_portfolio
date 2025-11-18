# image-text-matching
Image-text matching with legal filtering for minors (under 16 years old)

**Проект:** Демонстрационная версия поиска референсных фотографий по описанию сцены для профессионального фотохостинга.  

**Цель:** Продемонстрировать Proof of Concept (PoC) модели, которая позволяет находить изображения, соответствующие текстовому описанию сцены.  
## Функционал
- Ввод текстового описания сцены пользователем.
- Получение списка фотографий, подходящих под описание.
- Каждое изображение оценивается моделью на соответствие тексту (число от 0 до 1).
- В демонстрационной версии запрещённый контент (например, изображения детей до 16 лет) отображается через дисклеймер.

Модель преобразует изображения и текст в векторное представление.
На выходе выдаёт **score** соответствия текста и изображения (от 0 до 1).  Лучшая модель выбирается экспериментально для демонстрации PoC.
_____________________________________________________________________________________________________________________

**Project:** Demonstration version of a reference photo search based on scene descriptions for a professional photo hosting service.  

**Goal:** To showcase a Proof of Concept (PoC) model that allows finding images corresponding to a textual description of a scene.  

## Features
- User inputs a textual description of a scene.
- The system returns a list of photos matching the description.
- Each image is scored by the model for text-image relevance (a number between 0 and 1).
- In the demo version, restricted content (e.g., images of children under 16) is replaced with a disclaimer.

The model converts images and text into vector representations.  
It outputs a **score** indicating the match between the text and the image (from 0 to 1). The best model is chosen experimentally for the PoC demonstration.
