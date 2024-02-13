# FrameChat - Video Conferencing App

FrameChat is an open-source video conferencing application built with Django, integrating the ZegoCloud API for seamless and high-quality video communication. This project provides a platform for real-time collaboration, enabling users to connect through video calls with the power of ZegoCloud.

[Visit FrameChat](https://frame-chat.onrender.com/)

## Features

- **Video Conferencing**: Conduct high-quality video calls with multiple participants in real-time using the ZegoCloud API.
- **User Authentication**: Securely access the application with user accounts.
- **Chat Integration**: Instant messaging during video conferences for enhanced communication.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/framechat.git`
2. Navigate to the project directory: `cd framechat`
3. Install dependencies: `pip install -r requirements.txt`
4. Apply database migrations: `python manage.py migrate`
5. Configure ZegoCloud API keys in the settings.
6. Run the development server: `python manage.py runserver`

## Usage

1. Open the application in your web browser.
2. Register a new account or log in if you already have one.
3. Experience high-quality video conferencing with integrated chat features, powered by the ZegoCloud API.

## Files

- `videoconferencing_app/`: Django app directory containing models, views, and templates.
- `templates/`: HTML templates for the frontend.
- `static/`: Static files such as CSS and JavaScript.
- `manage.py`: Django management script.
- `requirements.txt`: File containing project dependencies.

## Dependencies

- Django
- Django Channels (for real-time communication)
- Bootstrap (for styling)
- ZegoCloud API (for video conferencing)

## Contributing

Contributions to FrameChat are welcome! Feel free to submit issues or pull requests. Your feedback and contributions will help enhance the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
