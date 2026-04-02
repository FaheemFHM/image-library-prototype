
# Image Library App

A desktop application built with Python and PyQt5 for managing and browsing images and videos.

This project was originally developed to explore UI design and local media management.

Future iterations focus on rebuilding this as a full-stack web application using React and modern backend services.

## Sample

![App Screenshot](screenshot.png)

## Features

- Image loading and viewing
- Image searching
- Metadata-based filter and sort systems
- Tag-based filtering
- Data persistence using SQLite
- Slideshow of selected images

## Tech Stack

- Python 3.11.9
- PyQt5 - GUI framework
- Pillow (PIL) - image processing  
- SQLite 3 - database interactions

## Project Structure

```text
image-library-app/
├── components/ # custom PyQt widget definitions
│ ├── init.py # makes 'components' a python package
│ ├── Gallery.py
│ ├── InputWidgets.py
│ ├── MediaBar.py
│ ├── Sidebar.py
│ ├── Slideshow.py
│ ├── StyledWidgets.py
│ ├── TagList.py
│ ├── Window.py
│ ├── Database.py # database interaction code
├── style.qss # visual styling
├── database.db # SQLite database
├── main.py # main entry point
├── ../media/ # folder containing loose image files
```

## Roadmap

- Image thumbnails for faster loading times
- Remove gallery size cap
- Improved error logging
- Responsiveness to screen sizes
- Video playing subsystem

## License

MIT License - feel free to use and adapt.

## Extra

Built as a learning project during my university break.
